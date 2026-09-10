# Convertir MP4 en TS gratuitement en ligne

Convertissez MP4 en MPEG-TS (.ts) gratuitement dans votre navigateur. Copie de flux sans perte avec FFmpeg.wasm, sans envoi. Vos fichiers restent sur votre appareil.

HTML: https://grepcut.com/fr/converters/mp4-to-ts

## Comment convertir MP4 en TS dans votre navigateur

1. **Choisissez votre MP4**: Déposez votre fichier .mp4 dans la zone de conversion, ou sélectionnez-le depuis votre appareil.
2. **Remux local**: GrepCut exécute FFmpeg.wasm avec copie de flux, de sorte que les paquets vidéo et audio compatibles sont réempaquetés dans un conteneur MPEG-TS sans nouveau encodage.
3. **Téléchargez le fichier TS**: Enregistrez le fichier .ts obtenu pour les outils IPTV, la remise à la diffusion, la préparation serveur ou un flux de travail de segments HLS.

Lorsque votre MP4 contient déjà des flux compatibles TS, il s'agit d'un changement de conteneur rapide et sans perte. Votre fichier reste dans l'onglet de votre navigateur et n'est pas envoyé.

## Ce qui change lorsque vous remuxez MP4 en MPEG-TS

MP4 et TS sont des conteneurs. Ils encapsulent la vidéo, l'audio, le timing et les métadonnées afin que différents outils sachent comment lire votre fichier.

Ce convertisseur ne promet pas un nouveau codec ou un fichier plus petit. Il demande à FFmpeg.wasm de copier les flux compatibles dans un conteneur Transport Stream, le format souvent utilisé dans la diffusion, l'IPTV et les segments HLS .ts classiques.

Si votre MP4 utilise déjà des flux courants comme la vidéo H.264 avec audio AAC, le résultat peut être créé sans décodage ni ré-encodage. Cela signifie que votre image et votre son sont copiés, non recompressés.

Si votre source utilise un codec, une fonctionnalité de métadonnées ou une piste de sous-titres que le TS ne peut pas transporter proprement, la copie de flux peut échouer ou ignorer les détails non pris en charge. Dans ce cas, vous avez besoin d'un transcodage ou d'une cible différente.

## Quand le TS est le bon format de sortie pour votre fichier

Choisissez TS lorsque votre outil suivant attend du MPEG-TS, pas lorsque vous voulez simplement le fichier vidéo le plus pratique au quotidien. Un fichier .ts est utile lorsque vous préparez des médias pour une infrastructure de streaming, un logiciel orienté diffusion, ou un flux de travail qui construira ensuite une playlist HLS.

Un simple MP4 est généralement préférable pour les galeries de téléphone, le partage occasionnel et les téléchargements directs. Le MP4 bénéficie d'une large prise en charge de la lecture et conserve généralement les métadonnées de manière plus propre pour les applications grand public.

Si vous construisez du HLS, rappelez-vous qu'un seul fichier .ts ne constitue pas l'ensemble du flux. HLS nécessite normalement un fichier de playlist et des règles de segmentation, tandis que ce convertisseur vous donne le conteneur TS que vous pouvez utiliser dans ce pipeline.

## MP4 vs TS pour votre flux de travail

| Besoin | MP4 | TS |
| --- | --- | --- |
| Lecture occasionnelle | Généralement le meilleur choix pour les téléphones, navigateurs et partage | Peut être lu dans certains outils, mais moins pratique au quotidien |
| Préparation au streaming | Bon comme fichier source avant conditionnement | Utile pour l'IPTV, la remise à la diffusion et les flux de travail de segments HLS |
| Taille du fichier | Souvent plus compact en tant que fichier stocké | Peut être plus volumineux car le Transport Stream ajoute des surcharges de paquets |
| Remux sans perte | Fonctionne comme entrée lorsque les codecs sont compatibles | Fonctionne comme sortie lorsque les flux peuvent être copiés dans MPEG-TS |
| Métadonnées | Mieux adapté aux métadonnées grand public et aux indicateurs de rotation | Peut ne pas préserver toutes les fonctionnalités de métadonnées du MP4 |

Utilisez TS parce que votre prochaine étape nécessite TS. Utilisez MP4 lorsque vous avez besoin du fichier final le plus portable.

## Pourquoi votre copie de flux MP4 vers TS pourrait échouer

La copie de flux est stricte car elle ne répare ni ne réinterprète vos médias en les ré-encodant. Si le muxeur TS ne peut pas accepter l'un de vos flux, FFmpeg s'arrête au lieu de créer silencieusement un fichier trompeur.

L'écueil courant est que l'extension de fichier ne dit pas tout. Votre .mp4 peut contenir du H.264 et de l'AAC, ou bien un autre codec vidéo, un audio inhabituel, des sous-titres, un timecode, des métadonnées de rotation ou des pistes supplémentaires qui ne se mappent pas proprement au MPEG-TS.

Si votre conversion échoue, essayez d'abord de convertir votre source en un MP4 standard H.264 et AAC, puis relancez la conversion MP4 vers TS. Cela ajoute une étape d'encodage, mais donne au muxeur TS des flux qu'il peut généralement transporter.

GrepCut garde le remux privé et local, mais il suit toujours les règles de FFmpeg. L'absence d'envoi ne signifie pas que toutes les combinaisons de codecs peuvent être copiées.

## Remux privé MP4 vers TS : avantages et compromis

### Advantages

- Sans perte lorsque la copie de flux réussit
- Beaucoup plus rapide qu'un transcodage complet
- Votre fichier reste sur votre appareil sans envoi cloud
- Utile pour l'IPTV, les outils de diffusion et les flux de travail HLS basés sur TS
- Propulsé par FFmpeg.wasm, donc le travail de conteneur se fait dans votre navigateur

### Disadvantages

- La sortie TS peut être plus volumineuse que le MP4 source
- Des codecs ou pistes non pris en charge peuvent faire échouer la copie de flux
- Les métadonnées de rotation, sous-titres ou pistes supplémentaires peuvent ne pas survivre au changement de conteneur
- Un seul fichier .ts n'est pas la même chose qu'une playlist HLS complète
- Le MP4 est généralement meilleur pour le partage quotidien et les galeries mobiles

## FAQ du convertisseur MP4 en TS

### Pouvez-vous convertir MP4 en TS sans envoi ?

Oui. GrepCut exécute FFmpeg.wasm localement dans votre navigateur, donc votre MP4 reste sur votre appareil au lieu d'être envoyé sur un serveur.

### La conversion MP4 en TS est-elle sans perte ?

Oui, lorsque la copie de flux réussit. Le convertisseur utilise la copie de flux de type FFmpeg, donc les paquets vidéo et audio compatibles sont copiés dans le conteneur TS sans nouvel encodage.

### Pourquoi votre fichier TS est-il plus volumineux que le MP4 ?

Cela peut être normal. Le MPEG-TS est conçu pour le transport et ajoute des surcharges de paquets, donc un remux sans perte peut produire un fichier plus volumineux même si la qualité vidéo et audio est inchangée.

### Cela va-t-il créer une playlist HLS ?

Non. Ce convertisseur vous donne un fichier .ts. Une sortie HLS complète nécessite généralement une playlist .m3u8 et des paramètres de segmentation, donc utilisez ce fichier TS comme une pièce de pipeline plutôt qu'un package HLS complet.

### Pourquoi ma conversion MP4 en TS a-t-elle échoué ?

Votre MP4 peut contenir des flux que le MPEG-TS ne peut pas copier tels quels. Essayez une source MP4 standard H.264 et AAC, ou transcodez d'abord votre fichier puis remuxez-le en TS.

### Puis-je utiliser TS pour l'IPTV ?

Oui, si votre outil IPTV accepte le MPEG-TS et que vos flux sont compatibles. Le TS est courant dans les flux de travail IPTV et de diffusion, mais les exigences exactes dépendent de votre serveur, playlist et appareil de lecture.

### Les sous-titres, la rotation ou les métadonnées resteront-ils intacts ?

Pas toujours. La copie de flux préserve l'audio et la vidéo compressés lorsque c'est possible, mais le TS peut ne pas transporter toutes les fonctionnalités de métadonnées du MP4, les formats de sous-titres ou les indicateurs de rotation de la même manière.

### Le TS est-il meilleur que le MP4 ?

Pas universellement. Utilisez TS lorsque votre prochain outil ou flux de travail de streaming attend du MPEG-TS. Utilisez MP4 lorsque vous voulez un fichier largement compatible pour la lecture, le stockage ou le partage.

## Sources et lectures complémentaires

- [Discussion Reddit r/ffmpeg sur l'enregistrement de flux en TS ou MP4](https://www.reddit.com/r/ffmpeg/comments/tiupo2/saving_a_video_stream_as_ts_or_mp4/)
- [Réponse Stack Exchange Production Vidéo sur la copie de flux MP4 vers TS](https://video.stackexchange.com/questions/27854/errors-in-converting-mp4-to-ts-with-ffmpeg)
- [Discussion Stack Overflow sur les métadonnées de rotation MP4 vers TS](https://stackoverflow.com/questions/64177769/ffmpeg-converts-incorrect-mp4-to-ts)
- [Guide Mux sur MP4, HLS, copie de flux et segments TS](https://www.mux.com/articles/how-to-convert-mp4-to-hls-format-with-ffmpeg-a-step-by-step-guide)
- [Présentation du projet ffmpeg.wasm](https://github.com/ffmpegwasm/ffmpeg.wasm)
- [Guide MDN sur les formats de conteneurs multimédia](https://developer.mozilla.org/en-US/docs/Web/Media/Guides/Formats/Containers)
- [RFC 8216 Spécification HTTP Live Streaming](https://datatracker.ietf.org/doc/html/rfc8216)

## Convertissez votre MP4 en TS en privé

Ouvrez GrepCut, déposez votre MP4 et créez un fichier .ts dans votre navigateur. Utilisez-le lorsque votre prochaine étape IPTV, diffusion ou streaming attend du MPEG-TS.

## Convertisseurs associés

- [MP4 en DivX](https://grepcut.com/fr/converters/mp4-to-divx) - Transcodez MP4 pour une lecture DivX héritée
- [MOV en MP4](https://grepcut.com/fr/converters/mov-to-mp4) - Convertissez les fichiers QuickTime en MP4 largement compatible

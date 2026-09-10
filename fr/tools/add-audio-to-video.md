# Ajouter de l'audio à une vidéo en ligne

Déposez une vidéo et un fichier audio - GrepCut remplace la bande sonore sans ré-encoder l'image. Rien ne quitte votre appareil.

HTML: https://grepcut.com/fr/tools/add-audio-to-video

## Comment ajouter un fichier audio à une vidéo dans votre navigateur

1. **Choisissez votre vidéo**: Déposez un fichier MP4, MOV, WebM, MKV, M4V, AVI, OGV, 3GP ou MPEG dans GrepCut. Votre vidéo reste sur votre appareil.
2. **Choisissez votre fichier audio**: Ajoutez un fichier MP3, WAV, AAC, M4A, FLAC, OGG ou Opus. Ce fichier deviendra la nouvelle bande sonore.
3. **Mixez et exportez**: Cliquez sur Mixer et exporter. GrepCut assemble le flux vidéo et votre nouveau fichier audio en un seul MP4.
4. **Téléchargez le résultat**: Enregistrez le MP4 avec -with-audio ajouté au nom du fichier. L'exportation s'arrête au plus court de vos deux fichiers sources.

Besoin d'ajouter une musique de fond avec la voix originale, de régler le volume, de fondre l'audio ou de synchroniser une piste de quelques images ? Ouvrez [GrepCut Studio](/) à la place.

## Ce que ce remplacement audio change réellement

Si vous avez déjà une vidéo terminée et un fichier audio séparé (voix off, chanson, narration ou fichier audio nettoyé), vous n'avez pas besoin d'un éditeur complet pour remplacer la bande sonore. GrepCut prend le flux vidéo de votre premier fichier et le flux audio de votre second fichier, puis les écrit dans un seul MP4.

Votre bande sonore originale n'est pas conservée. Le nouveau fichier audio devient la seule piste audio dans l'exportation. Cela est utile lorsque votre clip est silencieux, bruyant, muet par une plateforme ou exporté avec la mauvaise prise audio.

Le flux vidéo est copié lorsque c'est possible, donc l'image n'est pas recompressée simplement parce que vous avez changé l'audio. Si le codec vidéo ne peut pas être copié proprement dans un MP4, vous aurez peut-être besoin d'un autre flux de travail dans l'éditeur complet.

L'idée clé est simple : vous remplacez une piste, vous ne reconstruisez pas tout le montage.

## Remplacement audio vs édition complète

| Ce dont vous avez besoin | Utilisez cet outil rapide | Utilisez GrepCut Studio |
| --- | --- | --- |
| Remplacer un mauvais audio de caméra par un MP3 ou WAV séparé | Oui, c'est le flux principal | Seulement si vous avez aussi besoin de modifications |
| Ajouter une voix off à un enregistrement d'écran silencieux | Oui, si un seul fichier audio suffit | Utilisez-le pour des ajustements de timing |
| Garder l'audio original et ajouter de la musique par-dessus | Non, l'audio original est remplacé | Oui, utilisez plusieurs pistes |
| Faire un fondu d'entrée ou de sortie de la musique | Non, remplacement rapide uniquement | Oui, utilisez les contrôles de volume |
| Corriger un audio qui commence en retard ou en avance | Pas de contrôles de synchronisation précis ici | Oui, alignez-le sur la timeline |

Utilisez l'outil rapide lorsque votre vidéo et votre fichier audio de remplacement correspondent déjà bien. Utilisez le Studio lorsque votre audio nécessite des modifications, un mixage ou un travail de synchronisation.

## Formats vidéo et audio pris en charge

Commencez avec un fichier vidéo. GrepCut est conçu pour les entrées MP4, MOV, WebM, MKV, M4V, AVI, OGV, 3GP et MPEG, ainsi que d'autres fichiers vidéo lisibles lorsque le navigateur et FFmpeg peuvent les analyser.

Ajoutez ensuite un fichier audio. MP3, WAV, AAC, M4A, FLAC, OGG et Opus sont les entrées audio testées. La sortie est toujours un MP4, ce qui rend le résultat plus facile à partager, à lire et à importer dans les applications courantes.

### Quelques notes pratiques sur les formats :

- **MP4 et MOV**: bons pour les clips de téléphone, les enregistrements d'écran, les exportations de caméra et les brouillons de réseaux sociaux.
- **WebM et MKV**: utiles lorsque votre source provient d'un enregistreur de navigateur, d'un téléchargement ou d'un flux de travail open source.
- **WAV et FLAC**: bons pour une voix off propre ou des masters musicaux avant la création du MP4 final.
- **OGG et Opus**: utiles pour l'audio enregistré par des applications web, des jeux ou des outils médias ouverts.

Si un fichier s'ouvre mais que l'exportation échoue, le coupable habituel n'est pas l'extension du fichier. C'est le codec à l'intérieur du conteneur.

## Pourquoi votre exportation s'arrête au fichier le plus court

GrepCut réduit l'exportation à l'entrée la plus courte afin que vous n'ayez pas une longue queue noire, une fin silencieuse ou un fichier audio supplémentaire caché après la fin de l'image. Si votre chanson est plus longue que le clip, la chanson est coupée à la fin de la vidéo. Si votre voix off est plus courte que le clip, la vidéo exportée se termine lorsque la voix off se termine.

Ce comportement est intentionnel pour un outil de remplacement rapide. Il rend le résultat prévisible sans ajouter de boucle, de remplissage, de fondus ou de génération de silence. Pour ces choix de synchronisation, utilisez la timeline complète dans GrepCut Studio.

## Ce que vous obtenez avec un remplacement audio dans le navigateur

### Advantages

- Votre vidéo et votre fichier audio restent sur votre appareil, sans envoi vers un serveur.
- L'image n'est pas ré-encodée lorsque la copie de flux est possible.
- Vous obtenez un MP4 plus facile à lire et à partager.
- Vous pouvez remplacer un fichier audio bruyant, muet ou incorrect sans ouvrir une timeline complète.
- Vous pouvez utiliser des entrées vidéo courantes et des formats audio courants.

### Disadvantages

- Un seul fichier audio de remplacement est utilisé.
- L'audio original est supprimé au lieu d'être mixé en dessous.
- Les changements de volume, les fondus, le ducking et la synchronisation exacte nécessitent GrepCut Studio.
- Les très gros fichiers dépendent de la mémoire de votre appareil et des limites du navigateur.
- Certains codecs inhabituels peuvent nécessiter une conversion avant de pouvoir tenir dans un MP4.

> le rendu rend la vidéo 3 fois plus grande ou il y a une perte de qualité significative pour la même taille de fichier
>
> Reddit r/davinciresolve

## FAQ sur l'ajout d'un fichier audio à une vidéo

### Pouvez-vous remplacer l'audio d'un MP4 sans rendre la vidéo à nouveau ?

Oui, lorsque le flux vidéo peut être copié dans le MP4 de sortie. GrepCut essaie de copier le flux image au lieu de le ré-encoder, donc changer la bande sonore n'entraîne pas automatiquement une perte de qualité d'image.

### Votre vidéo ou votre fichier audio sera-t-il téléchargé ?

Non. GrepCut effectue le remplacement audio localement dans votre navigateur en utilisant FFmpeg compilé en WebAssembly. Vos fichiers restent sur votre appareil.

### Pouvez-vous conserver le son original et ajouter de la musique par-dessus ?

Pas dans cet outil rapide. Le fichier audio de remplacement devient la seule bande sonore. Utilisez [GrepCut Studio](/) si vous avez besoin que la musique, le dialogue et les effets sonores jouent ensemble.

### Que se passe-t-il si votre fichier audio est plus long que votre vidéo ?

L'exportation s'arrête à la fin du fichier le plus court. Si votre fichier audio est plus long que la vidéo, il est coupé. Si votre fichier audio est plus court, la vidéo se termine avec lui.

### Pouvez-vous synchroniser un fichier audio qui commence trop tôt ou trop tard ?

Cet outil n'inclut pas de contrôles de décalage. Si votre voix off nécessite un alignement au niveau de l'image, ouvrez la vidéo dans [GrepCut Studio](/) et déplacez l'audio sur la timeline.

### À quels formats pouvez-vous ajouter un fichier audio ?

Vous pouvez commencer avec une vidéo MP4, MOV, WebM, MKV, M4V, AVI, OGV, 3GP ou MPEG. Votre fichier audio de remplacement peut être MP3, WAV, AAC, M4A, FLAC, OGG ou Opus. Le fichier téléchargé est au format MP4.

### Pourquoi GrepCut exporte-t-il en MP4 au lieu de conserver le conteneur d'origine ?

Le MP4 est largement pris en charge par les navigateurs, les téléphones, les éditeurs et les applications sociales. Garder un seul conteneur de sortie rend également l'outil rapide plus simple et plus prévisible.

### Votre fichier perdra-t-il en qualité ?

L'image devrait rester la même lorsque la copie de flux fonctionne. L'audio est extrait de votre fichier de remplacement et multiplexé dans la sortie, donc le résultat dépend de la qualité du fichier audio que vous fournissez.

## Sources et lectures complémentaires

- [Discussion Reddit sur le remplacement de l'audio d'un MP4 sans rendu](https://www.reddit.com/r/davinciresolve/comments/1fnsfjb/how_do_i_replace_the_audio_of_an_mp4_without/)
- [Fil Super User sur le remplacement de l'audio dans une vidéo avec FFmpeg](https://superuser.com/questions/1137612/ffmpeg-replace-audio-in-video)
- [Fil Super User sur le comportement de la durée audio et vidéo](https://superuser.com/questions/801547/ffmpeg-add-audio-but-keep-video-length-the-same-not-shortest)
- [Discussion Reddit sur l'édition audio sans ré-encoder la vidéo](https://www.reddit.com/r/VideoEditing/comments/v1n6tu/edit_audio_without_reencoding_video/)
- [Documentation FFmpeg sur les spécificateurs de flux et la copie de codec](https://ffmpeg.org/ffmpeg.html)
- [Guide MDN sur les formats de conteneurs multimédia](https://developer.mozilla.org/fr/docs/Web/Media/Formats/Containers)

## Remplacez la bande sonore de votre vidéo en privé

Ouvrez GrepCut, ajoutez votre vidéo et votre fichier audio de remplacement, puis exportez un MP4 sans envoyer vos fichiers.

## Outils connexes

- [Mettre la vidéo en sourdine](https://grepcut.com/fr/tools/mute-video) - supprimez la bande sonore avant d’en ajouter une nouvelle.
- [Découper une vidéo](https://grepcut.com/fr/tools/video-trimmer) - découpez votre clip avant de remplacer l’audio.
- [Incruster des sous-titres SRT](https://grepcut.com/fr/tools/burn-srt-subtitles-to-video) - incrustez les sous-titres après avoir remplacé la bande sonore.

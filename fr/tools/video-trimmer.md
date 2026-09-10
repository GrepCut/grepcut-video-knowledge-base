# Coupe-vidéo en ligne gratuit

Coupez une vidéo pour n'en garder que la partie souhaitée en moins de 2 secondes. Grâce à la copie de flux sans perte alignée sur les images clés, tout se fait localement dans votre navigateur, sans téléversement ni perte de qualité.

HTML: https://grepcut.com/fr/tools/video-trimmer

## Comment couper une vidéo dans votre navigateur

1. **Ajoutez votre vidéo**: Déposez votre fichier sur le coupe-vidéo ou cliquez pour parcourir. Votre vidéo se charge localement dans l'aperçu.
2. **Choisissez la partie souhaitée**: Faites glisser les poignées de début et de fin, puis prévisualisez la plage avant d'exporter.
3. **Exportez votre découpe**: Créez un MP4 découpé à l'aide d'une copie de flux alignée sur les images clés, ou continuez l'édition dans GrepCut Studio.

Besoin de plusieurs découpes, de sous-titres, de musique ou de supprimer une section au milieu ? Ouvrez le clip dans [GrepCut Studio](/).

## Pourquoi vos vidéos s'exportent si rapidement

Lorsque vous avez seulement besoin de couper le début ou la fin d'un clip, téléverser l'intégralité du fichier sur un serveur peut sembler superflu. GrepCut conserve votre fichier sur votre appareil et le découpe directement dans votre navigateur.

Le coupe-vidéo utilise WebCodecs et MediaBunny pour lire le fichier multimédia, copier les paquets vidéo et audio déjà encodés, et les remuxer dans un nouveau MP4. Comme votre navigateur n'a pas besoin de décoder et ré-encoder chaque image, l'exportation se termine généralement en quelques secondes.

### Vous obtenez une découpe rapide car GrepCut évite la partie la plus lente du montage :

- **Pas de transcodage complet**: La plage sélectionnée est copiée à partir du flux source au lieu d'être ré-encodée depuis zéro.
- **Pas de file d'attente de téléversement**: Votre fichier reste local, vous n'attendez donc pas un téléversement sur le serveur avant de commencer la découpe.
- **Pas de perte de qualité générationnelle**: Le chemin de copie de flux préserve le média encodé d'origine dans la plage exportée.

## Ce que signifie une découpe alignée sur les images clés pour vous

Une vidéo compressée n'est pas simplement une pile d'images complètes. La plupart des images dépendent des images voisines, et les images clés sont les points sûrs où la lecture peut démarrer proprement.

C'est pourquoi un coupe-vidéo sans perte par copie de flux peut aligner votre découpe sur l'image clé utilisable la plus proche plutôt que de couper sur une image arbitraire. Vous obtenez un MP4 rapide et conforme aux normes, mais le début ou la fin exporté peut être légèrement plus tôt ou plus tard que la position de la poignée.

Si vous avez besoin d'une découpe image par image, d'effets visuels, de transitions ou d'une coupe au milieu d'un clip, utilisez l'éditeur complet plutôt que le coupe-vidéo à une seule plage.

## Coupe-vidéo navigateur vs Coupe-vidéo en ligne traditionnel

| Ce dont vous avez besoin | Coupe-vidéo GrepCut | Coupe-vidéo serveur typique |
| --- | --- | --- |
| Confidentialité | Votre vidéo reste sur votre appareil | Votre vidéo est téléversée avant traitement |
| Vitesse | Copie de flux rapide pour une plage continue | Temps de téléversement plus traitement serveur |
| Qualité | Préserve la qualité source pour la plage copiée | Peut ré-encoder et ajouter une perte de génération |
| Précision de coupe | Alignée sur les images clés vidéo sûres | Peut être image par image si le serveur ré-encode |
| Meilleure utilisation | Supprimer rapidement le début ou la fin d'un clip | Montages plus lourds, changements de format ou exportations image par image |

Choisissez GrepCut pour une découpe privée, rapide et sans téléversement. Choisissez un éditeur complet lorsque votre montage nécessite un timing image par image ou plusieurs plages séparées.

## Avant de couper

### Advantages

- Votre fichier n'est pas téléversé sur un serveur.
- L'aperçu se met à jour pendant que vous ajustez la plage.
- La copie de flux conserve la plage sélectionnée à la qualité source.
- Pas de filigrane, pas de compte et pas d'installation.

### Disadvantages

- Les points de coupe sont alignés sur les images clés voisines.
- Les très gros fichiers dépendent de la mémoire de votre appareil.
- Cet outil ne conserve qu'une seule plage continue.
- Vous avez besoin d'un navigateur prenant en charge WebCodecs.

> vous ne pouvez couper une vidéo que sur une image clé (sans encodage)
>
> Discussion Reddit r/ffmpeg

## FAQ du coupe-vidéo

### Votre vidéo est-elle téléversée lorsque vous la coupez ?

Non. Votre fichier est traité localement dans votre navigateur, il ne quitte donc pas votre appareil.

### Couper une vidéo réduit-il sa qualité ?

Aucune perte de qualité n'est introduite sur le chemin de copie de flux. GrepCut copie le média encodé de votre plage sélectionnée et le remuxe dans un nouveau MP4.

### Pourquoi votre découpe n'est-elle pas image par image ?

La découpe vidéo sans perte doit respecter les images clés. Si votre heure de début ou de fin choisie tombe entre des images clés, GrepCut aligne la coupe sur un point sûr proche afin que le MP4 exporté soit lisible correctement.

### Pouvez-vous couper le milieu d'une vidéo ?

Ce coupe-vidéo conserve une seule plage continue. Si vous devez supprimer une section au milieu ou effectuer plusieurs coupes, ouvrez le clip dans [GrepCut Studio](/).

### Pouvez-vous couper un fichier vidéo volumineux ?

Oui, mais votre navigateur et la mémoire de votre appareil comptent toujours. Comme le fichier est traité localement, les très grandes vidéos peuvent être limitées par votre ordinateur plutôt que par une limite de téléversement.

### Quels navigateurs fonctionnent le mieux ?

Utilisez un navigateur prenant en charge WebCodecs, comme Chrome, Edge ou Opera. Si votre navigateur ne prend pas en charge les API multimédia requises, le coupe-vidéo peut ne pas fonctionner.

### Quel fichier obtenez-vous après la découpe ?

Vous exportez un MP4 contenant la plage continue sélectionnée. L'objectif est d'obtenir un fichier largement lisible sans téléverser ni transcoder l'intégralité de votre vidéo.

## Sources et lectures complémentaires

- [Discussion Reddit sur la coupe vidéo sans ré-encodage sur les images clés](https://www.reddit.com/r/ffmpeg/comments/10tj7nu/can_you_only_cut_videos_without_reencoding_on/)
- [Discussion Reddit sur le découpage vidéo sans ré-encodage](https://www.reddit.com/r/ffmpeg/comments/1qag2ug/trimming_video_without_reencoding/)
- [Discussion Super User sur la coupe vidéo avec peu ou pas de ré-encodage](https://superuser.com/questions/1850814/how-to-cut-a-video-with-ffmpeg-with-no-or-minimal-re-encoding)
- [Discussion Super User sur la coupe vidéo rapide et la copie de flux](https://superuser.com/questions/1643484/fast-and-relatively-accurate-cutting-from-a-video)
- [Aperçu de l'API WebCodecs sur MDN](https://developer.mozilla.org/en-US/docs/Web/API/WebCodecs_API)
- [MediaBunny boîte à outils multimédia pour navigateur](https://mediabunny.dev/)

## Coupez votre clip, puis continuez le montage

Utilisez le coupe-vidéo pour une découpe privée et rapide. Lorsque votre clip a besoin de sous-titres, de musique, de modifications de mise en page ou d'une timeline complète, ouvrez-le dans GrepCut Studio et continuez à construire dans le navigateur.

## Outils connexes

- [Recadrer une vidéo](https://grepcut.com/fr/tools/crop-video) - recadrez votre clip dans une région ou un rapport hauteur/largeur.
- [Redimensionner une vidéo](https://grepcut.com/fr/tools/resize-video) - mettez à l'échelle les clips découpés vers une nouvelle résolution ou un nouveau rapport hauteur/largeur.
- [Couper le son d'une vidéo](https://grepcut.com/fr/tools/mute-video) - supprimez la piste audio de votre clip.

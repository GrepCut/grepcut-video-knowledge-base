# Couper le son d'une vidéo en ligne

Supprimez instantanément le son de n'importe quelle vidéo grâce au remuxage sans perte du conteneur. Tout s'exécute localement sur votre appareil : aucun envoi, aucune perte de qualité, aucun filigrane.

HTML: https://grepcut.com/fr/tools/mute-video

## Comment couper le son d'une vidéo dans votre navigateur

1. **Ajoutez votre vidéo**: Déposez votre fichier MP4, MOV, WebM, MKV ou un autre format vidéo courant dans la zone de dépôt, ou cliquez pour parcourir.
2. **Laissez GrepCut supprimer l'audio**: L'outil supprime automatiquement toute la piste audio, vous n'avez donc pas à choisir de codecs, de canaux ou de paramètres d'exportation.
3. **Téléchargez la vidéo silencieuse**: Enregistrez le MP4 sans son, ou ouvrez-le dans GrepCut Studio si vous souhaitez ajouter de la musique, des sous-titres ou une voix off ensuite.

Besoin de couper le son seulement quelques secondes, de baisser une section bruyante ou de remplacer la bande sonore ? Ouvrez votre fichier dans [GrepCut Studio](/) pour un contrôle sur la timeline.

## Quand supprimer complètement le son

Utilisez cet outil lorsque l'audio ne vaut pas la peine d'être conservé. Si votre clip contient du vent, de la circulation, du bruit de manipulation de la caméra, une conversation privée ou de la musique que vous ne pouvez pas utiliser, couper le son de toute la piste vous donne un fichier vidéo propre que vous pouvez partager ou reconstruire.

C'est différent d'une réparation audio. Si vous devez conserver une voix et supprimer uniquement la musique, un sifflement ou un bruit de fond unique, vous avez besoin d'une séparation audio, pas d'une simple coupure du son. GrepCut Couper le son d'une vidéo supprime toute la piste audio, de sorte que le résultat est silencieux du début à la fin.

### Bons cas pour une coupure du son en un clic :

- **B-roll silencieux**: Transformez des séquences de téléphone, des plans de produits ou des clips de voyage en visuels propres pour un montage.
- **Audio privé**: Supprimez les conversations, les noms ou le bruit ambiant avant d'envoyer le clip à quelqu'un d'autre.
- **Préparation d'une nouvelle bande sonore**: Créez une base silencieuse avant d'ajouter de la musique sous licence, une narration ou des sous-titres dans un éditeur complet.

Si vous avez seulement besoin de l'audio et non de la vidéo, utilisez plutôt [Vidéo vers MP3](/converters/video-to-mp3).

## Votre vidéo perdra-t-elle en qualité ?

Pour les fichiers MP4 ou MOV standard qui utilisent déjà H.264 ou H.265, GrepCut supprime la piste audio et copie le flux vidéo. Cela signifie que les images visibles restent intactes, donc la coupure du son est rapide et sans perte pour la piste vidéo.

Si votre fichier utilise un format nécessitant une exportation de compatibilité, comme WebM avec VP9 ou AV1, GrepCut le convertit en MP4 H.264 standard. Cela prend plus de temps car le navigateur doit encoder un nouveau fichier vidéo.

### La règle pratique :

- **MP4 ou MOV avec H.264/H.265**: le flux vidéo peut généralement être copié sans ré-encodage.
- **WebM, VP9 ou AV1**: l'outil peut transcoder vers H.264 MP4 pour une meilleure compatibilité de lecture.
- **Fichiers volumineux**: la mémoire de votre appareil et les performances du navigateur comptent car le travail s'effectue localement.

## Couper le son vs Nettoyage audio vs Montage sur timeline

| Ce dont vous avez besoin | Utiliser Couper le son | Utiliser une autre méthode |
| --- | --- | --- |
| Supprimer tous les sons du clip | Oui. Toute la piste audio est supprimée. | Pas nécessaire sauf si vous voulez aussi rogner ou ajouter un nouvel audio. |
| Garder le dialogue mais supprimer la musique | Non. Cet outil ne sépare pas les sons mélangés. | Utilisez une méthode dédiée de séparation ou de restauration audio. |
| Couper le son d'une seule partie de la vidéo | Non. L'outil rapide coupe le son de tout le fichier. | Utilisez GrepCut Studio ou un autre éditeur avec timeline. |
| Éviter le ré-encodage de la vidéo H.264/H.265 | Oui, lorsque le conteneur et le codec permettent une copie du flux vidéo. | Les outils de remuxage sur bureau peuvent faire la même chose avec plus de réglages manuels. |
| Traiter par lots des milliers de clips | Ce n'est pas le but de cet outil pour fichier unique dans le navigateur. | Utilisez un traitement par lots sur ordinateur si vous avez besoin de tâches massives sans surveillance. |

Une coupure rapide du son est idéale lorsque votre objectif est simple : rendre tout le clip silencieux sans l'envoyer.

## Couper le son dans le navigateur : ce que vous gagnez et ce à quoi faire attention

### Advantages

- Votre vidéo reste sur votre appareil, vous n'envoyez donc pas de séquences privées.
- Aucun filigrane n'est ajouté à l'exportation sans son.
- La vidéo H.264 et H.265 peut être copiée sans perte de qualité visible.
- Vous pouvez passer directement à GrepCut Studio lorsque vous voulez des sous-titres, de la musique ou un rognage.

### Disadvantages

- Les fichiers volumineux dépendent de la mémoire de votre appareil et des performances du navigateur.
- L'outil supprime toute la piste audio, pas une section chronométrée.
- L'audio mixte, comme la musique sous la parole, ne peut pas être séparé par une simple coupure du son.
- Les fichiers WebM, VP9 et AV1 peuvent nécessiter un transcodage vers MP4 H.264.
- Nécessite un navigateur de bureau compatible WebCodecs, comme Chrome, Edge ou Opera.

> Pensez-y comme essayer d'enlever la crème de votre café.
>
> Reddit r/VideoEditing

## Pourquoi le fichier reste privé

GrepCut exécute l'opération de coupure du son dans votre navigateur. Votre vidéo n'a pas besoin d'être envoyée sur un serveur juste pour supprimer la piste audio.

Ce traitement local est utile lorsque votre clip contient des visages, des séquences clients, des enregistrements internes ou tout ce que vous préférez ne pas envoyer à un service tiers. Vous obtenez toujours une exportation MP4 normale prête à être partagée.

## FAQ sur la coupure du son d'une vidéo

### Pouvez-vous couper le son d'une vidéo sans perte de qualité ?

Oui, lorsque votre vidéo peut être remuxée. Pour les fichiers MP4 ou MOV avec H.264 ou H.265, GrepCut supprime la piste audio et conserve le flux vidéo tel quel. Si votre fichier nécessite un transcodage, l'exportation est convertie en MP4 H.264 standard.

### Votre vidéo sera-t-elle envoyée ?

Non. Le fichier est traité localement dans votre navigateur, donc votre vidéo reste sur votre appareil.

### Pouvez-vous supprimer la musique mais garder les voix ?

Pas avec cet outil de coupure rapide. Si la musique, les voix et les bruits de fond sont mélangés dans la même piste audio, la coupure du son les supprime tous. Pour garder le dialogue, vous avez besoin d'une séparation audio ou d'un montage complet.

### Pouvez-vous couper le son d'une seule partie d'une vidéo ?

Cet outil supprime tout l'audio du clip. Si vous devez couper le son d'une section spécifique, baisser un moment bruyant ou remplacer le son, ouvrez la vidéo dans [GrepCut Studio](/).

### Quels formats vidéo pouvez-vous couper le son ?

Vous pouvez couper le son de fichiers vidéo courants tels que MP4, MOV, WebM et MKV. La vidéo H.264 et H.265 peut généralement être copiée sans ré-encodage, tandis que les sources WebM, VP9 ou AV1 peuvent être transcodées en MP4 H.264.

### Pourquoi votre exportation WebM prend-elle plus de temps ?

Les fichiers WebM utilisent souvent VP9 ou AV1. GrepCut peut convertir ces vidéos en MP4 H.264 pour la compatibilité, donc le navigateur doit encoder un nouveau fichier au lieu de simplement supprimer la piste audio.

### La vidéo sans son sera-t-elle plus petite ?

Généralement, la suppression de la piste audio réduit un peu la taille du fichier. La taille finale dépend toujours de votre format d'origine et si la piste vidéo peut être copiée ou doit être transcodée.

### Pouvez-vous ajouter de la nouvelle musique après avoir coupé le son ?

Oui. Téléchargez le MP4 silencieux pour un autre éditeur, ou ouvrez-le dans [GrepCut Studio](/) pour ajouter un nouveau fond musical, une voix off, des sous-titres ou des rognages.

## Sources et lectures complémentaires

- [Discussion Reddit sur la suppression de l'audio sans compresser la vidéo](https://www.reddit.com/r/editors/comments/1dp24dn/removing_audio_from_footage_without_compressing/)
- [Discussion Reddit sur la suppression en masse de l'audio des vidéos](https://www.reddit.com/r/VideoEditing/comments/10ndkj7/how_can_i_bulk_remove_audio_tracks_from_multiple/)
- [Discussion Reddit sur pourquoi séparer le dialogue de la musique est difficile](https://www.reddit.com/r/VideoEditing/comments/17m1d06/how_can_i_remove_a_song_including_vocals_but/)
- [Q&A Super User sur l'extraction de l'audio d'un fichier vidéo](https://superuser.com/questions/268985/remove-audio-from-video-file-with-ffmpeg)
- [Q&A Stack Overflow sur la coupure du son d'une partie seulement d'un MP4](https://stackoverflow.com/questions/54992785/ffmpeg-remove-a-part-of-audio-in-mp4-file-but-not-all)
- [Guide MDN sur les formats de conteneurs multimédia](https://developer.mozilla.org/fr/docs/Web/Media/Formats/Containers)
- [Aperçu de l'API WebCodecs MDN](https://developer.mozilla.org/fr/docs/Web/API/WebCodecs_API)

## Outils connexes

- [Rogner une vidéo](https://grepcut.com/fr/tools/video-trimmer) - coupez votre clip avant ou après avoir coupé le son.
- [Ajouter de l'audio à une vidéo](https://grepcut.com/fr/tools/add-audio-to-video) - remplacez ou ajoutez une nouvelle bande sonore après avoir coupé le son.
- [Vidéo vers MP3](https://grepcut.com/fr/converters/video-to-mp3) - extrayez l'audio au lieu de le supprimer.

## Besoin de plus qu'une exportation silencieuse ?

Ouvrez GrepCut Studio lorsque vous voulez rogner, ajouter des sous-titres, remplacer la bande sonore ou faire un montage complet après avoir coupé le son de votre vidéo. Vos séquences restent toujours dans votre navigateur.

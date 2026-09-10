# Rotation de vidéo en ligne

Redressez les vidéos filmées en mode paysage ou retournez vos clips pour les réseaux sociaux. Traité localement dans votre navigateur - sans envoi, sans filigrane.

HTML: https://grepcut.com/fr/tools/rotate-video

## Comment faire pivoter une vidéo dans votre navigateur

1. **Ajoutez votre vidéo**: Déposez votre MP4, MOV, WebM, MKV ou M4V dans l'outil, ou cliquez pour parcourir. Votre fichier reste sur votre appareil pendant que le navigateur prépare l'aperçu.
2. **Choisissez l'angle**: Sélectionnez 90° dans le sens horaire, 180° ou 90° dans le sens antihoraire. Utilisez l'aperçu pour vérifier que votre clip de téléphone est à l'endroit avant d'exporter.
3. **Sélectionnez le mode d'exportation**: Utilisez « Prêt pour les réseaux » lorsque vous souhaitez que la rotation soit intégrée dans les pixels, ou « Remux rapide » si vous avez seulement besoin de modifier le drapeau de rotation du MP4.
4. **Téléchargez votre MP4**: Cliquez sur « Pivoter » pour exporter votre vidéo corrigée au format MP4. Vous pouvez également ouvrir le clip dans GrepCut Studio si vous avez besoin de recadrer, redimensionner, ajouter des sous-titres ou des modifications sur la timeline.

Besoin de plus qu'une rotation ? Ouvrez votre clip dans [GrepCut Studio](/) et continuez l'édition dans le navigateur.

## Pourquoi votre vidéo de téléphone apparaît de travers

Une vidéo de téléphone peut sembler correcte dans votre galerie mais de travers dans une autre application car le fichier peut stocker un drapeau de rotation au lieu de pixels droits. Lorsqu'un lecteur ou un site respecte ce drapeau, votre clip s'affiche correctement. Lorsqu'il l'ignore, votre vidéo apparaît pivotée même si l'enregistrement n'est pas défectueux.

GrepCut vous offre deux solutions à ce problème. Le mode « Prêt pour les réseaux » fait pivoter physiquement les images et efface le drapeau de rotation, ce qui est le choix le plus sûr avant de publier. Le « Remux rapide » conserve le flux vidéo d'origine et met à jour les métadonnées de rotation, ce qui est plus rapide mais dépend de la capacité de l'application suivante à lire correctement le drapeau.

### Utilisez cet outil lorsque :

- **Votre clip de téléphone est de travers**: Redressez les vidéos en mode portrait ou paysage avant de les envoyer.
- **Votre vidéo est à l'envers**: Effectuez une rotation de 180° lorsque l'orientation de la caméra était incorrecte lors de l'enregistrement.
- **Votre application ignore les métadonnées de rotation**: Intégrez la rotation dans les pixels pour que le résultat ne dépende pas d'un drapeau caché.
- **Vous avez besoin d'une exportation MP4 rapide**: Enregistrez un MP4 corrigé sans ouvrir un éditeur vidéo de bureau.

Si vous publiez sur Instagram, TikTok, YouTube ou un autre site qui peut retraiter le fichier, choisissez **Prêt pour les réseaux** pour un résultat plus prévisible.

## Prêt pour les réseaux vs Remux rapide

| Besoin | Prêt pour les réseaux | Remux rapide |
| --- | --- | --- |
| Ce qui change | Fait pivoter les images vidéo réelles et efface le drapeau de rotation | Conserve les images d'origine et met à jour les métadonnées de rotation du MP4 |
| Vitesse | Plus lent car la vidéo est ré-encodée en H.264 | Presque instantané car les paquets vidéo compressés sont copiés |
| Qualité | Exportation H.264 de haute qualité, mais il s'agit toujours d'un ré-encodage | Identique au flux vidéo source |
| Idéal pour les publications sur les réseaux | Meilleur choix lorsque l'application suivante peut ignorer les métadonnées de rotation | Fonctionne uniquement lorsque l'application suivante respecte le drapeau de rotation |
| Résultat | Pixels droits dans un fichier MP4 | Mêmes pixels avec une instruction de rotation corrigée |

Les deux modes s'exécutent localement dans votre navigateur. Votre vidéo d'origine n'est pas envoyée et l'exportation ne comporte aucun filigrane.

## Quand ré-encoder plutôt que remuxer

Le remux rapide est utile lorsque vous souhaitez une correction locale rapide et que vous savez que le lecteur suivant lit les métadonnées de rotation MP4. Cela peut être le bon choix pour prévisualiser, archiver ou envoyer un fichier à une application qui gère déjà correctement les drapeaux de rotation.

Le mode « Prêt pour les réseaux » est meilleur lorsque le clip sera envoyé, compressé à nouveau ou ouvert sur différents appareils. En écrivant des pixels droits dans le MP4, vous éliminez les incertitudes. Votre exportation peut prendre plus de temps, mais le fichier est plus facile à afficher correctement pour les plateformes sociales et les lecteurs basiques.

### Une règle simple :

Si la vidéo est destinée à être publiée, choisissez **Prêt pour les réseaux**. Si la vidéo est pour votre propre appareil et que vous souhaitez la correction la plus rapide possible, essayez **Remux rapide**.

## Rotation de vidéo en un coup d'œil

### Advantages

- Traitement privé sans envoi vers un serveur.
- Options de rotation à 90°, 180° et 270°.
- Exportation MP4 prête pour les réseaux pour une orientation prévisible.
- Option de remux rapide lorsque vous avez seulement besoin d'une correction des métadonnées.
- Exportation gratuite sans filigrane.

### Disadvantages

- Le mode « Prêt pour les réseaux » ré-encode la vidéo, donc l'exportation prend plus de temps que le remux.
- Le remux rapide dépend de la capacité de l'application suivante à honorer les métadonnées de rotation.
- Seules les rotations à angle droit sont prises en charge, pas les angles arbitraires.
- Nécessite un navigateur moderne avec prise en charge de WebCodecs.

> observé par certains lecteurs et pas par d'autres
>
> Discussion Stack Overflow sur les métadonnées de rotation MP4

## Rotation de vidéo - FAQ

### Pouvez-vous faire pivoter une vidéo sans l'envoyer ?

Oui. GrepCut exécute le processus de rotation dans votre navigateur, donc votre fichier reste sur votre appareil au lieu d'être envoyé sur un serveur.

### Pourquoi votre MP4 apparaît-il de travers dans une application mais correct dans une autre ?

Votre MP4 peut contenir des métadonnées de rotation. Certains lecteurs lisent cette instruction et font pivoter la vidéo pendant la lecture, tandis que d'autres applications l'ignorent. Utilisez le mode **Prêt pour les réseaux** lorsque vous souhaitez que le MP4 exporté contienne des pixels droits au lieu de dépendre des métadonnées.

### Devriez-vous utiliser « Prêt pour les réseaux » ou « Remux rapide » ?

Utilisez **Prêt pour les réseaux** lorsque vous prévoyez de publier le clip en ligne ou de l'envoyer à une application qui peut ignorer les drapeaux de rotation. Utilisez **Remux rapide** lorsque vous souhaitez l'exportation la plus rapide et que le lecteur suivant est susceptible de respecter les métadonnées de rotation MP4.

### Faire pivoter votre vidéo réduira-t-il la qualité ?

Le remux rapide conserve le flux vidéo d'origine inchangé, donc le flux vidéo reste identique. Le mode « Prêt pour les réseaux » ré-encode en H.264 pour que la rotation soit intégrée dans les pixels, ce qui est plus fiable pour la publication mais prend plus de temps.

### Quels formats vidéo pouvez-vous faire pivoter ?

Vous pouvez ajouter des MP4, MOV, WebM, MKV, M4V et la plupart des formats vidéo courants. GrepCut exporte le résultat pivoté au format MP4.

### Votre audio restera-t-il synchronisé après la rotation ?

Oui. La rotation ne modifie pas la vitesse de lecture. L'audio est copié sans perte lorsqu'il est déjà en AAC, ou ré-encodé en AAC pour une large compatibilité MP4.

### Pouvez-vous faire pivoter selon un angle personnalisé comme 12° ?

Non. Cet outil est conçu pour les corrections à angle droit : 90° dans le sens horaire, 180° et 90° dans le sens antihoraire. Pour les vidéos de téléphone de travers, ce sont généralement les corrections dont vous avez besoin.

### Pourquoi GrepCut nécessite-t-il un navigateur moderne ?

L'exportation « Prêt pour les réseaux » dépend des fonctionnalités de traitement vidéo du navigateur telles que WebCodecs. Si votre navigateur ne prend pas en charge les API requises, essayez un navigateur basé sur Chromium à jour.

## Sources et lectures complémentaires

- [Discussion Reddit sur le tournage accidentel en mode portrait](https://www.reddit.com/r/VideoEditing/comments/xryq3n/i_accidentally_filmed_my_videos_in_portrait_mode/)
- [Question Reddit sur la rotation sans ré-encodage](https://www.reddit.com/r/VideoEditing/comments/uuw62f/automatically_rotate_video_without_actually/)
- [Explication Super User des métadonnées de rotation des vidéos iPhone](https://superuser.com/questions/564233/iphone-recorded-videos-getting-rotated-on-windows-systems)
- [Discussion Stack Overflow sur les drapeaux de rotation MP4](https://stackoverflow.com/questions/69386275/mp4-and-rotation-remove-flags-but-set-rotation)
- [Guide MDN sur l'API WebCodecs](https://developer.mozilla.org/en-US/docs/Web/API/WebCodecs_API)
- [Spécification W3C WebCodecs](https://www.w3.org/TR/webcodecs/)

## Rotation terminée ? Réalisez le montage complet

Ouvrez GrepCut Studio pour recadrer, redimensionner, ajouter des sous-titres, ajouter de la musique et terminer votre montage vidéo dans le navigateur.

## Outils connexes

- [Recadrer une vidéo](https://grepcut.com/fr/tools/crop-video) - recadrez votre cadre à une région ou un rapport hauteur/largeur.
- [Redimensionner une vidéo](https://grepcut.com/fr/tools/resize-video) - mettez votre clip à l'échelle par pourcentage.
- [Couper une vidéo](https://grepcut.com/fr/tools/video-trimmer) - coupez votre clip avant ou après la rotation.

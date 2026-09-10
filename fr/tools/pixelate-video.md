# Pixeliser une vidéo en ligne

Appliquez un effet de mosaïque à chaque image de votre clip. Tout est rendu localement sur votre appareil - pas d'envoi, pas de filigrane, pas de compte.

HTML: https://grepcut.com/fr/tools/pixelate-video

## Comment pixeliser une vidéo dans votre navigateur

1. **Ajoutez votre fichier vidéo**: Déposez votre clip MP4, MOV, WebM ou MKV dans la zone de dépôt.
2. **Choisissez la taille du bloc de pixels**: Sélectionnez une petite taille de bloc pour une mosaïque plus fine ou une grande taille pour un effet de blocage plus fort.
3. **Pixelisez et exportez**: Cliquez sur Pixeliser et exporter pour générer la mosaïque localement et télécharger le MP4.

Votre vidéo est traitée dans votre navigateur, vous pouvez donc ajouter un effet de pixelisation sans envoyer le fichier à un serveur.

## Quand un effet mosaïque plein écran a du sens

Pixeliser une vidéo transforme chaque image en blocs carrés visibles. C'est un bon choix lorsque vous souhaitez un style visuel rétro, un aperçu de type confidentialité, ou un simple aspect de censure plein écran sur l'ensemble du clip.

Cet outil applique la mosaïque à l'ensemble du cadre du début à la fin. Si vous avez seulement besoin de masquer un visage, une plaque d'immatriculation, un message de chat ou un petit objet, utilisez plutôt [Flouter une région vidéo](/tools/blur-region-video) pour que le reste de votre clip reste clair.

### Utilisez la pixelisation lorsque vous voulez que la modification soit évidente

- **Modifications stylisées**: Vous pouvez donner à un clip l'apparence d'un jeu vidéo basse résolution, d'un art glitch ou d'un segment de diffusion censuré.
- **Aperçus privés**: Vous pouvez rendre l'ensemble du cadre plus difficile à lire avant de partager un brouillon ou un clip de référence.
- **Effet cohérent**: Comme la mosaïque couvre tout le cadre, vous n'avez pas besoin de suivre un sujet en mouvement ou d'ajuster un masque.

## Ce que change la taille du bloc de pixels

La taille du bloc contrôle l'aspect grossier de la mosaïque. Les petits blocs préservent davantage les formes et le mouvement d'origine, tandis que les grands blocs rendent le cadre plus abstrait.

Si votre objectif est le style, commencez par une taille de bloc moyenne et prévisualisez le résultat. Si votre objectif est l'obscurcissement de type confidentialité, choisissez une taille de bloc plus lourde, mais ne considérez pas la pixelisation comme une garantie légale ou de sécurité pour des séquences sensibles.

Pour du matériel très sensible, la modification la plus sûre est généralement de supprimer, recadrer ou éviter de partager la zone d'identification plutôt que de se fier à un effet visuel.

## Pixeliser vs Flouter vs Flouter une région

| Effet | Idéal pour | Comment cela modifie votre vidéo |
| --- | --- | --- |
| Pixeliser une vidéo | Style mosaïque plein écran ou aperçus de type confidentialité | Regroupe tout le cadre en blocs carrés avec une taille de bloc réglable |
| Flouter une vidéo | Adoucir l'ensemble du clip | Applique un flou lisse sur chaque image avec une intensité réglable |
| Flouter une région vidéo | Masquer une zone rectangulaire | Cible uniquement la région sélectionnée tandis que le reste de la vidéo reste visible |

Si vous voulez un aspect pixelisé partout, utilisez Pixeliser une vidéo. Si vous voulez un voile lisse partout, utilisez [Flouter une vidéo](/tools/blur-video). Si vous avez seulement besoin de masquer une zone, utilisez [Flouter une région vidéo](/tools/blur-region-video).

## Pixelisation vidéo privée et locale

GrepCut traite vos images localement dans le navigateur. Votre fichier est décodé, pixelisé, rendu et exporté sur votre appareil au lieu d'être envoyé aux serveurs de GrepCut.

Ce flux de travail local est utile lorsque votre clip contient des séquences personnelles, du matériel de travail, des détails de localisation ou tout ce que vous préférez ne pas envoyer à un éditeur en ligne juste pour ajouter un simple effet mosaïque.

## Avantages de la pixelisation vidéo

### Advantages

- Votre fichier reste sur votre appareil car le traitement est 100 % côté client.
- Vous pouvez exporter gratuitement sans filigrane.
- Vous pouvez choisir des tailles de bloc prédéfinies, de la mosaïque subtile à la pixelisation extrême.
- Les clips plus longs peuvent utiliser un rendu multicœur parallèle.

### Disadvantages

- L'effet couvre l'ensemble du cadre, pas un objet ou un visage sélectionné.
- Les grandes vidéos peuvent prendre plus de temps car chaque image doit être décodée, traitée et exportée localement.
- La pixelisation peut réduire les détails, mais elle ne doit pas être considérée comme une garantie d'anonymat complète pour des séquences sensibles.

> Contrairement aux flous, un effet mosaïque détruit efficacement les données sur lesquelles il est appliqué.
>
> Discussion Reddit r/VideoEditing

## FAQ Pixeliser une vidéo

### Peut-on pixeliser une vidéo sans l'envoyer ?

Oui. GrepCut exécute l'effet de pixelisation dans votre navigateur, donc votre vidéo reste sur votre appareil et n'est pas envoyée aux serveurs de GrepCut.

### Peut-on pixeliser seulement un visage ou un objet ?

Non avec cet outil. Pixeliser une vidéo applique la mosaïque à l'ensemble du cadre. Si vous avez besoin de masquer seulement une zone rectangulaire, utilisez [Flouter une région vidéo](/tools/blur-region-video).

### Quelle est la différence entre flouter et pixeliser ?

Le flou adoucit les détails en un voile lisse. La pixelisation regroupe l'image en blocs nets. Choisissez la pixelisation lorsque vous voulez un effet mosaïque visible, et le flou lorsque vous voulez un aspect plus lisse.

### Peut-on ajuster l'intensité de la pixelisation ?

Oui. Vous pouvez choisir des tailles de bloc prédéfinies de 5 px à 1000 px. Les petits blocs créent une mosaïque plus fine, tandis que les grands blocs rendent la vidéo beaucoup plus abstraite.

### La vidéo exportée aura-t-elle un filigrane ?

Non. Les exportations GrepCut sont gratuites et sans filigrane.

### Pourquoi la pixelisation d'une vidéo prend-elle du temps ?

Chaque image doit être décodée, transformée en blocs et rendue à nouveau. Les clips plus longs, les résolutions plus grandes et les traitements plus lourds peuvent prendre plus de temps, d'autant plus que le travail est effectué localement sur votre appareil.

### La pixelisation est-elle suffisante pour un travail de confidentialité sensible ?

La pixelisation peut rendre les détails plus difficiles à lire, surtout avec de grands blocs, mais vous ne devez pas vous fier à un effet visuel comme garantie complète pour des séquences sensibles. Si l'exposition serait nuisible, recadrez, supprimez ou évitez de partager ce contenu.

## Sources et lectures complémentaires

- [Discussion Reddit sur le flou, la mosaïque et la réversibilité](https://www.reddit.com/r/VideoEditing/comments/1ttqwpd/can_facial_blur_be_removed_by_other_people/)
- [Fil Reddit sur le choix des outils de flou ou de pixelisation pour la confidentialité vidéo](https://www.reddit.com/r/poledancing/comments/1hhhxdo/best_apps_for_blurring_others_in_videos/)
- [Discussion Super User sur le floutage d'une partie d'une vidéo avec FFmpeg](https://superuser.com/questions/901099/ffmpeg-apply-blur-over-face)
- [Référence MDN pour canvas imageSmoothingEnabled](https://developer.mozilla.org/en-US/docs/Web/API/CanvasRenderingContext2D/imageSmoothingEnabled)
- [Aperçu de l'API WebCodecs sur MDN](https://developer.mozilla.org/en-US/docs/Web/API/WebCodecs_API)
- [Guide Chrome Developers pour le traitement vidéo avec WebCodecs](https://developer.chrome.com/docs/web-platform/best-practices/webcodecs)

## Pixelisez votre vidéo en privé

Ouvrez GrepCut, déposez votre clip, choisissez une taille de bloc mosaïque et exportez un MP4 pixelisé sans envoyer votre fichier.

## Outils connexes

- [Blur Video Region](https://grepcut.com/fr/tools/blur-region-video) - masquez une zone rectangulaire au lieu de tout le cadre.
- [Blur Video](https://grepcut.com/fr/tools/blur-video) - appliquez un flou doux à tout le clip.
- [Video Trimmer](https://grepcut.com/fr/tools/video-trimmer) - enlevez les passages inutiles avant ou après la pixellisation.

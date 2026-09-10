# Agrandisseur d'image IA gratuit en ligne

Améliorez vos photos et graphismes avec la super-résolution Real-CUGAN exécutée localement sur votre appareil. aucun envoi, aucune filigrane, ou utilisez le mode Toile rapide pour des exportations 3× rapides.

HTML: https://grepcut.com/fr/tools/ai-image-upscaler

## Comment agrandir une image avec l'IA dans votre navigateur

1. **Déposez votre image**: Téléchargez un fichier JPG, PNG ou WebP depuis votre appareil.
2. **Choisissez le mode d'agrandissement**: Utilisez l'IA Real-CUGAN pour une super-résolution 2x ou 4x, ou le mode Canvas rapide pour une mise à l'échelle rapide 2x, 3x et 4x.
3. **Exportez l'image agrandie**: Téléchargez votre image agrandie en PNG ou JPEG sans filigrane.

Votre image est traitée localement dans votre navigateur. Rien n'est téléchargé sur GrepCut. Besoin d'agrandir des clips plutôt que des images fixes ? Essayez l'[Agrandisseur vidéo](/tools/video-upscaler).

## Quand l'agrandissement par IA aide votre image

Si votre photo, scan, capture d'écran ou export social est trop petit pour une mise en page, vous avez besoin de plus de pixels avant de recadrer, imprimer ou réutiliser. La super-résolution IA fait plus qu'étirer l'image : elle prédit des bords et textures plus nets à partir de l'entrée basse résolution.

Le mode IA de GrepCut exécute Real-CUGAN localement avec TensorFlow.js. Cela signifie que vous pouvez agrandir une image sans envoyer le fichier hors de votre appareil, créer un compte ou ajouter un filigrane.

### Utilisez-le quand vous voulez un fichier plus grand sans quitter votre navigateur :

- **Petites photos**: Augmentez la résolution avant de recadrer plus serré ou de placer l'image dans un design plus grand.
- **Illustrations et art anime**: Real-CUGAN a été conçu pour la super-résolution d'image et est particulièrement pertinent pour les détails dessinés, les bords et les œuvres stylisées.
- **Captures d'écran et miniatures**: Rendez les captures d'interface, les images d'aperçu et les captures d'écran de documentation plus faciles à réutiliser à des tailles plus grandes.

## Mode IA vs Mode Canvas rapide

| Mode | Meilleur pour | À quoi s'attendre |
| --- | --- | --- |
| Real-CUGAN IA | Agrandissement 2x ou 4x quand la qualité des détails compte | Reconstruction plus nette, traitement plus lent et meilleurs résultats sur un navigateur moderne avec WebGPU ou WebGL |
| Canvas rapide | Exportations rapides en 2x, 3x ou 4x | Mise à l'échelle rapide du navigateur sans récupération des détails par réseau neuronal |
| Vérification de la taille d'origine | Entrées très bruitées, compressées ou floues | L'agrandissement peut rendre les défauts existants plus visibles, alors inspectez le résultat avant de l'utiliser dans des impressions ou des listes |

Si vous avez besoin de dimensions exactes en pixels plutôt que d'un multiplicateur, utilisez le [Redimensionneur d'image](/tools/resize-video) après l'agrandissement.

## Pourquoi l'agrandissement 4x n'est pas magique

Un agrandissement 4x donne à votre fichier beaucoup plus de pixels, mais il ne peut pas récupérer des informations qui n'ont jamais été capturées. Si votre image originale a du texte illisible, des blocs JPEG lourds ou un flou de mouvement, l'IA peut accentuer la forme du problème plutôt que révéler le vrai détail.

Pour des résultats plus propres, partez de la version la moins compressée que vous avez. Si vous comparez les modes, exportez les versions IA et Canvas rapide et choisissez celle qui semble la plus naturelle pour votre image.

Cela compte surtout pour les visages, le texte et les détails de produits, où un résultat plus net n'est pas toujours un résultat plus précis.

## Agrandisseur d'image IA en un coup d'œil

### Advantages

- Fonctionne dans votre navigateur sans envoyer l'image.
- Mode IA Real-CUGAN pour super-résolution 2x et 4x.
- Mode Canvas rapide prend en charge les échelles 2x, 3x et 4x.
- Export gratuit sans filigrane.

### Disadvantages

- Le mode IA peut être plus lent sur les grandes images.
- Les sources très floues ou compressées peuvent encore montrer des artefacts.
- Le mode IA nécessite un navigateur moderne avec support WebGPU ou WebGL.

> les résultats dépendent de la photo et de la résolution du fichier original
>
> Reddit r/photography

## FAQ Agrandisseur d'image IA

### Pouvez-vous agrandir une image sans la télécharger ?

Oui. GrepCut traite votre image localement dans votre navigateur, y compris le mode IA. Votre fichier ne quitte pas votre appareil.

### S'agit-il d'un véritable agrandissement IA ou simplement d'un redimensionnement ?

Le mode IA utilise la super-résolution Real-CUGAN. Le mode Canvas rapide est différent : il utilise la mise à l'échelle Canvas du navigateur pour des exportations rapides 2x, 3x et 4x sans reconstruction par réseau neuronal.

### Faut-il utiliser l'agrandissement IA 2x ou 4x ?

Utilisez 2x lorsque vous avez besoin d'une augmentation modeste de la résolution avec moins d'artefacts. Utilisez 4x lorsque la source est suffisamment propre et que vous avez besoin d'une image beaucoup plus grande pour le design, la préparation d'impression ou le recadrage serré.

### L'agrandissement IA peut-il corriger un texte ou des visages flous ?

Il peut rendre les bords plus nets, mais il ne peut pas garantir des détails manquants précis. Si votre texte ou visage original est trop flou, inspectez attentivement le résultat avant de le considérer comme fiable ou prêt à imprimer.

### Quels formats d'image pouvez-vous télécharger ?

Vous pouvez télécharger des images JPG, PNG ou WebP. L'export est enregistré en PNG ou JPEG selon ce que le navigateur peut préserver pour votre fichier.

### Pourquoi le mode IA est-il plus lent que le Canvas rapide ?

Le mode IA exécute un réseau neuronal sur votre appareil, donc le traitement dépend de la taille de votre image, du navigateur et du support GPU. Le mode Canvas rapide ignore le modèle IA, donc il est plus rapide mais moins détaillé.

### Pouvez-vous agrandir des images d'anime ou de jeu ?

Oui. Real-CUGAN est particulièrement pertinent pour les illustrations, l'art de style anime et les bords graphiques nets. Pour le pixel art, comparez l'IA avec le Canvas rapide car certaines œuvres sont meilleures lorsque la structure de pixels d'origine est préservée.

## Sources et lectures complémentaires

- [Discussion Reddit sur la dépendance de l'agrandissement IA à l'image source](https://www.reddit.com/r/photography/comments/bml58t/whats_your_opinion_on_upscaling_photos_with_ai/)
- [Fil Reddit sur Real-CUGAN pour les webtoons et les œuvres de style bande dessinée](https://www.reddit.com/r/StableDiffusion/comments/1jcuxna/upscaling_models_recommendations_for_a_newbie/)
- [README du projet Real-CUGAN](https://github.com/bilibili/ailab/blob/main/Real-CUGAN/README_EN.md)
- [Guide officiel TensorFlow.js pour les environnements navigateur et plateforme](https://www.tensorflow.org/js/guide/platform_environment)
- [Documentation MDN sur le lissage d'image Canvas](https://developer.mozilla.org/en-US/docs/Web/API/CanvasRenderingContext2D/imageSmoothingEnabled)
- [Notes du modèle Real-CUGAN TensorFlow.js sur Hugging Face](https://huggingface.co/shammisw/real-cugan-tensorflowjs)

## Agrandissement terminé ? Terminez le montage complet

Ouvrez GrepCut Studio lorsque vous souhaitez combiner votre travail d'image agrandie avec le montage de la timeline, les sous-titres, les LUT et l'export dans le navigateur.

## Outils connexes

- [Video Upscaler](https://grepcut.com/fr/tools/video-upscaler) - agrandissez les clips grâce à l'interpolation dans le navigateur.
- [Resize Video](https://grepcut.com/fr/tools/resize-video) - redimensionnez les vidéos aux dimensions exactes pour les formats sociaux.

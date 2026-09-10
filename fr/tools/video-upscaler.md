# Agrandisseur vidéo FSR en ligne gratuit

Augmentez la résolution de vos clips avec un suréchantillonnage FSR adaptatif aux contours, directement dans votre navigateur.

HTML: https://grepcut.com/fr/tools/video-upscaler

## À lire avant de commencer : FSR affine les contours, il n'invente pas les détails

Définissez vos attentes avant de commencer. FSR nettoie les contours tout en agrandissant votre clip, mais sur des séquences déjà floues, à faible débit ou mal cadrées, l'amélioration est souvent marginale car il y a très peu d'informations réelles sur les contours à reconstruire.

FSR est un suréchantillonneur spatial, pas une IA. Il ne peut pas ajouter des détails qui n'ont jamais été capturés. Reconstruire une texture absente de votre source nécessite un modèle de super-résolution IA, qui est un outil différent. Utilisez cet agrandisseur pour agrandir proprement et affiner les contours, pas pour récupérer des détails perdus.

## Comment agrandir une vidéo en ligne dans votre navigateur

1. **Ajoutez votre clip**: Déposez un fichier MP4, MOV, WebM ou MKV dans la zone de sélection.
2. **Choisissez 2×, 3× ou 4×**: Sélectionnez le facteur d'agrandissement adapté à votre timeline, export social ou mise en page HD.
3. **Exportez votre MP4**: Téléchargez le MP4 agrandi, ou ouvrez-le dans GrepCut Studio pour ajouter des sous-titres, des coupes et des finitions.

L'agrandissement s'effectue localement dans votre navigateur, votre vidéo reste donc sur votre appareil.

## Utilisez l'agrandissement FSR lorsque votre clip est trop petit

Si votre clip a été enregistré en 480p, 720p ou dans une petite fenêtre de capture d'écran, il peut sembler trop petit dans un montage HD. L'agrandissement augmente les dimensions en pixels avant l'export, afin que votre vidéo s'adapte à une timeline 1080p, à une mise en ligne sur YouTube ou à un préréglage social sans étirement manuel dans un autre éditeur.

GrepCut agrandit avec FSR (AMD FidelityFX Super Resolution). Au lieu d'un simple étirement lisse, FSR reconstruit les contours en agrandissant, de sorte que les lignes et les contours restent plus nets qu'avec un rééchantillonnage bicubique. C'est un choix pratique pour les séquences compressées de téléphone, les tutoriels et les reposts exportés trop petits.

### Idéal pour :

- **Anciennes séquences de téléphone**: Rapprochez un clip 480p ou 720p d'une mise en page HD avec des contours plus nets avant de publier.
- **Captures d'écran**: Facilitez le placement d'une petite fenêtre de capture dans un tutoriel ou une présentation.
- **Reposts sociaux**: Redimensionnez les clips verticaux provenant d'une autre application à une résolution inférieure.

## Comment fonctionne l'agrandissement FSR, et ce qu'il peut et ne peut pas corriger

FSR est un suréchantillonneur spatial : il travaille à partir d'une seule image, sans vecteurs de mouvement, tampon de profondeur ni modèle IA. Il s'exécute en deux passes GPU. D'abord, EASU (Edge-Adaptive Spatial Upsampling) rééchantillonne l'image de manière directionnelle, détectant comment les gradients voisins diffèrent afin que les contours soient reconstruits au lieu d'être simplement floutés. Ensuite, RCAS (Robust Contrast-Adaptive Sharpening) ajoute un accentuation contrôlée qui fait ressortir les détails sans créer d'auréoles ni amplifier le bruit.

Comme FSR utilise des shaders ordinaires et ne regarde jamais les autres images, il traite chaque image de la même manière et garantit la cohérence de votre export. Ce n'est cependant pas une super-résolution IA. Si votre source est très floue, fortement compressée ou manque de détails fins, FSR peut adapter une image plus grande avec des contours plus nets, mais il ne peut pas reconstruire une texture qui n'a jamais été capturée.

### Sous le capot :

- **EASU**: Rééchantillonnage adaptatif aux contours qui reconstruit les contours en agrandissant, plus net que le bilinéaire ou le bicubique.
- **RCAS**: Passe d'accentuation adaptative au contraste, appliquée automatiquement, qui ajoute du piquant aux vrais contours tout en laissant les zones plates tranquilles.

Pour les séquences très floues, faites d'abord un petit test d'export. Si l'aperçu semble déjà trop flou, un facteur plus petit donne souvent un résultat plus naturel qu'un étirement 4× forcé.

## Comparaison FSR vs mise à l'échelle simple

| Méthode | Comment elle met à l'échelle | Résultat typique |
| --- | --- | --- |
| Au plus proche voisin | Duplique le pixel le plus proche. | Bords en escalier, blocage. |
| Bilinéaire ou bicubique | Moyenne des pixels environnants. | Plus lisse, mais contours flous. |
| FSR (EASU + RCAS) | Rééchantillonnage adaptatif aux contours + accentuation adaptative au contraste. | Contours plus propres et plus nets sans modèle IA. |

FSR reconstruit les contours au lieu de simplement les lisser, mais comme toute méthode spatiale, il travaille avec les détails déjà présents dans votre clip.

## Quel facteur d'agrandissement choisir ?

Le bon facteur dépend de l'écart entre votre clip et la taille souhaitée. Des facteurs plus grands créent plus de pixels à reconstruire, donc une source molle montre ses limites plus vite en 4× qu'en 2×.

### Choisissez votre facteur :

- **2×**: Un premier test sûr lorsque votre clip n'a besoin que d'un léger agrandissement.
- **3×**: Utile lorsqu'un petit clip doit remplir davantage un canevas HD.
- **4×**: Idéal pour les clips courts où vous avez besoin des dimensions maximales et pouvez attendre un peu plus longtemps.

Commencez par 2× si vous n'êtes pas sûr, puis réessayez avec un facteur plus grand si votre source a assez de détails pour tenir.

## L'aperçu correspond à votre export

FSR agrandit et accentue automatiquement, donc il n'y a rien à configurer. Choisissez un facteur, vérifiez le résultat et exportez. EASU gère l'agrandissement adaptatif aux contours et RCAS ajoute une accentuation fixe et de bon goût par-dessus.

L'aperçu avant/après utilise le même pipeline FSR que l'export, donc ce que vous voyez est ce qui se retrouve dans votre MP4. Zoomez sur l'aperçu pour juger de la netteté des contours avant de vous lancer dans un rendu complet.

Si l'aperçu semble encore flou après l'agrandissement, cela signifie généralement que le détail n'était pas dans la source au départ, et un facteur plus faible peut sembler plus naturel.

## Gardez votre vidéo privée pendant vos tests

Les outils vidéo en ligne vous demandent souvent d'envoyer le fichier entier avant de voir un résultat. Cet agrandisseur fonctionne dans votre navigateur, donc vos séquences ne quittent pas votre appareil pendant le traitement.

C'est utile lorsque votre clip contient du contenu d'écran privé, des séquences sociales non publiées, des brouillons clients ou des enregistrements de cours. Vous pouvez tester un facteur, télécharger le MP4 et continuer le montage sans envoyer le fichier original à un serveur.

Les clips longs et les exports 4× dépendent de la vitesse de votre appareil. Pour des vérifications rapides, coupez d'abord le clip ou testez une courte section avant de traiter la vidéo entière.

## Agrandisseur vidéo en un coup d'œil

### Advantages

- Fonctionne localement dans votre navigateur, sans envoi.
- FSR reconstruit les contours, donc les résultats sont plus nets qu'avec un rééchantillonnage bicubique.
- L'agrandissement EASU et l'accentuation RCAS sont appliqués automatiquement, rien à configurer.
- Les préréglages 2×, 3× et 4× simplifient le choix.
- Export MP4 gratuit sans filigrane.

### Disadvantages

- C'est un suréchantillonneur spatial, pas une IA, donc il ne peut pas inventer des détails non capturés.
- Les sources très floues ou fortement compressées peuvent encore sembler molles.
- Les exports 4× longs peuvent prendre plus de temps sur les appareils lents.
- Si votre navigateur ne supporte pas WebGL2, il utilise un simple rééchantillonnage bicubique.

> FSR 1 ne regarde pas les données des images précédentes pour améliorer son agrandissement, mais étire simplement chaque image isolée, en utilisant des techniques comme la détection de contours pour déterminer la meilleure façon d'étirer l'image.
>
> PCGamesN

## FAQ Agrandisseur vidéo

### Peut-on agrandir une vidéo en ligne sans l'envoyer ?

Oui. Votre vidéo est traitée localement dans votre navigateur, donc le fichier reste sur votre appareil.

### FSR est-il identique à l'agrandissement par IA ?

Non. FSR est un suréchantillonneur spatial qui fonctionne sur des shaders ordinaires et travaille à partir d'une seule image. Il reconstruit les contours avec EASU et accentue avec RCAS, mais il n'utilise pas de réseau neuronal, donc il ne peut pas inventer des détails comme le ferait une super-résolution IA.

### En quoi FSR diffère-t-il de l'agrandissement bicubique ?

Le bicubique fait la moyenne des pixels voisins, ce qui agrandit l'image mais laisse les contours flous. FSR examine comment les gradients voisins changent et rééchantillonne le long des contours, donc les lignes et les contours restent plus nets, puis RCAS ajoute une accentuation contrôlée par-dessus.

### FSR rendra-t-il votre vidéo floue nette ?

Il peut rendre les contours plus propres et ajouter un peu de piquant, mais l'amélioration est souvent marginale sur des séquences molles, et il ne peut pas restaurer les détails manquants d'une source floue, à faible débit ou mal cadrée. Récupérer des détails absents nécessite un agrandisseur IA.

### Quel facteur d'agrandissement utiliser ?

Utilisez 2× pour un premier passage sûr, 3× lorsque votre clip a besoin d'un agrandissement plus fort, et 4× pour les clips courts de basse résolution où vous avez besoin de la sortie la plus grande.

### Peut-on agrandir une vidéo 480p pour un montage 1080p ?

Oui. Vous pouvez agrandir le clip avant de le placer dans une timeline HD. FSR garde les contours plus nets qu'un simple étirement, bien que le résultat puisse encore sembler plus mou qu'une séquence native 1080p car l'original a moins de pixels.

### Faut-il ajuster des paramètres ?

Non. FSR agrandit avec EASU et accentue avec RCAS automatiquement, donc vous choisissez simplement un facteur et exportez. L'aperçu avant/après utilise le même pipeline que l'export.

### Quels formats vidéo peut-on importer, et y a-t-il un filigrane ?

Vous pouvez importer des fichiers MP4, MOV, WebM et MKV, et exporter votre MP4 agrandi sans filigrane.

## Sources et lectures complémentaires

- [Aperçu AMD GPUOpen de FidelityFX Super Resolution 1 (EASU et RCAS)](https://gpuopen.com/fidelityfx-superresolution/)
- [Manuel technique AMD GPUOpen FSR 1 suréchantillonnage spatial](https://gpuopen.com/manuals/fidelityfx_sdk/techniques/super-resolution-spatial/)
- [FidelityFX Super Resolution 1.0 démystifié (explication des shaders)](https://jntesteves.github.io/shadesofnoice/graphics/shaders/upscaling/2021/09/11/amd-fsr-demystified.html)
- [Tom's Hardware : test des performances et de la qualité d'image FSR](https://www.tomshardware.com/news/amd-fidelityfx-super-resolution-fsr-performance-tested)
- [Fil de discussion guru3D : FSR 1 est excellent pour ce qu'il est](https://forums.guru3d.com/threads/fsr-1-is-great-actually-for-what-it-is.453779/)
- [Fil Reddit sur pourquoi les séquences agrandies peuvent sembler floues](https://www.reddit.com/r/premiere/comments/1asd5id/scaling_up_video_to_a_higher_resolution_makes_it/)
- [Aperçu Wikipedia des méthodes de redimensionnement d'image](https://en.wikipedia.org/wiki/Image_scaling)

## Agrandissement terminé ? Peaufinez le montage complet

Ouvrez votre MP4 agrandi dans GrepCut Studio pour couper la timeline, ajouter des sous-titres, ajuster l'apparence et exporter la vidéo finale dans votre navigateur.

## Outils connexes

- [Redimensionner une vidéo](https://grepcut.com/fr/tools/resize-video) - mettre à l'échelle votre clip en pourcentage.
- [Changer la vitesse d'une vidéo](https://grepcut.com/fr/tools/change-video-speed) - ralentir ou accélérer vos séquences.
- [Flouter une vidéo](https://grepcut.com/fr/tools/blur-video) - adoucir les arrière-plans ou masquer les zones sensibles.

# Modifier la vitesse d'une vidéo en ligne

Accélérez un time-lapse, ralentissez un replay ou ajustez n'importe quel clip dans votre navigateur. Le mode rapide modifie le timing sans ré-encodage, conservant une qualité d'image identique. Le mode ré-encodage crée un MP4 H.264 compatible, avec correction de la hauteur tonale audio dans les deux modes.

HTML: https://grepcut.com/fr/tools/change-video-speed

## Comment changer la vitesse d'une vidéo dans votre navigateur

1. **Ajoutez votre vidéo**: Déposez votre fichier dans GrepCut ou cliquez pour parcourir. Votre vidéo reste sur votre appareil pendant que l'outil travaille dans votre navigateur.
2. **Choisissez une vitesse de lecture**: Ralentissez tout le clip jusqu'à 0,25x ou accélérez-le jusqu'à 60x pour un effet accéléré de type time-lapse.
3. **Sélectionnez un mode d'exportation**: Utilisez le mode Rapide pour copier le flux vidéo et ne modifier que le timing, ou le mode Ré-encodage pour obtenir un MP4 H.264 largement compatible.
4. **Exportez votre MP4**: Prévisualisez la vitesse modifiée, appliquez-la et téléchargez le résultat sans filigrane.

Besoin de rampes de vitesse, de coupes, de sous-titres ou d'un changement de vitesse sur une seule section ? Ouvrez le clip dans [GrepCut Studio](/) et éditez-le sur une timeline complète.

## Pourquoi changer la vitesse d'une vidéo nécessite plus qu'un simple curseur

Changer la vitesse semble simple jusqu'à ce que votre clip contienne de la parole, de la musique ou un audio sensible à la synchronisation. Si vous accélérez simplement la vidéo, la voix peut devenir aiguë. Si vous ne touchez qu'à la piste vidéo, l'audio et la vidéo peuvent se désynchroniser.

C'est pourquoi GrepCut traite le timing et l'audio ensemble. Lorsque vous modifiez la vitesse du clip, la durée audio change également, et la correction de hauteur aide la parole à rester naturelle au lieu de devenir un effet d'écureuil.

Vous pouvez utiliser cet outil lorsque votre tutoriel comporte de longues pauses, que votre enregistrement d'écran nécessite un rythme plus serré, que votre réaction a besoin d'un ralenti, ou que votre clip de processus nécessite un effet d'accéléré rapide.

### Cas d'usage adaptés :

- **Ralenti**: ralentissez un tir acrobatique, un mouvement de danse, un détail produit, une réaction ou un moment sportif pour mieux le voir.
- **Effet time-lapse**: accélérez une installation, une construction, un trajet, un enregistrement de bureau, une démonstration ou une section de chargement.
- **Nettoyage de tutoriel**: accélérez les pauses et les étapes répétitives sans ouvrir un éditeur complet au préalable.
- **Rythme pour les réseaux sociaux**: resserrez votre clip avant de le partager lorsque la prise originale semble trop lente.

## Le mode Rapide modifie le timing sans recompresser la vidéo

En mode Rapide, GrepCut ne reconstruit pas l'image image par image. Il copie le flux vidéo compressé et modifie le timing pour que les mêmes images soient lues plus lentement ou plus rapidement.

Cela préserve une qualité visuelle identique au flux vidéo source car les données vidéo sont copiées au lieu d'être décodées et ré-encodées. L'exportation peut également être beaucoup plus rapide qu'un rendu complet, surtout lorsque votre appareil peut éviter un travail lourd d'encodage vidéo.

L'audio doit encore être reconstruit car sa durée change avec la vitesse choisie. GrepCut étire temporellement l'audio et corrige automatiquement la hauteur.

Choisissez le mode Rapide lorsque vous voulez le résultat le plus rapide, éviter une perte de qualité visuelle inutile, et que votre codec source est déjà adapté à votre destination.

## Le mode Ré-encodage crée un MP4 H.264 plus compatible

Une extension de fichier ne dit pas tout. Votre fichier peut être MP4, MOV, WebM, MKV ou M4V, mais le codec interne peut toujours décider si un appareil, un navigateur, un site de partage ou un éditeur l'accepte.

Le mode Ré-encodage rend le résultat entièrement en MP4 H.264. Cela prend plus de temps car chaque image est encodée à nouveau, mais vous obtenez une sortie plus facile à ouvrir, envoyer et téléverser dans les applications courantes.

Utilisez le mode Ré-encodage lorsque la compatibilité est plus importante que la préservation exacte du flux vidéo source. Utilisez le mode Rapide lorsque vous privilégiez la vitesse et la qualité vidéo copiée.

## Rapide vs Ré-encodage : quel moteur de vitesse choisir ?

| Besoin | Mode Rapide | Mode Ré-encodage |
| --- | --- | --- |
| Vitesse d'exportation | Généralement l'option la plus rapide car le flux vidéo est copié | Plus lent car la vidéo est rendue à nouveau |
| Qualité vidéo | Identique au flux vidéo source | Recompressée lors de l'exportation |
| Gestion audio | L'audio est étiré temporellement et corrigé en hauteur | L'audio est étiré temporellement et corrigé en hauteur |
| Codec de sortie | Conserve le codec vidéo source | Crée un MP4 H.264 |
| Idéal pour | Exportations rapides et sans compression visuelle supplémentaire | Compatibilité avec les plateformes, appareils et éditeurs |

Les deux modes s'exécutent localement dans votre navigateur. Votre fichier n'est pas envoyé et votre vidéo exportée est sans filigrane.

## Changement de vitesse dans le navigateur vs un éditeur de bureau complet

### Advantages

- Votre vidéo reste sur votre appareil au lieu d'être envoyée.
- Vous pouvez changer la vitesse sans installer d'éditeur de bureau.
- La correction de hauteur est gérée automatiquement lors du changement de durée audio.
- Le mode Rapide évite de recompresser le flux vidéo.

### Disadvantages

- Les très gros fichiers dépendent de la mémoire de votre appareil et des performances du navigateur.
- Cet outil applique une seule vitesse à l'ensemble du clip.
- Pour les rampes de vitesse ou un timing section par section, vous avez besoin de GrepCut Studio.
- Le mode Rapide est optimal lorsque le codec source est déjà compatible avec l'utilisation prévue du résultat.

> Ça ressemble à un écureuil, je ne veux pas ça.
>
> Discussion Reddit r/premiere sur l'accélération de la parole

## FAQ sur le changement de vitesse vidéo

### Puis-je changer la vitesse d'une vidéo sans envoyer le fichier ?

Oui. GrepCut traite votre vidéo localement dans votre navigateur, donc votre fichier reste sur votre appareil au lieu d'être envoyé sur un serveur.

### Changer la vitesse va-t-il réduire la qualité de ma vidéo ?

En mode Rapide, le flux vidéo est copié et seul le timing change, donc la qualité visuelle reste identique au flux source. En mode Ré-encodage, la vidéo est recompressée pour créer un MP4 H.264 plus compatible.

### Pourquoi le mode Rapide est-il plus rapide qu'une exportation vidéo normale ?

Le mode Rapide saute la partie la plus lente d'un rendu complet. Il ne décode et ne ré-encode pas chaque image vidéo. Il copie le flux vidéo compressé original et ajuste le moment où ces images sont lues.

### Mon audio sera-t-il plus aigu ou plus grave après le changement de vitesse ?

GrepCut corrige automatiquement la hauteur tout en modifiant la durée audio. Cela aide la parole à rester naturelle au lieu de devenir aiguë en accéléré ou trop grave en ralenti.

### Dois-je choisir le mode Rapide ou le mode Ré-encodage ?

Choisissez le **mode Rapide** pour l'exportation la plus rapide et sans compression visuelle supplémentaire. Choisissez le **mode Ré-encodage** si un appareil, un site de partage ou un éditeur rejette votre fichier, ou si vous avez besoin d'un MP4 largement compatible.

### Puis-je accélérer seulement une partie de la vidéo ?

Cet outil modifie la vitesse de l'ensemble du clip. Si vous devez accélérer une section, en ralentir une autre ou créer une rampe, ouvrez le fichier dans [GrepCut Studio](/) et éditez-le sur la timeline.

### Quels formats vidéo puis-je utiliser ?

Vous pouvez ajouter des fichiers MP4, MOV, WebM, MKV, M4V et d'autres formats vidéo courants. Le résultat téléchargé est un MP4.

### Changer la vitesse peut-il réduire la taille de mon fichier ?

Pas de manière fiable. En mode Rapide, la taille du fichier reste généralement proche de la source car les données vidéo sont copiées. Si vous avez besoin d'une exportation plus petite ou d'un fichier plus compatible, utilisez le mode Ré-encodage.

## Sources et lectures complémentaires

- [Fil Reddit sur l'accélération de la parole sans effet d'écureuil](https://www.reddit.com/r/premiere/comments/16hgm22/how_to_speed_up_speech_without_changing_the_pitch/)
- [Fil Reddit sur le changement de fréquence d'images sans ré-encodage](https://www.reddit.com/r/shutterencoder/comments/qwlt3f/is_it_possible_to_change_frame_rate_without/)
- [Réponse Super User sur le changement de vitesse vidéo sans transcodage complet](https://superuser.com/questions/523465/changing-video-speed-without-transcoding-reencoding)
- [Aperçu de l'API WebCodecs sur MDN](https://developer.mozilla.org/fr/docs/Web/API/WebCodecs_API)
- [Documentation MDN sur preservesPitch de HTMLMediaElement](https://developer.mozilla.org/fr/docs/Web/API/HTMLMediaElement/preservesPitch)
- [Guide MDN sur les codecs vidéo web et la compatibilité MP4 H.264](https://developer.mozilla.org/fr/docs/Web/Media/Formats/Video_codecs)

## Besoin d'édition de vitesse plus avancée ?

Ouvrez GrepCut Studio lorsque vous avez besoin d'une timeline, de rampes de vitesse, de rognage, de sous-titres, de musique et de contrôles d'exportation dans le navigateur, sans envoyer votre vidéo.

## Outils connexes

- [Rogner une vidéo](https://grepcut.com/fr/tools/video-trimmer) - coupez votre clip avant ou après avoir changé sa vitesse.
- [Couper le son d'une vidéo](https://grepcut.com/fr/tools/mute-video) - supprimez la piste audio lorsque vous n'avez besoin que des visuels.
- [Redimensionner une vidéo](https://grepcut.com/fr/tools/resize-video) - mettez votre clip à l'échelle d'une nouvelle résolution ou d'un nouveau format.

# Normalisateur de volume audio en ligne

Mesurez la sonie intégrée et normalisez vos pistes à -14, -16 ou -23 LUFS. Fonctionne entièrement dans votre navigateur, sans envoi ni compte.

HTML: https://grepcut.com/fr/tools/audio-normalizer

## Comment normaliser le volume audio en ligne

1. **Ajoutez votre audio**: Déposez un fichier MP3, WAV, M4A ou OGG dans la zone de sélection.
2. **Choisissez votre cible LUFS**: Sélectionnez Streaming à -14 LUFS, Podcast à -16 LUFS ou Diffusion à -23 LUFS.
3. **Normalisez et exportez en WAV**: Cliquez sur Normaliser pour mesurer le volume, appliquer un gain sûr avec limitation de crête et télécharger une copie WAV.

Votre fichier est traité localement dans votre navigateur. Rien n'est envoyé à GrepCut.

## Pourquoi votre audio a besoin de LUFS, pas seulement d'une normalisation de crête

Si votre clip atteint des crêtes proches de 0 dB mais semble encore silencieux à côté d'autres audios, la normalisation de crête ne résoudra pas le vrai problème. Les crêtes n'indiquent que l'échantillon le plus fort, tandis que le LUFS estime le volume perçu de votre piste dans le temps.

GrepCut mesure le volume intégré avec une pondération K, puis applique un gain vers votre cible choisie tout en respectant un plafond de crête de -1 dBTP. Cela aide votre audio à se rapprocher d'une cible de volume pour le streaming, le podcast ou la diffusion sans pousser les crêtes à l'écrêtage.

### Utilisez cet outil lorsque vous souhaitez un volume perçu cohérent avant de partager, publier ou éditer davantage.

Si votre fichier est déjà très fort et n'a plus de marge, le plafond de crête peut empêcher l'outil d'atteindre la cible LUFS exacte. Dans ce cas, un résultat plus sûr est généralement préférable à un résultat écrêté.

## Quelle cible LUFS choisir ?

| Cible | Idéal pour | Ce qu'elle fait |
| --- | --- | --- |
| -14 LUFS | Aperçus vidéo ou musique en streaming | Une cible de volume courante pour que votre audio se rapproche des niveaux de lecture des principaux services de streaming. |
| -16 LUFS | Podcasts et clips parlés | Une cible pratique pour les contenus axés sur la voix où la clarté et la cohérence priment sur le volume maximal. |
| -23 LUFS | Diffusion de type broadcast | Une cible plus silencieuse alignée sur les flux de travail de volume de diffusion EBU R128. |

Ces préréglages sont des points de départ. Votre plateforme de diffusion finale peut appliquer sa propre normalisation de lecture après publication.

## Ce qui se passe dans votre navigateur

Lorsque vous ajoutez un fichier, votre navigateur décode l'audio pour que GrepCut puisse analyser la forme d'onde. L'outil mesure le volume sur l'ensemble de la piste, calcule le gain nécessaire pour la cible LUFS sélectionnée et limite le résultat pour que les crêtes restent sous le plafond.

Comme le traitement est local, votre audio reste sur votre appareil. Les fichiers très longs peuvent prendre plus de temps car votre navigateur doit décoder et traiter l'audio en mémoire.

- **Conçu pour la confidentialité**: Votre audio source n'est pas envoyé à un serveur.
- **Conscient du LUFS**: L'outil cible le volume perçu, pas seulement l'échantillon le plus fort.
- **Export WAV**: Le résultat normalisé est téléchargé en fichier WAV pour édition, archivage ou conversion.

## Quand la normalisation du volume est la plus utile

Utilisez la normalisation LUFS lorsque votre note vocale, segment de podcast, enregistrement d'écran ou clip musical semble beaucoup plus silencieux ou plus fort que le reste de votre projet. C'est particulièrement utile avant d'assembler plusieurs clips dans une même timeline.

Pour la voix, vous pouvez encore nettoyer le bruit, égaliser, compresser ou éditer les silences avant la normalisation. La normalisation du volume est généralement la dernière étape d'égalisation des niveaux, pas un substitut à la correction d'un enregistrement bruyant ou d'une performance inégale.

## Avantages et limites du normalisateur audio

### Advantages

- Vous pouvez normaliser MP3, WAV, M4A ou OGG sans envoyer votre fichier.
- Vous pouvez choisir des préréglages LUFS clairs pour les flux de travail de streaming, podcast ou diffusion.
- La limitation de crête réduit le risque d'écrêtage lorsque du gain est ajouté.

### Disadvantages

- Le format d'export est WAV, pas MP3 ou M4A.
- Un fichier sans marge restante peut ne pas atteindre la cible LUFS exacte sans écrêtage.
- La prise en charge du décodage par le navigateur peut varier selon le codec du fichier et l'appareil.

> La normalisation ajuste chaque chanson au même niveau de crête, mais ce n'est pas la même chose que de les ajuster au même niveau de volume.
>
> Reddit r/audioengineering

## FAQ du normalisateur audio

### Peut-on normaliser l'audio à -14 LUFS en ligne ?

Oui. Choisissez le préréglage Streaming pour cibler -14 LUFS, puis exportez le résultat normalisé en WAV. Votre navigateur effectue le traitement localement, donc votre fichier n'est pas envoyé.

### Faut-il utiliser -14 LUFS ou -16 LUFS ?

Utilisez -14 LUFS pour une cible de type streaming courante. Utilisez -16 LUFS pour préparer un contenu parlé comme un segment de podcast. En cas de doute, choisissez le préréglage correspondant à l'utilisation prévue de votre audio.

### Peut-on normaliser l'audio pour le volume de diffusion ?

Oui. Choisissez le préréglage Diffusion pour cibler -23 LUFS. Cela est utile lorsque vous souhaitez une cible de volume plus silencieuse de type broadcast plutôt qu'une cible streaming ou podcast.

### Mon fichier audio sera-t-il envoyé ?

Non. GrepCut traite votre audio dans votre navigateur. Le fichier source reste sur votre appareil et le WAV normalisé est généré localement.

### La normalisation du volume va-t-elle déformer mon audio ?

L'outil applique un gain avec un plafond de crête de -1 dBTP pour réduire le risque d'écrêtage. Si votre source est déjà très forte, le limiteur peut empêcher d'atteindre la cible LUFS exacte pour que l'export reste plus sûr.

### Pourquoi mon fichier sonne-t-il encore différemment après avoir atteint le même LUFS ?

Le LUFS est un bon indicateur de volume, mais le timbre, les basses, la compression, le bruit de fond et la plage dynamique affectent toujours la perception du volume. Deux fichiers peuvent avoir la même valeur LUFS et sembler différents.

### Peut-on exporter en MP3 après normalisation ?

Cet outil exporte en WAV. Si vous avez besoin d'un autre format, normalisez d'abord, puis convertissez le WAV avec un convertisseur séparé.

## Sources et lectures complémentaires

- [Discussion Reddit sur la normalisation du volume des podcasts](https://www.reddit.com/r/podcasts/comments/f1fbew/editing_question_do_you_normalize_and_if_so_how/)
- [Discussion Reddit sur la normalisation de crête versus le volume perçu](https://www.reddit.com/r/audioengineering/comments/kctip9/normalising_the_volume_of_100_tracks_at_once/)
- [Guide Spotify sur la normalisation du volume](https://support.spotify.com/us/artists/article/loudness-normalization/)
- [Recommandation UIT-R BS.1770-5 sur le volume et la crête réelle](https://www.itu.int/dms_pubrec/itu-r/rec/bs/R-REC-BS.1770-5-202311-I!!PDF-E.pdf)
- [Aperçu de l'API Web Audio MDN](https://developer.mozilla.org/fr/docs/Web/API/Web_Audio_API)
- [Référence MDN decodeAudioData pour le décodage audio dans le navigateur](https://developer.mozilla.org/fr/docs/Web/API/BaseAudioContext/decodeAudioData)

## Normalisez votre audio en toute confidentialité

Ouvrez le normalisateur audio, choisissez votre cible LUFS et exportez un WAV propre sans envoyer votre fichier sur un serveur.

## Outils connexes

- [Suppresseur de bruit audio](https://grepcut.com/fr/tools/audio-noise-remover) - Nettoyez le bruit de fond avant de normaliser le niveau sonore.
- [Créateur de sonneries](https://grepcut.com/fr/tools/ringtone-maker) - Coupez un court extrait et exportez une sonnerie M4R ou MP3.

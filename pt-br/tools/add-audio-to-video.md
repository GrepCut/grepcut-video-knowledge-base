# Adicionar Áudio ao Vídeo Online

Solte um vídeo e um arquivo de áudio - o GrepCut substitui a trilha sonora sem recodificar a imagem. Nada sai do seu dispositivo.

HTML: https://grepcut.com/pt-br/tools/add-audio-to-video

## Como Adicionar Áudio a um Vídeo no Seu Navegador

1. **Escolha seu vídeo**: Arraste um arquivo MP4, MOV, WebM, MKV, M4V, AVI, OGV, 3GP ou MPEG para o GrepCut. Seu vídeo permanece no seu dispositivo.
2. **Escolha seu áudio**: Adicione um arquivo MP3, WAV, AAC, M4A, FLAC, OGG ou Opus. Este arquivo se tornará a nova trilha sonora.
3. **Misture e exporte**: Clique em Misturar e exportar. O GrepCut multiplexa o fluxo de vídeo e seu novo áudio em um único MP4.
4. **Baixe o resultado**: Salve o MP4 com -com-audio adicionado ao nome do arquivo. A exportação termina no mais curto dos dois arquivos de entrada.

Precisa sobrepor música de fundo com a voz original, ajustar volume, fade de áudio ou sincronizar uma faixa por alguns quadros? Abra o [GrepCut Studio](/) em vez disso.

## O Que Esta Troca de Áudio Realmente Altera

Se você já tem um vídeo finalizado e um arquivo de áudio separado (narração, música, voz limpa), não precisa de um editor completo apenas para substituir a trilha sonora. O GrepCut pega o fluxo de vídeo do primeiro arquivo e o fluxo de áudio do segundo, e os combina em um único MP4.

Sua trilha sonora original não é mantida. O novo arquivo de áudio se torna a única faixa de áudio na exportação. Isso é útil quando seu clipe está silencioso, com ruído, mudo em alguma plataforma ou exportado com a faixa de áudio errada.

O fluxo de vídeo é copiado quando possível, então a imagem não é recompactada só porque você mudou o áudio. Se o codec de vídeo não puder ser copiado para MP4 de forma limpa, talvez seja necessário um fluxo de trabalho diferente no editor completo.

A ideia principal é simples: você está substituindo uma faixa, não reconstruindo toda a edição.

## Substituição de Áudio vs Edição Completa

| O que você precisa | Use esta ferramenta rápida | Use o GrepCut Studio |
| --- | --- | --- |
| Substituir áudio ruim da câmera por um MP3 ou WAV separado | Sim, este é o fluxo principal | Apenas se também precisar de edições |
| Adicionar narração a uma gravação de tela silenciosa | Sim, se um arquivo de áudio for suficiente | Use para ajustes de tempo |
| Manter o áudio original e adicionar música por cima | Não, o áudio original é substituído | Sim, use múltiplas faixas |
| Fazer fade in/out da música | Não, apenas substituição rápida | Sim, use controles de volume |
| Corrigir áudio que começa atrasado ou adiantado | Não há controles precisos de sincronia aqui | Sim, alinhe na linha do tempo |

Use a ferramenta rápida quando seu vídeo e áudio de substituição já combinarem bem. Use o Studio quando seu áudio precisar de edição, mixagem ou ajuste de tempo.

## Entradas de Vídeo e Áudio Suportadas

Comece com um arquivo de vídeo. O GrepCut é construído para entradas MP4, MOV, WebM, MKV, M4V, AVI, OGV, 3GP e MPEG, além de outros arquivos de vídeo legíveis quando o navegador e o FFmpeg conseguem interpretá-los.

Em seguida, adicione um arquivo de áudio. MP3, WAV, AAC, M4A, FLAC, OGG e Opus são as entradas de áudio testadas. A saída é sempre um MP4, o que facilita compartilhar, reproduzir e importar o resultado em aplicativos comuns.

### Algumas notas práticas sobre formatos:

- **MP4 e MOV**: bons para clipes de celular, gravações de tela, exportações de câmera e rascunhos de redes sociais.
- **WebM e MKV**: úteis quando sua fonte veio de um gravador de navegador, download ou fluxo de trabalho de código aberto.
- **WAV e FLAC**: bons para narração limpa ou masters de música antes da criação do MP4 final.
- **OGG e Opus**: úteis para áudio gravado por aplicativos web, jogos ou ferramentas de mídia abertas.

Se um arquivo abre mas a exportação falha, o culpado geralmente não é a extensão do arquivo, mas o codec dentro do contêiner.

## Por Que Sua Exportação Termina no Arquivo Mais Curto

O GrepCut corta a exportação na entrada mais curta para que você não obtenha uma longa cauda preta, final silencioso ou áudio extra oculto após o fim da imagem. Se sua música é mais longa que o clipe, a música é cortada no final do vídeo. Se sua narração é mais curta que o clipe, o vídeo exportado termina quando a narração termina.

Esse comportamento é intencional para uma ferramenta de substituição rápida. Mantém o resultado previsível sem adicionar looping, preenchimento, fades ou geração de silêncio. Para essas escolhas de tempo, use a linha do tempo completa no GrepCut Studio.

## O Que Você Obtém com uma Troca de Áudio Baseada em Navegador

### Advantages

- Seu vídeo e áudio permanecem no seu dispositivo, sem serem enviados para um servidor.
- A imagem não é recodificada quando a cópia de fluxo é possível.
- Você obtém um MP4 que é mais fácil de reproduzir e compartilhar.
- Você pode substituir áudio ruidoso, mudo ou errado sem abrir uma linha do tempo completa.
- Você pode usar entradas de vídeo comuns e formatos de áudio comuns.

### Disadvantages

- Apenas um arquivo de áudio de substituição é usado.
- O áudio original é removido em vez de mixado por baixo.
- Alterações de volume, fades, ducking e sincronia exata precisam do GrepCut Studio.
- Arquivos muito grandes dependem da memória do seu dispositivo e dos limites do navegador.
- Alguns codecs incomuns podem precisar de conversão antes de caberem dentro do MP4.

> renderizar ou torna o vídeo 3 vezes maior ou há uma perda significativa de qualidade para o mesmo tamanho de arquivo
>
> Reddit r/davinciresolve

## FAQ: Adicionar Áudio ao Vídeo

### É possível substituir o áudio em um MP4 sem renderizar o vídeo novamente?

Sim, quando o fluxo de vídeo pode ser copiado para o MP4 de saída. O GrepCut tenta copiar o fluxo de imagem em vez de recodificá-lo, então mudar a trilha sonora não significa automaticamente perda de qualidade de imagem.

### Seu vídeo ou áudio será enviado?

Não. O GrepCut realiza a troca de áudio localmente no seu navegador usando FFmpeg compilado para WebAssembly. Seus arquivos permanecem no seu dispositivo.

### É possível manter o som original e adicionar música por cima?

Não nesta ferramenta rápida. O áudio de substituição se torna a única trilha sonora. Use o [GrepCut Studio](/) se precisar de música, diálogo e efeitos sonoros juntos.

### O que acontece se seu áudio for mais longo que seu vídeo?

A exportação termina no final do arquivo mais curto. Se seu áudio for mais longo que o vídeo, ele é cortado. Se seu áudio for mais curto, o vídeo termina junto com ele.

### É possível sincronizar áudio que começa muito cedo ou muito tarde?

Esta ferramenta não inclui controles de deslocamento. Se sua narração precisar de alinhamento no nível do quadro, abra o vídeo no [GrepCut Studio](/) e mova o áudio na linha do tempo.

### Quais formatos podem receber áudio?

Você pode começar com vídeo MP4, MOV, WebM, MKV, M4V, AVI, OGV, 3GP ou MPEG. Seu áudio de substituição pode ser MP3, WAV, AAC, M4A, FLAC, OGG ou Opus. O arquivo baixado é MP4.

### Por que o GrepCut exporta MP4 em vez de manter o contêiner original?

MP4 é amplamente suportado por navegadores, celulares, editores e aplicativos sociais. Manter um único contêiner de saída também torna a ferramenta rápida mais simples e previsível.

### Seu arquivo perderá qualidade?

A imagem deve permanecer a mesma quando a cópia de fluxo funciona. O áudio é retirado do seu arquivo de substituição e multiplexado na saída, então o resultado depende da qualidade do arquivo de áudio que você fornece.

## Fontes e leitura adicional

- [Discussão no Reddit sobre substituir áudio em MP4 sem renderizar](https://www.reddit.com/r/davinciresolve/comments/1fnsfjb/how_do_i_replace_the_audio_of_an_mp4_without/)
- [Tópico no Super User sobre substituir áudio em vídeo com FFmpeg](https://superuser.com/questions/1137612/ffmpeg-replace-audio-in-video)
- [Tópico no Super User sobre comportamento de duração de áudio e vídeo](https://superuser.com/questions/801547/ffmpeg-add-audio-but-keep-video-length-the-same-not-shortest)
- [Discussão no Reddit sobre editar áudio sem recodificar vídeo](https://www.reddit.com/r/VideoEditing/comments/v1n6tu/edit_audio_without_reencoding_video/)
- [Documentação do FFmpeg sobre especificadores de fluxo e cópia de codec](https://ffmpeg.org/ffmpeg.html)
- [Guia da MDN sobre formatos de contêiner de mídia](https://developer.mozilla.org/pt-BR/docs/Web/Media/Guides/Formats/Containers)

## Substitua Sua Trilha Sonora de Vídeo Privadamente

Abra o GrepCut, adicione seu vídeo, adicione seu áudio de substituição e exporte um MP4 sem enviar seus arquivos.

## Ferramentas Relacionadas

- [Silenciar vídeo](https://grepcut.com/pt-br/tools/mute-video) - remova a trilha sonora antes de adicionar uma nova.
- [Cortar vídeo](https://grepcut.com/pt-br/tools/video-trimmer) - corte o clipe antes de substituir o áudio.
- [Gravar legendas SRT](https://grepcut.com/pt-br/tools/burn-srt-subtitles-to-video) - grave as legendas depois de substituir a trilha sonora.

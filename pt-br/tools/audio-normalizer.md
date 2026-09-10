# Normalizador de Loudness de Áudio Online

Meça o loudness integrado e normalize suas faixas para -14, -16 ou -23 LUFS. Funciona inteiramente no seu navegador, sem enviar o arquivo e sem conta.

HTML: https://grepcut.com/pt-br/tools/audio-normalizer

## Como Normalizar o Volume do Áudio Online

1. **Envie seu áudio**: Arraste um arquivo MP3, WAV, M4A ou OGG para a área de envio.
2. **Escolha seu alvo LUFS**: Selecione Streaming em -14 LUFS, Podcast em -16 LUFS ou Broadcast em -23 LUFS.
3. **Normalize e exporte WAV**: Clique em Normalizar para medir o volume, aplicar ganho seguro com limitador de pico e baixar uma cópia em WAV.

Seu arquivo é processado localmente no seu navegador. Nada é enviado para o GrepCut.

## Por que seu áudio precisa de LUFS, não apenas de normalização de pico

Se seu clipe tem picos próximos a 0 dB, mas soa baixo comparado a outros áudios, a normalização de pico não resolverá o problema real. Picos mostram apenas a amostra mais alta, enquanto LUFS estima o quão alto seu áudio soa ao longo do tempo.

O GrepCut mede a loudness integrada com ponderação K, depois aplica ganho em direção ao alvo selecionado, respeitando um teto de pico de -1 dBTP. Isso ajuda seu áudio a se aproximar de um alvo de loudness para streaming, podcast ou broadcast sem empurrar os picos para o clipping.

### Use isto quando quiser uma loudness percebida consistente antes de compartilhar, publicar ou editar mais.

Se seu arquivo já está muito alto e não tem margem de headroom, o teto de pico pode impedir que a ferramenta atinja o alvo LUFS exato. Nesse caso, um resultado mais seguro é geralmente melhor do que um resultado com clipping.

## Qual alvo LUFS você deve escolher?

| Alvo | Melhor para | O que faz |
| --- | --- | --- |
| -14 LUFS | Streaming de vídeo ou prévias musicais | Um alvo de loudness comum quando você quer que o áudio se aproxime dos níveis de reprodução dos principais streamings. |
| -16 LUFS | Podcasts e clipes de voz | Um alvo prático para conteúdo focado em voz, onde clareza e consistência importam mais que o volume máximo. |
| -23 LUFS | Entrega no estilo broadcast | Um alvo mais silencioso alinhado com fluxos de trabalho de loudness broadcast como o EBU R128. |

Esses predefinições são pontos de partida. Sua plataforma de entrega final pode aplicar sua própria normalização de reprodução após a publicação.

## O que acontece dentro do seu navegador

Quando você adiciona um arquivo, seu navegador decodifica o áudio para que o GrepCut possa analisar a forma de onda. A ferramenta mede a loudness em toda a faixa, calcula o ganho necessário para o alvo LUFS selecionado e limita o resultado para que os picos fiquem abaixo do teto.

Como o processamento é local, seu áudio permanece no seu dispositivo. Arquivos muito longos podem demorar mais porque seu navegador precisa decodificar e processar o áudio na memória.

- **Privado por design**: Seu áudio de origem não é enviado para um servidor.
- **Consciente de LUFS**: A ferramenta visa a loudness percebida, não apenas o pico de amostra mais alto.
- **Exportação WAV**: O resultado normalizado é baixado como um arquivo WAV para edição, arquivamento ou conversão.

## Quando a normalização de loudness é mais útil

Use a normalização LUFS quando seu memo de voz, segmento de podcast, gravação de tela ou clipe musical soar muito mais baixo ou mais alto que o resto do seu projeto. É especialmente útil antes de montar vários clipes em uma única timeline.

Para voz, você ainda pode querer limpar ruídos, equalizar, comprimir ou editar pausas antes da normalização. A normalização de loudness é geralmente a etapa final de ajuste de nível, não um substituto para corrigir uma gravação ruidosa ou uma performance irregular.

## Prós e Limites do Normalizador de Áudio

### Advantages

- Você pode normalizar MP3, WAV, M4A ou OGG sem enviar seu arquivo.
- Você pode escolher predefinições LUFS claras para streaming, podcast ou broadcast.
- O limitador de pico reduz o risco de clipping quando o ganho é adicionado.

### Disadvantages

- O formato de exportação é WAV, não MP3 ou M4A.
- Um arquivo sem headroom restante pode não atingir o alvo LUFS exato sem clipping.
- O suporte de decodificação do navegador pode variar conforme o codec do arquivo e o dispositivo.

> Normalização ajusta cada música ao mesmo nível de pico, mas isso não é o mesmo que ajustá-las ao mesmo nível de loudness.
>
> Reddit r/audioengineering

## FAQ do Normalizador de Áudio

### É possível normalizar áudio para -14 LUFS online?

Sim. Escolha a predefinição Streaming para alvo -14 LUFS e exporte o resultado normalizado como WAV. Seu navegador faz o processamento localmente, então seu arquivo não é enviado.

### Devo usar -14 LUFS ou -16 LUFS?

Use -14 LUFS quando quiser um alvo comum de streaming. Use -16 LUFS quando estiver preparando áudio de voz, como um segmento de podcast. Se não tiver certeza, escolha a predefinição que corresponde ao uso do seu áudio.

### É possível normalizar áudio para loudness de broadcast?

Sim. Escolha a predefinição Broadcast para alvo -23 LUFS. Isso é útil quando você quer um alvo de loudness mais silencioso no estilo broadcast, em vez de um alvo de streaming ou podcast.

### Meu arquivo de áudio será enviado?

Não. O GrepCut processa seu áudio no navegador. O arquivo de origem permanece no seu dispositivo, e o WAV normalizado é gerado localmente.

### A normalização de loudness distorce o áudio?

A ferramenta aplica ganho com um teto de pico de -1 dBTP para reduzir o risco de clipping. Se sua origem já estiver muito alta, o limitador pode impedir o alvo LUFS exato para que a exportação seja mais segura.

### Por que meu arquivo ainda soa diferente após igualar o LUFS?

LUFS é um guia forte de loudness, mas tom, graves, compressão, ruído de fundo e faixa dinâmica ainda afetam o quão alto seu áudio soa. Dois arquivos podem compartilhar um valor LUFS e ainda soar diferentes.

### Posso exportar MP3 após a normalização?

Esta ferramenta exporta WAV. Se precisar de outro formato de entrega, normalize primeiro e depois converta o WAV com um conversor separado.

## Fontes e leitura adicional

- [Discussão no Reddit sobre normalização de loudness em podcasts](https://www.reddit.com/r/podcasts/comments/f1fbew/editing_question_do_you_normalize_and_if_so_how/)
- [Discussão no Reddit sobre normalização de pico versus loudness percebida](https://www.reddit.com/r/audioengineering/comments/kctip9/normalising_the_volume_of_100_tracks_at_once/)
- [Guia do Spotify sobre normalização de loudness](https://support.spotify.com/us/artists/article/loudness-normalization/)
- [Recomendação ITU-R BS.1770-5 sobre loudness e pico verdadeiro](https://www.itu.int/dms_pubrec/itu-r/rec/bs/R-REC-BS.1770-5-202311-I!!PDF-E.pdf)
- [Visão geral da Web Audio API no MDN](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API)
- [Referência de decodificação de áudio no navegador (decodeAudioData) no MDN](https://developer.mozilla.org/en-US/docs/Web/API/BaseAudioContext/decodeAudioData)

## Normalize seu áudio de forma privada

Abra o Normalizador de Áudio, escolha seu alvo LUFS e exporte um WAV limpo sem enviar seu arquivo para um servidor.

## Ferramentas Relacionadas

- [Removedor de ruído de áudio](https://grepcut.com/pt-br/tools/audio-noise-remover) - Limpe o ruído de fundo antes de normalizar o volume.
- [Criador de toques](https://grepcut.com/pt-br/tools/ringtone-maker) - Corte um clipe curto e exporte um toque M4R ou MP3.

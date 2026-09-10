# Cortador de Vídeo Online Grátis

Corte um vídeo até a parte que você precisa em menos de 2 segundos. Usando cópia de fluxo sem perdas alinhada a keyframes, tudo acontece localmente no seu navegador, sem upload e sem perda de qualidade.

HTML: https://grepcut.com/pt-br/tools/video-trimmer

## Como Cortar um Vídeo no Seu Navegador

1. **Adicione seu vídeo**: Solte o arquivo no cortador ou clique para procurar. Seu vídeo carrega localmente na pré-visualização.
2. **Escolha a parte desejada**: Arraste os controles de início e fim, depois pré-visualize o intervalo antes de exportar.
3. **Exporte seu corte**: Crie um MP4 cortado usando cópia de fluxo alinhada a keyframes, ou continue editando no GrepCut Studio.

Precisa de vários cortes, legendas, música ou remover uma seção do meio? Abra o clipe no [GrepCut Studio](/).

## Por Que Seus Vídeos Exportam Tão Rápido

Quando você só precisa cortar o início ou o fim de um clipe, fazer upload do arquivo inteiro para um servidor pode parecer desperdício. O GrepCut mantém seu arquivo no dispositivo e o corta diretamente no navegador.

O cortador usa WebCodecs e MediaBunny para ler o arquivo de mídia, copiar os pacotes de vídeo e áudio já codificados e remuxá-los em um novo MP4. Como seu navegador não precisa decodificar e recodificar cada quadro, a exportação geralmente termina em segundos.

### Você obtém um corte rápido porque o GrepCut evita a parte mais lenta da edição:

- **Sem transcodificação completa**: O intervalo selecionado é copiado do fluxo de origem em vez de ser recodificado do zero.
- **Sem espera de envio**: Seu arquivo permanece no dispositivo, então você não precisa esperar que ele seja enviado a um servidor antes de começar o corte.
- **Sem perda de qualidade por geração**: O caminho de cópia de fluxo preserva a mídia codificada original no intervalo exportado.

## O Que o Corte Alinhado a Keyframes Significa para Você

Um vídeo comprimido não é apenas uma pilha de imagens completas. A maioria dos quadros depende de quadros próximos, e os keyframes são os pontos seguros onde a reprodução pode começar de forma limpa.

É por isso que um cortador de cópia de fluxo sem perdas pode ajustar seu corte ao keyframe utilizável mais próximo, em vez de cortar em qualquer quadro arbitrário. Você obtém um MP4 rápido e compatível com os padrões, mas o início ou fim exportado pode ser ligeiramente anterior ou posterior à posição do controle.

Se você precisa de corte exato por quadro, efeitos visuais, transições ou um corte no meio de um clipe, use o editor completo em vez do cortador de intervalo único.

## Cortador de Navegador vs Cortador Online Tradicional

| O que você precisa | Cortador de Vídeo GrepCut | Cortador de servidor típico |
| --- | --- | --- |
| Privacidade | Seu vídeo permanece no seu dispositivo | Seu vídeo é enviado antes do processamento |
| Velocidade | Cópia de fluxo rápida para um intervalo contínuo | Tempo de upload mais processamento no servidor |
| Qualidade | Preserva a qualidade original no intervalo copiado | Pode recodificar e adicionar perda por geração |
| Precisão do corte | Alinhado a keyframes seguros de vídeo | Pode ser exato por quadro se o servidor recodificar |
| Melhor uso | Remover rapidamente o início ou fim de um clipe | Edições mais pesadas, mudanças de formato ou exportações exatas por quadro |

Escolha o GrepCut quando quiser um corte privado, rápido e sem upload. Escolha um editor completo quando sua edição precisar de temporização exata por quadro ou vários intervalos separados.

## Antes de Cortar

### Advantages

- Seu arquivo não é enviado para um servidor.
- A pré-visualização é atualizada enquanto você ajusta o intervalo.
- A cópia de fluxo mantém o intervalo selecionado na qualidade original.
- Sem marca d'água, sem conta e sem instalação.

### Disadvantages

- Os pontos de corte são alinhados aos keyframes próximos.
- Arquivos muito grandes dependem da memória do seu dispositivo.
- Esta ferramenta mantém apenas um intervalo contínuo.
- Você precisa de um navegador com suporte a WebCodecs.

> você só pode cortar um vídeo em um keyframe (sem codificação)
>
> Discussão no Reddit r/ffmpeg

## Perguntas Frequentes sobre o Cortador de Vídeo

### O vídeo é enviado quando você o corta?

Não. Seu arquivo é processado localmente no navegador, portanto não sai do seu dispositivo.

### Cortar reduzirá a qualidade do vídeo?

Nenhuma perda de qualidade é introduzida no caminho de cópia de fluxo. O GrepCut copia a mídia codificada do intervalo selecionado e a remuxa em um novo MP4.

### Por que o corte não é exato por quadro?

O corte de vídeo sem perdas precisa respeitar os keyframes. Se o início ou fim escolhido cair entre keyframes, o GrepCut alinha o corte a um ponto seguro próximo para que o MP4 exportado seja reproduzido corretamente.

### Você pode cortar o meio de um vídeo?

Este cortador mantém um intervalo contínuo. Se precisar remover uma seção do meio ou fazer vários cortes, abra o clipe no [GrepCut Studio](/).

### Você pode cortar um arquivo de vídeo grande?

Sim, mas seu navegador e a memória do dispositivo ainda importam. Como o arquivo é manipulado localmente, vídeos muito grandes podem ser limitados pelo seu computador, e não por um limite de upload.

### Quais navegadores funcionam melhor?

Use um navegador com suporte a WebCodecs, como Chrome, Edge ou Opera. Se o seu navegador não suportar as APIs de mídia necessárias, o cortador pode não funcionar.

### Que arquivo você obtém após o corte?

Você exporta um MP4 contendo o intervalo contínuo selecionado. O objetivo é um arquivo amplamente reproduzível sem fazer upload ou transcodificar todo o vídeo.

## Fontes e leitura adicional

- [Discussão no Reddit sobre cortar vídeo sem recodificar em keyframes](https://www.reddit.com/r/ffmpeg/comments/10tj7nu/can_you_only_cut_videos_without_reencoding_on/)
- [Discussão no Reddit sobre cortar vídeo sem recodificar](https://www.reddit.com/r/ffmpeg/comments/1qag2ug/trimming_video_without_reencoding/)
- [Discussão no Super User sobre cortar vídeo com nenhuma ou mínima recodificação](https://superuser.com/questions/1850814/how-to-cut-a-video-with-ffmpeg-with-no-or-minimal-re-encoding)
- [Discussão no Super User sobre corte rápido de vídeo e cópia de fluxo](https://superuser.com/questions/1643484/fast-and-relatively-accurate-cutting-from-a-video)
- [Visão geral da API WebCodecs no MDN](https://developer.mozilla.org/en-US/docs/Web/API/WebCodecs_API)
- [MediaBunny toolkit de mídia para navegador](https://mediabunny.dev/)

## Corte Seu Clipe e Continue Editando

Use o cortador para um corte privado e rápido. Quando seu clipe precisar de legendas, música, alterações de layout ou uma linha do tempo completa, abra-o no GrepCut Studio e continue criando no navegador.

## Ferramentas Relacionadas

- [Cortar Vídeo](https://grepcut.com/pt-br/tools/crop-video) - reformate seu clipe para uma região ou proporção.
- [Redimensionar Vídeo](https://grepcut.com/pt-br/tools/resize-video) - redimensione clipes cortados para uma nova resolução ou proporção.
- [Silenciar Vídeo](https://grepcut.com/pt-br/tools/mute-video) - remova a faixa de áudio do seu clipe.

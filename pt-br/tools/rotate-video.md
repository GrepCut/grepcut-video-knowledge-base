# Girar Vídeo Online

Endireite gravações de celular na vertical ou gire seu clipe para postagens em redes sociais. Processado localmente no seu navegador - sem upload, sem marca d'água.

HTML: https://grepcut.com/pt-br/tools/rotate-video

## Como Girar um Vídeo no Seu Navegador

1. **Adicione seu vídeo**: Arraste seu MP4, MOV, WebM, MKV ou M4V para a ferramenta, ou clique para procurar. Seu arquivo permanece no seu dispositivo enquanto o navegador prepara a prévia.
2. **Escolha o ângulo**: Selecione 90° no sentido horário, 180° ou 90° no sentido anti-horário. Use a prévia para verificar se o clipe do celular está na vertical antes de exportar.
3. **Selecione o modo de exportação**: Use "Pronto para redes sociais" quando quiser que a rotação seja incorporada aos pixels, ou "Remux rápido" quando precisar apenas alterar a flag de rotação do MP4.
4. **Baixe seu MP4**: Clique em Girar para exportar seu vídeo corrigido como MP4. Você também pode abrir o clipe no GrepCut Studio se precisar cortar, redimensionar, adicionar legendas ou editar a linha do tempo.

Precisa de mais do que rotação? Abra seu clipe no [GrepCut Studio](/) e continue editando no navegador.

## Por Que o Vídeo do Seu Celular Aparece Lateral

Um vídeo de celular pode parecer correto na sua galeria, mas lateral em outro aplicativo porque o arquivo pode armazenar uma flag de rotação em vez de pixels na orientação correta. Quando um player ou serviço de upload respeita essa flag, seu clipe fica correto. Quando ignora a flag, o vídeo aparece rotacionado, mesmo que a gravação em si não esteja quebrada.

O GrepCut oferece duas soluções para esse problema. O modo "Pronto para redes sociais" rotaciona fisicamente os quadros e limpa a flag de rotação, sendo a escolha mais segura antes de publicar. O "Remux rápido" mantém o fluxo de vídeo original e atualiza os metadados de rotação, sendo mais rápido, mas depende de o próximo aplicativo ler a flag corretamente.

### Use quando:

- **Seu clipe do celular está lateral**: Deixe a gravação em retrato ou paisagem na vertical antes de fazer o upload.
- **Seu vídeo está de cabeça para baixo**: Gire 180° quando a orientação da câmera estava errada durante a gravação.
- **Seu aplicativo ignora metadados de rotação**: Incorpore a rotação nos pixels para que a saída não dependa de uma flag oculta.
- **Você precisa de uma exportação rápida em MP4**: Salve um MP4 corrigido sem abrir um editor de vídeo no computador.

Se for postar no Instagram, TikTok, YouTube ou outro serviço que possa processar o arquivo novamente, escolha **Pronto para redes sociais** para obter o resultado mais previsível.

## Pronto para Redes Sociais vs Remux Rápido

| Necessidade | Pronto para redes sociais | Remux rápido |
| --- | --- | --- |
| O que muda | Rotaciona os quadros de vídeo reais e limpa a flag de rotação | Mantém os quadros originais e atualiza os metadados de rotação do MP4 |
| Velocidade | Mais lento porque o vídeo é recodificado para H.264 | Quase instantâneo porque os pacotes de vídeo comprimidos são copiados |
| Qualidade | Exportação H.264 de alta qualidade, mas ainda é uma recodificação | Idêntico ao fluxo de vídeo original |
| Melhor para uploads em redes sociais | Melhor escolha quando o próximo aplicativo pode ignorar metadados de rotação | Funciona apenas quando o próximo aplicativo respeita a flag de rotação |
| Saída | Pixels na orientação correta em um arquivo MP4 | Mesmos pixels com uma instrução de rotação corrigida |

Ambos os modos são executados localmente no seu navegador. Seu vídeo original não é enviado e a exportação não tem marca d'água.

## Quando Recodificar em Vez de Remux

O remux rápido é útil quando você quer uma correção local rápida e sabe que o próximo player lê os metadados de rotação do MP4. Pode ser a escolha certa para pré-visualização, arquivamento ou envio de arquivo para um aplicativo que já lida corretamente com flags de rotação.

O modo "Pronto para redes sociais" é melhor quando o clipe será enviado, comprimido novamente ou aberto em diferentes dispositivos. Ao escrever pixels na orientação correta no MP4, você elimina as incertezas. Sua exportação pode demorar mais, mas o arquivo é mais fácil para plataformas sociais e players básicos exibirem corretamente.

### Uma regra simples:

Se o vídeo é para postar, escolha **Pronto para redes sociais**. Se o vídeo é para seu próprio dispositivo e você quer a correção mais rápida possível, tente o **Remux rápido**.

## Girar Vídeo de Relance

### Advantages

- Processamento privado sem upload para servidor.
- Opções de rotação de 90°, 180° e 270°.
- Exportação MP4 pronta para redes sociais para orientação previsível.
- Opção de remux rápido quando você precisa apenas de uma correção de metadados.
- Exportação gratuita sem marca d'água.

### Disadvantages

- O modo pronto para redes sociais recodifica o vídeo, então a exportação demora mais que o remux.
- O remux rápido depende de o próximo aplicativo respeitar os metadados de rotação.
- Apenas rotação em ângulos retos é suportada, não ângulos arbitrários.
- Requer um navegador moderno com suporte a WebCodecs.

> observado por alguns players e não por outros
>
> Discussão no Stack Overflow sobre metadados de rotação MP4

## Girar Vídeo - FAQ

### É possível girar um vídeo sem fazer upload?

Sim. O GrepCut executa o processo de rotação no seu navegador, então seu arquivo permanece no seu dispositivo em vez de ser enviado para um servidor.

### Por que meu MP4 aparece lateral em um aplicativo, mas correto em outro?

Seu MP4 pode conter metadados de rotação. Alguns players leem essa instrução e giram o vídeo durante a reprodução, enquanto outros aplicativos a ignoram. Use o modo **Pronto para redes sociais** quando quiser que o MP4 exportado contenha pixels na orientação correta em vez de depender de metadados.

### Devo usar Pronto para redes sociais ou Remux rápido?

Use **Pronto para redes sociais** quando planeja postar o clipe online ou enviá-lo para um aplicativo que pode ignorar flags de rotação. Use **Remux rápido** quando quiser a exportação mais rápida e o próximo player provavelmente respeitar os metadados de rotação do MP4.

### Girar o vídeo reduzirá a qualidade?

O remux rápido mantém o fluxo de vídeo original inalterado, então o vídeo permanece idêntico. O modo pronto para redes sociais recodifica para H.264 para que a rotação seja incorporada aos pixels, o que é mais confiável para postagem, mas leva mais tempo.

### Quais formatos de vídeo posso girar?

Você pode adicionar MP4, MOV, WebM, MKV, M4V e a maioria dos formatos de vídeo comuns. O GrepCut exporta o resultado girado como MP4.

### O áudio permanecerá sincronizado após a rotação?

Sim. A rotação não altera a velocidade de reprodução. O áudio é copiado sem perdas quando já está em AAC, ou recodificado para AAC para ampla compatibilidade com MP4.

### Posso girar por um ângulo personalizado, como 12°?

Não. Esta ferramenta foi criada para correções em ângulos retos: 90° no sentido horário, 180° e 90° no sentido anti-horário. Para vídeos laterais de celular, essas são geralmente as correções necessárias.

### Por que o GrepCut precisa de um navegador moderno?

A exportação pronta para redes sociais depende de recursos de processamento de vídeo do navegador, como WebCodecs. Se seu navegador não suportar as APIs necessárias, tente um navegador baseado em Chromium atualizado.

## Fontes e leitura adicional

- [Discussão no Reddit sobre filmar acidentalmente no modo retrato](https://www.reddit.com/r/VideoEditing/comments/xryq3n/i_accidentally_filmed_my_videos_in_portrait_mode/)
- [Pergunta no Reddit sobre fluxo de trabalho para girar sem recodificar](https://www.reddit.com/r/VideoEditing/comments/uuw62f/automatically_rotate_video_without_actually/)
- [Explicação no Super User sobre metadados de rotação de vídeos do iPhone](https://superuser.com/questions/564233/iphone-recorded-videos-getting-rotated-on-windows-systems)
- [Discussão no Stack Overflow sobre flags de rotação MP4](https://stackoverflow.com/questions/69386275/mp4-and-rotation-remove-flags-but-set-rotation)
- [Guia MDN sobre a API WebCodecs](https://developer.mozilla.org/en-US/docs/Web/API/WebCodecs_API)
- [Especificação W3C do WebCodecs](https://www.w3.org/TR/webcodecs/)

## Terminou de Girar? Monte a Edição Completa

Abra o GrepCut Studio para cortar, redimensionar, adicionar legendas, adicionar música e finalizar sua edição de vídeo baseada no navegador.

## Ferramentas Relacionadas

- [Cortar Vídeo](https://grepcut.com/pt-br/tools/crop-video) - apare seu quadro para uma região ou proporção.
- [Redimensionar Vídeo](https://grepcut.com/pt-br/tools/resize-video) - escala seu clipe por porcentagem.
- [Cortador de Vídeo](https://grepcut.com/pt-br/tools/video-trimmer) - corte seu clipe antes ou depois de girar.

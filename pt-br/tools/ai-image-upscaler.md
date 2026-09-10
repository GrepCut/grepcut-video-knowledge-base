# Ampliador de Imagens por IA Online Grátis

Melhore fotos e gráficos com super-resolução Real-CUGAN executada localmente no seu dispositivo. Sem enviar imagens, sem marca d'água; ou use o modo Canvas rapido para exportações rápidas em 3×.

HTML: https://grepcut.com/pt-br/tools/ai-image-upscaler

## Como Ampliar uma Imagem com IA no Seu Navegador

1. **Arraste sua imagem**: Carregue um arquivo JPG, PNG ou WebP do seu dispositivo.
2. **Escolha o modo de ampliação**: Use a IA Real-CUGAN para super-resolução 2x ou 4x, ou o modo Canvas Rápido para redimensionamento rápido em 2x, 3x e 4x.
3. **Exporte a imagem ampliada**: Baixe sua imagem ampliada em PNG ou JPEG sem marca d'água.

Sua imagem é processada localmente no seu navegador. Nada é enviado para o GrepCut. Precisa ampliar clipes em vez de imagens estáticas? Experimente o [Ampliador de Vídeo](/tools/video-upscaler).

## Quando a Ampliação por IA Ajuda Sua Imagem

Se sua foto, digitalização, captura de tela ou exportação de rede social é muito pequena para um layout, você precisa de mais pixels antes de cortar, imprimir ou reutilizar. A super-resolução por IA faz mais do que esticar a imagem: ela prevê bordas e texturas mais nítidas a partir da entrada de baixa resolução.

O modo IA do GrepCut executa o Real-CUGAN localmente com TensorFlow.js. Isso significa que você pode ampliar uma imagem sem enviar o arquivo para fora do seu dispositivo, criar uma conta ou adicionar uma marca d'água.

### Use quando quiser um arquivo maior sem sair do navegador:

- **Fotos pequenas**: Aumente a resolução antes de cortar mais apertado ou colocar a imagem em um design maior.
- **Ilustrações e arte de anime**: O Real-CUGAN foi criado para super-resolução de imagem e é especialmente relevante para detalhes desenhados, bordas e obras de arte estilizadas.
- **Capturas de tela e miniaturas**: Torne capturas de interface, imagens de pré-visualização e capturas de documentação mais fáceis de reutilizar em tamanhos maiores.

## Modo IA vs Modo Canvas Rápido

| Modo | Melhor para | O que esperar |
| --- | --- | --- |
| Real-CUGAN IA | Ampliação 2x ou 4x quando a qualidade dos detalhes importa | Reconstrução mais nítida, processamento mais lento e melhores resultados em navegadores modernos com WebGPU ou WebGL |
| Canvas Rápido | Exportações rápidas em 2x, 3x ou 4x | Redimensionamento rápido do navegador sem recuperação de detalhes por rede neural |
| Verificação do tamanho original | Entradas muito ruidosas, comprimidas ou borradas | A ampliação pode tornar danos existentes mais visíveis, então inspecione o resultado antes de usar em impressão ou listagens |

Se você precisa de dimensões exatas em pixels em vez de um multiplicador, use o [Redimensionador de Imagem](/tools/resize-video) após a ampliação.

## Por que a Ampliação 4x Não é Mágica

Uma ampliação 4x dá ao seu arquivo muito mais pixels, mas não pode recuperar informações que nunca foram capturadas. Se sua imagem original tem texto ilegível, blocos JPEG pesados ou desfoque de movimento, a IA pode nitidificar a forma do problema em vez de revelar o detalhe real.

Para resultados mais limpos, comece pela versão menos comprimida que você tiver. Se estiver comparando modos, exporte ambas as versões (IA e Canvas Rápido) e escolha a que parecer mais natural para sua imagem.

Isso é mais importante para rostos, textos e detalhes de produtos, onde um resultado mais nítido nem sempre é um resultado mais preciso.

## Amplificador de Imagem com IA em Resumo

### Advantages

- Funciona no navegador sem enviar a imagem.
- Modo IA Real-CUGAN para super-resolução 2x e 4x.
- Modo Canvas Rápido suporta redimensionamento 2x, 3x e 4x.
- Exportação gratuita sem marca d'água.

### Disadvantages

- O modo IA pode ser mais lento em imagens grandes.
- Fontes muito borradas ou comprimidas ainda podem apresentar artefatos.
- O modo IA precisa de um navegador moderno com suporte a WebGPU ou WebGL.

> os resultados dependem da foto e da resolução do arquivo original
>
> Reddit r/photography

## FAQ do Amplificador de Imagem com IA

### Posso ampliar uma imagem sem fazer upload?

Sim. O GrepCut processa sua imagem localmente no navegador, incluindo o modo IA. Seu arquivo não sai do seu dispositivo.

### Isso é ampliação por IA de verdade ou apenas redimensionamento?

O modo IA usa super-resolução Real-CUGAN. O modo Canvas Rápido é diferente: usa o redimensionamento do Canvas do navegador para exportações rápidas 2x, 3x e 4x sem reconstrução por rede neural.

### Devo usar ampliação IA 2x ou 4x?

Use 2x quando precisar de um aumento modesto de resolução com menos artefatos. Use 4x quando a fonte for limpa o suficiente e você precisar de uma imagem muito maior para design, preparação de impressão ou corte fechado.

### A ampliação por IA corrige texto ou rostos borrados?

Pode tornar as bordas mais nítidas, mas não garante a precisão de detalhes ausentes. Se seu texto ou rosto original estiver muito borrado, inspecione o resultado cuidadosamente antes de tratá-lo como factual ou pronto para impressão.

### Quais formatos de imagem posso enviar?

Você pode enviar imagens JPG, PNG ou WebP. A exportação é salva como PNG ou JPEG, dependendo do que o navegador pode preservar para o seu arquivo.

### Por que o modo IA é mais lento que o Canvas Rápido?

O modo IA executa uma rede neural no seu dispositivo, então o processamento depende do tamanho da imagem, navegador e suporte a GPU. O modo Canvas Rápido pula o modelo de IA, sendo mais rápido, mas com menos detalhes.

### Posso ampliar arte de anime ou imagens de jogos?

Sim. O Real-CUGAN é especialmente relevante para ilustrações, arte estilo anime e bordas gráficas nítidas. Para pixel art, compare IA com Canvas Rápido, pois algumas obras ficam melhores quando a estrutura original de pixels é preservada.

## Fontes e leitura adicional

- [Discussão no Reddit sobre como a ampliação por IA depende da imagem de origem](https://www.reddit.com/r/photography/comments/bml58t/whats_your_opinion_on_upscaling_photos_with_ai/)
- [Thread no Reddit sobre Real-CUGAN para webtoons e arte em estilo de quadrinhos](https://www.reddit.com/r/StableDiffusion/comments/1jcuxna/upscaling_models_recommendations_for_a_newbie/)
- [README do projeto Real-CUGAN](https://github.com/bilibili/ailab/blob/main/Real-CUGAN/README_EN.md)
- [Guia oficial do TensorFlow.js para ambientes de navegador e plataforma](https://www.tensorflow.org/js/guide/platform_environment)
- [Documentação do MDN sobre suavização de imagem em Canvas](https://developer.mozilla.org/en-US/docs/Web/API/CanvasRenderingContext2D/imageSmoothingEnabled)
- [Notas do modelo Real-CUGAN TensorFlow.js no Hugging Face](https://huggingface.co/shammisw/real-cugan-tensorflowjs)

## Terminou de Ampliar? Finalize a Edição Completa

Abra o GrepCut Studio quando quiser combinar seu trabalho de imagem ampliada com edição de linha do tempo, legendas, LUTs e exportação baseada no navegador.

## Ferramentas Relacionadas

- [Video Upscaler](https://grepcut.com/pt-br/tools/video-upscaler) - aumente clipes com interpolação no navegador.
- [Resize Video](https://grepcut.com/pt-br/tools/resize-video) - redimensione vídeos para dimensões exatas em formatos sociais.

# Ampliador de Vídeo FSR Online Grátis

Aumente a resolução do clipe com o upscaling FSR adaptativo de bordas no seu navegador.

HTML: https://grepcut.com/pt-br/tools/video-upscaler

## Leia Isto Primeiro: FSR Nitidiza Bordas, Não Inventa Detalhes

Defina suas expectativas antes de começar. O FSR torna as bordas mais nítidas ao ampliar seu clipe, mas em filmagens já suaves, de baixa taxa de bits ou desfocadas, a melhoria costuma ser marginal, pois há pouca informação real de borda para reconstruir.

FSR é um upscaler espacial, não IA. Ele não pode adicionar detalhes que nunca foram capturados. Reconstruir textura que não está na sua fonte requer um modelo de super-resolução de IA, que é um tipo diferente de ferramenta. Use este upscaler para ampliar de forma limpa e nitidizar bordas, não para recuperar detalhes perdidos.

## Como Ampliar Vídeo Online no Seu Navegador

1. **Carregue seu clipe**: Arraste um arquivo MP4, MOV, WebM ou MKV para a área de envio.
2. **Escolha 2×, 3× ou 4×**: Selecione o fator de ampliação que se adequa à sua linha do tempo, exportação para redes sociais ou layout HD.
3. **Exporte seu MP4**: Baixe o MP4 ampliado ou abra-o no GrepCut Studio para legendas, cortes e finalização.

A ampliação é executada localmente no seu navegador, então seu vídeo permanece no seu dispositivo.

## Use a Ampliação FSR Quando Seu Clipe For Muito Pequeno

Se seu clipe foi gravado em 480p, 720p ou em uma janela pequena de captura de tela, ele pode parecer subdimensionado dentro de uma edição HD. A ampliação aumenta as dimensões dos pixels antes da exportação, para que seu vídeo se encaixe em uma linha do tempo 1080p, um upload no YouTube ou um preset de rede social sem esticamento manual em outro editor.

O GrepCut amplia com FSR (AMD FidelityFX Super Resolution). Em vez de um esticamento suave comum, o FSR reconstrói bordas enquanto amplia, fazendo com que linhas e contornos permaneçam mais nítidos do que com o escalonamento bicúbico. Isso o torna uma escolha prática para filmagens de celular comprimidas, clipes de tutoriais e repostagens que foram exportadas muito pequenas.

### Melhor para:

- **Filmagens antigas de celular**: Aproxime um clipe 480p ou 720p de um layout HD com bordas mais limpas antes de publicar.
- **Gravações de tela**: Facilite a colocação de uma janela de captura pequena em uma edição de tutorial ou apresentação.
- **Repostagens sociais**: Redimensione clipes verticais que vieram de outro aplicativo em uma resolução mais baixa.

## Como Funciona a Ampliação FSR, e o Que Ela Pode e Não Pode Corrigir

FSR é um upscaler espacial: ele trabalha a partir do quadro único à sua frente, sem vetores de movimento, buffer de profundidade ou modelo de IA. Ele é executado em duas passagens na GPU. Primeiro, o EASU (Edge-Adaptive Spatial Upsampling) reamostra o quadro de forma direcional, detectando como os gradientes vizinhos diferem para que as bordas sejam reconstruídas em vez de apenas borradas. Em seguida, o RCAS (Robust Contrast-Adaptive Sharpening) adiciona uma nitidez controlada que realça detalhes sem criar halos ou amplificar ruído.

Como o FSR usa shaders comuns e nunca olha para outros quadros, ele trata cada quadro da mesma forma e mantém sua exportação consistente. No entanto, não é super-resolução de IA. Se sua fonte estiver muito borrada, fortemente comprimida ou com falta de detalhes finos, o FSR pode ajustar um quadro maior com bordas mais nítidas, mas não pode reconstruir textura que nunca foi capturada.

### Nos bastidores:

- **EASU**: Reamostragem adaptativa de borda que reconstrói bordas enquanto amplia, mais nítida que bilinear ou bicúbica.
- **RCAS**: Passagem de nitidez adaptativa ao contraste, aplicada automaticamente, que adiciona definição a bordas reais enquanto deixa áreas planas intactas.

Para filmagens muito suaves, faça primeiro uma exportação de teste curta. Se a pré-visualização já parecer muito suave, um fator menor geralmente parece mais natural do que um esticamento 4× agressivo.

## Comparação entre FSR e Escalonamento Comum

| Método | Como escala | Resultado típico |
| --- | --- | --- |
| Vizinho mais próximo | Duplica o pixel mais próximo. | Bordas em blocos, com degraus duros. |
| Bilinear ou bicúbico | Calcula a média dos pixels vizinhos. | Mais suave, mas bordas parecem macias. |
| FSR (EASU + RCAS) | Reamostragem adaptativa de borda mais nitidez adaptativa ao contraste. | Bordas mais limpas e nítidas sem modelo de IA. |

FSR reconstrói bordas em vez de apenas suavizá-las, mas como todo método espacial, trabalha com o detalhe já presente no seu clipe.

## Qual Fator de Ampliação Você Deve Escolher?

O fator certo depende de quão longe seu clipe está do tamanho necessário. Fatores maiores criam mais pixels a serem reconstruídos, então uma fonte suave mostra seus limites mais cedo em 4× do que em 2×.

### Escolha seu fator:

- **2×**: Um primeiro teste seguro quando seu clipe precisa apenas de um aumento moderado de tamanho.
- **3×**: Útil quando um clipe pequeno precisa preencher mais de uma tela HD.
- **4×**: Melhor para clipes curtos onde você precisa de dimensões máximas e pode esperar um pouco mais.

Comece com 2× quando não tiver certeza e depois tente um fator maior se sua fonte tiver detalhes suficientes para sustentar.

## A Pré-visualização Corresponde à Sua Exportação

O FSR amplia e nitidiza automaticamente, então não há nada para configurar. Escolha um fator, verifique o resultado e exporte. O EASU cuida da ampliação adaptativa de borda e o RCAS adiciona uma nitidez fixa e de bom gosto por cima.

A pré-visualização de antes e depois executa o mesmo pipeline FSR da exportação, então o que você vê é o que estará no seu MP4. Aumente o zoom na pré-visualização para avaliar a nitidez das bordas antes de se comprometer com uma renderização completa.

Se a pré-visualização ainda parecer suave após a ampliação, isso geralmente significa que o detalhe não estava na fonte para começar, e um fator menor pode parecer mais natural.

## Mantenha Seu Vídeo Privado Enquanto Testa

Ferramentas de vídeo online geralmente pedem que você faça upload do arquivo inteiro antes de ver um resultado. Este upscaler é executado no seu navegador, então sua filmagem não sai do seu dispositivo durante o processamento.

Isso é útil quando seu clipe contém conteúdo de tela privado, filmagens sociais não lançadas, rascunhos de clientes ou gravações de sala de aula. Você pode testar um fator, baixar o MP4 e continuar editando sem enviar o arquivo original para um servidor.

Clipes mais longos e exportações 4× dependem da velocidade do seu dispositivo. Para verificações rápidas, corte o clipe primeiro ou teste uma seção curta antes de processar o vídeo completo.

## Ampliador de Vídeo em Resumo

### Advantages

- Executa localmente no seu navegador, sem upload.
- FSR reconstrói bordas, resultando em imagens mais nítidas que o escalonamento bicúbico.
- Ampliação EASU e nitidez RCAS são aplicadas automaticamente, sem necessidade de configuração.
- Predefinições 2×, 3× e 4× mantêm a escolha simples.
- Exportação gratuita em MP4 sem marca d'água.

### Disadvantages

- É um upscaler espacial, não IA, portanto não pode inventar detalhes que não foram capturados.
- Fontes muito borradas ou fortemente comprimidas ainda podem parecer suaves.
- Exportações 4× longas podem demorar mais em dispositivos lentos.
- Se seu navegador não tiver WebGL2, ele recai para uma escala bicúbica simples.

> O FSR 1 não analisa dados de quadros anteriores para melhorar sua ampliação, mas apenas estica cada imagem isoladamente, usando técnicas como detecção de bordas para ajudar a determinar a melhor forma de esticar a imagem.
>
> PCGamesN

## FAQ do Ampliador de Vídeo

### É possível ampliar vídeo online sem fazer upload?

Sim. Seu vídeo é processado localmente no seu navegador, então o arquivo permanece no seu dispositivo.

### FSR é o mesmo que ampliação por IA?

Não. FSR é um upscaler espacial que roda em shaders comuns e trabalha a partir de um único quadro. Ele reconstrói bordas com EASU e nitidiza com RCAS, mas não usa uma rede neural, portanto não pode inventar detalhes como a super-resolução de IA tenta fazer.

### Como o FSR difere da ampliação bicúbica?

A bicúbica calcula a média dos pixels vizinhos, o que amplia o quadro mas deixa as bordas suaves. O FSR analisa como os gradientes vizinhos mudam e reamostra ao longo das bordas, fazendo com que linhas e contornos permaneçam mais nítidos, e então o RCAS adiciona uma nitidez controlada por cima.

### O FSR deixará meu vídeo borrado nítido?

Pode tornar as bordas mais limpas e adicionar alguma definição, mas a melhoria costuma ser marginal em filmagens suaves, e não pode restaurar detalhes ausentes de uma fonte borrada, de baixa taxa de bits ou desfocada. Recuperar detalhes que não estão lá requer um upscaler de IA.

### Qual fator de ampliação devo usar?

Use 2× para uma primeira passagem segura, 3× quando seu clipe precisar de um aumento de tamanho mais forte, e 4× para clipes curtos de baixa resolução onde você precisa da maior saída.

### Posso ampliar um vídeo 480p para uma edição 1080p?

Sim. Você pode ampliar o clipe antes de colocá-lo em uma linha do tempo HD. O FSR mantém as bordas mais limpas do que um esticamento simples, embora o resultado ainda possa parecer mais suave que uma filmagem nativa 1080p porque o original tem menos pixels.

### Preciso ajustar alguma configuração?

Não. O FSR amplia com EASU e nitidiza com RCAS automaticamente, então você só precisa escolher um fator e exportar. A pré-visualização de antes e depois usa o mesmo pipeline da exportação.

### Quais formatos de vídeo posso importar e há marca d'água?

Você pode importar arquivos MP4, MOV, WebM e MKV, e exportar seu MP4 ampliado sem marca d'água.

## Fontes e leitura adicional

- [Visão geral da AMD GPUOpen sobre FidelityFX Super Resolution 1 (EASU e RCAS)](https://gpuopen.com/fidelityfx-superresolution/)
- [Manual técnico de ampliação espacial AMD GPUOpen FSR 1](https://gpuopen.com/manuals/fidelityfx_sdk/techniques/super-resolution-spatial/)
- [FidelityFX Super Resolution 1.0 desmistificado (passo a passo do shader)](https://jntesteves.github.io/shadesofnoice/graphics/shaders/upscaling/2021/09/11/amd-fsr-demystified.html)
- [Tom's Hardware: testando desempenho e qualidade de imagem do FSR](https://www.tomshardware.com/news/amd-fidelityfx-super-resolution-fsr-performance-tested)
- [Tópico do fórum guru3D: FSR 1 é ótimo para o que é](https://forums.guru3d.com/threads/fsr-1-is-great-actually-for-what-it-is.453779/)
- [Tópico do Reddit sobre por que filmagens ampliadas podem parecer borradas](https://www.reddit.com/r/premiere/comments/1asd5id/scaling_up_video_to_a_higher_resolution_makes_it/)
- [Visão geral da Wikipedia sobre métodos de escalonamento de imagem](https://en.wikipedia.org/wiki/Image_scaling)

## Terminou de Ampliar? Aprimore a Edição Completa

Abra seu MP4 ampliado no GrepCut Studio para cortar a linha do tempo, adicionar legendas, ajustar a aparência e exportar o vídeo final no seu navegador.

## Ferramentas Relacionadas

- [Redimensionar Vídeo](https://grepcut.com/pt-br/tools/resize-video) - escala seu clipe por porcentagem.
- [Alterar Velocidade do Vídeo](https://grepcut.com/pt-br/tools/change-video-speed) - desacelere ou acelere sua filmagem.
- [Desfocar Vídeo](https://grepcut.com/pt-br/tools/blur-video) - suavize fundos ou oculte áreas sensíveis.

[5 blocos] / [20 parágrafos totais] / [360 palavras estimadas] / [360 ÷ 200 = 1,8 minutos]

# Como funciona a geração de vídeos com IA

## O que você vai aprender

Nesta aula, você distingue os mecanismos técnicos por trás da geração de vídeo com IA: desde os modelos de difusão até os conceitos de interpolação, optical flow e física simulada que tornam o movimento possível.

## Modelos de difusão e espaço latente

A geração de vídeo começa no mesmo princípio das imagens: modelos de difusão que aprendem a reconstruir padrões visuais a partir de ruído. A diferença está na dimensão temporal.

Um vídeo não é uma sequência de imagens independentes. A IA precisa manter coerência entre quadros, o que exige mecanismos adicionais.

## Os conceitos que definem o movimento

**Interpolação de frames:** a IA preenche os quadros intermediários entre dois estados visuais, criando a ilusão de movimento contínuo.

**Optical flow:** algoritmo que detecta como objetos se movem entre frames e usa esse fluxo para guiar a geração dos próximos quadros.

**Física simulada:** a IA aprende padrões de como líquidos, tecidos e objetos se comportam no mundo real e aplica esses padrões na geração.

**Consistência temporal:** a maior diferença entre gerar imagens e vídeos. Cada frame precisa ser coerente com o anterior, o que multiplica a complexidade computacional.

## FPS e duração

A taxa de frames por segundo (FPS) define a fluidez do vídeo. Modelos diferentes trabalham com FPS diferentes, e isso afeta diretamente a qualidade percebida do movimento.

A duração ideal para a maioria dos modelos atuais fica entre 8 e 20 segundos. Vídeos mais longos aumentam drasticamente o custo computacional e a chance de inconsistências.

## Coloque em prática

Gere um vídeo curto de teste em qualquer ferramenta de IA de vídeo. Observe especificamente o movimento: identifique onde a física simulada parece convincente e onde ela falha. Esse exercício de leitura crítica vai acelerar sua evolução como prompt engineer de vídeo.

---

*Esta descrição cobre os principais conteúdos da aula. Alguns detalhes complementares estão disponíveis apenas no vídeo.*

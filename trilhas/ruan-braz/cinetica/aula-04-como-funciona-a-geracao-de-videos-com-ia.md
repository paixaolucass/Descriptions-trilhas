Cálculo interno: [5 blocos] / [20 parágrafos totais] / [380 palavras estimadas] / [380 ÷ 200 = 2 minutos]

# Como funciona a geração de vídeos com IA

**Tempo estimado de leitura:** 2 minutos

## Objetivos de aprendizado

Ao final desta aula, você será capaz de:

- Identificar os mecanismos técnicos que diferenciam a geração de vídeo da geração de imagens
- Reconhecer o papel do espaço latente e da interpolação de frames no processo de geração
- Aplicar o conceito de FPS e duração ideal para otimizar seu fluxo de trabalho

## Modelos de difusão e espaço latente

A geração de vídeo começa no mesmo princípio das imagens: modelos de difusão que aprendem a reconstruir padrões visuais a partir de ruído. O modelo começa com ruído gaussiano e vai "escavando" a imagem iterativamente até chegar ao resultado final.

A diferença está no espaço latente: ao invés de trabalhar diretamente em alta resolução, a IA opera em uma representação comprimida da imagem. Uma imagem de 512x512 pixels tem cerca de 786 mil números. No espaço latente, isso é condensado em aproximadamente 16 mil números — dezenas de vezes mais eficiente.

## Os conceitos que definem o movimento

**Interpolação de frames:** a IA não gera todos os frames individualmente. Ela gera frames-chave e preenche os intermediários combinando frames entre si, criando a ilusão de movimento contínuo.

**Optical flow:** algoritmo que detecta como objetos se movem entre frames, usando esse fluxo para guiar a geração dos próximos quadros com coerência física.

**Física simulada:** tecidos, líquidos, pele e partículas precisam se comportar de acordo com padrões físicos que a IA aprendeu. Isso é mais exigente do que em imagens estáticas.

**Consistência temporal:** cada frame precisa ser coerente com o anterior e o próximo. Isso multiplica a complexidade computacional do vídeo em relação à imagem.

## FPS e duração ideal

A taxa de frames por segundo (FPS) define a fluidez do vídeo. 24 FPS é o padrão cinema; 30 FPS oferece mais fluidez; 60 FPS é mais fluido ainda. Cada segundo a 24 FPS são 24 frames a serem gerados e mantidos coerentes.

A duração ideal para a maioria dos modelos atuais fica entre 8 e 20 segundos. Gerar em resolução menor primeiro e depois fazer upscale é mais eficiente do que gerar direto em 4K.

## Coloque em prática

Gere um vídeo curto de teste em qualquer ferramenta de IA de vídeo. Observe especificamente o movimento: identifique onde a física simulada parece convincente e onde ela falha. Esse exercício de leitura crítica vai acelerar sua evolução como criador de vídeos com IA.

---

*Esta descrição cobre os principais conteúdos da aula. Alguns detalhes complementares estão disponíveis apenas no vídeo.*

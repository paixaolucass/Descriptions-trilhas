Cálculo interno: 5 blocos / 15 parágrafos totais / 300 palavras estimadas / 300 ÷ 200 = 2 minutos

# O que é e como funciona a geração de imagens com IA

**Tempo estimado de leitura:** 2 minutos

## Objetivos de aprendizado

Ao final desta aula, você será capaz de:

- Distinguir como modelos de difusão funcionam em relação a LLMs
- Identificar por que a geração de imagens é um processo estatístico baseado em padrões
- Reconhecer os vetores como representação matemática que a IA usa para processar imagens

## LLM versus modelo de difusão

Modelos de linguagem (LLMs) como ChatGPT, Claude e Gemini são modelos preditivos que analisam cada palavra de um prompt e devolvem o output estatisticamente mais provável. Já os modelos de difusão operam de forma diferente: eles aprendem desconstruindo imagens em ruído e depois reconstruindo esse ruído progressivamente até chegar a uma imagem coerente com o input recebido.

## O processo de aprendizado da IA

Durante o treinamento, a IA recebe milhões de imagens e vai removendo pixels progressivamente, como um processo de destruição e reconstrução. Repetindo esse ciclo trilhões de vezes, ela começa a identificar padrões. Quando os pixels se organizam de determinada maneira, ela aprende que aquilo é uma orelha, depois um felino, depois um gato. Com isso, ela conecta padrões visuais a palavras, criando rótulos.

## O papel dos vetores

Para a IA, cada pixel é um número com várias dimensões, e esses números carregam a posição, a relação com os pixels vizinhos e os padrões do conjunto. Esse conjunto de números é chamado de vetor. Toda imagem, palavra e artefato digital tem um vetor, e a IA usa esses vetores para identificar padrões e gerar novas imagens.

## Por que a teoria importa na prática

Saber que a IA funciona estatisticamente deixa claro por que ela falha. Erros como mãos com dedos extras ou olhos distorcidos acontecem porque são padrões menos frequentes nos dados de treinamento. Quem reconhece isso toma decisões melhores de prompt e de revisão do resultado.

## Coloque em prática

Gere uma imagem simples com um prompt de uma linha. Depois adicione detalhes específicos de textura, iluminação e ângulo. Compare os dois resultados e observe como a especificidade do prompt afeta o controle sobre o output.

---

*Esta descrição cobre os principais conteúdos da aula. Alguns detalhes complementares estão disponíveis apenas no vídeo.*

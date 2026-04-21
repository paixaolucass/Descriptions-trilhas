Cálculo interno: [5 blocos] / [21 parágrafos totais] / [370 palavras estimadas] / [370 ÷ 200 = 2 minutos]

# Prompts básicos e boas práticas

**Tempo estimado de leitura:** 2 minutos

## Objetivos de aprendizado

Ao final desta aula, você será capaz de:

- Estruturar prompts eficazes para geração de vídeo usando o framework de 6 partes
- Aplicar os 5 níveis evolutivos que definem a progressão de qualidade nos resultados
- Reconhecer o peso das posições no prompt e como isso afeta o resultado gerado

## O peso das palavras no prompt

A posição das palavras no prompt importa. Modelos de difusão atribuem pesos algorítmicos maiores ao início e ao final do prompt — o meio tem menos influência. Os parâmetros da ferramenta têm peso ainda maior do que o texto.

Regra prática: coloque o elemento mais importante primeiro. Se o foco é o enquadramento de câmera, comece por ele. Se é o sujeito, comece pelo sujeito.

## Os 5 níveis evolutivos

**Nível 1 - Ideia:** prompt simples e vago, resultado genérico. "Um homem caminhando na rua."

**Nível 2 - Estrutura:** adiciona os 6 elementos do framework. Resultado mais controlado e previsível.

**Nível 3 - Controle:** usa referências visuais, negative prompt e parâmetros específicos da ferramenta.

**Nível 4 - Alavancagem:** combina image-to-video com referências de estilo e câmera para maximizar consistência.

**Nível 5 - Pipeline:** integra múltiplos modelos em fluxo automatizado com controle paramétrico via API.

## O framework de 6 partes

Todo prompt de vídeo eficaz contém estes 6 elementos, nesta ordem:

1. **Câmera e movimento:** tipo de plano, movimento de câmera (ex.: close-up, dolly in lento, tracking shot)
2. **Sujeito e atributos:** quem ou o quê está no vídeo, com suas características visuais específicas
3. **Ação única:** o que acontece na cena — uma ação específica, não uma sequência
4. **Ambiente:** onde a cena acontece, com detalhes do cenário
5. **Luz e atmosfera:** tipo, direção e qualidade da luz
6. **Estilo e referência:** estética, paleta de cores ou referência cinematográfica

## Assistente de prompt

Você pode criar um assistente em qualquer LLM (ChatGPT, Claude, Gemini) com a estrutura do framework e pedir que ele transforme suas ideias em prompts profissionais para geração de vídeo. Isso agiliza o processo sem depender de memorizar toda a estrutura.

## Coloque em prática

Escreva um prompt no nível 1 (ideia básica) e depois reescreva o mesmo conceito no nível 2 aplicando os 6 elementos do framework. Gere os dois e compare os resultados lado a lado.

---

*Esta descrição cobre os principais conteúdos da aula. Alguns detalhes complementares estão disponíveis apenas no vídeo.*

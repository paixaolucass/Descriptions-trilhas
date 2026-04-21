[5 blocos] / [21 parágrafos totais] / [360 palavras estimadas] / [360 ÷ 200 = 1,8 minutos]

# Estruturas JSON para prompts avançados

## O que você vai aprender

Nesta aula, você reconhece quando e por que usar JSON como linguagem de prompt para geração de vídeo, distingue os casos em que ele supera o texto natural e aplica o fluxo correto para gerar e versionar shot breakdowns estruturados.

## O que é JSON em prompt de vídeo

JSON é uma linguagem de programação usada para estruturar dados. Aplicada a prompts de vídeo, ela substitui o texto livre por campos explícitos: cada elemento da cena (câmera, sujeito, ação, ambiente, iluminação, estilo) ocupa um slot separado.

Resultado: zero ambiguidade. A IA não precisa inferir o que pertence a cada camada do prompt.

## Quando JSON faz sentido

JSON é desnecessário para imagens. Em vídeo, ele é relevante quando:

- Você precisa de controle temporal por segundo (timestamp prompting)
- Trabalha com equipes que precisam versionar e modificar shots de forma cirúrgica
- Usa pipelines avançados com APIs que aceitam parâmetros estruturados

Em plataformas de navegador comuns, o JSON pode ser interpretado de forma incorreta devido a mecanismos de proteção contra prompt injection.

## O fluxo correto

1. Descreva o conceito em linguagem natural para um LLM (Claude, ChatGPT, Gemini)
2. Peça ao LLM para gerar o shot breakdown em JSON com os 6 campos do framework
3. Revise o JSON gerado para verificar consistência entre os shots
4. Use o JSON via API no pipeline da ferramenta de vídeo escolhida

Você não precisa escrever JSON manualmente. A IA faz isso por você.

## Versionamento com Git

Uma das vantagens do JSON é que ele é compatível com sistemas de versionamento como Git. Isso permite guardar o histórico de cada versão do prompt, reverter para versões anteriores e modificar apenas um parâmetro específico sem reescrever o prompt inteiro.

## Coloque em prática

Pegue um prompt de vídeo que você já usou. Peça a um LLM para convertê-lo em JSON com os 6 campos do framework. Compare o resultado gerado com o texto original e observe onde o JSON ganhou em precisão.

---

*Esta descrição cobre os principais conteúdos da aula. Alguns detalhes complementares estão disponíveis apenas no vídeo.*

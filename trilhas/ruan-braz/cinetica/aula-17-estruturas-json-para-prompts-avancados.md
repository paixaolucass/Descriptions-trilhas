Cálculo interno: [5 blocos] / [21 parágrafos totais] / [380 palavras estimadas] / [380 ÷ 200 = 2 minutos]

# Estruturas JSON para prompts avançados

**Tempo estimado de leitura:** 2 minutos

## Objetivos de aprendizado

Ao final desta aula, você será capaz de:

- Reconhecer quando e por que usar JSON como linguagem de prompt para geração de vídeo
- Distinguir os casos em que JSON supera o texto natural em precisão paramétrica
- Aplicar o fluxo correto para gerar e versionar shot breakdowns estruturados com LLMs

## O que é JSON em prompt de vídeo

JSON é uma linguagem usada para estruturar dados. Aplicada a prompts de vídeo, ela substitui o texto livre por campos explícitos: cada elemento da cena (câmera, sujeito, ação, ambiente, iluminação, estilo) ocupa um slot separado com zero ambiguidade.

JSON surgiu como linguagem de prompt de vídeo no final de 2024 e início de 2025, quando profissionais perceberam que o controle paramétrico via texto estruturado produzia resultados mais precisos em pipelines avançados.

## Quando JSON faz sentido

JSON é desnecessário para imagens. Em vídeo, é relevante quando:

- Você precisa de controle temporal por segundo (timestamp prompting): definir o que acontece de 0 a 3 segundos, aos 4 segundos, de 5 a 8 segundos
- Trabalha com equipes que precisam versionar e modificar shots de forma cirúrgica, alterando apenas a chave de iluminação sem reescrever o prompt inteiro
- Usa pipelines com APIs que aceitam parâmetros estruturados (Hilo Minimax, LTX Studio)

Em plataformas de navegador comuns, o JSON pode ser interpretado incorretamente por mecanismos de proteção contra prompt injection.

## O fluxo correto

1. Descreva o conceito em linguagem natural para um LLM (Claude, ChatGPT, Gemini)
2. Peça ao LLM para gerar o shot breakdown em JSON com os 6 campos do framework
3. Revise o JSON gerado para verificar consistência entre os shots e âncoras visuais
4. Use o JSON via API no pipeline da ferramenta de vídeo escolhida

Você não precisa escrever JSON manualmente. A IA faz isso por você. Peça ao Claude ou ao ChatGPT para converter seu prompt em JSON e valide o resultado.

## Versionamento com Git

Uma das vantagens do JSON é compatibilidade com sistemas como Git. Isso permite guardar o histórico de cada versão do prompt, reverter para versões anteriores e modificar um parâmetro específico sem reescrever o prompt inteiro — impossível com texto livre.

## QA automatizado

Agentes de IA conseguem fazer Quality Analysis do JSON gerado: identificam postura contraditória entre shots, âncoras visuais inconsistentes, temperatura de cor oscilando sem motivação e propõem correções cirúrgicas antes da geração do vídeo.

## Coloque em prática

Pegue um prompt de vídeo que você já usou. Peça a um LLM para convertê-lo em JSON com os 6 campos do framework. Compare o resultado com o texto original e observe onde o JSON ganhou em precisão.

---

*Esta descrição cobre os principais conteúdos da aula. Alguns detalhes complementares estão disponíveis apenas no vídeo.*

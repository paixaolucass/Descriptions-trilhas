[5 blocos] / [20 parágrafos totais] / [340 palavras estimadas] / [340 ÷ 200 = 1,7 minutos]

# Edição de vídeos com IA

## O que você vai aprender

Nesta aula, você aplica o fluxo de edição de vídeos gerados com IA, usa agentes para fazer QA automático de consistência e distingue quando usar text-to-video ou image-to-video para cada etapa da produção.

## QA com agentes

Antes de editar, vale rodar um QA (Quality Analysis) no prompt usado. Um agente instruído para analisar o JSON do shot pode identificar:

- Sujeito com postura contraditória entre shots
- Inconsistência de âncoras visuais (o mesmo personagem muda de características)
- Temperatura de cor oscilando entre shots sem motivação
- Transições quebradas por salto de plano sem continuidade

Com o JSON estruturado, o agente pode corrigir o prompt cirurgicamente: alterando só a chave problemática, sem reescrever tudo.

## O poder do first frame

A diferença entre text-to-video e image-to-video é clara na prática: com uma imagem de referência como primeiro frame, a IA tem uma âncora visual e produz muito mais consistência no personagem ou ambiente.

O fluxo recomendado:

1. Gere a imagem de referência com alta qualidade (Midjourney, Seedream, Gemini)
2. Use essa imagem como first frame no modelo de vídeo
3. Gere cada shot com o first frame correspondente

## Ferramentas de edição

Para montar os shots gerados:

- **CapCut Online:** rápido e gratuito para testes básicos
- **DaVinci Resolve:** referência profissional com recursos de IA nativos
- **Premiere Pro:** padrão da indústria para produções mais complexas
- **Remotion:** para quem quer criar o próprio software de edição com código

## Negative prompt na edição

Artefatos recorrentes (brilhos excessivos, movimentos mecânicos, ruído de textura) são mais fáceis de eliminar via negative prompt do que via pós-produção. Resolva na geração antes de levar para edição.

## Coloque em prática

Gere dois shots do mesmo personagem: um com text-to-video e outro com image-to-video. Monte os dois em sequência no CapCut e avalie a consistência visual da transição entre eles.

---

*Esta descrição cobre os principais conteúdos da aula. Alguns detalhes complementares estão disponíveis apenas no vídeo.*

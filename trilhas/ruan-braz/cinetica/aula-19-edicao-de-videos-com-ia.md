Cálculo interno: [5 blocos] / [20 parágrafos totais] / [360 palavras estimadas] / [360 ÷ 200 = 2 minutos]

# Edição de vídeos com IA

**Tempo estimado de leitura:** 2 minutos

## Objetivos de aprendizado

Ao final desta aula, você será capaz de:

- Aplicar o fluxo de edição de vídeos gerados com IA usando image-to-video como base
- Executar QA automatizado com agentes para identificar inconsistências antes de editar
- Distinguir quando usar text-to-video ou image-to-video para cada etapa da produção

## O poder do first frame

A diferença entre text-to-video e image-to-video é evidente na prática: com uma imagem de referência como primeiro frame, a IA tem uma âncora visual e produz muito mais consistência no personagem ou ambiente.

O fluxo recomendado:
1. Gere a imagem de referência com alta qualidade (Midjourney, Seedream, Gemini Imagen)
2. Use essa imagem como first frame no modelo de vídeo escolhido
3. Gere cada shot com o first frame correspondente para manter continuidade visual

## QA com agentes

Antes de editar, vale rodar um QA (Quality Analysis) no prompt ou no JSON do shot. Um agente instruído pode identificar:

- Sujeito com postura contraditória entre shots
- Inconsistência de âncoras visuais (o personagem muda de características entre cenas)
- Temperatura de cor oscilando entre shots sem motivação narrativa
- Transições quebradas por salto de plano sem continuidade

Com JSON estruturado, o agente corrige o prompt cirurgicamente: alterando só a chave problemática, sem reescrever tudo.

## Negative prompt na etapa de geração

Artefatos recorrentes — brilhos excessivos, movimentos mecânicos, ruído de textura — são mais fáceis de eliminar via negative prompt do que em pós-produção. Resolva na geração antes de levar para o editor.

## Ferramentas de edição

- **CapCut Online:** rápido e gratuito para testes básicos e montagem simples
- **DaVinci Resolve:** referência profissional com recursos de IA nativos para color grading e upscale
- **Adobe Premiere Pro:** padrão da indústria para produções mais complexas
- **Remotion:** para quem quer criar o próprio software de edição com código e agentes

## Coloque em prática

Gere dois shots do mesmo personagem: um com text-to-video e outro com image-to-video. Monte os dois em sequência no CapCut e avalie a consistência visual da transição entre eles.

---

*Esta descrição cobre os principais conteúdos da aula. Alguns detalhes complementares estão disponíveis apenas no vídeo.*

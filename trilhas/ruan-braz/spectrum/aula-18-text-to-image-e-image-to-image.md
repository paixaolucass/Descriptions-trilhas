Cálculo interno: 4 blocos / 14 parágrafos totais / 270 palavras estimadas / 270 ÷ 200 = 1 minuto

# Text to Image e Image to Image

**Tempo estimado de leitura:** 1 minuto

## Objetivos de aprendizado

Ao final desta aula, você será capaz de:

- Distinguir os fluxos Text to Image e Image to Image e suas características
- Aplicar cada modalidade conforme o nível de controle exigido pelo projeto
- Executar gerações híbridas combinando os dois fluxos para explorar e refinar

## Text to Image (T2I)

No fluxo T2I, o prompt de texto é o único insumo. A IA parte de ruído e constrói a imagem a partir das instruções textuais. É o fluxo mais rápido para exploração conceitual. A variação entre gerações tende a ser alta, o que favorece a descoberta de novas direções mas dificulta a consistência quando o projeto exige fidelidade a uma referência específica.

## Image to Image (I2I)

No fluxo I2I, uma imagem de referência é enviada junto ao prompt. A IA usa a estrutura, composição e elementos da imagem original como ponto de partida e modifica a partir das instruções textuais.

O grau de influência da referência é controlado por um parâmetro de força (strength ou image weight). Quanto maior o peso da imagem, mais a estrutura original é preservada. Quanto menor, mais liberdade a IA tem para reinterpretar. Imagens de referência de maior qualidade e resolução produzem resultados mais precisos.

## O fluxo híbrido na prática

A aula mostra como a Overlens usa Text to Image para explorar e Image to Image para refinar. Um modelo gerado por T2I é usado como referência para I2I na etapa seguinte, produzindo variações mais consistentes da mesma direção visual. Para figurinos, produtos e personagens, a consistência conseguida com I2I é muito superior à gerada apenas por T2I.

## Quando usar cada fluxo

Use T2I nas fases iniciais de conceituação e exploração. Use I2I quando você tem uma composição, sketch ou referência que precisa ser respeitada. Na maioria dos projetos profissionais, os dois fluxos se combinam: T2I para descobrir, I2I para fixar e refinar.

## Coloque em prática

Pegue uma referência visual de um projeto real. Use-a como base para uma geração I2I com um prompt descritivo. Compare com uma T2I do mesmo prompt sem referência. Avalie qual resultado serve melhor ao objetivo e o que cada fluxo perdeu ou ganhou.

---

*Esta descrição cobre os principais conteúdos da aula. Alguns detalhes complementares estão disponíveis apenas no vídeo.*

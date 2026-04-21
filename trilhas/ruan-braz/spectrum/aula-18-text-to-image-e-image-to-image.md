[4 blocos] / [15 parágrafos totais] / [250 palavras estimadas] / [250 ÷ 200 = 1,3 minutos]

# Text to Image e Image to Image

## O que você vai aprender

Nesta aula, você distingue os fluxos de Text to Image e Image to Image e aplica cada modalidade conforme o nível de controle exigido pelo projeto.

## Text to Image (T2I)

No fluxo T2I, o prompt de texto é o único insumo. A IA parte de ruído puro e constrói a imagem a partir das instruções textuais.

É o fluxo mais rápido para exploração conceitual. Porém, a variação entre gerações é alta, o que pode dificultar a consistência em projetos que exigem fidelidade a uma referência específica.

## Image to Image (I2I)

No fluxo I2I, uma imagem de referência é enviada junto ao prompt. A IA usa a estrutura, composição e elementos da imagem original como ponto de partida.

O grau de influência da referência é controlado por um parâmetro de força (strength ou image weight). Quanto maior o peso, mais a imagem original é preservada. Quanto menor, mais liberdade a IA tem para reinterpretar.

## Quando usar cada fluxo

T2I: quando você quer explorar possibilidades sem restrição de composição. Útil nas fases iniciais de conceituação.

I2I: quando você tem uma composição, sketch ou referência que precisa ser respeitada. Útil nas fases de refinamento e consistência.

Na maioria dos projetos profissionais, os dois fluxos se combinam: T2I para explorar, I2I para refinar e fixar.

## Coloque em prática

Pegue uma referência visual de um projeto real. Use-a como base para uma geração I2I e compare com uma T2I do mesmo prompt. Avalie qual resultado serve melhor ao objetivo do projeto.

---

*Esta descrição cobre os principais conteúdos da aula. Alguns detalhes complementares estão disponíveis apenas no vídeo.*

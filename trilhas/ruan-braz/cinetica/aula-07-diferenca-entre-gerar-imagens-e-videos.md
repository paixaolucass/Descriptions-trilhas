[5 blocos] / [20 parágrafos totais] / [340 palavras estimadas] / [340 ÷ 200 = 1,7 minutos]

# Diferença entre gerar imagens e vídeos

## O que você vai aprender

Nesta aula, você distingue as cinco dimensões que separam a geração de imagens da geração de vídeos com IA e reconhece por que o fluxo image-to-video produz resultados superiores ao text-to-video na maioria dos casos.

## As 5 dimensões exclusivas do vídeo

**1. Dimensão temporal:** um vídeo existe no tempo. A IA precisa manter coerência não só no espaço visual, mas na sequência de momentos.

**2. Optical flow:** o modelo calcula o fluxo de movimento entre quadros para garantir que objetos se desloquem de forma fisicamente plausível.

**3. Física simulada:** tecidos, líquidos, cabelos e objetos precisam se comportar de acordo com leis físicas aproximadas. Imagens não precisam disso.

**4. Consistência de frames:** cada quadro precisa ser compatível com o anterior e o próximo. Um rosto não pode mudar de estrutura entre frames.

**5. Custo computacional:** gerar 4 segundos de vídeo exige muito mais processamento do que gerar uma imagem de alta resolução.

## Por que image-to-video é superior

Quando você fornece uma imagem de referência como primeiro frame, a IA tem uma âncora visual clara: sabe como o personagem ou ambiente deve aparecer. Isso reduz alucinações visuais e aumenta a consistência.

Text-to-video funciona bem para testes rápidos, mas para resultados profissionais o fluxo correto é: gerar imagem de referência de qualidade, depois animar essa imagem.

## Duração ideal

A maioria dos modelos atuais funciona melhor entre 8 e 20 segundos. Durações maiores aumentam o custo e a chance de inconsistências acumuladas ao longo do tempo.

## Coloque em prática

Gere o mesmo conceito nos dois fluxos: uma vez com text-to-video e uma vez com image-to-video. Compare a consistência visual do personagem ou ambiente entre os dois resultados.

---

*Esta descrição cobre os principais conteúdos da aula. Alguns detalhes complementares estão disponíveis apenas no vídeo.*

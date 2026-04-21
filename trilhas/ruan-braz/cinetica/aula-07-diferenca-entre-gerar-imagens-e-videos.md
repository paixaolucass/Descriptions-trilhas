Cálculo interno: [5 blocos] / [20 parágrafos totais] / [360 palavras estimadas] / [360 ÷ 200 = 2 minutos]

# Diferença entre gerar imagens e vídeos

**Tempo estimado de leitura:** 2 minutos

## Objetivos de aprendizado

Ao final desta aula, você será capaz de:

- Distinguir as cinco dimensões que separam a geração de imagens da geração de vídeos com IA
- Reconhecer por que o fluxo image-to-video produz resultados superiores ao text-to-video na maioria dos casos
- Aplicar a lógica de referência de imagem para aumentar a consistência nos vídeos gerados

## As 5 dimensões exclusivas do vídeo

**1. Dimensão temporal:** um vídeo existe no tempo. A IA precisa manter coerência não só no espaço visual, mas na sequência de momentos. Um frame está sempre relacionado ao anterior e ao próximo.

**2. Optical flow:** o modelo calcula o fluxo de movimento entre quadros para garantir que objetos se desloquem de forma fisicamente plausível. Em imagens, esse cálculo não existe.

**3. Física simulada:** tecidos, líquidos, pele e partículas precisam se comportar de acordo com padrões físicos aprendidos. Imagens estáticas não precisam simular nada — o pixel simplesmente fica onde está.

**4. Consistência de frames:** cada quadro precisa ser compatível com o anterior e o próximo. Um rosto não pode mudar de estrutura entre frames. Em imagem, cada geração é independente.

**5. Custo computacional:** gerar 4 segundos de vídeo a 24 FPS exige processar 96 frames de forma coerente. É muito mais exigente do que gerar uma única imagem em alta resolução.

## Por que image-to-video é superior

Quando você fornece uma imagem de referência como primeiro frame, a IA tem uma âncora visual clara: sabe como o personagem ou ambiente deve aparecer. Isso reduz alucinações e aumenta a consistência ao longo do vídeo.

Text-to-video funciona bem para testes rápidos, mas para resultados profissionais o fluxo correto é: gerar imagem de referência de qualidade, depois animar essa imagem.

## Duração ideal e limitações

A maioria dos modelos atuais funciona melhor entre 8 e 20 segundos. Feature drift — quando a IA adiciona elementos não solicitados ou gera movimentos estranhos ao longo do vídeo — é mais frequente em durações maiores.

## Coloque em prática

Gere o mesmo conceito nos dois fluxos: uma vez com text-to-video e uma vez com image-to-video. Compare a consistência visual do personagem ou ambiente entre os dois resultados.

---

*Esta descrição cobre os principais conteúdos da aula. Alguns detalhes complementares estão disponíveis apenas no vídeo.*

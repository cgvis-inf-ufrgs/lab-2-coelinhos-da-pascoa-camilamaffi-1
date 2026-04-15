# Relatório - Coelinhos da Páscoa

> [!CAUTION]
> - Lembre-se que você <ins>**não pode utilizar ferramentas de IA para
>   escrever este relatório**</ins>

## Dados do aluno

- **Cartão UFRGS**: <mark>00243691</mark>
- **Nome**: <mark>Camila Maffi</mark>

## Passos que eu segui para resolver o problema especificado (em formato de *"prompt"*)

> [!IMPORTANT]
> - Coloque aqui todas as informações necessárias para que alguém
>   (pessoa ou ferramenta de IA) possa reproduzir os seus passos para
>   solucionar o problema
> - Escreva em formato imperativo, como se fosse um *prompt* com as
>   instruções a serem seguidas na solução do problema
> - Seja objetivo e conciso: quanto *menos palavras* você utilizar,
>   melhor
> - Seja técnico e use terminologia adequada: assuma que quem irá ler
>   os seus passos possui conhecimento de Ciência da Computação e
>   Computação Gráfica
> - Caso você queira incluir informações "longas" (como algum *prompt*
>   grande usado com alguma ferramenta de IA), crie arquivos à parte e
>   adicione links no texto (por exemplo, crie o arquivo `PROMPTS.md`
>   e adicione um link markdown `[os prompts detalhados estão
>   aqui](PROMPTS.md)`)
> - Novamente, lembre-se que você *não pode utilizar ferramentas
>   de IA para escrever este relatório*

- Use o main.cpp original como base.
- Mantenha igual tudo que já existia fora da cena.
- Localize o trecho que desenha a esfera, o coelho e o plano.
- Substitua só esse trecho por uma animação com 15 coelhos e 2 ovos para cada coelho.
- Distribua os coelhos ao longo de uma trajetória circular.
- Faça cada coelho se mover no plano XZ e variar a altura com uma função senoidal.
- Aplique translação, rotação e escala para posicionar e orientar cada coelho.
- Em alguns coelhos, aplique também rotação extra em Z.
- Gere os ovos a partir da esfera base com escala não uniforme.
- Faça os 2 ovos de cada coelho se moverem ao redor dele em lados opostos.
- Use a transformação do coelho como base para transformar os ovos.
- Desenhe os coelhos com DrawVirtualObject("the_bunny").
- Desenhe os ovos com DrawVirtualObject("the_sphere").
- Desenhe o chão com DrawVirtualObject("the_plane").

## Principais dificuldades encontradas durante o desenvolvimento (formato livre)

- Ordenar as transformações para que a movimentação ficasse natural e bem configurada. 
- Posicionar os ovos ao redor dos coelhos e preservar suas movimentações.

## Você acha que conseguiu resolver o problema de forma adequada?

Acredito que sim, creio que a solução gerou uma reprodução fiel ao esperado.

## Se você quiser compartilhar mais alguma coisa, coloque aqui:

<mark>`<preencher>`</mark>

## Se você possui alguma sugestão para o professor sobre esta atividade, coloque aqui:

<mark>`<preencher>`</mark>

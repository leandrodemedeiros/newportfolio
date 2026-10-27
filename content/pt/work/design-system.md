---
slug: "design-system"
title: "Mandala DS: um design system para 6 produtos, documentado com IA"
summary: "Criei e mantenho o Mandala DS, design system da Sittax, com componentes, tokens e documentação automatizada com o Claude, para que qualquer pessoa do time construa telas no mesmo padrão."
company: "Sittax"
role: "Senior UX Designer"
period: "2024 até hoje"
team: "Design, com os times dos 6 produtos"
cover: "system"
image: "img/cases/mandala-variaveis.jpg"
imageSmall: true
imageAlt: "Logotipo do Mandala DS ao lado do painel de variáveis do Figma, com coleções de primitivos, tokens e tema, e variáveis de borda e espaçamento"
imageCaption: "Variáveis do Mandala DS no Figma, organizadas em primitivos, tokens e tema."
weight: 2
metrics:
  - value: "60%"
    label: "menos tempo de desenvolvimento por produto, aproximadamente"
  - value: "6"
    label: "produtos usando o mesmo sistema"
---

## Contexto

A Sittax tem 6 produtos para escritórios de contabilidade e profissionais da área fiscal. Para manter a consistência entre eles e acelerar as entregas, o design precisava escalar além de telas desenhadas uma a uma. A solução foi um sistema que o time inteiro pudesse usar.

## O que eu fiz

- **Tokens e componentes.** Defini tokens de cor, tipografia e espaçamento e uma biblioteca de componentes reutilizáveis, com atenção especial aos padrões que mais aparecem em software fiscal: formulários, navegação e apresentação de dados em tabelas.
- **UI kit.** Montei o UI kit no Figma como fonte única de verdade para design e desenvolvimento.
- **Documentação automatizada com IA.** Usei o Claude para gerar e manter a documentação do sistema, de modo que ela acompanhe o que está em produção em vez de ficar desatualizada.

{{< shot src="img/cases/mandala-menu-temas.jpg" alt="Menu lateral do Sittax Simples nas versões clara e escura, com os mesmos itens e ícones" caption="O mesmo componente de menu nos temas claro e escuro, gerados a partir das mesmas variáveis." >}}

{{< todo >}}
As duas imagens têm só 600 px de largura e ficam um pouco borradas em telas grandes. Se puder, exporte em 2x (1600 px ou mais). Também vale explicar em 2 ou 3 frases como funciona o fluxo de documentação com o Claude: o que entra, o que sai e quem usa.
{{< /todo >}}

## Por que isso importa agora

Com IA, qualquer pessoa do time consegue gerar uma tela em segundos. Sem um sistema documentado, cada tela gerada inventa o próprio visual e o produto vira uma colcha de retalhos. Com tokens, componentes e regras escritas, a IA passa a gerar dentro do padrão, e a revisão de design se concentra no que importa: o fluxo, as exceções e a acessibilidade.

## Decisões e o que ficou de fora

{{< todo >}}
Conte uma decisão: por exemplo, o que entrou primeiro no sistema e o que ficou para depois, ou como você lidou com produtos que já existiam com visuais diferentes.
{{< /todo >}}

## Resultado

O design system é usado pelos 6 produtos da empresa e reduziu em cerca de 60% o tempo de desenvolvimento de um produto.

{{< todo >}}
Se souber, diga como esse 60% foi medido (comparação entre dois produtos, estimativa do time de desenvolvimento etc.). Uma frase basta.
{{< /todo >}}

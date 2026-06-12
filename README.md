## Portfólio Fictício

Landing page de projetos pessoais

## Cores
- Fundo: #0a0a0a (preto quase puro)
- Principal: #6c63ff (roxo moderno)
- Destaque: #ff6584 (rosa/coral)
- Texto: #f5f5f5 (branco suave)

## Fontes
- Títulos: Playfair Display
- Textos: Inter

## Layout
- Header: ocupa a tela inteira, imagem de fundo, menu superior, título e botão de contato
- Main: três sections, última com formulário
- Footer: nome, ano, parceiros e redes sociais



## Aula 9 - Responsividade com Mobile First

- Repositório: https://github.com/s-a-m-i-o/mobile-first
- Projeto: Landing page de portfólio fictício completa

- Mobile First: começar o CSS pelo mobile, adicionar media queries pra telas maiores
- No mobile elementos em coluna (flex-direction: column), no desktop em linha (flex-direction: row)
- min-width nas media queries pro Mobile First, max-width pro Desktop First
- Wireframe e README.md pra planejar o projeto antes de codar (cores, fontes, layout)
- Separar CSS em arquivos por função: reset, root, global, landinpage, responsivo, animacoes
- Reset profissional: img com max-width 100% e display block, font inherit nos inputs, list-style none
- h2 com display block e width 100% dentro do flex-wrap pra ocupar linha inteira
- min-height em vez de height fixo nos cards pra não cortar conteúdo
- Abordagem de CSS separado por função é ideal pra projetos médios
- Dois @media iguais podem ser unidos em um só bloco
- Hover nos ícones de redes sociais com filter drop-shadow colorido
- position sticky pra headers que grudam no topo, fixed pra elementos sempre visíveis
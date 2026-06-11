# Visualizador de Árvore Rubro-Negra

Visualizador interativo de árvores rubro-negras com reprodução passo a passo das comparações, recolorações e rotações. Página única em HTML/JavaScript, sem dependências externas.

## Funcionalidades

- Inserção e remoção com duas estratégias de balanceamento, selecionáveis a qualquer momento:
  - **Bottom-up (CLRS)**: corrige as violações subindo após a operação (casos pai/tio na inserção; casos 1–4 do duplo-negro na remoção);
  - **Top-down (passada única)**: corrige durante a descida (split de 4-nós na inserção; "empurra" um nó vermelho até a folha na remoção), no estilo Guibas–Sedgewick.
- Reprodução passo a passo de cada operação, descrevendo a comparação, recoloração ou rotação aplicada, com destaque dos nós envolvidos e controle de velocidade.
- Busca vértice a vértice, mostrando cada comparação até encontrar a chave (ou alcançar uma folha NIL).
- Painel com medidas (número de nós, altura, altura negra) e verificação ao vivo das propriedades rubro-negras a cada passo.
- Exibição opcional das folhas NIL; remoção por clique no nó; inserção em lote (valores separados por vírgula).

## Como usar

Acesse a versão publicada em **[https://badregi.github.io/arvore-rubro-negra/](https://badregi.github.io/arvore-rubro-negra/)** .

## Licença

MIT

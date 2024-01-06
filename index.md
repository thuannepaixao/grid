##PROPRIEDADES FUNDAMENTAIS

Todo grid é composto de 2 principais grupos:
'container: o pai' e 'itens: o(s) filhos'

---
### CONTAINER (pai)

- display: grid;
- grid-template;
  - grid-template-columns;
  - grid-template-rows;
  - grid-template-areas;
- gap;
  - row-gap;
  -column-gap;

  ---
  ### ITENS (filhos)

  - grid-column;
    - grid-column-start;
    - grid-column-end;
  - grid-row;
    - grid-row-start;
    - grid-row-end;
  - grid-area;

  ### PROPRIEDADES DE ALINHAMENTO

  Existem 9 propriedades FUNDAMENTAIS

  **6 aplicadas em container**
  `align-content`
  `justify-content`
  `place-content`

  `align-items`
  `justify-items`
  `place-items`

  **3 aplicadas em itens**
  `align-self`
  `justify-self`
  `place-self`

  Então podemos separar em 3 grupos:
  `align`, `justify`, `place`

  E cada um deles irá observar ou o
  - conteúdo do elemento `content`
  - itens do elemento `items`
  - o próprio elemento `self`
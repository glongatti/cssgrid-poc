# CSS GRID

## GRID
- Bidimensional
- Divisão de toda a página em linhas e colunas
- COlocar elementos onde quiser nessa divisão

## GRID OU FLEXBOX

- Grid: Duas dimensões (colunas e linhas)
- Flexbox: Uma dimensões (ou coluna ou linha)
- Um complementa o trabalho do outro

## PROPRIEDADES

Vamos separar em 2 grupos:
`container` e `item(s)`

## CONTAINER
  - display: grid;
  - grid-template-columns;
  - grid-template-rows;
  - grid-gap;
    - grid-row-gap;
    - grid-column-gap;
  - grid-template-areas;

... e mais 4 propriedades de **alinhamento**

## ITEM(s)
  - grid-column
    - grid-column-start
    - grid-column-end
  - grid-row
    - grid-row-start
    - grid-row-end
  - grid-area

  ... e mais 2 propriedades de **alinhamento**


# ALINHAMENTOS:

Existem 6 propriedades para alinhamento: 
1. `justify-content`
2. `align-content`
3. `justify-items`
4. `align-items`
5. `justify-self`
6. `align-self`

Separar em 2 grupos
1. `justify` e `align` 
2. `content`,`items` e `self`

## JUSTIFY E ALIGN

Sabendo que o grid é bidimensional, nós temos o eixo x e o y

O **eixo x** é o posicionamento horizontal, da esquerda para direita
O **eixo y** é o posicionamento vertical, de cima para baixo

## CONTENT, ITEMS e SELF

### CONTENT
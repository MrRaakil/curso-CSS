# CSS GRID

## GRID
-Bidimensional
-Divisão de toda a página em linhas e colunas
-Colocas elementos onde quiser nessa divisão

## FLEXBOX


## GRID OU FLEXBOX
-GRID: Duas dimensões (coluna e linha)
-FLEXBOX: Uma dimensão (ou coluna ou linha)
-Um completa o trabalho de outro
-Verificas quais navegadores ainda não aceitam Grid

## PROPIEDADES
-VAMOS SEPARAR EM DOIS GRUPOS:
'container' e 'item(s)'
# CONTAINER
- display: grid; (inicia o container dizendo que ele é um grid)
- grid-template-columns:(fatia as colunas e fala quantas colunas o grid vai ter)
- grid-template-rows: (quantas linhas esse grid vai ter)
- grid-gap (ele ai dizer a respeito do nosso espaçamento)
  - grid-row-gap
  - grid-colum-gap 
- grid-template-areas: "header header header"
    - grid-areas:      "aside main main"
                       "aside main main"
                       5"footer footer footer"; (estrutura 3 colunas x 4 linhas. Delimita as areas a serem usadas)
                     


... e mais 4 propiedades de **alinhamento**

# ITEM(S)
- grid-colum
  -grid-colum-start
  -grid-colum-end
- grid-row
  - grid-row-start
  - grid-row-end
-grid-area

... e mais 2 propiedadas de **alinhamento**

## GRID ALINHAMENTO
1. `justify-content`
2. `align-content`
3. `justify-items`
4. `align-items`
5. `justify-self`
6. `align-self`

# separar em dois grupos pra melhor entendimento
1. `justify` e  `align`
2. `content`, `items` e `self`

# `JUSTIFY E ALIGN`

- Sabendo que o grid é bidimensional, nós temos o eixo 'x' e o 'y'.
- o **eixo 'x'** é o posicionamento horizontal, da esquerda para a direita.
- o **eixo 'y'** é o posicionamento vertical, de cima para baixo
- `justify` é o posicionamento horizontal
- `align` é o posicionamento vertical

# `CONTENT E ITEMS E SELF`

### content
- `justify-content` e `align-content` nos permite alinhas o própio grid, relativo ao espaço fora do grid.

* o uso dessas propiedades são raras, pois só é aplicado caso o grid seja menos que a area definida. (por exemplo, quando usamos em px o tamanho do grid, poderemos terminar com um grid pequeno, para o tamanho da area do grid)

-Podemos usar **7 valores**
1. start /* espaço inicial*/
2. end /* final da página*/ 
3. center /* centro horizontal */
4. stretch
5. space-between /* espaço igual entre as colunas*/
6. space-around /* espaço ao redor*/
7. space-evenly /* espaço contínuo*/

### items
- `justify-items` e `align-items` vai permitir alinhas os itens em si. (dentro do container)

-Podemos usar **4 valores**
1. start
2. end
3. center
4. stretch

### self
- `justify-self` e `align-self` vai permitir alinhas os itens em si, porém aplicado diretamente no item de um grid. (mexe no container em si)

-Podemos usar **4 valores**
1. start
2. end
3. center
4. stretch

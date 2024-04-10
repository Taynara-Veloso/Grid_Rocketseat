## PROPRIEDADES FUNDAMENTAIS

Todo grid é composto de 2 principais grupos:
`container: o pai` e `itens: o(s) filhos`

o que é Grid?
    Malha, grid ou grelha, em design gráfico, é uma estrutura geométrica constituída por eixos desenvolvida para auxiliar o alinhamento de elementos textuais e imagéticos numa composição visual. É uma ferramenta de programação visual que auxilia no desenvolvimento de layouts mais bem organizados e estruturados.

    O grid tem como principal objetivo auxiliar na ordenação, distribuição, alinhamento e dimensão de imagens, textos, formas e outros elementos. Em resumo, ele organiza todas as informações dentro da estrutura de uma peça de comunicação visual, ajudando o designer a manter a harmonia visual do layout.
---

![image description](/img/gridDrawing.jpg)

---
### CONTAINER (pai)

- display: grid;
- grid-template;
    - grid-template-columns;
      
            Define o número total de colunas que serão criadas no grid.
    - grid-template-rows;
      
            Especifica o número (e as alturas) das linhas em um layout de grade.
    - grid-template-areas;
           
            Uma das formas de criar áreas em um grid. Temos também a “propriedade-atalho” grid-template. Com o grid-template conseguimos definir as áreas, o tamanho das colunas e o tamanho das linhas de uma vez só.           
- gap;
    - row-gap;

        Define o tamanho do intervalo entre as linhas de um elemento.
    - column-gap;

        Define o tamanho da lacuna entre as colunas de um elemento.
---
### ITENS (filhos)

- grid-column;
    - grid-column-start;
    - grid-column-end;
- grid-row;
    - grid-row-start;
    - grid-row-end;      
- grid-area;      
---

## PROPRIEDADES DE ALINHAMENTO

Existem 9 propriedades fundamentais 

**6 aplicadas em container**
- `align-content`
    - Descrito nas especificações como `empacotamento de linhas flexíveis`; controla o espaço entre linhas flexíveis no eixo cruzado.
- `justify-content`
- `place-content`

- `align-items` 
    - Controla o alinhamento de todos os itens no eixo cruzado.

- `justify-items`
- `place-items`

**3 aplicadas em itens**
- `align-self`
    - Controla o alinhamento de um item flexível individual no eixo cruzado.
- `justify-self`
- `place-self`

Cada um deles erá observar ou o:
- Conteúdo do elemento `content`
- Itens do elemento `items`
- O próprio elemento `self`


**Align:** 
    `trabalha com o eixo y`

**Justify:** 
    `trabalha com o eixo x`

**Place:** 
    `trabalha com o eixo y e x`

---
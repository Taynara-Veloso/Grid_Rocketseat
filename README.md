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
    
---
### ITENS (filhos)

- grid-column;
    - grid-column-start;
    - grid-column-end;
- grid-row;
    - grid-row-start;
    - grid-row-end;        

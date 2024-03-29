# Flex Container
O Flex Container é a tag que envolve os itens flex, ao indicar display: flex, essa tag passa a ser um Flex Container.

## 1 • display
Define o elemento como um flex container, tornando os seus filhos flex-itens.

```css
display: flex;
/*
Torna o elemento um flex container automaticamente transformando todos os seus filhos diretos em flex itens.
*/
```

## 2 • flex-direction
Define a direção dos flex itens. Por padrão ele é row (linha), por isso quando o display: flex; é adicionado, os elementos ficam em linha, um do lado do outro.

A mudança de row para column geralmente acontece quando estamos definindo os estilos em media queries para o mobile. Assim você garante que o conteúdo seja apresentado em coluna única.

```css
flex-direction: row;
/* 
# Os itens ficam em linha
flex-direction: row-reverse;

# Os itens ficam em linha reversa, ou seja 3, 2, 1.
flex-direction: column;

# Os itens ficam em uma única coluna, um embaixo do outro.
flex-direction: column-reverse;

# Os itens ficam em uma única coluna, um embaixo do outro, porém em ordem reversa: 3, 2 e 1.
*/
```
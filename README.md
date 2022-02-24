# Markdown syntax guide

***COMANDS FOR README***

*COMANDOS PARA ESTILIZAR O README*


## Headers

*cabecalho*

# This is a Heading h1
## This is a Heading h2 
### This is a Heading h3
#### This is a Heading h4 
##### This is a Heading h5 
###### This is a Heading h6

## Emphasis
*ENFASE AO TEXTO*

*This text will be italic*  
_This will also be italic_

**This text will be bold**  
__This will also be bold__

_You **can** combine them_

## Lists
*EXEMPLO DE LISTAS*

### Unordered
***NAO ORDENADA***
*REFERENCIANDO SUB-ITENS COM O MESMO NUMERO EX: 2a, 2b.*

* Item 1
* Item 2
* Item 2a
* Item 2b

### Ordered
***ORDENADA***
*REFERENCIANDO SUB-ITENS COM O MESMO NUMERO EX: 3a, 3b.*

1. Item 1
1. Item 2
1. Item 3
  1. Item 3a
  1. Item 3b

## Images
*A IMAGEM NAO APARECE, POIS NAO FOI ADD UM ARQUIVO*

![This is a alt text.](/image/sample.png "This is a sample image.")

## Links
*LINK DO GOOGLE SO PARA REFERENCIA*

You may be using [Google](https://www.google.com/).

## Blockquotes
*PARA CITACOES DE BLOCO USE (>), PARA BLOCO COM RECUO USE (>>) QUANTO MAIS USAR O (>) MAIOR SERA O RECUO*

> Markdown is a lightweight markup language with plain-text-formatting syntax, created in 2004 by John Gruber with Aaron Swartz.
>
>> Markdown is often used to format readme files, for writing messages in online discussion forums, and to create rich text using a plain text editor.
>>> CERTO DIA ENTREI NA LIFERAY, 

## Tables
*TABELAS*

| Left columns  | Right columns |
| ------------- |:-------------:|
| left foo      | right foo     |
| left bar      | right bar     |
| left baz      | right baz     |

## Blocks of code
*BLOCO DE CODIGO TUDO QUE ESTIVER ENTRE (...) SERA CONSIDERADO BLOCO DE CODIGO*

```
let message = 'Hello world';
alert(message);
```

## Inline code
*MARCACAO FEITA COM CRAZE (`)*

This web site is using `markedjs/marked`.

# HTML - Resumo

## O que é HTML?
HTML significa ***Hyper Text Markup Langage***. É a linguagem da **World Wide Web**. Trata-se de uma linguagem de marcação de texto padrão utlizada para criar e exibir páginas na **Web**, tornando o texto interativo e dinâmico. Essa linguagem pode transformar texto em imagens, tabelas, ***links***, etc.

```
<!-- Estrutura de um documento HMTL -->
<!DOCTYPE html>
<html>
    <head>
        <title>HTML Tutorial</title>
    </head>

<body>

    <h1>This is a heading</h1>
    <p>This is a paragraph.</p>

</body>
</html>
```

## O que são marcadores (***tags***)?
Os marcadores HTML compõem-se de três elementos: marcador inicial, conteúdo e marcador final. Alguns marcadores não possuem fechamento. Os documentos HTML contém dois elementos:

* Conteúdo
* Marcadores

Quando o navegador lê um documento HTML, o faz de cima para baixo e da esquerda para a direita. Os marcadores HTML são usados para criar documentos HTML e reproduzir suas propriedades. Cada marcador HTML tem propriedades distintas.

### Sintaxe

```
<marcador>conteúdo</marcador>
```

O conteúdo localiza-se entre os marcadores para exibir dados na página **web**.

## Todos os marcadores HMTL têm um fechamento?
Não. Há alguns marcadores HTML que são vazios. Exemplo: `img`, `br`, `hr`.

## O que é a formatação no HTML?
A formatação no HTML é um processo no qual o texto sofre modificações para obter uma aparência melhor. Utiliza marcadores diferentes para deixar o texto em negrito, itálico, sublinhado, etc.

## Quantos tamanhos de título existem no HTML?
Existem no HTML seis tamanhos diferentes de títulos definidos de `h1` (maior) a `h6` (menor).

### Exemplo

```
<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
<h6>Heading 6</h6>
```

## Como criar um hipertexto (***hyperlink***) no HTML?
O HTML fornece um marcador âncora para criar um hipertexto que vincula uma página a outra.

### Exemplo

```
<a href="url">link text</a>
```

Esses marcadores podem aparecer nas formas a seguir:

* ***Link*** **não visitado**: aparece sublinhado e com a cor azul.
* ***Link*** **visitado**: aparece sublinhado e com a cor púrpura.
* ***Link*** **ativo**: aparece sublinhado e com a cor vermelha.

## Qual marcador HTML é utilizado para exibir dados em forma de tabela?
O marcador `table` é utilizado para exibir dados em forma de tabela (linha * coluna). Esse marcador também controla o visual da página, por exemplo: cabeçalho, navegação, conteúdo, rodapé. Aqui está uma lista de marcadores utilizados que exibem os dados em forma de tabela.

* `table`: define uma tabela.
* `tr`: define uma linha em uma tabela.
* `th`: define uma célula de cabeçalho em uma tabela.
* `td`: define uma célula em uma tabela.
* `caption`: define uma legenda.
* `colgroup`: especifica um grupo de uma ou mais colunas em uma tabela para fins de formatação.
* `col`: utilizado com o marcador `colgroup` para especificar propriedades para cada coluna.
* `tbody`: usado para agrupar o conteúdo do corpo de uma tabela.
* `thead`: usado para agrupar o conteúdo do cabeçalho de uma tabela.
* `tfooter`: usado para agrupar o conteúdo do rodapé de uma tabela.

## Escreva uma tabela em HTML com os seguintes dados:
#### 50 pcs 100 500
#### 10 pcs 5 50

```
<table>
    <tr>
        <td>50 pcs</td>
        <td>100</td>
        <td>500</td>
    </tr>
    <tr>
        <td>10 pcs</td>
        <td>5</td>
        <td>50</td>
    </tr>
</table>
```

## Quais são os tipos de lista usados ao desenhar uma página?
Existem alguns tipos de lista usados para desenhar uma página. Você pode escolher qualquer tipo de lista a seguir:

* ***Lista ordenada***: exibe elementos em formato numerado. É representada pelo marcador `ol`.

```
<ol>
    <li>Item 1</li>
    <li>Item 2</li>
    <li>Item 3</li>
</ol>
```

* ***Lista não ordenada***: exibe elementos em formato de ponto. É representada pelo marcador `ul`.

```
<ul>
    <li>Item 1</li>
    <li>Item 2</li>
    <li>Item 3</li>
</ul>
```

* ***Lista de definição***: exibe elementos como se fosse um dicionário. Os marcadores `dl`, `dt` e `dd` são usados para configurar a lista de definição.

```
<dl>
    <dt>Item</dt>
    <dd>Definition</dd>
    <dt>Item</dt>
    <dd>Definition</dd>
</dl>
```

## Qual é a diferença entre elementos e marcadores no HMTL?
Elementos HTML comunicam-se com o navegador para reproduzir texto. Quando um elemento está contido entre colchetes angulares `<>`, forma um marcador HTML. Na maioria das vezes, os marcadores vêm em pares e rodeiam o conteúdo.

## O que é o HTML semântico?
HTML semântico é um estilo de código. É a utilização de marcação HTML para reforçar a semântica ou o significado do conteúdo. Exemplo: no HTML semântico o marcador `b` não é utilizado para textos em negrito, nem o marcador `i` é utilizado para textos em itálico. Em vez desses marcadores, utilizamos `strong` e `em`.

## O que é um mapa de imagem?
O mapa de imagem facilita o vínculo a várias páginas diferentes com o uso de uma única imagem. É representado pelo marcado `map`. Você pode definir formas em imagens que você quer que façam parte do mapa.

```
<map name="planetmap">
  <area shape="rect" coords="0,0,82,126" href="sun.htm" alt="Sun">
  <area shape="circle" coords="90,58,3" href="mercur.htm" alt="Mercury">
  <area shape="circle" coords="124,58,8" href="venus.htm" alt="Venus">
</map>
```

## Como inserir um símbolo de *copyright* em uma página HTML?
Você pode inserir um símbolo de *copyright* usando `&copy;` ou `&#169;` em um arquivo HTML.

## Qual é o propósito do atributo *alt* em imagens?
O atributo `alt` fornece informações alternativas com relação à imagem, quando um usuário não consegue vê-la. Esse atributo deve ser utilizado para descrever qualquer imagem, com exceção das imagens que servem somente para fins de decoração.

```
<img src="img.jpg" alt="montanha">
```

## Explique o uso do marcador *meta* no HTML
O marcador `meta` descreve metadados dentro de um documento HTML. Estes metadados não aparecerão na página, porém serão analisados pela máquina. Este marcador especifica a descrição da página, palavras-chave (***keywords***), autor do documento, última modificação e outros metadados.

```
<head>
  <meta charset="UTF-8">
  <meta name="description" content="Free Web tutorials">
  <meta name="keywords" content="HTML,CSS,XML,JavaScript">
  <meta name="author" content="John Doe">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
```

## Para que serve o marcador *iframe*?
O marcador `iframe` serve para exibir uma página dentro de outra página.

```
<iframe src="https://www.google.com"></iframe>
```

## Descreva alguns dos objetivos e motivações principais da especificação HTML5
O HTML5 foi criado para substituir HTML4, XHTML e HTML DOM Nível 2. Os objetivos e motivações principais por trás da especificação HTML5 eram:

* Entrega de um rico conteúdo (gráficos, vídeos, etc.) sem a necessidade de *plugins* adicionais como o Flash.
* Fornecimento de um suporte semântico melhor para a página *web* por meio de marcadores de elementos estruturais.
* Fornecimento de um padrão de análise (***parse***) mais preciso de modo a simplificar o manuseio de erros, além de garantir um comportamento entre navegadores mais consistente e simplificar a compatibilidade com documentos escritos em outros padrões.
* Fornecimento de um melhor suporte entre plataformas, quer a pessoa utilize um PC, um *tablet* ou um *smartphone*.

## Como posso conseguir uma colocação melhor nas páginas de busca?
É possível obter melhores colocações ao incluir as seguintes declarações no `head` do documento:

```
<meta name="keywords" content="keyword keyword keyword keyword">
<meta name="description" content="description of your site">
```

Ambas declarações podem conter até 1022 caracteres. Se uma palavra-chave for utilizada mais de 7 vezes, o marcador de palavras-chave será totalmente ignorado. Além disso, você também não pode incluir marcação (além de entidades) na descrição ou lista de palavras-chave.

## Qual é a diferença entre *span* e *div*?

* `div` é um elemento em bloco (***block element***).
* `span` é um elemento em linha (***inline element***).
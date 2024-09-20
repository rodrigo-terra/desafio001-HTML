Desafio de Projeto: Estrutura Básica em HTML

Este repositório contém o código de um website simples, criado como parte de um desafio de projeto para praticar as tags básicas e sugeridas do HTML. A ideia principal é utilizar uma estrutura básica, aplicando as tags aprendidas nas aulas e buscando entender novas tags sugeridas. Este documento README fornece uma explicação detalhada sobre cada tag utilizada no projeto, com exemplos e uma visão mais aprofundada de seu uso.

Tags Utilizadas:

1. Cabeçalhos: <h1> a <h6>
Os cabeçalhos são utilizados para organizar o conteúdo em uma página, definindo a hierarquia de títulos e subtítulos. Eles vão de <h1> (o mais importante) a <h6> (o menos importante).

Exemplo de uso:
<h1>Título Principal</h1>
<h2>Subtítulo</h2>
<h3>Subseção</h3>

2. Parágrafos: <p>
A tag <p> é usada para definir um parágrafo de texto. É uma das tags mais utilizadas em qualquer conteúdo de texto na web.

Exemplo de uso:
<p>Este é um parágrafo de texto.</p>

3. Destaque: <mark>
A tag <mark> destaca o texto dentro de um parágrafo como se fosse marcado com um marca-texto.

Exemplo de uso:
<p>Este texto está <mark>destacado</mark>.</p>

4. Texto em Tamanho Reduzido: <small>
A tag <small> é usada para reduzir o tamanho do texto, normalmente para indicar rodapés ou textos secundários.

Exemplo de uso:
<p><small>Texto em tamanho reduzido.</small></p>

5. Negrito e Itálico: <strong>, <i>, <u>
- <strong>: Usado para dar ênfase a um texto importante, geralmente exibido em negrito.
- <i>: Exibe o texto em itálico.
- <u>: Sublinha o texto.

Exemplo de uso:
<p><strong>Texto importante.</strong></p>
<p><i>Texto em itálico.</i></p>
<p><u>Texto sublinhado.</u></p>

6. Listas Ordenadas e Não Ordenadas: <ol>, <ul>, <li>
As listas são usadas para organizar itens:
- <ol>: Cria uma lista ordenada (numerada).
- <ul>: Cria uma lista não ordenada (com marcadores).
- <li>: Define os itens dentro das listas.

Exemplo de uso:
<ol>
    <li>Primeiro item</li>
    <li>Segundo item</li>
</ol>
<ul>
    <li>Item com marcador</li>
    <li>Outro item com marcador</li>
</ul>

7. Links: <a>
A tag <a> cria um link para outras páginas ou sites. O atributo href especifica o URL de destino. O atributo target="_blank" abre o link em uma nova aba.

Exemplo de uso:
<a href="https://www.example.com" target="_blank">Visite o site</a>

8. Linha Horizontal: <hr>
A tag <hr> cria uma linha horizontal que separa seções do conteúdo.

Exemplo de uso:
<hr>

9. Subscrito e Sobrescrito: <sub>, <sup>
- <sub>: Coloca o texto como subscrito, útil para fórmulas químicas, por exemplo.
- <sup>: Coloca o texto como sobrescrito, útil para potências.

Exemplo de uso:
<p>H<sub>2</sub>O é água.</p>
<p>10<sup>2</sup> é 100.</p>

10. Citação em Bloco: <blockquote>
A tag <blockquote> é usada para exibir uma citação em bloco, geralmente com formatação especial para destacar uma fala.

Exemplo de uso:
<blockquote>
    "A melhor maneira de prever o futuro é criá-lo." - Peter Drucker
</blockquote>

Tags Sugeridas:

1. Abreviação: <abbr>
A tag <abbr> define uma abreviação, e ao passar o mouse sobre o texto, o título completo aparece.

Exemplo de uso:
<p><abbr title="HyperText Markup Language">HTML</abbr> é uma linguagem de marcação.</p>

2. Texto Riscado: <del>
A tag <del> risca o texto, indicando que ele foi removido ou substituído.

Exemplo de uso:
<p>Este texto foi <del>deletado</del>.</p>

3. Fonte e Cor: <font> (Obsoleto)
Embora a tag <font> esteja obsoleta e o uso de CSS seja recomendado, ela foi usada neste projeto para fins educativos, permitindo definir a fonte e a cor do texto.

Exemplo de uso:
<p><font face="Arial" color="blue">Texto em azul com a fonte Arial.</font></p>

Atributos Globais
Tags como <a>, <p>, e <strong> podem usar atributos globais, como class, id, e style, para aplicar estilos personalizados, conectar com CSS ou fazer referência ao JavaScript.

Exemplo de uso:
<p id="paragrafo1" class="texto-destaque">Parágrafo com ID e Classe.</p>

Estrutura Geral
O objetivo deste desafio é demonstrar o uso adequado dessas tags e criar uma estrutura semântica simples, mas eficaz, para uma página HTML. Cada tag foi explicada e demonstrada para proporcionar uma compreensão prática do HTML básico e como ele pode ser aplicado para organizar conteúdo na web.

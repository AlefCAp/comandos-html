<h1>• Anatomia de um elemento HTML</h1>

O elemento é a tag de abertura, seguida pelo conteúdo, seguida pela tag de fechamento.

Exemplo: ``<p>Meu gato é muito rabugento</p>``

<h1>• Elementos de Aninhamento</h1>

Aninhamento é quando podemos colocar elementos dentro de outros elementos.

Obs: um elemento aberto dentro de outro elemento deve ser fechado antes do elemento principal

Exemplo: ``<p>Meu gato é <strong>muito</strong> rabugento</p>``✔        
         ``<p>Meu gato é <strong>muito rabugento</p></strong>``✖

<h1>• Elementos Vazios</h1>

Elementos vazios não precisam de tag de abertura e fechamento, eles consistem em uma unica tag. Geralmente utilizada para inserir/embutir algo no documento.

Obs: Não há necessidade de adicionar um ``/`` no final da tag de um elemento vázio, no entanto também é uma sintaxe válida.

Exemplo: ``<img src=https://github-readme-stats.vercel.app/api?username=AlefCAp&show_icons=true&theme=dark/>``

<h3>- O que são atributos de um elemento vázio?</h3>
Um atributo contêm informações extras sobre o elemento que não aparecerão no conteúdo.

Um atributo deve ter:

• Um espaço entre ele e o nome do elemento. (Para um elemento com mais de um atributo, os atributos também devem ser separados por espaços.)
<br>
• O nome do atributo, seguido por um sinal de igual.
• Um valor de atributo, entre aspas de abertura e fechamento.

<h3>- Atributos:</h3>

Especificar o endereço da web para o link:
<br>
``href="link da página"``

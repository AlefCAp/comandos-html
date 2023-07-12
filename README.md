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

Exemplo: ``<img src="Endereço da imagem"/>``

<h3>- O que são atributos de um elemento vázio?</h3>
Um atributo contêm informações extras sobre o elemento que não aparecerão no conteúdo.

Um atributo deve ter:

• Um espaço entre ele e o nome do elemento. (Para um elemento com mais de um atributo, os atributos também devem ser separados por espaços.)
<br>
• O nome do atributo, seguido por um sinal de igual.
• Um valor de atributo, entre aspas de abertura e fechamento.

<h1>• Anatomia de um documento HTML</h1>

<img src="https://static.platzi.com/media/articlases/Images/frontend_developer09.png">

``<!DOCTYPE html>``
<br>
Tag utilizada para que tudo funcione corretamente.

``<html></html>``
<br>
Envolve o conteudo da pagina inteira.

``<head></head>``
<br>
Lugar onde é colocado todo conteudo não visível para os visitantes do site. Exemplo: titulo da pagina, descrição, etc.

``<meta charset="utf-8">``
<br>
Tag utilizada para comunicar aos navegadores qual o formato de codificação de caracteres utilizado naquele documento.

``<title></title>``
<br>
Define o título da página que aparecerá na guia do navegador.

``<body></body>``
<br>
Lugar onde é colocado todo o conteudo você quer mostrar aos usuários.




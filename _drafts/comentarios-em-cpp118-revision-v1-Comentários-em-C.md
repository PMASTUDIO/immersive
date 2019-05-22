---
id: 127
title: Comentários em C++
date: 2019-03-08T19:11:35-03:00
author: PGANME
excerpt: O que são comentários? Como usar-los? Como não usar-los? Crie comentários de múltiplas e únicas linhas em C++.
layout: revision
guid: http://imersive.tech/118-revision-v1/
permalink: /118-revision-v1/
---
### Introdução

Para quem não sabe comentários em uma linguagem de programação é uma maneira de deixar uma nota no código explicando o que ele está fazendo, qual a sua lógica, como ele deve se comportar, etc&#8230;<figure class="wp-block-pullquote">

> Se você escrever um código bom ele será auto explicativo e menos comentários serão necessários
> 
> <cite>DICA</cite></figure> 

### Sintaxe

Lembrando que sintaxe é basicamente a forma de executar certa tarefa em uma linguagem.

Existem dois tipos de comentários em C++, os comentários de uma linha e os de múltiplas linhas.

#### Single Line

Um comentario single line ou em português &#8220;única linha&#8221; é criado da seguinte maneira: 

Em qualquer linha de código em qualquer lugar do programa escreva duas barras &#8220;//&#8221; e o que estiver escrito depois das duas linhas será ignorado pela linguagem.

Por exemplo:

<pre class="brush: cpp; title: ; notranslate" title="">std::cout &lt;&lt; "Hello Comment" &lt;&lt; std::endl; //Este é um comentário
</pre>

Vale lembrar que os comentários não precisam estar no final de um comando, eles podem estar em qualquer lugar do programa desde que não bloqueie nenhum código, veja os exemplos:

Correto ✔

<pre class="brush: cpp; title: ; notranslate" title="">//Isto está absolutamente correto nada está sendo bloqueado
std::cout &lt;&lt; "Hello Comment" &lt;&lt; std::endl;
</pre>

Correto ✔

<pre class="brush: cpp; title: ; notranslate" title="">std::cout &lt;&lt; "Hello Comment" &lt;&lt; std::endl; //Nada está sendo bloqueado
</pre>

Incorreto ❌

<pre class="brush: cpp; title: ; notranslate" title="">std::cout &lt;&lt; //O código a seguir não vai ser executado: "Hello Comment"
</pre>

#### Multiple Lines

Um comentário Multiple Lines ou &#8220;Várias Linhas&#8221; em portugûes, segue as mesmas regras do comentário de uma linha:

Ele pode se localizar em qualquer lugar desde que não bloqueie nem uma parte da aplicação

Para criar-lo basta escrever barra e asterisco para começar o comentário &#8221; /\* &#8221; e asterisco barra para terminar-lo &#8221; \*/ &#8220;, vejá o exemplo a seguir:

<pre class="brush: cpp; title: ; notranslate" title="">std::cout &lt;&lt; "Hello Comment" &lt;&lt; std::endl;
/* Este é um comentário
de
várias
linhas 
nada vai ser executado
até que o comentário 
se feche */ 
</pre>

## Conclusão

Um comentário serve para explicar a lógica de uma parte de um código.

Não use comentários demais, se o seu código for bem escrito ele se auto explicará.

Para criar um comentário de uma linha basta usar duas barras &#8220;//&#8221;

Para criar um comentário de duas linhas basta usar barra asterisco para iniciar um comentário &#8220;/\*&#8221; e asterisco barra &#8220;\*/&#8221; para terminá-lo

Não coloque deixe um comentário bloquear o seu código
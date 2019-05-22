---
id: 148
title: O seu primeiro programa em C++
date: 2019-03-11T19:23:56-03:00
author: PGANME
excerpt: Crie seu primeiro programa em C++
layout: revision
guid: http://imersive.tech/139-revision-v1/
permalink: /139-revision-v1/
---
### Introdução

Vamos criar o famoso programa &#8220;Hello World&#8221; (Olá Mundo) em C++ <figure class="wp-block-image">

<img src="http://imersive.tech/wp-content/uploads/2019/03/HelloWorld_Maktivism_ComputerProgramming_LEDs-1024x914.jpg" alt="" class="wp-image-141" /> <figcaption>[Wikipedia](https://en.wikipedia.org/wiki/%22Hello,_World!%22_program#/media/File:HelloWorld_Maktivism_ComputerProgramming_LEDs.jpg)  
A &#8220;Hello, World!&#8221; message being displayed through long-exposure [light painting](https://en.wikipedia.org/wiki/Light_painting) with a moving strip of LED lights  
</figcaption></figure> 

### O programa

Veja agora o programa &#8220;Hello World&#8221; em C++, não se preocupe em entende-lo ainda:

<pre class="brush: cpp; auto-links: false; gutter: false; title: ; notranslate" title="">#include &lt;iostream&gt;

int main(){
  std::cout &lt;&lt; "Hello World!" &lt;&lt; std::endl;
  return 0;
}
</pre>

Agora tente recriar este programa simples na sua própria IDE o resultado deve ser:

<pre class="brush: plain; gutter: false; title: ; notranslate" title="">Hello World!
</pre>

Exemplo no Visual Studio 2019:<figure class="wp-block-video aligncenter"><video controls muted preload="auto" src="http://imersive.tech/wp-content/uploads/2019/03/2019-03-11-18-43-54.mp4"></video></figure> 

Repare que para executar o programa foi necessário abrir o comand prompt (cmd) para ver a mensagem, já vamos ver o porque.

### Entendendo cada linha

<pre class="brush: cpp; gutter: false; title: ; notranslate" title="">#include &lt;iostream&gt;
</pre>

Nesta primeira linha é possível perceber o hashtag &#8216;#&#8217; antes do include, [como você deve saber](http://imersive.tech/cpp-a-linguagem/#pre-processor) isso significa que está sendo enviada uma instrução para o pré-processador

O comando include em si significa que o compilador deve incluir o conteúdo do arquivo &#8220;iostream&#8221; neste local.

Precisamos deste arquivo pois ele contem os comandos que nos permitem escrever mensagens &#8220;no programa&#8221;, este é um arquivo da [bibliotéca-padrão](http://imersive.tech/cpp-a-linguagem/#std-library) do C++.

<pre class="brush: cpp; title: ; notranslate" title="">int main(){
</pre>

Aqui nós estamos declarando o ponto de entrada do programa, ou seja a primeira coisa que ele vai fazer ao ser executado.

Perceba o uso do tipo &#8220;int&#8221; isso é melhor detalhado na [aula sobre variáveis](http://imersive.tech/variaveis-em-c/) e depois na aula sobre funções, mas neste caso significa basicamente que a função &#8220;main&#8221; está esperando um numero inteiro para ser retornado.

A função main é declarada pelo nome main + parenteses &#8220;()&#8221;

E a chave &#8220;{&#8221; significa o começo desta função

Não se preocupe com essas coisas ainda. 

<pre class="brush: cpp; title: ; notranslate" title="">std::cout &lt;&lt; "Hello World!" &lt;&lt; std::endl;
</pre>

Para começar perceba o uso do prefixo &#8220;std::&#8221;, isso significa basicamente que os &#8220;comandos&#8221; &#8220;cout&#8221; e &#8220;endl&#8221; pertencem a biblioteca padrão (std standard library).

O comando &#8220;cout&#8221; recebe dados através do operador &#8220;<<&#8220;. Ele vai recolher estes dados e mostrá-los em forma de texto na tela.

Perceba que à dois &#8220;comandos&#8221; sendo passados para &#8220;cout&#8221;: O texto &#8220;Hello World!&#8221; (Todo texto tem que estar entre parenteses, [veja esta aula](http://imersive.tech/variaveis-em-c/)) e o comando &#8220;endl&#8221; que significa termine a linha.

<pre class="brush: cpp; gutter: false; title: ; notranslate" title="">return 0;
}
</pre>

Agora sim vamos retornar um numero inteiro para a função main, no caso 0 que significa que tudo ocorreu bem.

Depois fechamos a chave &#8220;}&#8221; que havíamos aberto no começo da função, indicando assim o fim desta função

### Conclusão

A sintaxe do C++, pode parecer um pouco confusa, mas tudo isso vai ser esclarecido nas futuras aulas.
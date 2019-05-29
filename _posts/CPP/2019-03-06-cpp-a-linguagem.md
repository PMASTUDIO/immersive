---
id: 81
title: C++ A Linguagem
date: 2019-03-06T17:01:52-03:00
author: PGANME
excerpt: Uma introdução a linguagem C++, Suas principais características, sua História, como ela funciona, e mais...
layout: post
guid: http://imersive.tech/?p=81
permalink: /cpp-a-linguagem/
slide_template:
  - ""
categories:
  - CPP
  - Programação para Iniciantes
tags:
  - c++
  - cpp
---
### Introdução a C++

C++ é uma linguagem de programação **[compilada](http://imersive.tech/linguagens-de-programacao/#interpreted-compiled)** e [**multi-paradigma**](https://pt.wikipedia.org/wiki/Paradigma_de_programa%C3%A7%C3%A3o), é uma linguagem popular desde os anos 1990, atualmente é usada principalmente para computação gráfica.

<div class="wp-block-image">
  <figure class="aligncenter is-resized"><img src="http://imersive.tech/wp-content/uploads/2019/03/c-plus-plus.png" alt="" class="wp-image-83" width="211" height="211" /></figure>
</div>

### Suas características

#### A linguagem

  * É uma [**linguagem tipada**](https://pt.wikipedia.org/wiki/Linguagem_tipada)
  * Suporta múltiplos [**paradigmas**](https://pt.wikipedia.org/wiki/Paradigma_de_programa%C3%A7%C3%A3o)
  * Existem várias formas de fazer uma mesma coisa
  * É extremamente compartível com a linguagem C
  * É uma linguagem multi plataforma
  * Não é necessário um ambiente de desenvolvimento sofisticado para usá-la

#### Biblioteca padrão {#std-library}

A linguagem contem uma grande biblioteca de utilidades chamada de standard library ou biblioteca padrão que facilita a programação. Você pode pensar nela como o sinto de utilidades do Batman, a linguagem já faz muito sozinha mas pode fazer mais ainda com a biblioteca padrão.

A biblioteca padrão desta linguagem é baseada na biblioteca padrão do C com novas adições.

### História

A linguagem foi criada por **Bjarne Stroustrup** dos Bell Labs durante a década de 1980. Seu objetivo era implementar uma versão distribuída do [núcleo](https://pt.wikipedia.org/wiki/N%C3%BAcleo_(inform%C3%A1tica)) **[Unix](https://pt.wikipedia.org/wiki/Unix)**. 

Como Unix era escrito em C, era necessário manter a compartibilidade, mas adicionando novos recursos.

Bjarne percebeu que a linguagem [Simula 67](https://pt.wikipedia.org/wiki/Simula_67) tinha características muito úteis para o desenvolvimento de software, mas era lento na prática. Já a linguagem [BCPL](https://pt.wikipedia.org/wiki/BCPL) era rápida mas possuía demassiado [**baixo nível**](http://imersive.tech/linguagens-de-programacao/#high-low-level).

Então a partir da sua experiencia de doutorado, começou a acrescentar elementos do Simula 67 no C, principalmente recursos relacionados a [**objetos**](https://pt.wikipedia.org/wiki/Objeto_(ci%C3%AAncia_da_computa%C3%A7%C3%A3o)), assim começou o desenvolvimento da nova linguagem C com classes.

Ainda em 1983 o nome da linguagem foi alterado de C com classes para C++. 

A linguagem sofreu várias melhorias ao longo do tempo assim como a sua biblioteca padrão que passou a ser chamada de STL para abreviar.

<div class="wp-block-image">
  <figure class="aligncenter"><img src="http://imersive.tech/wp-content/uploads/2019/03/portrait.jpg" alt="" class="wp-image-87" /><figcaption>Bjarne Stroustrup &#8211; https://usesthis.com/interviews/bjarne.stroustrup/ </figcaption></figure>
</div>

### Como ela funciona

A linguagem utiliza um **compilador** que compila cada arquivo de código principal (extensão: .cpp) para um arquivo de objeto.

Os objetos resultantes do processo de compilação são &#8220;lincados&#8221; pelo **linker** em um executável (.exe), uma [biblioteca compartilhada](https://pt.wikipedia.org/wiki/DLL) (.dll) ou uma [biblioteca estática](https://pt.wikipedia.org/wiki/Biblioteca_est%C3%A1tica) (.lib)

Um arquivo de código principal ou &#8220;**source file**&#8221; pode conter outros arquivos chamados de arquivos de cabeçalho ou &#8220;**header files**&#8221; que usam a extensão .h, .hpp ou .hxx.

#### Pré processador {#pre-processor}

Na verdade antes do compilador compilar algum arquivo principal ele executa o pré processador ou &#8220;**preprocessor**&#8221; nele.

O pré processador é responsável por substituir pedaços de código específicos, como por exemplo [macros](https://pt.wikipedia.org/wiki/Macro) ou includes.

Geralmente estes trechos de código que são destinados ao pré processador começam com &#8220;#&#8221;, por exemplo:

<pre class="brush: cpp; title: ; notranslate" title="">#include &lt;iostream&gt;
</pre>

### Compiladores e [IDE](https://pt.wikipedia.org/wiki/Ambiente_de_desenvolvimento_integrado) mais conhecidos [table id=2 /] 

Tabela retirada da [Wikipédia](https://pt.wikipedia.org/wiki/C%2B%2B#cite_note-entrevista_A-Z-4) no dia da postagem.

### Conclusão

C++ é uma linguagem multi paradigma, compilada e fortemente tipada.

É uma linguagem extremamente usada e muito poderosa.

Tem muitas características do C.

Seu processo de compilação consiste em:

  * Pré processar os arquivos principais
  * Compilar os arquivos gerando objetos
  * Lincar os objetos
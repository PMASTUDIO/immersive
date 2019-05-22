---
id: 106
title: Variáveis em C++
date: 2019-03-07T21:20:32-03:00
author: PGANME
excerpt: 'O que são variáveis? Tipos? Como eu as uso em C++?  Tamanhos e mais...'
layout: post
guid: http://imersive.tech/?p=106
permalink: /variaveis-em-c/
slide_template:
  - ""
categories:
  - C++
---
### Introdução

Você talvez já saiba o que é uma variável, mas explicando brevemente: **váriaveis são um objeto armazenado na memória do computador capaz de reter um valor ou expressão**.

Por exemplo digamos que no seu programa você quer que o usuario escreva um numero qualquer que vai ser multiplicado por 10, neste caso você precisa guardar este numero em algum lugar para executar a multiplicação.

Para fazer isso você precisa guardar este número na memória e ter alguma forma de se referenciar a ele depois dando um nome ao numero.

Para isso você pode usar uma variável, veja o exemplo em uma linguagem qualquer:

<pre class="brush: python; title: ; notranslate" title="">numeroParaSerMultiplicado = inputDoUsuário()
numeroParaSerMultiplicado * 10
</pre>

Qual é a variável neste caso? &#8220;numeroParaSerMultiplicado&#8221; e qual o valor inicial desta váriavel? O input do usuário (O que ele escreveu), e o valor final? &#8220;numeroParaSerMultiplicado&#8221; * 10. 

Simples não? Se você não entendeu completamente [clique aqui](https://www.devmedia.com.br/programacao-o-que-e-uma-variavel/38475) e veja o vídeo explicando as variáveis.

### Tipos de Variáveis

A linguagem C++ é uma linguagem fortemente tipada, isto significa que não é possível declarar uma variável simplesmente assim, como no exemplo acima:

<pre class="brush: python; gutter: false; title: ; notranslate" title="">minhaVariavel = 2
</pre>

Alem de dar um nome e um valor para uma variável é necessário escrever o seu tipo.

Vamos ver os principais tipos de variáveis:

  * Inteira (int) &#8211; Este tipo só suporta números inteiros negativos ou positivos. _Ex: 34_
  * Flutuante (float) &#8211; Este tipo suporta números inteiros e números quebrados negativos e positivos. _Ex: 3.14_
  * Booleana (bool) &#8211; Este tipo só suporta dois valores: Verdadeiro ou Falso, (True or False). _Ex: true_
  * String (string) &#8211; Este tipo só suporta &#8220;texto&#8221; e os textos tem que estar entre aspas duplas &#8220;&#8221;. _Ex: &#8220;Este é um texto 678, apesar dos números&#8221;_

Cada um destes tipos consegue armazenar uma certa quantidade de bytes, por exemplo em C++ o tipo **int** reserva **4 bytes**, para um numero com mais casas é necessário usar outro tipo.

_Haverá uma lista de tipos e tamanhos no final do artigo, não se preocupe em memorizar nada. Só memorize os 4 principais tipos._

Isso pode ser um pouco confuso mais você vai entender melhor na próxima sessão qual o papel dos tipos em C++.

### A Sintaxe básica das variáveis em C++

Primeiro de tudo, vale lembrar que sintaxe é a forma que é feita certa tarefa em certa linguagem.

A **Sintaxe** das variáveis em C++ é: o tipo, o nome e ponto e virgula (; para sinalizar que você acabou o comando) . Por exemplo:

<pre class="brush: cpp; title: ; notranslate" title="">int numeroDigitado;
</pre>

Perceba que eu declarei o tipo, no caso inteiro (int) e um nome para referenciar a variável. Perceba que eu não dei nenhum valor para ela pois isso não é necessário. 

Neste estágio eu estou reservando 4 bytes de memória no nome de &#8220;numeroDigitado&#8221;.

Agora para dar valor a uma variável basta escrever o nome, o sinal de igual e o valor correspondente ao tipo, lembrando que os valores de váriaveis podem mudar, por exemplo:

<pre class="brush: cpp; title: ; notranslate" title="">numeroDigitado = 0;
numeroDigitado = inputDoUsuario();
numeroDigitado = numeroDigitado * 10;
</pre>

Para declara e definir uma variável ao mesmo tempo basta usar a sintaxe de declaração de uma variável + a sintaxe de definição, por exemplo:

<pre class="brush: cpp; title: ; notranslate" title="">int numeroDigitado = 0;
</pre>

Também é possível criar várias variáveis do mesmo tipo ao mesmo tempo, por exemplo:

<pre class="brush: cpp; title: ; notranslate" title="">float a, b, c, d;
a = 3.14;
b = 4.5;
c = -3.8;
d = 9;
</pre>

### Tipos de variáveis e tamanhos em C++

Aqui está uma tabela de tipos de variáveis e os seus tamanhos, perceba que não existe o tipo string, porque na verdade este tipo é um tipo complexo e para usá-lo em C++ é necessário usar a [**biblioteca padrão**](http://imersive.tech/cpp-a-linguagem/#std-library). [table id=3 /] 

### Signed ou Unsigned

Em C++ uma variável também **pode** ser **unsigned**.

Até agora só vimos variáveis **signed**, isso significa que só vimos variáveis que podem ser negativas e positivas.

Mas também podem haver variáveis **unsigned** que só podem ter valores positivos, isso é útil alem do fato de proibir um valor de ser negativo pois você consegue obter um numero maior.

Vamos ver como podemos declarar variáveis **unsigned**:

<pre class="brush: cpp; title: ; notranslate" title="">unsigned int a, b, c, d;
</pre>

### Conclusão

Uma variável é um objeto armazenado na memória capaz de reter um valor ou uma expressão.

Existem quatro tipos principais de variáveis: Int (Numeros inteiros), Bool (Verdadeiro e Falso), Float (Numeros Quebrados) e String (Texto).

Para criar uma variável em C++ basta escrever o seu tipo, seu nome e o seu valor (_Lembrete: O valor terá que ser definido em algum momento na aplicação)_

Variáveis também podem ser **unsigned**, ou seja só podem ter valores positivos.

&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;- NOTA &#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;-

Vamos começar a dar exemplos práticos quando falarmos de ponto de entrada. Comente o que poderíamos melhorar!
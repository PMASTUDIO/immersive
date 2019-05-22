---
id: 138
title: IDE para C++
date: 2019-03-09T10:56:06-03:00
author: PGANME
excerpt: "O que é uma IDE? Quais são as IDE's mais usadas para C++? Qual a melhor IDE para mim? Como configurar-la? E mais..."
layout: revision
guid: http://imersive.tech/128-revision-v1/
permalink: /128-revision-v1/
---
### Introdução

Neste artigo vamos falar sobre como escolher a melhor IDE para trabalhar com C++ na sua plataforma.

Primeiro de tudo uma IDE é nada mais que um programa que reúne ferramentas para o desenvolvimento de um software

Ou seja uma IDE é um programa para programar.

### As principais IDE s

Antes de começar veja esta tabela mostrando as principais IDEs: [table id=2 /] 

### Qual a melhor IDE para mim?

É impossível uma ide ser a melhor de todas, pois cada uma tem as suas características.

Como não temos tempo de falar de todas neste artigo vamos focar nas minhas IDEs e compiladores favoritos para cada plataforma.

Todas as IDEs que vamos ver oferecem uma versão grátis com todos os recursos de que vamos precisar e mais um pouco.

#### Windows

O meu ambiente de trabalho favorito para Windows é o [**Microsoft Visual Studio**](https://visualstudio.microsoft.com/pt-br/vs/), pois ele tem todas as ferramentas que eu preciso, alem de um ótimo compilador.

<div class="wp-block-image">
  <figure class="aligncenter"><img src="http://imersive.tech/wp-content/uploads/2019/03/vs-ide-windows-device-1024x513.png" alt="Interface Visual Studio Windows" class="wp-image-129" /><figcaption>Imagem da Microsoft Visual Studio</figcaption></figure>
</div>

#### MacOS

O caso do MacOS é um pouco diferente, pois ele já tem um ótimo ambiente de desenvolvimento chamado de **[Xcode](https://developer.apple.com/xcode/)** 

Sempre que temos a opção de trabalhar em uma plataforma nativa geralmente esta é a melhor opção, pois a plataforma foi criada especificamente para aquele sistema pelos próprios desenvolvedores.<figure class="wp-block-image">

<img src="http://imersive.tech/wp-content/uploads/2019/03/xcode-hero-primary-large-1024x640.png" alt="Interface Xcode macOS" class="wp-image-130" /> <figcaption>Imagem da Apple Xcode</figcaption></figure> 

#### Linux

O caso do Linux também é diferente pois geralmente as pessoas usam um editor de código como o [**SublimeText**](https://www.sublimetext.com/) para criar o código

E depois geram a aplicação com o compilador [**GCC**](https://gcc.gnu.org/) pelo terminal.<figure class="wp-block-image">

<img src="http://imersive.tech/wp-content/uploads/2019/03/linux-1024x598.png" alt="" class="wp-image-131" /> </figure> 

### Como instalar estas IDEs ?

#### Visual Studio &#8211; Windows

  1. Para começar entre no site do [Visual Studio](https://visualstudio.microsoft.com/pt-br/?rr=https%3A%2F%2Fwww.google.com%2F)
  2. Clique em baixar para windows -> Community
  3. Um executável será baixado.
  4. Execute o arquivo baixado.
  5. Você deverá estar na janela do Visual Studio Installer
  6. Siga as instruções até que o programa pergunte que Workloads você quer instalar, então marque a caixa **Desktop Development with C++**

<div class="wp-block-image">
  <figure class="aligncenter"><img src="http://imersive.tech/wp-content/uploads/2019/03/desktop-development-with-cpp.png" alt="" class="wp-image-132" /><figcaption>Imagem Retirada de: <a href="https://github.com/MicrosoftDocs/cpp-docs/blob/master/docs/build/vscpp-step-0-installation.md">MicrosoftDocs</a></figcaption></figure>
</div>

Pronto quando a instalação acabar basta executar o Visual Studio e Pronto!

#### Xcode &#8211; MacOS

Para instalar o Xcode o processo é muito simples:

  1. No sistema operacional entre na Apple Store e busque por Xcode
  2. Basta instalar-lo como se fosse qualquer outra aplicação
  3. Se sua versão do MacOS for incompatível entre [neste link](https://developer.apple.com/download/more/) e baixe uma versão mais antiga do Xcode

Pronto! O Xcode está instalado e pronto para ser usado!

#### Sublime Text e Gcc &#8211; Linux

Vamos começar instalando o compilador:

Abra o terminal e execute o seguinte comando:

<pre class="brush: bash; title: ; notranslate" title="">sudo apt-get install build-essential
</pre>

Para testar se funcionou execute o seguinte comando:

<pre class="brush: bash; title: ; notranslate" title="">gcc –version or gcc –v
</pre>

Ele deve mostrar a versão do GCC

Agora vamos ver como instalar o sublime text no linux:

Execute os seguintes comandos:

<pre class="brush: bash; title: ; notranslate" title="">wget -qO - https://download.sublimetext.com/sublimehq-pub.gpg | sudo apt-key add -
sudo apt-get install apt-transport-https
echo "deb https://download.sublimetext.com/ apt/stable/" | sudo tee /etc/apt/sources.list.d/sublime-text.list
sudo apt-get update
sudo apt-get install sublime-text
</pre>

Pronto o Sublime e o GCC estão prontos para ser usados.

### Próximos passos&#8230;

Agora que você já instalou as suas IDEs só falta conhecer-las

Para fazer isso eu recomendo que você entre no site oficial do seu ambiente de trabalho (IDE) e veja os tutoriais iniciais.

Se familiarize com a sua plataforma.

Para a plataforma linux, veja alguns tutoriais ensinando a usar o Sublime Text e depois mais alguns tutoriais ensinando como usar o GCC.
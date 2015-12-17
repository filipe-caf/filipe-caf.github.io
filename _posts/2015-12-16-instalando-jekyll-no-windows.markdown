---
layout: post
title:  "Instalando o Jekyll no windows!"
date:   2015-12-16 03:00:00
categories: jekyll
comments: true
---

<p align="justify">Após gastar algumas horas quebrando a cabeça, descobri que instalar o <code>Jekyll</code> no windows é mais fácil do que parece!
Eles possuem um <a href="http://jekyll-windows.juthilo.com/" target="_new">tutorial</a> bem detalhado e se você seguir com atenção conseguirá instalar e rodar o servidor local tranquilamente.</p>

<p align="justify">Mas se é tão fácil assim porque você teve dificuldade? Sabe como é, a pessoa vai lendo o tutorial e não se atenta aos pequenos detalhes como as versões de alguns programas e também se sua arquitetura do windows é 32x ou 64x.</p>

<p align="justify">Neste post não vou fazer um tutorial pois creio que o tutorial já feito pelo pessoal da <code>Jekyll</code> está bem detalhado mas se mesmo assim você tiver algum problema na instalação deixe uma mensagem que tentarei te ajudar!</p>
<a href="http://jekyll-windows.juthilo.com/" target="_new">Tutorial de instalação Jekyll no Windows</a>
<br>

<h4>Com o <code>Jekyll</code> instalado vamos criar nosso primeiro blog!</h4>

{% highlight ruby %}
gem install jekyll
jekyll new nome-do-blog
cd nome-do-blog
jekyll serve

# => Acesse seu blog pelo endereço http://localhost:4000
{% endhighlight %} 

<p align="justify">Após rodar os comandos será criado em seu diretório local a seguindo estrutura de pastas</p>
<img src="../images/estrutura-pasta-jekyll.jpg" alt="Estrutura de pasta Jekyll" align="center">

<p align="justify">E ao acessar o endereço:  <code>http://localhost:4000</code> verá que já foi criado o Blog padrão. </p>
<img src="../images/blog-jekyll.jpg" alt="Blog em Jekyll" align="center">

<p align="justify">Para adicionar um novo post basta criar um documento na pasta <code>_post</code> seguindos os padrões do arquivo que já vem na pasta.</p>

<p align="justify">Vou ficando por aqui e em outro post mostro como instalar um thema e deixa o blog mais bonitão!</p>



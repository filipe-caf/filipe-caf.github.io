---
layout: post
title:  "Formatando data em uma linha com PHP!"
date:   2015-12-22 23:40:00
category: programming
tags: [php]
comments: true
---

<p align="justify">
Por padrão o banco de dados MySQL retorna a data no formato americano e muitas das vezes precisamos manipular essa data e apresenta-la no nosso padrão.
</p>

<p align="justify">
Geralmente eu usava a função <code>explode()</code> para 'quebrar' a variável e reorganizar porém tem uma forma bem mais simples e em apenas uma linha.</p>
<p align="justify">
Veja como é bem mais fácil utilizando a função <code>strtotime()</code>
</p>


{% highlight php %}
<?php
//Exemplo com Data e Hora
$dataAmericana = "2015-12-22 23:55:01"; //Data no formato americano
echo date('d/m/Y H:i:s', strtotime($dataAmericana)); 
//Data formatada: 22/12/2015 23:55:01

//Exemplo com Data
$dataAmericana = "2015-12-22"; //Data no formato americano
echo date('d/m/Y', strtotime($dataAmericana)); 
//Data formatada: 22/12/2015
?>
{% endhighlight %} 

<p align="justify">Simples assim e até a próxima!</p>



---
layout: post
title: "Podcast 15 de la temporada 0"
date: 2012-03-15T13:48:39-05:00
author:
  name: José Juan Reyes Zuñiga
comments: true
categories: 
---

Bienvenidos nuevamente a esta emisión de ViveCodigo.org.

Previo a nuestra actividad entramos en una charla muy amena, al respecto de la adopción del Testing como técnica de programación y la necesidad de adoptarlo.

Y en esta ocasión estamos presentando nuestro tercer #CodingDojo, en donde, de la mano de respetables desarrolladores tratamos de resolver una Kata de nombre: LCD Numbers.

<iframe src="https://player.vimeo.com/video/38532924" height="281" width="500" allowfullscreen="" frameborder="0"></iframe>
<!-- more -->
Esta Kata consiste en crear una función que me permita convertir un número entre el 0 y el 9 a su representación en LCD, sin embargo, el acercamiento que se le debe hace a este ejercicio es mediante una prueba, de tal forma que se empiece a resolver de la forma más simple y se progrese en su desarrollo mientras se sigue ejecutando dicha prueba.

Esto es lo primero que se debe realizar:
<pre class="brush:java;">String numberLCD =  " - \n" +
                    "| |\n" +
                    " - \n" +
                    "| |\n" +
                    " - ";
assert convertToLCD(8) == numberLCD;</pre>
Se recomienda comenzar con el número 1, e ir avanzando progresivamente con los demás números para refinar tanto el código como la prueba.

Además, existen por así decirlo, dos tipos de fuentes, las cuales mostramos a continuación:
<p style="text-align: center;"><a href="http://vivecodigo.org/2012/03/15/podcast-15-de-la-temporada-0/ang-2qycaaii4-h-jpg-large/" rel="attachment wp-att-268"><img class="size-medium wp-image-268 aligncenter" title="Ang-2qYCAAIi4-h.jpg-large" alt="" src="/vive-codigo-HugoMigration/images/Ang-2qYCAAIi4-h.jpg-large-300x91.jpg" width="300" height="91" /></a></p>
Como se puede apreciar, la fuente grande consiste de 5 líneas y la pequeña de 3, en la experiencia de quienes han desarrollado la Kata, la de 5 líneas es la más sencilla de implementar, por lo tanto se recomienda comenzar con dicha implementación.

Queremos agradecer a quienes asistieron al Dojo:
<ul>
  <li>Theo Grip(<a href="http://twitter.com/tgrip">@tgrip</a>)</li>
  <li>Alfredo Chávez(<a href="http://twitter.com/alfredochv">@alfredochv</a>)</li>
  <li>Alcides Flores(<a href="http://twitter.com/alcidesfp">@alcidesfp</a>)</li>
  <li>Edgar López(<a href="http://twitter.com/iamcoder">@iamcoder</a>)</li>
</ul>
Y ponemos sus soluciones disponibles a través de nuestro GitHub para que se descarguen las soluciones que desarrollaron:
<ul>
  <li>Alfredo
<ul>
  <li>Python
<ul>
  <li>LCD numbers kata and tests -&gt; <a href="https://gist.github.com/2025419">https://gist.github.com/2025419</a></li>
</ul>
</li>
  <li>Java
<ul>
  <li>LCD numbers' tests -&gt; <a href="https://gist.github.com/2025444">https://gist.github.com/2025444</a></li>
  <li>LCD numbers kata -&gt; <a href="https://gist.github.com/2025449">https://gist.github.com/2025449</a></li>
</ul>
</li>
  <li>C#
<ul>
  <li>LCD numbers' tests -&gt; <a href="https://gist.github.com/2025462">https://gist.github.com/2025462</a></li>
  <li>LCD numbers kata -&gt; <a href="https://gist.github.com/2025475">https://gist.github.com/2025475</a></li>
</ul>
</li>
</ul>
</li>
  <li>Alcides
<ul>
  <li>Pruebas unitarias: <a href="https://gist.github.com/2027117">https://gist.github.com/2027117</a></li>
  <li>Código de producción: <a href="https://gist.github.com/2027144">https://gist.github.com/2027144</a></li>
</ul>
</li>
  <li>José Juan
<ul>
  <li><a href="https://gist.github.com/2046018">https://gist.github.com/2046018</a></li>
</ul>
</li>
  <li>Theo Grip
<ul>
  <li><a href="https://github.com/tgrip/CodingKata">https://github.com/tgrip/CodingKata</a></li>
</ul>
</li>
  <li>Edgar López
<ul>
  <li><a href="https://github.com/elopezanaya/Katas" target="_blank">https://github.com/elopezanaya/Katas</a></li>
</ul>
</li>
  <li>Incluso hubo quién la hizo  distancia. Rodrigo Salado Anaya:
<ul>
  <li><a href="https://gist.github.com/2051680">https://gist.github.com/2051680</a></li>
</ul>
</li>
</ul>
Además, les dejamos el archivo para que lo descarguen directamente:
<strong>
<a href="http://s3.amazonaws.com/media.vivecodigo.org/podcast/temporada0/ViveCodigo00x15.mov">Video</a>
</strong>

Hemos venido disfrutando mucho de estos Dojo's, te invitamos a que asistas al siguiente Dojo.

Mantente atento y esperalo.

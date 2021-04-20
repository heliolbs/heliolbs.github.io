---
layout: post
title:  "Bem vindos ao meu site!"
date:   2021-04-19 22:59:43 -0300
categories: update
permalink: /boas-vindas/
video: /video/highrise-solitude.mp4
---

Olá, pessoal! Bem-vindos ao meu site. Aqui postarei conteúdo relacionado a diversos assuntos, incluindo Letras, Linguística, Programação, Revisão, Formatação, Tradução, Interpretação, entre outros. Espero trazer tópicos do interesse de vocês também e de uma forma que informe, entretenha, agregue e divirta.

<style>
* {
  box-sizing: border-box;
}

body {
  margin: 0;
  font-family: Arial;
  font-size: 17px;
}

#myVideo {
  position: fixed;
  right: 0;
  bottom: 0;
  min-width: 100%; 
  min-height: 100%;
}

.content {
  position: fixed;
  bottom: 0;
  background: rgba(0, 0, 0, 0.5);
  color: #f1f1f1;
  width: 100%;
  padding: 20px;
}

#myBtn {
  width: 200px;
  font-size: 18px;
  padding: 10px;
  border: none;
  background: #000;
  color: #fff;
  cursor: pointer;
}

#myBtn:hover {
  background: #ddd;
  color: black;
}
</style>

<body>

<video autoplay muted loop id="myVideo">
  <source src="rain.mp4" type="video/mp4">
  Your browser does not support HTML5 video.
</video>

<div class="content">
  <h1>Heading</h1>
  <p>Lorem ipsum dolor sit amet, an his etiam torquatos. Tollit soleat phaedrum te duo, eum cu recteque expetendis neglegentur. Cu mentitum maiestatis persequeris pro, pri ponderum tractatos ei. Id qui nemore latine molestiae, ad mutat oblique delicatissimi pro.</p>
  <button id="myBtn" onclick="myFunction()">Pause</button>
</div>

</body>

<!-- {% if page.image %}
  {% assign postImage = page.image %}
{% elsif post.image %}
  {% assign postImage = post.image %}
{% else %}
  {% if page.video %}
    {% assign postVideo = page.video %}
  {% elsif post.video %}
    {% assign postVideo = post.video %}
  {% else %}
    {% assign postImage = site.default_image %}
  {% endif %}
{% endif %} -->

<!-- <video class="background"
	loop
	muted
	autoplay
	preload="auto"
	poster="{{ postVideo }}.png">
<source src="{{ postVideo }}.mp4" type="video/mp4">
<source src="{{ postVideo }}.webm" type="video/webm">
</video> -->

<!-- video.background {
  position: absolute;
  top: 50%;
  left: 50%;
  min-width: 100%;
  min-height: 100%;
  width: auto;
  height: auto;
  z-index: -100;
  transform: translate(-50%, -50%);
  } -->
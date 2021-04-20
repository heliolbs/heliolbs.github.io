---
layout: post
title:  "Bem vindos ao meu site!"
date:   2021-04-19 22:59:43 -0300
categories: update
permalink: /boas-vindas/
video: /video/highrise-solitude.mp4
---

Olá, pessoal! Bem-vindos ao meu site. Aqui postarei conteúdo relacionado a diversos assuntos, incluindo Letras, Linguística, Programação, Revisão, Formatação, Tradução, Interpretação, entre outros. Espero trazer tópicos do interesse de vocês também e de uma forma que informe, entretenha, agregue e divirta.

{% if page.image %}
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
{% endif %}

<video class="background"
	loop
	muted
	autoplay
	preload="auto"
	poster="{{ postVideo }}.png">
<source src="{{ postVideo }}.mp4" type="video/mp4">
<source src="{{ postVideo }}.webm" type="video/webm">
</video>

video.background {
  position: absolute;
  top: 50%;
  left: 50%;
  min-width: 100%;
  min-height: 100%;
  width: auto;
  height: auto;
  z-index: -100;
  transform: translate(-50%, -50%);
  }
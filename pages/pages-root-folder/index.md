---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: header_unsplash_12.jpg
widget1:
  title: "Conheça o Pr0GamErs"
  url: '/sobre/'
  image: widget_sobre.png
  text: 'Somos um Clan de Clash Royal, focados em Guerras de Clan e no Desenvolvimento dos nosso Jogadores. Levamos o jogo a sério, estamos muito bem organizados e subindo no Ranking! <strong>Venha jogar conosco</strong>!'
widget2:
  title: "Pra não ter Confusão"
  url: '/regras/'
  image: widget_regras.png
  text: 'O grupo é grande e muito <em>heterogêneo</em>. Pra não dar confusão e para que não aconteçam injustiças, criamos algumas regras. Assim todos podem focar no jogo ao invés de ficar se preocupando com outras bobagens.<br/>1. Faça Parte.<br/>2. Grupo do WhatApp.<br/>3. Promoçoes e Patentes.'
widget3:
  title: "Faça Parte"
  url: '/regras/faca_parte_do_pr0gamers/'
  image: widget_facaparte-303x182.png
  text: 'Quer vir jogar conosco no clan? <strong>Que ótimo!</strong><br> Nem todo mundo pode fazer parte, existen akguns requisitos. Descubra o que vc precisa fazer no botão abaixo.'
#
# Use the call for action to show a button on the frontpage
#
# To make internal links, just use a permalink like this
# url: /getting-started/
#
# To style the button in different colors, use no value
# to use the main color or success, alert or secondary.
# To change colors see sass/_01_settings_colors.scss
#
callforaction:
  url: https://tinyletter.com/feeling-responsive
  text: Inform me about new updates and features ›
  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---

<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/3b5zCFSmVvU" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>

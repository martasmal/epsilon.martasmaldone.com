---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header: no
widget1:
  title: "Osaka-eki"
  url: 'http://epsilon.martasmaldone.com//design/%C5%8Csaka-eki/'
  text: '<em>Ōsaka-eki</em> Snippet of larger project on Japan<br/>1. Japan :)<br/>2. Japan&#39;Japan<br/>3. Japan <a href="https://vimeo.com/219274698">Foundation Framework</a>.<br/>4. Seven different Headers.<br/>5. Customizable navigation, footer,...'
  video: '<div class="flex-video widescreen vimeo">
  <iframe src="http://player.vimeo.com/video/219274698" width="400" height="225" frameborder="0" webkitAllowFullScreen mozallowfullscreen allowFullScreen></iframe>
</div>'
widget2:
 title: "La memoria si fa carne"
 url: '/works/la-memoria-si-fa-carne/'
 image: arnolfini.jpg
 text: 'Le portrait des époux &shy;<em>Arnolfini de Jan Van Eyck,</em>qui date 1434 montre la condition d’un couple de migrantes toscanes qui habitait en Belgique. Bien évidement le couple appartenait a une classe sociale haute
pour confier au peintre flamand leur portrait.Je reprend avec ironie cette œuvre comme une référence, comme pour créer une continuité. '
widget3:
 title: "Time Caspsule Josaphat"
 url: 'works/Time-Capsule-Josaphat/'
 image: 04.jpg
 text: '<em>Feeling Responsive</em> is free and licensed under a MIT License. Make it your own and start building. Grab the <a href="https://github.com/Phlow/feeling-responsive/tree/bare-bones-version">Bare-Bones-Version</a> for a fresh start or learn how to use it with the <a href="https://github.com/Phlow/feeling-responsive/tree/gh-pages">education-version</a> with sample posts and images. Then tell me via Twitter <a href="http://twitter.com/phlow">@phlow</a>.'
# Use the call for action to show a button on the frontpage
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
#callforaction:
# url: http://www.aavv.io
# text: Aa.Vv. Auctores Varii asbl ›
#  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---

<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://vimeo.com/219274698" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>

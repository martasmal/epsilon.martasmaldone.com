---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header: no

widget1:
  title: "La memoria si fa carne"
  url: '/design/la-memoria-si-fa-carne'
  image: arnolfini.jpg
  text: 'Le portrait des époux Arnolfini de Jan Van Eyck, qui date 1434 montre la condition d’un couple de mi-
grantes toscanes qui habitait en Belgique. Bien évidement le couple appartenait a une classe sociale haute
pour confier au peintre flamand leur portrait. Je reprend avec ironie cette œuvre comme une référence, com-
me pour créer une continuité.<em>Feeling Responsive</em> offers you a fully functional blog with an archive page to give readers a quick overview of all your posts.'
widget2:
  title: "Osaka-eki"
  url: 'https://vimeo.com/219274698'
  text: '<em>Osaka-eki</em> is heavily customizable.<br/>1. Japan :)<br/>2. Japan&#39;Japan.<br/>3. video <a href="http://foundation.zurb.com/">Foundation Framework</a>.<br/>4. Seven different Headers.<br/>5. Customizable navigation, footer,...'
  video: '<a href="#" data-reveal-id="videoModal"><img src="/images/osaka_eki.jpg" width="302" height="182" alt=""/></a>'
widget3:
  title: "Time Capsule Josaphat"
  url: 'https://github.com/Phlow/feeling-responsive'
  image: download.png
  text: '<em>Time capsule Josaphat</em> est une action, un happening, une mémoire, un lieu.
Time Capsule Josaphat est une œuvre de sauvegarde collective de biens et d’informations, une trace pour le futur qui marque une connexion établie dans le présent.
L’action restera liée à la mémoire du lieu; elle sera soit une rupture soit une initiation du lieu et dans le lieu. Une autre valeur à l’espace collectif. <a href="https://github.com/Phlow/feeling-responsive/tree/bare-bones-version">Bare-Bones-Version</a> for a fresh start or learn how to use it with the <a href="https://github.com/Phlow/feeling-responsive/tree/gh-pages">education-version</a> with sample posts and images. Then tell me via Twitter <a href="http://twitter.com/phlow">@phlow</a>.'
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
  url: http://www.aavv.io/
  text: Go to Aa.Vv.io website ›
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
    <iframe width="1280" height="720" src="https://vimeo.com/219274698" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>

---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header: no
widget1:
 title: "Marta del parto"
 url: '/works/Marta-del-parto/'
 text: 'Marta del parto bla bla..'
 video: '<div class="flex-video widescreen vimeo">
 <iframe src="https://player.vimeo.com/video/273497960" width="640" height="360" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>
</div>'
widget2:
  title: "Ōsaka-eki"
  url: '/works/Ōsaka-eki/'
  text: '<em>Snippet of larger project on</em> <br/>1. Empire<br/>2. of<br/>3. signs<br/>4. Japan<br/>5. ...'
  video: '<div class="flex-video widescreen vimeo">
  <iframe src="http://player.vimeo.com/video/219274698" width="400" height="225" frameborder="0" webkitAllowFullScreen mozallowfullscreen allowFullScreen></iframe>
</div>'
widget3:
 title: "La memoria si fa carne"
 url: '/works/la-memoria-si-fa-carne/'
 image: arnolfini.jpg
 text: 'Le portrait des époux &shy;<em>Arnolfini de Jan Van Eyck</em> date 1434 et montre la condition d’un couple de migrantes toscanes qui habitait en Belgique. Je reprend avec ironie cette œuvre comme une référence, comme pour créer une continuité. '
widget4:
 title: "I buried a Time Capsule"
 url: '/works/Time-Capsule-Josaphat/'
 image: 04.jpg
 text: '<em>On 14 February 2015 I buried a time capsule under the Josaphat terrain, in Brussels.</em> It will remain buried for 25 years. It can not be recovered until the year 2040.'
widget5:
title: "Il dottore della peste"
 url: '/works/Il-dottore-della-peste/'
 text:/'dottore'
 video: '<div class="flex-video widescreen vimeo">
 <iframe src="https://player.vimeo.com/video/44689169" width="640" height="362" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe> 
 </div>'
widget6:
title: "Areta in utero"
url: '/works/Areta-in-utero/'
text: 'Areta in utero'
video: '<div class="flex-video widescreen vimeo">
 <iframe src="https://player.vimeo.com/video/93275523" width="640" height="360" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>
</div>'

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

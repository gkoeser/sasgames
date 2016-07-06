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
  title: "Corporate Training"
  url: '/corporate/'
  image: meeting.png
  text: ' Use games, activities, jolts, balloon twisting, magic, improv theater and more to make learning stick. Activity-based training with a facilitated debrief.'
widget2:
  title: "Balloons & Entertaining"
  url: '/balloons/'
  image: greg-balloonheart.png
  text: 'Balloon twisting and decorations, juggling, and entertaining for corporate events, birthday parties, wedding receptions.'
widget3:
  title: "Game Designs"
  url: '/designs/'
  image: Abi_Wedding_Card_back.png
  text: 'Board and card game designs, both custom ordered and personally developed.'
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
  url: https://tinyletter.com/gkoeser
  text: Sign up to my mailing list to keep informed of new games and ideas ›
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

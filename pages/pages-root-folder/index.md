---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: gislovHammer.png
widget1:
  title: "Blinky-Lite"
  url: 'https://www.blinky-lite.se/'
  image: flowMeter302x182.jpg
widget2:
  title: "RF Courses"
  url: '/rfcourses/'
  image: rfq302x182.jpg
widget3:
  title: "Applications"
  url: '/myApps/'
  image: watchApp302x182.png
widget4:
  title: "BL-MC"
  url: 'https://www.bl-mc.se/'
  image: fpga302x182.jpg
widget5:
  title: "Curriculum Vitae"
  url: '/mcginnisCV/'
  image: stochastic.jpg
widget6:
  title: "History"
  url: '/history/'
  image: stone1_302x182.png
  
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
# callforaction:
#  url: https://tinyletter.com/feeling-responsive
#  text: Inform me about new updates and features ›
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
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/edGANlcLQb0" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>

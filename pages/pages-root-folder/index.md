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
  title: "About Me"
  url: 'https://rebshannon.github.io/about-me/'
  image: widget-1-302x182.jpg
  text: 'about me link'
widget2:
  title: "Research"
  url: 'https://rebshannon.github.io/research/'
  text: 'Learn about my CFD experience'
  video: '<a href="#" data-reveal-id="videoModal"><img src="http://phlow.github.io/feeling-responsive/images/start-video-feeling-responsive-302x182.jpg" width="302" height="182" alt=""/></a>'
widget3:
  title: "Cirriculum Vitae"
  url: 'https://rebshannon.github.io/cv/'
  image: widget-github-303x182.jpg
  text: 'See my full CV here'
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
# Welcome

I'm a PhD candidate in the Unstead Fluid Mechanics and Acoustics Lab at Boston University. I am a National Defense Science and Engineering Graduate Fellow, and I specialize in simluation of high-speed multiphase flows.



<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/3b5zCFSmVvU" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>

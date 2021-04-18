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
  title: "Design 4 Developers"
  url: '/'
  text: 'Design 4 Developers is a passion project that distills the <b>Science, Art, Patterns, and Methods of Software Development and Design</b> into its essence!'
  video: '<a href="#" data-reveal-id="Design4DevelopersIntro"><img src="/images/design-4-developers-button-303x182.png" width="302" height="182" alt=""/></a>'
widget2:
  title: "The Designatic"
  url: '/the-designatic'
  text: '<b>Des-ing-a-tic</b> - A person passionate and obsessed about the intersection of engineering, humans and business in the context of software development and delivery; done in a sustainable, profitable and ethical manner.'
  video: '<a href="#" data-reveal-id="DesignaticIntro"><img src="/images/designatic-button-303x182.png" width="302" height="182" alt=""/></a>'
widget3:
  title: "The Foundation"
  url: '/the-foundation'
  image: the-foundation-303x182.jpg
  text: '<b>The Foundation</b>, 6 foundational modules that will give developers freedom from revisiting completed work.  Since all developers are designers, this material is the missing manual for being a better and more thoughtful software developer.'





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
#   url: https://tinyletter.com/feeling-responsive
#   text: Inform me about new updates, articles and features ›
#   style: alert

permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---
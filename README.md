

# Mobile View #

We made an angular app with a mobile-optimised UI, but we needed a nicer (than development tools) way to present it as part of a portfolio, so this is a simple <iframe> based solution to that problem.

If the viewport size is less than 650px then there is a media query that displays a full screen <iframe> of the target website.

If the viewport is greater than 650px then the interface is changed to use a static outline (.png) of a generic mobile phone with an <iframe> sitting on top of that images display.

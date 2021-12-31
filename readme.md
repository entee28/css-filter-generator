# CSS Filter Generator

> A recreation of Barrett Sonntag's project

Let's say you have just got for yourself an amazing SVG icon that you thought is ready for use in your project, then you realise that a black icon won't just fit in your layout. This is when CSS Filter Generator come to your rescue. The goal is making coloring of icons possible by applying `filter` CSS property to the element.

For this code to work well, the starting color needs to be black. If your icon set isn't black, you can prepend `brightness(0) saturate(100%)` to your filter property which will first turn the icon set to black.
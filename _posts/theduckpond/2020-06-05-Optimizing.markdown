---
layout: default
project-title: Optimizing
projectcategory: theduckpond
url: theduckpond
modal-id: theduckpondoptimizing
date: 2020-06-05
img: /img/portfolio/theduckpond/stresstest.gif
alt: image-alt
description: |
  We originally planned to have a massive number of ducks displaying on the screen at the same time, so the player could just keep adding ducks. However, this resulted in performance issues that would require significant effort to stifle. The gif above shows one such stress test in the bathtub pond (this bathtub ended up being cut in the end for scope reasons). We ended up adjusting the game-mechanics for the player slightly to make it so the player would never end up with enough ducks to cause performance issues. See more details below.
img1: /img/portfolio/vul/layers.jpg
gallery:
  - image: "/img/portfolio/theduckpond/stresstest2.gif"
    label: Early stress test
    description: "This gif shows our early tests with spawning lots of ducks and how it effected performance."
  - image: "/img/portfolio/theduckpond/Image Sequence_022_0015.png"
    label: The Hut - mitigating performance issues
    description: "We introduced this hut that the ducks start moving into when you have enough ducks in the pond. This in effect caps the ducks you have in your pond, meaning they can never reach a number that will cause performance issues on most computers."
---
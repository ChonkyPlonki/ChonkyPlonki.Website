---
layout: default
project-title: Water and Swimming Mechanics
projectcategory: vulpion
url: vulpion
modal-id: vulpionswimming
date: 2020-07-09
img: /img/portfolio/vul/swimming.gif
alt: image-alt
description: |
  I love making beautiful water in games, it is one of my favorite things! So for Vulpion I set out to do the same. I also wanted to capture that peaceful feeling one can get when diving in real life. One of the ways I tried to do this was to have the diving obscure everything above land with a dark overlay, tint the colors to sea green, and add a filter to the music when you:

  - Obscure everything above land with a dark overlay
  - Tint the colors to sea green
  - Add a filter to the music

  In this game, both the water surface and the underwater surface are set up in similar ways:
  
  - First, there's a sprite that holds just one color
  - Layered on top of that are images of water-like patterns that have a shader on them causing the patterns to sway
  
  See the image below to see how the water is structured visually.

img1: /img/portfolio/vul/layers.jpg
gallery:
  - image: "/img/portfolio/vul/walking-2encoder.gif"
    description: "I wanted the edge of the water to look soft, so I made translucent sprites with a wave shader to portray a soft water edge. You can see this in the gif where the edge of the water slowly roles against the grass."
  - image: "/img/portfolio/vul/swimanim.gif"
    description: "This is a gif of as I was animating the player's underwater swimming animation. The animations are done with Unity's 2DAnimation tool, it's awesome!"
  - image: "/img/portfolio/vul/Using Heightmap trying at least.gif"
    description: 
     Because the game is in 2D and I didn't want to use 3D terrain I needed to figure out a way to have the player 'sink' into the water as the player walks out into it. I ended up using a heightmap (that's hidden to the player) that pushes the player's position up or down depending on if it's walking over white on the height map (up) or black (down). In the gif above you can see the Vulp-player bump up and down depending on the color of the texture it."
  - image: "/img/portfolio/vul/forest fauna.jpg"
    description: "In one biome I wanted the water to have this deep green almost brownish color that reminds me of Swedish rich forests. I find this color scheme for cozy forests rarely used in media - but I find it so beautiful and calming! This image is concept art I made for that type of water for Vulpion."
---
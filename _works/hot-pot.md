---
layout: blog
card_size: small
title: Hot Pot
description: UI Design / Branding
cover_image: assets/images/hp_thumbnail.png
post_image: assets/images/hp_hero.png
project_link: ''
context_work: ''
context_date: ''
contribution: []
collaborator: []

---
### Introduction

While working for Flux Studio  at Oregon State University, a client approached my team got about redesigning the app interface of a new mobile card game. Battle Casters is a PVP digital trading card game in which players control a single character’s stats, movement, and attacks through the various cards they control.

### Interface

At the start of the project, they showed our team the current prototype game. However they made it clear that all of the current assets besides the logo were placeholders and gave us free rein to create a new look and systems. <figure> <img src="/assets/images/bc-startingdesign.png"> <small>↑ previous icon design</small> </figure> For the new look, we kept the texture paper background. To make the most of the screen and maximize the amount of the battlefield a player can see at any given time, we made elements transparent and pushed them off-screen when not active. We positioned these interactive elements at the bottom of the screen to make it easier to hit with one's fingers. ![starting design](/assets/images/bc_mobileFriends.jpg) ![starting design](/assets/images/bc_mobileStart.jpg) ![starting design](/assets/images/bc_battlescreen.jpg) ![starting design](/assets/images/bc_mobileMenu.jpg)

<style> .glide ul { max-width: initial; } .glide img { pointer-events: none; } .glide__slides { padding-left: 0; } .glide .glide__slide { opacity: 1; transform: scale(1); } </style> <div class="glide mt4"> <div class="glide__track" data-glide-el="track"> <ul class="glide__slides"> <li class="glide__slide"> <img src="/assets/images/ui_buttons.png" alt="first draft" style="text-align: center;"> </li> <li class="glide__slide" style="text-align: center;"> <img src="/assets/images/hp_bar_right.png" alt="second draft"> </li> </ul> </div> </div>

We used transparency and light to make the interface look more open and indicate information. To make sure that text would still be readable even on a light background we used subtle drop shadows and a slight blur effect along with a generous text-shadow.

## Cards

While not in the initial brief. The design team felt that the current card design did not match the new UI assets and was not very legible when shrunk down to fit on the iPhone.

![card designs](/assets/images/bc_cards.png)

Some of the biggest changes were cleaning up the card shape and remove the textured background. To make the text more legible, we also bumped up the font size and removed unnecessary elements such as flavor text and artist description. Instead, those elements moved to the deck builder page. The team also moved the damage amount to the upper left to increase visibility.

![card infomation](/assets/images/bc_cardInfo.jpg)

## Symbols

The last component of the card we changed was the element symbols. The original symbols were more artistry rendered but did not scale well when smaller than 32px. Therefore a team member came up with a simpler flatter, more scalable symbol.

![element symbols](/assets/images/bc_symbols.png)

<script src="{{site.url}}/logic/glide.min.js"></script> <script> var slide = new Glide(".glide", { perView: 2, gap: 24, focusAt: 'center', keyboard: true, rewind: true, bound: true, autoheight: true, bound: 'true', perTouch: 1, touchRatio: 1, focusAt: 'center', peak: { before: 0, after: 0, }, breakpoints: { 600: { gap: 4, peek: { before: 0, after: 48, }, perView: 1, } }, }).mount(); </script>
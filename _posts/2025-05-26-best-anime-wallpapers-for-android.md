---
layout: post
title:  "Best Anime wallpapers for Android"
author: jay
categories: [ Wallpapers, Anime ]
tags: [ wallpapers, anime, onepiece, naruto, dbz ]
comments: false
rating: 5
---

Best Anime Wallpapers for mobile phone. One piece, Naruto, DBZ, Pokemon and more

<div style="display: grid; grid-template-columns: 1fr 1fr; gap: 16px;">
  {% assign anime_images = site.static_files | where_exp: "file", "file.path contains 'assets/images/anime_walls/'" %}
  {% for img in anime_images %}
    <div>
      <img src="{{ img.path }}" alt="Anime Wallpaper {{ forloop.index }}" style="width:100%; border-radius:8px;">
    </div>
  {% endfor %}
</div>

[Get on Google Play](https://play.google.com/store/apps/details?id=com.hhstudio.wallpapers.anime)
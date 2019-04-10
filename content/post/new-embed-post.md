---
title: Go WIG or go HOME
date: 2018-04-10
tags:
    - dragrace
    - youtube
    - season 11
---

This post contains season 11 promo video where all of the contestants are revealed.

<!--more-->
<div id="ytplayer"></div>

<script>
  // Load the IFrame Player API code asynchronously.
  var tag = document.createElement('script');
  tag.src = "https://www.youtube.com/player_api";
  var firstScriptTag = document.getElementsByTagName('script')[0];
  firstScriptTag.parentNode.insertBefore(tag, firstScriptTag);

  // Replace the 'ytplayer' element with an <iframe> and
  // YouTube player after the API code downloads.
  var player;
  function onYouTubePlayerAPIReady() {
    player = new YT.Player('ytplayer', {
      height: '360',
      width: '640',
      videoId: 'uyiDn9YXe3g'
    });
  }
</script>

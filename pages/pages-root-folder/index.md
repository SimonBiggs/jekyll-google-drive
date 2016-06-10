---
layout: frontpage
header:
  image_fullwidth: waggachurchofchristfamily.jpg
permalink: /index.html
homepage: true
googlesheetpull: true
---

<div class="row t60">
    <div class="medium-6 columns flex-video"></div>
        <a href="#" data-reveal-id="videoModal">
            <img src="images/video-modal.png" width="500" height="281" alt=""/>
        </a>
    </div>

    <div class="medium-6 columns flex-video embedded_map"></div>
</div>

<div class="row">
    <div class="medium-4 columns">
        <h2 class="font-size-h3 t10">Greetings!</h2>        
        <p class="welcome"></p>
    </div>

    <div class="medium-4 columns">
        <h2 class="font-size-h3 t10">Most recent sermons</h2>           
        <p>An audio bar goes here. TEST</p>
    </div>

    <div class="medium-4 columns">
        <h2 class="font-size-h3 t10">Events coming up</h2>           
        <p class="upcoming_events"></p>
    </div>
</div>


<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/unIIn_1JOAE" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>

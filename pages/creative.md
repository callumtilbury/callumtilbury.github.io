---
layout: default
title: creative
weight: 4
permalink: /creative
---

<br/>

<div class="row justify-content-center">
  <div class="col-lg-4 col-md-6 text-left mt-4">
    <b> digital photography </b>
    testing out writing a paragraph here.
  </div>
    <div class="col-md-8">
        {% capture carousel_images %}
            {%- for i in (1..20) -%}
                /assets/images/portfolio/callumtilbury-portfolio-digital-{{i}}.jpg
            {% endfor %}
        {% endcapture %}
        {% include elements/carousel_a.html %}
    </div>
</div>

<br/>

<div class="row justify-content-center">
  <div class="col-lg-4 col-md-6 text-left mt-4">
    <b> analog photography </b>
    
  </div>
    <div class="col-md-8">
        {% capture carousel_images %}
            {%- for i in (1..15) -%}
                /assets/images/portfolio/callumtilbury-portfolio-analog-{{i}}.jpg
            {% endfor %}
        {% endcapture %}
        {% include elements/carousel_b.html %}
    </div>
</div>

<br/>


<div class="row justify-content-center">
  <div class="col-lg-4 col-md-6 text-left mt-4">
    <b> music </b><br/>
    <p>I love making music.</p>
  </div>
    <div class="col-md-8">
        <div class="music_widget_center">
            <iframe allow="autoplay *; encrypted-media *;" frameborder="0" height="150" style="width:100%;overflow:hidden;background:transparent;" sandbox="allow-forms allow-popups allow-same-origin allow-scripts allow-storage-access-by-user-activation allow-top-navigation-by-user-activation" src="https://embed.music.apple.com/za/album/on-strike/1278731364?i=1278731370"></iframe>
        </div>
        <div class="music_widget_center">
            <iframe width="100%" height="166" scrolling="no" frameborder="no" allow="autoplay" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/272986047&color=%23ff5500&auto_play=false&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true"></iframe><div style="font-size: 10px; color: #cccccc;line-break: anywhere;word-break: normal;overflow: hidden;white-space: nowrap;text-overflow: ellipsis; font-family: Interstate,Lucida Grande,Lucida Sans Unicode,Lucida Sans,Garuda,Verdana,Tahoma,sans-serif;font-weight: 100;"><a href="https://soundcloud.com/goodbyecorolla" title="Goodbye, Corolla" target="_blank" style="color: #cccccc; text-decoration: none;">Goodbye, Corolla</a> · <a href="https://soundcloud.com/goodbyecorolla/not-just-yet-ukulele" title="Not Just Yet (Ukulele)" target="_blank" style="color: #cccccc; text-decoration: none;">Not Just Yet (Ukulele)</a></div>
        </div>
        <div class="music_widget_center">
            <iframe width="100%" height="420" src="https://www.youtube-nocookie.com/embed/69vM_XhQ20I" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        </div>
    </div>
</div>

<br/>

<div class="row justify-content-center">
  <div class="col-lg-4 col-md-6 text-left mt-4">
    <b> design </b><br/>
    <p> </p>
  </div>
    <div class="col-md-8">
        <p>hullo</p>
    </div>
</div>

<br/>
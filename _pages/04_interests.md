---
layout: archive
permalink: /interests/
title: "INTERESTS"
author_profile: true
---

<!DOCTYPE html PUBLIC "-//W3C//DTD HTML 4.0 Transitional//EN" "http://www.w3.org/TR/REC-html40/loose.dtd">
<html style="-webkit-box-sizing: border-box;
            box-sizing: border-box;
            margin: 0;
            padding: 0;"><body style='-webkit-box-sizing:border-box;box-sizing:border-box;margin:0;padding:0;background-image:url("../img/cover/back_dot.jpg");font-family:"Nanum Barun Gothic", "Ubuntu Condensed", "Noto Sans Korean";'><div id="gallery_layout" style="-webkit-box-sizing:border-box;box-sizing:border-box;margin:0 auto;padding:0;width:100%;position:absolute;top:50%;left:50%;transform:translate(-50%, -50%);">
    <div class="gallery_content" style="-webkit-box-sizing:border-box;box-sizing:border-box;margin:0;padding:0;position:relative;float:left;width:100%;overflow:hidden;">
        <img src="img/travel_img.jpg" alt="travel_img" style="-webkit-box-sizing:border-box;box-sizing:border-box;margin:0 auto;padding:0;width:100%;height:300px;display:block;transition:all 1s ease-in-out;">
    </div>
    <div class="gallery_content top" style="-webkit-box-sizing:border-box;box-sizing:border-box;margin:0;padding:0;position:relative;float:left;width:100%;overflow:hidden;">
        <img src="img/travel_img2.jpg" alt="&#50668;&#54665;&#51060;&#48120;&#51648;2" style="-webkit-box-sizing:border-box;box-sizing:border-box;margin:0 auto;padding:0;width:100%;height:300px;display:block;transition:all 1s ease-in-out;"> 
    </div>
    <div class="gallery_content" style="-webkit-box-sizing:border-box;box-sizing:border-box;margin:0;padding:0;position:relative;float:left;width:100%;overflow:hidden;">
        <img src="img/travel_img3.jpg" alt="&#50668;&#54665;&#51060;&#48120;&#51648;3" style="-webkit-box-sizing:border-box;box-sizing:border-box;margin:0 auto;padding:0;width:100%;height:300px;display:block;transition:all 1s ease-in-out;">
    </div>
    <div class="gallery_content" style="-webkit-box-sizing:border-box;box-sizing:border-box;margin:0;padding:0;position:relative;float:left;width:100%;overflow:hidden;">
        <img src="img/travel_img4.jpg" alt="&#50668;&#54665;&#51060;&#48120;&#51648;4" style="-webkit-box-sizing:border-box;box-sizing:border-box;margin:0 auto;padding:0;width:100%;height:300px;display:block;transition:all 1s ease-in-out;">
    </div>
    <div class="gallery_content" style="-webkit-box-sizing:border-box;box-sizing:border-box;margin:0;padding:0;position:relative;float:left;width:100%;overflow:hidden;">
        <img src="img/travel_img5.jpg" alt="&#50668;&#54665;&#51060;&#48120;&#51648;5" style="-webkit-box-sizing:border-box;box-sizing:border-box;margin:0 auto;padding:0;width:100%;height:300px;display:block;transition:all 1s ease-in-out;"> 
    </div>
    <div class="gallery_content" style="-webkit-box-sizing:border-box;box-sizing:border-box;margin:0;padding:0;position:relative;float:left;width:100%;overflow:hidden;">
        <img src="img/travel_img6.jpg" alt="&#50668;&#54665;&#51060;&#48120;&#51648;6" style="-webkit-box-sizing:border-box;box-sizing:border-box;margin:0 auto;padding:0;width:100%;height:300px;display:block;transition:all 1s ease-in-out;">
    </div>
</div></body></html>

{% include group-by-array collection=site.posts field="categories" %}
{% for category in group_names %}
  {% assign posts = group_items[forloop.index0] %}
  <h2 id="{{ category | slugify }}" class="archive__subtitle">{{ category }}</h2>
  {% for post in posts %}
    {% include archive-single.html %}
  {% endfor %}
{% endfor %}

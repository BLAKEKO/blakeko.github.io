---
layout: archive
permalink: /about/
title: "ABOUT"
author_profile: true
---

I am studying for a Master's degree in the Graduate School of Convergence Science and Technology [(GSCST)](http://convergence.snu.ac.kr/main/) from Seoul National University [(SNU)](http://snu.ac.kr/index.html), studying under Joongseek Lee.
<div class="row">
            <h1><span data-i18n="skills.my_skills">Bio</span></h1>

<div class="archive">
  <div class="timeline" id="timeline">
    
  <div class="archive-title"><div class="archive-year"><strong style="margin-right: 2px;">Mar. 2015 &ndash; <i class="fa fa-clock-o" aria-hidden="true" title="Until Now"></i></strong> Graduate Research Assistant @ <a href="http://ux.snu.ac.kr/" target="_blank">User eXperience Lab at Seoul National University</a></div></div>

  <div class="archive-title"><div class="archive-year"><strong style="margin-right: 2px;">May 2012 &ndash; Feb. 2015</strong> Junior Developer @ <a href="http://www.redwood-inc.com/" target="_blank">Redwood Interactive</a></div></div>

  <div class="archive-title"><div class="archive-year"><strong style="margin-right: 2px;">Sep. 2011 &ndash; Feb. 2015</strong> Graduate Research Assistant @ <a href="https://sites.google.com/site/cvgyonsei/members" target="_blank">Computer Vision & Graphics Lab at Yonsei University</a></div></div>
    
  </div>
</div>

</div>
<div class="row">
    <div class="navy-line"></div>
<h1><span data-i18n="skills.my_skills">Education</span></h1>

<div class="archive">
  <div class="timeline" id="timeline">
    
  <div class="archive-title bio"><div class="archive-year"><strong style="margin-right: 2px;">2015 &ndash; <i class="fa fa-clock-o" aria-hidden="true" title="Until Now"></i></strong> <a href="http://www.snu.ac.kr/">  Seoul National University</a></div></div>

  <div class="archive-title bio"><div class="archive-year"><strong style="margin-right: 2px;">2011 &ndash; 2015</strong> <a href="http://www.yonsei.ac.kr/">  Yonsei University</a></div></div>

  <div class="archive-title bio"><div class="archive-year"><strong style="margin-right: 2px;">2007 &ndash; 2011</strong> <a href="http://www.colorado.edu/">  University of Colorado at Boulder</a></div></div>
    
  </div>
</div>

{% include group-by-array collection=site.posts field="categories" %}
{% for category in group_names %}
  {% assign posts = group_items[forloop.index0] %}
  <h2 id="{{ category | slugify }}" class="archive__subtitle">{{ category }}</h2>
  {% for post in posts %}
    {% include archive-single.html %}
  {% endfor %}
{% endfor %}

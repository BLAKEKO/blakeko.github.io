---
layout: archive
permalink: /about/
title: "ABOUT"
author_profile: true
---

I am studying for a Master's degree in the Graduate School of Convergence Science and Technology [(GSCST)](http://convergence.snu.ac.kr/main/) from Seoul National University [(SNU)](http://snu.ac.kr/index.html), studying under Joongseek Lee.

---

<h1>Bio</h1>
	
- **March 2019 ~ July 2019** 
Graduate Research Assistant @ <a href="http://ux.snu.ac.kr/" target="_blank">User eXperience Lab at Seoul National University</a><br>
- **June 2016 ~ September 2016** 
Internship @ <a href="http://www.redwood-inc.com/" target="_blank">Seoul City Hall Information and Communication Security Officer Information Protection Team</a><br>

---

<h1>Education</h1>

- **2018 ~** 
<a href="http://www.snu.ac.kr/">  Seoul National University</a><br>
- **2012 ~ 2018**
<a href="http://www.hanyang.ac.kr/">Hanyang University</a><br>
- **2016 ~ 2017**
<a href="https://h-da.com/">Darmstadt University of Applied Sciences</a><br>
- **2007 ~ 2010**
<a href="http://djflhs.djsch.kr/main.do">Daejeon Foreign Language High School</a><br>
	
---

<script src="https://cdnjs.cloudflare.com/ajax/libs/Chart.js/2.6.0/Chart.min.js"></script>
<h1><span data-i18n="skills.my_skills">Skills</span></h1>
<canvas id="cs" height="100" width="100"></canvas>    
<script>
    var ctx = document.getElementById("cs");
    var data = {
    labels: "Collaboration, Data Analysis, Python, HTML/CSS, C++, PM".split(","),
    datasets: [{
        label: "Ability",
        backgroundColor: "rgba(179,181,198,0.2)",
        borderColor: "#3385FF",
        pointBackgroundColor: "#3385FF",
        pointBorderColor: "#fff",
        pointHoverBackgroundColor: "#3385FF",
        pointHoverBorderColor: "#3385FF",
        data: [95, 80, 90, 70, 70, 80]
        }]
    };
    var myRadarChart = new Chart(ctx, {
    type: 'radar',
    data: data,
    options: {
        scale: {
            responsive: true,
            ticks: {min: 0, max: 100},
            lineArc: false,
            pointLabels: {fontSize: 14},
        },
        scaleFontSize: 0,
        legend: {display: false},
    }
    });
</script>





{% include group-by-array collection=site.posts field="categories" %}
{% for category in group_names %}
  {% assign posts = group_items[forloop.index0] %}
  <h2 id="{{ category | slugify }}" class="archive__subtitle">{{ category }}</h2>
  {% for post in posts %}
    {% include archive-single.html %}
  {% endfor %}
{% endfor %}

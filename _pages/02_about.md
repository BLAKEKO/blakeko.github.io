---
layout: archive
permalink: /about/
title: "ABOUT"
author_profile: true
---

I am studying for a Master's degree in **the Graduate School of Convergence Science and Technology** [(GSCST)](http://convergence.snu.ac.kr/main/) from **Seoul National University** [(SNU)](http://snu.ac.kr/index.html), studying under Joongseek Lee.

---


<script src="https://cdnjs.cloudflare.com/ajax/libs/Chart.js/2.6.0/Chart.min.js"></script>
<div class="col l4 offset-l1">
        <div class="row">
<h1><span data-i18n="skills.my_skills">SKILLS</span></h1>
<canvas id="cs" height="100" width="100"></canvas>    
<script>
    var ctx = document.getElementById("cs");
    var data = {
    labels: "Collaboration, Data Analysis, Python, HTML/CSS, Communication, PM".split(","),
    datasets: [{
        label: "Ability",
        backgroundColor: "rgba(179,181,198,0.2)",
        borderColor: "#FF6B6B",
        pointBackgroundColor: "#FF6B6B",
        pointBorderColor: "#fff",
        pointHoverBackgroundColor: "#FF6B6B",
        pointHoverBorderColor: "#FF6B6B",
        data: [95, 80, 70, 85, 85, 80]
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
            pointLabels: {fontSize: 15},
        },
        scaleFontSize: 0,
        legend: {display: false},
    }
    });

</script>
</div>
</div>

---
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
	<style>

	body {
	  color: #768390;
	  background: #FFF;
	  font-family: "Effra", Helvetica, sans-serif;
	  padding: 0;
	  -webkit-font-smoothing: antialiased; }

	h1, h2, h3, h4, h5, h6 {
	  color: #3D4351;
	  margin-top: 0; }

	a {
	  color: #FF6B6B; }
	  a:hover {
	    color: #ff9a9a;
	    text-decoration: none; }

	.example-header {
	  background: #3D4351;
	  color: #FFF;
	  font-weight: 300;
	  padding: 3em 1em;
	  text-align: center; }
	  .example-header h1 {
	    color: #FFF;
	    font-weight: 300;
	    margin-bottom: 20px; }
	  .example-header p {
	    font-size: 12px;
	    text-transform: uppercase;
	    letter-spacing: 3px;
	    font-weight: 700; }

	.container-fluid .row {
	  padding: 0 0 4em 0; }
	  .container-fluid .row:nth-child(even) {
	    background: #F1F4F5; }

	.example-title {
	  text-align: center;
	  margin-bottom: 60px;
	  padding: 3em 0;
	  border-bottom: 1px solid #E4EAEC; }
	  .example-title p {
	    margin: 0 auto;
	    font-size: 16px;
	    max-width: 400px; }

	/*==================================
	    TIMELINE
	==================================*/
	/*-- GENERAL STYLES
	    ------------------------------*/
	.timeline {
	  line-height: 1.5em;
	  list-style: none;
	  margin: 0;
	  padding: 0;
	  width: 100%; }
	  .timeline h1, .timeline h2, .timeline h3, .timeline h4, .timeline h5, .timeline h6 {
	    line-height: inherit; }

	/*----- TIMELINE ITEM -----*/
	.timeline-item {
	  padding-left: 30px;
	  position: relative; }
	  .timeline-item:last-child {
	    padding-bottom: 0; }

	/*----- TIMELINE INFO -----*/
	.timeline-info {
	  font-size: 12px;
	  font-weight: 700;
	  letter-spacing: 3px;
	  margin: 0 0 .5em 0;
	  text-transform: uppercase;
	  white-space: nowrap; }

	/*----- TIMELINE MARKER -----*/
	.timeline-marker {
	  position: absolute;
	  top: 0;
	  bottom: 0;
	  left: 0;
	  width: 15px; }
	  .timeline-marker:before {
	    background: #FF6B6B;
	    border: 3px solid transparent;
	    border-radius: 100%;
	    content: "";
	    display: block;
	    height: 10px;
	    position: absolute;
	    top: 4px;
	    left: 0;
	    width: 10px;
	    transition: background 0.3s ease-in-out, border 0.3s ease-in-out; }
	  .timeline-marker:after {
	    content: "";
	    width: 3px;
	    background: #CCD5DB;
	    display: block;
	    position: absolute;
	    top: 24px;
	    bottom: 0;
	    left: 6px; }
	  .timeline-item:last-child .timeline-marker:after {
	    content: none; }

	.timeline-item:not(.period):hover .timeline-marker:before {
	  background: transparent;
	  border: 3px solid #FF6B6B; }

	/*----- TIMELINE CONTENT -----*/
	.timeline-content {
	  padding-bottom: 40px; }
	  .timeline-content p:last-child {
	    margin-bottom: 0; }

	/*----- TIMELINE PERIOD -----*/
	.period {
	  padding: 0; }
	  .period .timeline-info {
	    display: none; }
	  .period .timeline-marker:before {
	    background: transparent;
	    content: "";
	    width: 15px;
	    height: auto;
	    border: none;
	    border-radius: 0;
	    top: 0;
	    bottom: 30px;
	    position: absolute;
	    border-top: 3px solid #CCD5DB;
	    border-bottom: 3px solid #CCD5DB; }
	  .period .timeline-marker:after {
	    content: "";
	    height: 32px;
	    top: auto; }
	  .period .timeline-content {
	    padding: 40px 0 70px; }
	  .period .timeline-title {
	    margin: 0; }

	/*----------------------------------------------
	        MOD: TIMELINE SPLIT
	    ----------------------------------------------*/
	@media (min-width: 768px) {
	  .timeline-split .timeline, .timeline-centered .timeline {
	    display: table; }
	  .timeline-split .timeline-item, .timeline-centered .timeline-item {
	    display: table-row;
	    padding: 0; }
	  .timeline-split .timeline-info, .timeline-centered .timeline-info,
	  .timeline-split .timeline-marker,
	  .timeline-centered .timeline-marker,
	  .timeline-split .timeline-content,
	  .timeline-centered .timeline-content,
	  .timeline-split .period .timeline-info,
	  .timeline-centered .period .timeline-info {
	    display: table-cell;
	    vertical-align: top; }
	  
	  .timeline-split .timeline-marker,
	  .timeline-centered .timeline-marker {
	    position: relative; }
	  
	  .timeline-split .timeline-content,
	  .timeline-centered .timeline-content {
	    padding-left: 30px; }
	  .timeline-split .timeline-info, .timeline-centered .timeline-info {
	    padding-right: 30px; }
	  .timeline-split .period .timeline-title, .timeline-centered .period .timeline-title {
	    position: relative;
	    left: -45px; } }

	/*----------------------------------------------
	        MOD: TIMELINE CENTERED
	    ----------------------------------------------*/
	@media (min-width: 992px) {
	  .timeline-centered,
	  .timeline-centered .timeline-item,
	  .timeline-centered .timeline-info,
	  .timeline-centered .timeline-marker,
	  .timeline-centered .timeline-content {
	    display: block;
	    margin: 0;
	    padding: 0; }
	  .timeline-centered .timeline-item {
	    padding-bottom: 40px;
	    overflow: hidden; }
	  .timeline-centered .timeline-marker {
	    position: absolute;
	    left: 50%;
	    margin-left: -7.5px; }
	  .timeline-centered .timeline-info,
	  .timeline-centered .timeline-content {
	    width: 50%; }
	  .timeline-centered > .timeline-item:nth-child(odd) .timeline-info {
	    float: left;
	    text-align: right;
	    padding-right: 30px; }
	  .timeline-centered > .timeline-item:nth-child(odd) .timeline-content {
	    float: right;
	    text-align: left;
	    padding-left: 30px; }
	  .timeline-centered > .timeline-item:nth-child(even) .timeline-info {
	    float: right;
	    text-align: left;
	    padding-left: 30px; }
	  .timeline-centered > .timeline-item:nth-child(even) .timeline-content {
	    float: left;
	    text-align: right;
	    padding-right: 30px; }
	  .timeline-centered > .timeline-item.period .timeline-content {
	    float: none;
	    padding: 0;
	    width: 100%;
	    text-align: center; }
	  .timeline-centered .timeline-item.period {
	    padding: 50px 0 90px; }
	  .timeline-centered .period .timeline-marker:after {
	    height: 30px;
	    bottom: 0;
	    top: auto; }
	  .timeline-centered .period .timeline-title {
	    left: auto; } }

	/*----------------------------------------------
	        MOD: MARKER OUTLINE
	    ----------------------------------------------*/
	.marker-outline .timeline-marker:before {
	  background: transparent;
	  border-color: #FF6B6B; }

	.marker-outline .timeline-item:hover .timeline-marker:before {
	  background: #FF6B6B; }


	</style>
</head>
<body>
<script src="https://use.typekit.net/bkt6ydm.js"></script>
<script>try{Typekit.load({ async: true });}catch(e){}</script>
<!-- <header class="example-header">
    <h1 class="text-center">About Me</h1>
    <p>I am studying for a Master's degree in the Graduate School of Convergence Science and Technology <a href="http://convergence.snu.ac.kr/main/" target="_blank">(GSCST)</a> from Seoul National University <a href="http://snu.ac.kr/index.html" target="_blank">(SNU)</a>, studying under Joongseek Lee. </p>
</header> -->
<div class="container-fluid">
    <div class="row example-basic">
    	<h1> EDUCATION </h1>
        <div class="col-xs-10 col-xs-offset-1 col-sm-8 col-sm-offset-2">
            <ul class="timeline">
                <li class="timeline-item">
                    <div class="timeline-info">
                        <span>March 2018 ~</span>
                    </div>
                    <div class="timeline-marker"></div>
                    <div class="timeline-content">
                        <h3 class="timeline-title">Seoul National University</h3>
                        <p>서울대학교 융합과학기술대학원 사용자경험연구실</p>
                    </div>
                </li>
                <li class="timeline-item">
                    <div class="timeline-info">
                        <span>August 2016 ~ Februrary 2017</span>
                    </div>
                    <div class="timeline-marker"></div>
                    <div class="timeline-content">
                        <h3 class="timeline-title">University of Applied Sciences Darmstadt</h3>
                        <p>한-EU ICI 교환학생 장학 프로그램</p>
                    </div>
                </li>
                <li class="timeline-item">
                    <div class="timeline-info">
                        <span>March 2012 ~ Februrary 2018</span>
                    </div>
                    <div class="timeline-marker"></div>
                    <div class="timeline-content">
                        <h3 class="timeline-title">Hanyang University</h3>
                        <p>한양대학교 공과대학 정보시스템학과</p>
                    </div>
                </li>
                <li class="timeline-item">
                    <div class="timeline-info">
                        <span>March 2007 ~ Februrary 2010</span>
                    </div>
                    <div class="timeline-marker"></div>
                    <div class="timeline-content">
                        <h3 class="timeline-title">Daejeon Foreign Language High School</h3>
                        <p>대전외국어고등학교 영어과</p>
                    </div>
                </li>
            </ul>
        </div>
    </div>
 </div>
</body>
</html>


<!-- ---

<h1>Education</h1>

- **2018 ~** 
<a href="http://www.snu.ac.kr/">  Seoul National University</a><br>
- **2012 ~ 2018**
<a href="http://www.hanyang.ac.kr/">Hanyang University</a><br>
- **2016 ~ 2017**
<a href="https://h-da.com/">Darmstadt University of Applied Sciences</a><br>
- **2007 ~ 2010**
<a href="http://djflhs.djsch.kr/main.do">Daejeon Foreign Language High School</a><br>
	 -->
---

<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
	<style>

	body {
	  color: #768390;
	  background: #FFF;
	  font-family: "Effra", Helvetica, sans-serif;
	  padding: 0;
	  -webkit-font-smoothing: antialiased; }

	h1, h2, h3, h4, h5, h6 {
	  color: #3D4351;
	  margin-top: 0; }

	a {
	  color: #FF6B6B; }
	  a:hover {
	    color: #ff9a9a;
	    text-decoration: none; }

	.example-header {
	  background: #3D4351;
	  color: #FFF;
	  font-weight: 300;
	  padding: 3em 1em;
	  text-align: center; }
	  .example-header h1 {
	    color: #FFF;
	    font-weight: 300;
	    margin-bottom: 20px; }
	  .example-header p {
	    font-size: 12px;
	    text-transform: uppercase;
	    letter-spacing: 3px;
	    font-weight: 700; }

	.container-fluid .row {
	  padding: 0 0 4em 0; }
	  .container-fluid .row:nth-child(even) {
	    background: #F1F4F5; }

	.example-title {
	  text-align: center;
	  margin-bottom: 60px;
	  padding: 3em 0;
	  border-bottom: 1px solid #E4EAEC; }
	  .example-title p {
	    margin: 0 auto;
	    font-size: 16px;
	    max-width: 400px; }

	/*==================================
	    TIMELINE
	==================================*/
	/*-- GENERAL STYLES
	    ------------------------------*/
	.timeline {
	  line-height: 1.5em;
	  list-style: none;
	  margin: 0;
	  padding: 0;
	  width: 100%; }
	  .timeline h1, .timeline h2, .timeline h3, .timeline h4, .timeline h5, .timeline h6 {
	    line-height: inherit; }

	/*----- TIMELINE ITEM -----*/
	.timeline-item {
	  padding-left: 30px;
	  position: relative; }
	  .timeline-item:last-child {
	    padding-bottom: 0; }

	/*----- TIMELINE INFO -----*/
	.timeline-info {
	  font-size: 12px;
	  font-weight: 700;
	  letter-spacing: 3px;
	  margin: 0 0 .5em 0;
	  text-transform: uppercase;
	  white-space: nowrap; }

	/*----- TIMELINE MARKER -----*/
	.timeline-marker {
	  position: absolute;
	  top: 0;
	  bottom: 0;
	  left: 0;
	  width: 15px; }
	  .timeline-marker:before {
	    background: #FF6B6B;
	    border: 3px solid transparent;
	    border-radius: 100%;
	    content: "";
	    display: block;
	    height: 10px;
	    position: absolute;
	    top: 4px;
	    left: 0;
	    width: 10px;
	    transition: background 0.3s ease-in-out, border 0.3s ease-in-out; }
	  .timeline-marker:after {
	    content: "";
	    width: 3px;
	    background: #CCD5DB;
	    display: block;
	    position: absolute;
	    top: 24px;
	    bottom: 0;
	    left: 6px; }
	  .timeline-item:last-child .timeline-marker:after {
	    content: none; }

	.timeline-item:not(.period):hover .timeline-marker:before {
	  background: transparent;
	  border: 3px solid #FF6B6B; }

	/*----- TIMELINE CONTENT -----*/
	.timeline-content {
	  padding-bottom: 40px; }
	  .timeline-content p:last-child {
	    margin-bottom: 0; }

	/*----- TIMELINE PERIOD -----*/
	.period {
	  padding: 0; }
	  .period .timeline-info {
	    display: none; }
	  .period .timeline-marker:before {
	    background: transparent;
	    content: "";
	    width: 15px;
	    height: auto;
	    border: none;
	    border-radius: 0;
	    top: 0;
	    bottom: 30px;
	    position: absolute;
	    border-top: 3px solid #CCD5DB;
	    border-bottom: 3px solid #CCD5DB; }
	  .period .timeline-marker:after {
	    content: "";
	    height: 32px;
	    top: auto; }
	  .period .timeline-content {
	    padding: 40px 0 70px; }
	  .period .timeline-title {
	    margin: 0; }

	/*----------------------------------------------
	        MOD: TIMELINE SPLIT
	    ----------------------------------------------*/
	@media (min-width: 768px) {
	  .timeline-split .timeline, .timeline-centered .timeline {
	    display: table; }
	  .timeline-split .timeline-item, .timeline-centered .timeline-item {
	    display: table-row;
	    padding: 0; }
	  .timeline-split .timeline-info, .timeline-centered .timeline-info,
	  .timeline-split .timeline-marker,
	  .timeline-centered .timeline-marker,
	  .timeline-split .timeline-content,
	  .timeline-centered .timeline-content,
	  .timeline-split .period .timeline-info,
	  .timeline-centered .period .timeline-info {
	    display: table-cell;
	    vertical-align: top; }
	  
	  .timeline-split .timeline-marker,
	  .timeline-centered .timeline-marker {
	    position: relative; }
	  
	  .timeline-split .timeline-content,
	  .timeline-centered .timeline-content {
	    padding-left: 30px; }
	  .timeline-split .timeline-info, .timeline-centered .timeline-info {
	    padding-right: 30px; }
	  .timeline-split .period .timeline-title, .timeline-centered .period .timeline-title {
	    position: relative;
	    left: -45px; } }

	/*----------------------------------------------
	        MOD: TIMELINE CENTERED
	    ----------------------------------------------*/
	@media (min-width: 992px) {
	  .timeline-centered,
	  .timeline-centered .timeline-item,
	  .timeline-centered .timeline-info,
	  .timeline-centered .timeline-marker,
	  .timeline-centered .timeline-content {
	    display: block;
	    margin: 0;
	    padding: 0; }
	  .timeline-centered .timeline-item {
	    padding-bottom: 40px;
	    overflow: hidden; }
	  .timeline-centered .timeline-marker {
	    position: absolute;
	    left: 50%;
	    margin-left: -7.5px; }
	  .timeline-centered .timeline-info,
	  .timeline-centered .timeline-content {
	    width: 50%; }
	  .timeline-centered > .timeline-item:nth-child(odd) .timeline-info {
	    float: left;
	    text-align: right;
	    padding-right: 30px; }
	  .timeline-centered > .timeline-item:nth-child(odd) .timeline-content {
	    float: right;
	    text-align: left;
	    padding-left: 30px; }
	  .timeline-centered > .timeline-item:nth-child(even) .timeline-info {
	    float: right;
	    text-align: left;
	    padding-left: 30px; }
	  .timeline-centered > .timeline-item:nth-child(even) .timeline-content {
	    float: left;
	    text-align: right;
	    padding-right: 30px; }
	  .timeline-centered > .timeline-item.period .timeline-content {
	    float: none;
	    padding: 0;
	    width: 100%;
	    text-align: center; }
	  .timeline-centered .timeline-item.period {
	    padding: 50px 0 90px; }
	  .timeline-centered .period .timeline-marker:after {
	    height: 30px;
	    bottom: 0;
	    top: auto; }
	  .timeline-centered .period .timeline-title {
	    left: auto; } }

	/*----------------------------------------------
	        MOD: MARKER OUTLINE
	    ----------------------------------------------*/
	.marker-outline .timeline-marker:before {
	  background: transparent;
	  border-color: #FF6B6B; }

	.marker-outline .timeline-item:hover .timeline-marker:before {
	  background: #FF6B6B; }


	</style>
</head>
<body>
<script src="https://use.typekit.net/bkt6ydm.js"></script>
<script>try{Typekit.load({ async: true });}catch(e){}</script>
<!-- <header class="example-header">
    <h1 class="text-center">About Me</h1>
    <p>I am studying for a Master's degree in the Graduate School of Convergence Science and Technology <a href="http://convergence.snu.ac.kr/main/" target="_blank">(GSCST)</a> from Seoul National University <a href="http://snu.ac.kr/index.html" target="_blank">(SNU)</a>, studying under Joongseek Lee. </p>
</header> -->
 <div class="container-fluid">
    <div class="row example-basic">
            <h1>WORK EXPERIENCE</h1>
        <div class="col-xs-10 col-xs-offset-1 col-sm-8 col-sm-offset-2">
            <ul class="timeline">
                <li class="timeline-item">
                    <div class="timeline-info">
                        <span>March 2019 ~ July 2019</span>
                    </div>
                    <div class="timeline-marker"></div>
                    <div class="timeline-content">
                        <h3 class="timeline-title">Graduate Research Assistant</h3>
                        <p>서울대학교 자유전공학부 수업 조교</p>
                    </div>
                </li>
                <li class="timeline-item">
                    <div class="timeline-info">
                        <span>June 2016 ~ September 2016</span>
                    </div>
                    <div class="timeline-marker"></div>
                    <div class="timeline-content">
                        <h3 class="timeline-title">Internship</h3>
                        <p>서울시청 정보통신보안담당관 정보보안팀
                        	<br>Seoul City Hall Information Protection Team</p>
                    </div>
                </li>
            </ul>
        </div>
    </div>
</div>
</body>
</html>




{% include group-by-array collection=site.posts field="categories" %}
{% for category in group_names %}
  {% assign posts = group_items[forloop.index0] %}
  <h2 id="{{ category | slugify }}" class="archive__subtitle">{{ category }}</h2>
  {% for post in posts %}
    {% include archive-single.html %}
  {% endfor %}
{% endfor %}

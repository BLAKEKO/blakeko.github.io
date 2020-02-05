---
layout: archive
permalink: /about/
title: "ABOUT"
author_profile: true
---

I am studying for a Master's degree in the Graduate School of Convergence Science and Technology [(GSCST)](http://convergence.snu.ac.kr/main/) from Seoul National University [(SNU)](http://snu.ac.kr/index.html), studying under Joongseek Lee.

---
<div class="col">
<div class="row">
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
</div>
<div class="row">
    <h1><span data-i18n="skills.my_skills">Bio</span></h1>
	<div class="archive">
		<div class="timeline" id="timeline">
			<div class="archive-title">
				<div class="archive-year"><strong style="margin-right: 2px;">March 2019 &ndash; July 2019<i class="fa fa-clock-o" aria-hidden="true" title="Until Now"></i></strong> Graduate Research Assistant @ <a href="http://ux.snu.ac.kr/" target="_blank">User eXperience Lab at Seoul National University</a></div>
			</div>
			<div class="archive-title">
				<div class="archive-year"><strong style="margin-right: 2px;">June 2016 &ndash; September 2016</strong> Internship @ <a href="http://www.redwood-inc.com/" target="_blank">Seoul City Hall Information and Communication Security Officer Information Protection Team</a></div>
			</div>
		</div>
	</div>
</div>
<div class="row">
<div class="navy-line"></div>
<h1><span data-i18n="skills.my_skills">Education</span></h1>
	<div class="archive">
		<div class="timeline" id="timeline">
			<div class="archive-title bio">
				<div class="archive-year"><strong style="margin-right: 2px;">2018 &ndash; <i class="fa fa-clock-o" aria-hidden="true" title="Until Now"></i></strong> <a href="http://www.snu.ac.kr/">  Seoul National University</a></div>
			</div>
			<div class="archive-title bio">
				<div class="archive-year"><strong style="margin-right: 2px;">2012 &ndash; 2018</strong> <a href="http://www.hanyang.ac.kr/">Hanyang University</a></div>
			</div>
			<div class="archive-title bio">
				<div class="archive-year"><strong style="margin-right: 2px;">2016 &ndash; 2017</strong> <a href="https://h-da.com/">Darmstadt University of Applied Sciences</a></div>
			</div>
			<div class="archive-title bio">
				<div class="archive-year"><strong style="margin-right: 2px;">2007 &ndash; 2010</strong> <a href="http://djflhs.djsch.kr/main.do">Daejeon Foreign Language High School</a></div>
			</div>
		</div>
	</div>
</div>
</div>

<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<style>
* {
  box-sizing: border-box;
}

body {
  background-color: #ffffff;
  font-family: Helvetica, sans-serif;
}

/* The actual timeline (the vertical ruler) */
.timeline {
  position: relative;
  max-width: 1200px;
  margin: 0 auto;
}

/* The actual timeline (the vertical ruler) */
.timeline::after {
  content: '';
  position: absolute;
  width: 6px;
  background-color: black;
  top: 0;
  bottom: 0;
  left: 50%;
  margin-left: -3px;
}

/* Container around content */
.container {
  padding: 10px 40px;
  position: relative;
  background-color: inherit;
  width: 50%;
}

/* The circles on the timeline */
.container::after {
  content: '';
  position: absolute;
  width: 25px;
  height: 25px;
  right: -17px;
  background-color: white;
  border: 4px solid #FF9F55;
  top: 15px;
  border-radius: 50%;
  z-index: 1;
}

/* Place the container to the left */
.left {
  left: 0;
}

/* Place the container to the right */
.right {
  left: 50%;
}

/* Add arrows to the left container (pointing right) */
.left::before {
  content: " ";
  height: 0;
  position: absolute;
  top: 22px;
  width: 0;
  z-index: 1;
  right: 30px;
  border: medium solid white;
  border-width: 10px 0 10px 10px;
  border-color: transparent transparent transparent white;
}

/* Add arrows to the right container (pointing left) */
.right::before {
  content: " ";
  height: 0;
  position: absolute;
  top: 22px;
  width: 0;
  z-index: 1;
  left: 30px;
  border: medium solid white;
  border-width: 10px 10px 10px 0;
  border-color: transparent white transparent transparent;
}

/* Fix the circle for containers on the right side */
.right::after {
  left: -16px;
}

/* The actual content */
.content {
  padding: 20px 30px;
  background-color: white;
  position: relative;
  border-radius: 6px;
}

/* Media queries - Responsive timeline on screens less than 600px wide */
@media screen and (max-width: 600px) {
  /* Place the timelime to the left */
  .timeline::after {
  left: 31px;
  }
  
  /* Full-width containers */
  .container {
  width: 100%;
  padding-left: 70px;
  padding-right: 25px;
  }
  
  /* Make sure that all arrows are pointing leftwards */
  .container::before {
  left: 60px;
  border: medium solid white;
  border-width: 10px 10px 10px 0;
  border-color: transparent white transparent transparent;
  }

  /* Make sure all circles are at the same spot */
  .left::after, .right::after {
  left: 15px;
  }
  
  /* Make all right containers behave like the left ones */
  .right {
  left: 0%;
  }
}
</style>
</head>
<body>

<div class="timeline">
  <div class="container left">
    <div class="content">
      <h2>2017</h2>
      <p>Lorem ipsum dolor sit amet, quo ei simul congue exerci, ad nec admodum perfecto mnesarchum, vim ea mazim fierent detracto. Ea quis iuvaret expetendis his, te elit voluptua dignissim per, habeo iusto primis ea eam.</p>
    </div>
  </div>
  <div class="container right">
    <div class="content">
      <h2>2016</h2>
      <p>Lorem ipsum dolor sit amet, quo ei simul congue exerci, ad nec admodum perfecto mnesarchum, vim ea mazim fierent detracto. Ea quis iuvaret expetendis his, te elit voluptua dignissim per, habeo iusto primis ea eam.</p>
    </div>
  </div>
  <div class="container left">
    <div class="content">
      <h2>2015</h2>
      <p>Lorem ipsum dolor sit amet, quo ei simul congue exerci, ad nec admodum perfecto mnesarchum, vim ea mazim fierent detracto. Ea quis iuvaret expetendis his, te elit voluptua dignissim per, habeo iusto primis ea eam.</p>
    </div>
  </div>
  <div class="container right">
    <div class="content">
      <h2>2012</h2>
      <p>Lorem ipsum dolor sit amet, quo ei simul congue exerci, ad nec admodum perfecto mnesarchum, vim ea mazim fierent detracto. Ea quis iuvaret expetendis his, te elit voluptua dignissim per, habeo iusto primis ea eam.</p>
    </div>
  </div>
  <div class="container left">
    <div class="content">
      <h2>2011</h2>
      <p>Lorem ipsum dolor sit amet, quo ei simul congue exerci, ad nec admodum perfecto mnesarchum, vim ea mazim fierent detracto. Ea quis iuvaret expetendis his, te elit voluptua dignissim per, habeo iusto primis ea eam.</p>
    </div>
  </div>
  <div class="container right">
    <div class="content">
      <h2>2007</h2>
      <p>Lorem ipsum dolor sit amet, quo ei simul congue exerci, ad nec admodum perfecto mnesarchum, vim ea mazim fierent detracto. Ea quis iuvaret expetendis his, te elit voluptua dignissim per, habeo iusto primis ea eam.</p>
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

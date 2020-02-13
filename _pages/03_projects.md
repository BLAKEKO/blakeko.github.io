---
layout: archive
permalink: /projects/
title: "PROJECTS"
author_profile: true
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
		    height: 8px;
		    position: absolute;
		    top: 4px;
		    left: 0;
		    width: 8px;
		    transition: background 0.2s ease-in-out, border 0.2s ease-in-out; }
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

<div class="col">
<div class="container-fluid">
    <div class="row example-basic">
    	<div class="row example-basic">
        <div class="col-xs-10 col-xs-offset-1 col-sm-8 col-sm-offset-2">
            <ul class="timeline">
                <li class="timeline-item">
                    <div class="timeline-info">
                        <span>Jenuary 2019 ~ December 2019</span>
                    </div>
                    <div class="timeline-marker"></div>
                    <div class="timeline-content">
                        <h3 class="timeline-title"> Designing Interactive Contents on Smart Speaker<br>공공 문화/예술/관광 콘텐츠 서비스를 위한 챗봇 프레임워크 개발</h3>
                        <img src="/assets/images/2.png">
                        <p>- Project with <b>Korea Creative Content Agency, KOCCA</b>
                        <br>- My Role : Main Developer, Research Assistant
                        <br>Developing a smart speaker service that curates classical music, named Classic Mate(CM). Each day one pair of classical musics are provided with simple explanations based on user's response. </p>
                    </div>
                </li>
                <li class="timeline-item">
                    <div class="timeline-info">
                        <span>September 2018 ~ December 2018</span>
                    </div>
                    <div class="timeline-marker"></div>
                    <div class="timeline-content">
                        <h3 class="timeline-title"> Next step for Conversational Agents <br> Bixby, Next step에 대한 고민 :UX관점에서</h3>
                        <img src="/assets/images/bixby.png">
                        <p>- Project with <b>Samsung Electronics</b>
                        <br>- My Role : Research Assistant</p>
                        <!-- <p>머신 러닝의 고도화와 스마트 스피커의 보급으로 IPA는 사람들의 일상 곳곳에서 나타나고 있다. 그러나, 단순히 흥미롭고 신기한 이유로 IPA를 사용하는 단계를 지나 지속적으로 이를 사용하기에는 아직 기술이 뒷받침해주지 못하는 실정이다.이에 기업에서는 유명 연예인의 목소리를 통해 사용자에게 친근감을 준다거나 귀여운 외형으로 호감을 불러일으키는 등의 ‘인간적인 호감을 얻을 수 있는’ 접근을 취하고 있다. 본 프로젝트는 현재의 접근 방향의 한계를 지적하고, 비기술적인 측면에서 사용자의 경험을 극대화하여 IPA가 발전할 수 있는 방향을 모색한다.</p> -->
                    </div>
                </li>
                <li class="timeline-item">
                    <div class="timeline-info">
                        <span>May 2018 ~ September 2018</span>
                    </div>
                    <div class="timeline-marker"></div>
                    <div class="timeline-content">
                        <h3 class="timeline-title"> Culture Concierge & Preference Collection<br>공공 문화/예술/관광 콘텐츠 서비스를 위한 챗봇 프레임워크 개발</h3>
                        <img src="/assets/images/1.png">
                        <p>- Project with <b>Korea Creative Content Agency, KOCCA</b>
                        <br>- My Role : Research Assistant
                        <br>Developing a smart speaker service that curates events in various domains such as, but not limited to, classical music, musicals, plays, and concerts. Investigating the potential use of user preference data on various everyday objects to supplement the recommendation of cultural events.</p>
                        <!-- 문화콘텐츠진흥원이 공모한 프로젝트로, 서울대학교 사용자경험연구실이 주관하며 공동연구기관 머니브레인과 위탁연구기관 크레디아와 함께 진행중인 3개년도 프로젝트. 기존 공연 관람은 탐색이 어렵고 복잡한 카탈로그 브라우징이었다. 그러나 이제는 CAs를 통해 정보의 통합/추천/개인화가 가능해졌다. 이를 구현하기 위해 문화 도메인 특성을 고려한 시나리오 도출 및 엔진 개발을 하고자 한다.</p> -->
                    </div>
                </li>
                <li class="timeline-item">
                    <div class="timeline-info">
                        <span>March 2018 ~ May 2018</span>
                    </div>
                    <div class="timeline-marker"></div>
                    <div class="timeline-content">
                        <h3 class="timeline-title"> Designing Home Entertainment AI Service Concept <br>공간 특화 Home Entertainment AI 컨셉 발굴</h3>
                        <img src="/assets/images/LG.png">
                        <p>- Project with <b>LG Electronics</b>
                        <br>- My Role : Research Assistant</p>
                        <!-- <p>Home Entertainment(HE) 기기 확산에 따른 새로운 카테고리의 서비스 및 폼팩터 발굴이 필요하다. 주거 공간마다 상이한 콘텐츠를 소비하는 사용자 행태에 맞게 공간 특화 서비스 제작이 필요한 것이다. 인공지능 서비스의 지향점은 Data Intelligence를 통한 예측력의 구축하는 것이다.</p> -->
                    </div>
                </li>
            </ul>
        </div>
        <div class="col-xs-10 col-xs-offset-1 col-sm-8 col-sm-offset-2">
        	<h1>PUBLICATION</h1>
            <ul class="timeline">
                <li class="timeline-item">
                    <div class="timeline-info">
                        <span>February 2020</span>
                    </div>
                    <div class="timeline-marker"></div>
                    <div class="timeline-content">
                        <h3 class="timeline-title">How do users react to interactive contents on smart speaker?</h3>
                        <p><b>Byunghi Ko</b>, Jeongbok Lee, Soomin Lee, Joongseek Lee</p>
                        <p><i>In Proc. of the HCIK ’20: Human Computer Interaction Korea. 2020.</i></p>
                    </div>
                </li>
            </ul>
        </div>
        </div>
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
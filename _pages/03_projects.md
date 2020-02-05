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
</html>
<div class="row">
    <div class="col">
            <h1><span data-i18n="skills.my_skills">Projects</span></h1>
		<div class="row" style="margin-bottom: 20px">
            <div class="col">
                <h4 style="margin: 0">Culture Concierge & Preference Collection</h4>
                <p style="margin: 0; font-style: italic;">Project with the Korea Creative Contents Agency, May. 2018 &ndash; Current</p>
                <p style="margin: 5px 0 0 0">: Developing a smart speaker service that curates events in various domains such as, but not limited to, classical music, musicals, plays, and concerts. Investigating the potential use of user preference data on various everyday objects to supplement the recommendation of cultural events.</p>
            </div>
        </div>
		<div class="row" style="margin-bottom: 20px">
        	<div class="col">
            <h4 style="margin: 0">Television Audio Experience</h4>
            <p style="margin: 0; font-style: italic;">Project with Samsung Electronics, Mar. 2017 &ndash; Dec. 2017</p>
            <p style="margin: 5px 0 0 0">: A data-driven investigation focused on user behaviors and satisfaction points during television watching. Data collected from the TV, remote controller, and bluetooth trackers are supplemented by qualitative user data collected via event-timely chatbots.</p>
        	</div>
        </div>
		<div class="row" style="margin-bottom: 20px">
        	<div class="col">
            <h4 style="margin: 0">News Big Data - User Participatory Services</h4>
            <p style="margin: 0; font-style: italic;">Project with the Korea Press Foundation, May 2016 &ndash; Dec. 2016</p>
            <p style="margin: 5px 0 0 0">: Analysis of news quotes from press releases, understanding how users obtain news and information, and suggesting a new interface and service where users can easily participate in writing well-founded news articles with official quotes and sources.</p>
        	</div>
        </div>
    </div>
    <div class="col">
        <h1><span data-i18n="skills.my_skills">Publications</span></h1>
		<div class="row" style="margin-bottom: 20px">
	    	<div class="col">
	            <p style="margin: 0;">Minjoon Kim, Jinyoung Kim, Sugyo Han, Joongseek Lee (2018)</p>
	            <p style="margin: 0; font-weight: 700;">A Data-driven Approach to Explore Television Viewing in the Household Environment</p>
	            <p style="margin: 0;">Proceedings of the 2018 ACM International Conference on Interactive Experiences for TV and Online Video (TVX ’18)</p> <a href="https://dl.acm.org/citation.cfm?id=3210829 " target="_blank"><i class="fa fa-external-link-square"></i>  [URL]</a>
	         </div>
	    </div>
    	<div class="row" style="margin-bottom: 20px">
            <div class="col">
                <p style="margin: 0;">Minjoon Kim, Nuri Na, Joongseek Lee (2017)</p>
                <p style="margin: 0; font-weight: 700;">Re-intermediation in the Fashion Industry: A Qualitative Study on Brokers in the Dongdae-mun Fashion District</p>
                <p style="margin: 0;">In iConference 2017 Proceedings, Vol. 2 (pp. 43 &ndash; 53)</p>
                <p style="margin: 0; color: #8C7FD8; font-weight: 700;">Lee Dirks Award for Best Paper Nomination (top 5 papers)</p><a href="https://www.ideals.illinois.edu/handle/2142/98871 " target="_blank"><i class="fa fa-external-link-square"></i>  [URL]</a>
            </div>
   		</div>
	</div>
</div>

**공간 특화 Home Entertainment AI 컨셉 발굴** 

Home Entertainment(HE) 기기 확산에 따른 새로운 카테고리의 서비스 및 폼팩터 발굴이 필요하다.
주거 공간마다 상이한 콘텐츠를 소비하는 사용자 행태에 맞게 공간 특화 서비스 제작이 필요한 것이다.
인공지능 서비스의 지향점은 Data Intelligence를 통한 예측력의 구축하는 것이다.

* 참여 기간: 2018.03 - 2018.05<br> 
* 주최 기관: LG HE 디자인 연구소<br>

---

**공공 문화/예술/관광 콘텐츠 서비스를 위한 챗봇 프레임워크 개발(1)**

문화콘텐츠진흥원이 공모한 프로젝트로, 서울대학교 사용자경험연구실이 주관하며 공동연구기관 머니브레인과 위탁연구기관 크레디아와 함께 진행중인 3개년도 프로젝트. 기존 공연 관람은 탐색이 어렵고 복잡한 카탈로그 브라우징이었다. 그러나 이제는 CAs를 통해 정보의 통합/추천/개인화가 가능해졌다. 이를 구현하기 위해 문화 도메인 특성을 고려한 시나리오 도출 및 엔진 개발을 하고자 한다.

* 참여 기간: 2018.05 - 2018.09<br>
* 주최 기관: 한국콘텐츠진흥원<br>  

---

**Bixby, Next step에 대한 고민 :UX관점에서**

머신 러닝의 고도화와 스마트 스피커의 보급으로 IPA는 사람들의 일상 곳곳에서 나타나고 있다. 그러나, 단순히 흥미롭고 신기한 이유로 IPA를 사용하는 단계를 지나 지속적으로 이를 사용하기에는 아직 기술이 뒷받침해주지 못하는 실정이다.
이에 기업에서는 유명 연예인의 목소리를 통해 사용자에게 친근감을 준다거나 귀여운 외형으로 호감을 불러일으키는 등의 ‘인간적인 호감을 얻을 수 있는’ 접근을 취하고 있다. 본 프로젝트는 현재의 접근 방향의 한계를 지적하고, 비기술적인 측면에서 사용자의 경험을 극대화하여 IPA가 발전할 수 있는 방향을 모색한다.

* 참여 기간: 2018.09 - 2018.12<br> 
* 주최 기관: 삼성전자 디자인경영센터<br>

---

**공공 문화/예술/관광 콘텐츠 서비스를 위한 챗봇 프레임워크 개발(2)**


* 참여 기간: 2019.01 - 2019.12<br> 
* 주최 기관: 한국콘텐츠진흥원<br> 

---

{% include group-by-array collection=site.posts field="categories" %}
{% for category in group_names %}
  {% assign posts = group_items[forloop.index0] %}
  <h2 id="{{ category | slugify }}" class="archive__subtitle">{{ category }}</h2>
  {% for post in posts %}
    {% include archive-single.html %}
  {% endfor %}
{% endfor %}
---
layout: archive
permalink: /projects/
title: "PROJECTS"
author_profile: true
---

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
  background-color: #70cc73;
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
  border: 4px solid #0d703c;
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
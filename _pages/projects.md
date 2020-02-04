---
layout: archive
permalink: /projects/
title: "projects"
author_profile: true
---

**랜덤 추천받기**

스테이지에 상관없이 새로운 음악이 듣고 싶을 때는 “Ok Google, 클래식 메이트한테 랜덤추천받기”라고 말해보세요. 오늘의 음악을 듣다가도 "Ok Google, 랜덤곡 들려줘"라고 하시면 새로운 음악을 소개해드린답니다!

---

**루틴 설정하기**

구글홈 루틴 설정을 이용하시면 정해진 시간에 클래식 메이트가 찾아와요!


---

**클래식 메이트의 공연 추천**

음악 감상이 끝나고 클래식 메이트가 공연 추천을 해주기도 한답니다. 깜짝 선물처럼 찾아오는 공연 추천을 놓치지 마세요!
아래 올해의 추천 공연도 확인해보세요!

**10월**

* 2019년 10월 15일<br>
[제 16회 차이콥스키 콩쿠르 우승자 갈라콘서트](http://www.clubbalcony.com/home/library/leaflet_list.aspx?Mode=r&mid=8&pid=&bid=38926&Se=TITLE&Sestr=&page=1)

{% assign postsByYear = site.posts | group_by_exp:"post", "post.date | date: '%Y'"  %}
{% for year in postsByYear %}
  <h2 id="{{ year.name | slugify }}" class="archive__subtitle">{{ year.name }}</h2>
  {% for post in year.items %}
    {% include archive-single.html %}
  {% endfor %}
{% endfor %}
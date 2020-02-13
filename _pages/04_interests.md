---
layout: archive
permalink: /interests/
title: "INTERESTS"
author_profile: true
---

 <div id="gallery_layout">
        <div class="gallery_content">
            <img src="img/travel_img.jpg" alt="travel_img">
            <div class="content">
                <h1>travel</h1>
                <p>도전하지 않으면, 아무것도 얻을 수 없다.</p>
            </div>
            <div class="overlay darkBlue"></div>
        </div>
        <div class="gallery_content top">
            <img src="img/travel_img2.jpg" alt="여행이미지2">
            <div class="content">
                <h1>travel</h1>
                <p>여행은 언제나 돈의 문제가 아니고 용기의 문제다.</p>
            </div>
            <div class="overlay red"></div>
        </div>
        <div class="gallery_content">
            <img src="img/travel_img3.jpg" alt="여행이미지3">
            <div class="content">
                <h1>travel</h1>
                <p>여행은 정신을 다시 젊어지게 하는 샘이다.</p>
            </div>
            <div class="overlay pink"></div>
        </div>
        <div class="gallery_content">
            <img src="img/travel_img4.jpg" alt="여행이미지4">
            <div class="content">
                <h1>travel</h1>
                <p>여행과 변화를 사랑하는 사람은 생명을 가진 사람이다.</p>
            </div>
            <div class="overlay black"></div>
        </div>
        <div class="gallery_content">
            <img src="img/travel_img5.jpg" alt="여행이미지5">
            <div class="content">
                <h1>travel</h1>
                <p>바보는 방황을 하고 현명한 사람은 여행을 한다.</p>
            </div>
            <div class="overlay yellow"></div>
        </div>
        <div class="gallery_content">
            <img src="img/travel_img6.jpg" alt="여행이미지6">
            <div class="content">
                <h1>travel</h1>
                <p>낯선 땅이란 없다.</p>
                <p>단지 여행자가 낯설 뿐이다.</p>
            </div>
            <div class="overlay gold"></div>
        </div>
    </div>

@import url(https://cdn.rawgit.com/openhiun/hangul/14c0f6faa2941116bb53001d6a7dcd5e82300c3f/nanumbarungothic.css); 

    * {
        -webkit-box-sizing: border-box;
        box-sizing: border-box;
        margin: 0;
        padding: 0;
    }

    body {
        background-image:url("../img/cover/back_dot.jpg");
        font-family: "Nanum Barun Gothic", "Ubuntu Condensed", "Noto Sans Korean";;
    }
    .gallery_content:hover .overlay.right {
        top: 0;
    }

    #gallery_layout {
        width: 960px;
        margin: 0 auto;
    }

    #gallery_layout:after {
        content: "";
        display: block;
        clear: both;
    }

    .gallery_content {
        position: relative;
        float: left;
        width: 33.3333333%;
        overflow: hidden;
    }

    .gallery_content img {
        width: 100%;
        height: 300px;
        display: block;
        margin: 0 auto;
        transition: all 1s ease-in-out;
    }

    .content {
        z-index: 1;
        display: none;
        color: #fff;
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
    }
    
    .content h1 {
        font-size: 1.2em;
        text-transform: uppercase;
        text-align: center;
    }
    .content p {
        padding: 2px 0;
        font-size: 0.8em;
        text-align: center;
    }        
    .gallery_content:hover .content {
        display: block;
        transition: all 1s ease-in-out;
    }

    .gallery_content:hover img {
        transform: scale(1.2);
        transition: all 1s ease-in-out;
    }

    .overlay {
        display: none;
        width: 100%;
        height: 100%;
        position: absolute;
        top: 0;
        left: 0;
        right: 0;
        bottom: 0;
        transition: top 0.3s, right 0.3s, bottom 0.3s, left 0.3s;
    }

    /* overlay color */
    .overlay.darkBlue {
        background-color:rgba(31, 50, 99, 0.6);
    }
    .overlay.gold {
        background-color:rgba(216, 177, 126, 0.5);
    }  
    .overlay.pink {
        background-color:rgba(255, 113, 181, 0.7);
    }  
    .overlay.black {
        background-color: rgba(0, 0, 0, 0.5);
    }  
    .overlay.yellow {
        background-color: rgba(103, 58, 183, 0.5);
    }
    .overlay.red {
        background-color: rgba(244, 67, 54, 0.5);
    }      

    .gallery_content:hover .overlay {
        display: block;
        transition: all 0.5s ease-in-out;
    }
    
    @media all and (min-width: 960px) {
        #gallery_layout {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
        }  
    }

    @media all and (max-width: 959px) {
    #gallery_layout {
        width: 100%;
    }
    .gallery_content {
        width: 50%;
    }

    }
    @media all and (max-width: 499px) {
    #gallery_layout {
        width: 100%;
    }
    .gallery_content {
        width: 100%;
    }

    }

 @media all and (min-width: 960px) {
            #gallery_layout {
                position: absolute;
                top: 50%;
                left: 50%;
                transform: translate(-50%, -50%);
            }  
        }

        @media all and (max-width: 959px) {
        #gallery_layout {
            width: 100%;
        }
        .gallery_content {
            width: 50%;
        }

        }
        @media all and (max-width: 499px) {
        #gallery_layout {
            width: 100%;
        }
        .gallery_content {
            width: 100%;
        }

        }


{% include group-by-array collection=site.posts field="categories" %}
{% for category in group_names %}
  {% assign posts = group_items[forloop.index0] %}
  <h2 id="{{ category | slugify }}" class="archive__subtitle">{{ category }}</h2>
  {% for post in posts %}
    {% include archive-single.html %}
  {% endfor %}
{% endfor %}

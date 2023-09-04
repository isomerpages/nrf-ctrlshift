---
title: Video Series
permalink: /explore/video-series/
description: ""
---
<style>
	* {
  box-sizing: border-box;
}
	.column {
  float: left;
  width: 30%;
  padding: 8px;
}
	.logos::after {
  content: "";
  clear: both;
  display: table;
}
.video-series {
    width:100%;
	  text-align: center; 
		display: flex;
	margin-bottom: 25px
}
.video-series img {
    max-width:100%;
    height:auto;
}
	.purpose {
    width:30%;
	  text-align: left; 
}
.purpose img {
    max-width:100%;
    height:auto;
}
	.video-series-header-img{
		width: 434px !important;

	
	}
	.desktop-only{
	display: block !important
	}
	.mobile-only{
	display: none !important
	}
	.video-series-header-entries{
	text-align: center;
font-family: Lato,sans-serif;
font-size: 1.25rem;
line-height: 2rem;
	text-align: center
	}
@media only screen and (max-width: 768px) {
    .about {
        width:80%;
				text-align: left
    }
    .about img {
        max-width:100%;
    }
	    .purpose, .mission {
        width:40%;
				text-align: left
    }
    .purpose img, .mission img{
        max-width:100%;
    }
	 .column{
        width:30%;
				text-align: left
    }
    .column img{
        max-width:100%;
    }
	.video-series-header-img{
		width: 100%
	}
	.video-series-header-entries{
	font-weight: 800;
	text-align: left
	}
	.desktop-only{
	display: none !important
	}
	.mobile-only{
	display: block !important
	}
}
</style>
<style>
	@keyframes tonext {
  75% {
    left: 0;
  }
  95% {
    left: 100%;
  }
  98% {
    left: 100%;
  }
  99% {
    left: 0;
  }
}

@keyframes tostart {
  75% {
    left: 0;
  }
  95% {
    left: -300%;
  }
  98% {
    left: -300%;
  }
  99% {
    left: 0;
  }
}

@keyframes snap {
  96% {
    scroll-snap-align: center;
  }
  97% {
    scroll-snap-align: none;
  }
  99% {
    scroll-snap-align: none;
  }
  100% {
    scroll-snap-align: center;
  }
}


* {
  box-sizing: border-box;
  scrollbar-color: transparent transparent; /* thumb and track color */
  scrollbar-width: 0px;
}

*::-webkit-scrollbar {
  width: 0;
}

*::-webkit-scrollbar-track {
  background: transparent;
}

*::-webkit-scrollbar-thumb {
  background: transparent;
  border: none;
}

* {
  -ms-overflow-style: none;
}

ol, li {
  list-style: none;
  margin: 0;
  padding: 0;
}

.carousel {
  position: relative;
  padding-top: 75%;
	padding-bottom: 250px;
  filter: drop-shadow(0 0 10px #0003);
  perspective: 100px;
}

.carousel__viewport {
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  display: flex;
  overflow-x: scroll;
  counter-reset: item;
  scroll-behavior: smooth;
  scroll-snap-type: x mandatory;
	margin-top: 40px !important;
	margin-left: 0 !important;
}

.carousel__slide {
  position: relative;
  flex: 0 0 100%;
  width: 100%;

}

.carousel__slide:nth-child(even) {

}

.carousel__slide:before {
  content: counter(item);
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate3d(-50%,-40%,70px);
  color: #fff;
  font-size: 2em;
}

.carousel__snapper {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  scroll-snap-align: center;
	margin-top: 50px
}

@media (hover: hover) {
  .carousel__snapper {
    animation-name: tonext, snap;
    animation-timing-function: ease;
    animation-duration: 40000000s;
    animation-iteration-count: infinite;
  }

  .carousel__slide:last-child .carousel__snapper {
    animation-name: tostart, snap;
  }
}

@media (prefers-reduced-motion: reduce) {
  .carousel__snapper {
    animation-name: none;
  }
}

.carousel:hover .carousel__snapper,
.carousel:focus-within .carousel__snapper {
  animation-name: none;
}

.carousel__navigation {
  position: absolute;
  right: 0;
  bottom: 0;
  left: 0;
  text-align: center;
}

.carousel__navigation-list,
.carousel__navigation-item {
  display: inline-block;
 margin-left: 0 !important;
}

.carousel__navigation-button {
  display: inline-block;
  width: 1.5rem;
  height: 1.5rem;
  background-color: #333;
  background-clip: content-box;
  border: 0.25rem solid transparent;
  border-radius: 50%;
  font-size: 0;
  transition: transform 0.1s;
}


.carousel__prev,
.carousel__next {
  position: absolute;
  top: 0;
  margin-top: 37.5%;
  width: 4rem;
  height: 4rem;
  transform: translateY(-50%);
  border-radius: 50%;
  font-size: 0;
  outline: 0;
}

.carousel::before,
.carousel__prev {
  left: -1rem;
}

.carousel::after,
.carousel__next {
  right: -1rem;
}

.carousel::before,
.carousel::after {
  content: '';
  z-index: 1;
  background-color: #333;
  background-size: 1.5rem 1.5rem;
  background-repeat: no-repeat;
  background-position: center center;
  color: #fff;
  font-size: 2.5rem;
  line-height: 4rem;
  text-align: center;
  pointer-events: none;
}

.carousel::before {
  background-image: url("data:image/svg+xml,%3Csvg viewBox='0 0 100 100' xmlns='http://www.w3.org/2000/svg'%3E%3Cpolygon points='0,50 80,100 80,0' fill='%23fff'/%3E%3C/svg%3E");
}

.carousel::after {
  background-image: url("data:image/svg+xml,%3Csvg viewBox='0 0 100 100' xmlns='http://www.w3.org/2000/svg'%3E%3Cpolygon points='100,50 20,100 20,0' fill='%23fff'/%3E%3C/svg%3E");
}
	.content ol{
	width: 100%
	}
.content ol>li.carousel\_\_navigation-item{
	width: 24% !important;
	}
	.content ol.carousel\_\_viewport>li{
	height: 450px
	}
	.carousel__navigation-button{
	width: 100% !important
	}
	.carousel__navigation{
     top: 525px !important;
	}
	.carousel\_\_navigation-list > li img{
	border: 5px solid #fff
	}
	.carousel\_\_navigation-list > li img:focus, .carousel\_\_navigation-list > li img:visited, .carousel\_\_navigation-list > li img:active{
	border: 5px solid #0037cc
	}
	.video-content{
	position: absolute;
	text-align: center;
	top: 490px
	}
	.carousel\_\_viewport{
	overflow-y: visible
	}
	.carousel{
	padding-bottom: 240px
	}
	.video-title{
		font-size: 32px;
	font-weight: 900;
	color: #000
	}
	.video-detail{
		text-align: center;
font-family: Lato,sans-serif;
font-size: 1.25rem;
line-height: 2rem;
	}
	@media only screen and (max-width: 1280px) {
	.carousel{
 padding-bottom: 580px;
	}
	}
@media only screen and (max-width: 768px) {
		.content ol.carousel\_\_viewport>li{
	height: 230px
	}
	.carousel{
 padding-bottom: 690px;
	}
	.carousel\_\_navigation{
 top: 306px !important;
	}
	.video-content{top: 250px}
	.video-detail{text-align: left}
}
	.video-series-header-entries{font-weight: initial }
	</style>
<div class="video-series">
    <img class="desktop-only video-series-header-img" src="https://raw.githubusercontent.com/isomerpages/psd-ste-whats-next/staging/images/Video%20Series/video-series-header.png">
	 <img class="mobile-only video-series-header-img" src="https://raw.githubusercontent.com/isomerpages/psd-ste-whats-next/staging/images/Video%20Series/video-series-header.png">
</div>
<div class="video-series-header-entries">
Organised by the Ministry of Education (MOE), the Engineering and Tech Programme (ETPS) Scholarship is an inaugural scholarship that recognises the academic prowess of 200 pre-university students who possess a firm foundation in mathematics and science, and display an inclination towards practical, cross-disciplinary, and experiential learning.
</div>
<section aria-label="Gallery" class="video-carousel carousel">
  <ol class="carousel__viewport">
    <li class="carousel__slide" tabindex="0" id="carousel__slide1">
      <div class="carousel__snapper"><img style="width: 100px !important; position: absolute; left: 0; top: -50px" src="https://raw.githubusercontent.com/isomerpages/psd-ste-whats-next/staging/images/Video%20Series/new-label.png">
				<iframe allowfullscreen="" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" frameborder="0" title="YouTube video player" src="https://www.youtube.com/embed/RbsmEEuHwuA?si=DQwLkhILu5BglcaG" height="100%" width="100%"></iframe>
				<div class="video-content">
					<p class="video-title">STE+P UP: EPISODE 1 - WHO WILL KEEP US SAFE?</p>
					<p class="video-detail">Drones, germs and petri dishes... oh my!<br><br>In the shadows of our nation's security, lies a league of experts who don't wear capes but perform remarkable feats to protect us all. These unsung heroes, armed with drones, germs, and petri dishes - work tirelessly behind the scenes to keep our country safe.</p>
				</div>
      </div>
    </li>
</ol>
  <!--<aside class="carousel__navigation">
    <ol class="carousel__navigation-list">
      <li class="carousel__navigation-item">
        <a href="#carousel__slide1" class="carousel__navigation-button"><img src="https://raw.githubusercontent.com/isomerpages/psd-ste-whats-next/staging/images/Video%20Series/dummy-vids.jpg"></a>
      </li> </ol>
  </aside>-->
</section>
<img style="width: 80%; margin-top: 30px" class="desktop-only" src="https://raw.githubusercontent.com/isomerpages/psd-ste-whats-next/staging/images/Video%20Series/video-series-footer.png">  
<img style="width: 60%;" class="mobile-only" src="https://raw.githubusercontent.com/isomerpages/psd-ste-whats-next/staging/images/Video%20Series/video-series-footer-mobile.png">
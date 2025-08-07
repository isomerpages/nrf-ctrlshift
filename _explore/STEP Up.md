---
title: STEP Up
permalink: /explore/video-series/
description: Whether it's preventing another outbreak, navigating our urban
  landscape or having enough power to charge your smartphones - there is always
  someone behind it.
variant: markdown
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
	color: #000;
	text-align: center;
	margin-top: 0 !Important
	}
		.video-subtitle{
		font-size: 24px;
	font-weight: 900;
	color: #000;
		text-align: center;
	margin-bottom: 0 !important
	}
	.video-detail{
		text-align: center;
font-family: Lato,sans-serif;
font-size: 1.25rem;
line-height: 2rem;
	}
		.video-series-header-entries{font-weight: initial; margin-bottom: 20px }
	.video-section{border-top: 1px solid #0037CC;margin-top: 80px; padding-top: 20px; position: relative; text-align: center}
	.video-frame{width: 645px; height: 370px; margin-bottom: 30px}
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
		.video-frame{width: 100%; height: 170px; margin-bottom: 15px}
	
	.video-detail{text-align: left}
	.video-title{font-size: 24px; line-height: 30px}
	.video-subtitle{font-size: 16px; line-height: 24px}
}

	</style><div class="video-series"><img alt="step up video series banner" class="desktop-only video-series-header-img" src="/images/video%20series/video-series-header-new-desktop.png"><img alt="step up video series mobile banner" class="mobile-only video-series-header-img" src="/images/video%20series/video-series-header-new-mobile.png">
</div>
<div class="video-series-header-entries">
Whether it's preventing another outbreak, navigating our urban landscape or having enough power to charge your smartphones - there is always someone behind it. STE+P Up uncovers never-seen-before projects and efforts of STE professionals who shape the way we eat, play, and live.
</div><section aria-label="Gallery" class="video-section"><p class="video-subtitle">STE+P UP: EPISODE 1</p><p class="video-title">WHO WILL KEEP US SAFE?</p><iframe allowfullscreen="" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" frameborder="0" title="YouTube video player" src="https://www.youtube.com/embed/S3yRHGlEzqU?si=nku6KCBl0aAQyS03" class="video-frame"></iframe><div class="video-content">
<p class="video-detail">Drones, germs, and petri dishes... oh my!<br><br>In the shadows of our nation's security, lies a league of experts who don't wear capes but perform remarkable feats to protect us all. These unsung heroes, armed with drones, germs, and petri dishes - work tirelessly behind the scenes to keep our country safe.</p></div><section aria-label="Gallery" class="video-section">
			<p class="video-subtitle">STE+P UP: EPISODE 2</p>
  	<p class="video-title">OUR FULLY ELECTRIC VEHICULAR (EV) FUTURE</p>
				<iframe allowfullscreen="" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" frameborder="0" title="YouTube video player" src="https://www.youtube.com/embed/53lWodxrJBc?si=AuvP2cgBku3cJNsm" class="video-frame"></iframe>
				<div class="video-content">
					<p class="video-detail">Keeping your cars running have never been easier. That is if you drive an electric vehicle (EV)!<br><br>Get ready to meet the brilliant minds who orchestrate everything related to ensuring there's enough energy to go around through our electrical grid infrastructure and EV charging ports as we drive down the road to a sustainable future. Find out how they're taking steps to achieve an electric revolution!</p>
				</div><section aria-label="Gallery" class="video-section">
			<p class="video-subtitle">STE+P UP: EPISODE 3</p>
  	<p class="video-title">PEOPLE FOR THE PLANET</p>
				<iframe allowfullscreen="" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" frameborder="0" title="YouTube video player" src="https://www.youtube.com/embed/Adx3Y5FOdlA?si=to-1eZty0p8Y3rkE" class="video-frame"></iframe>
				<div class="video-content">
					<p class="video-detail">We all applaud Singapore's sustainability efforts and here are some of the reasons why.<br><br>Believe it or not, the government is already paving the way for a futuristic landscape with automated cars, robots, and underground infrastructure right beneath our feet. From combating illegal wildlife trade to expanding public infrastructure with underground roads, we meet the visionaries who are shaping Singapore's tomorrow - where innovation and conservation go hand-in-hand.</p>
	</div><section aria-label="Gallery" class="video-section">
		<p class="video-subtitle">STE+P UP: EPISODE 4</p>
  	<p class="video-title">FINDING SPACE IN LIMITED SPACES</p>
				<iframe allowfullscreen="" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" frameborder="0" title="YouTube video player" src="https://www.youtube.com/embed/MXxJWpFraWM?si=hC3HFNMospHPgQw4" class="video-frame"></iframe>
				<div class="video-content">
					<p class="video-detail">As our population steadily grows, so does our quest to source for more spaces on our little red dot!<br><br>Find out how these STE architects redefine convenience and accessibility through meticulous planning when deciding how to optimise urban spaces. In this episode, we uncover how research shares the untold stories of many Singaporeans.</p>
				</div><section aria-label="Gallery" class="video-section"></section>
</section></section></section></section>
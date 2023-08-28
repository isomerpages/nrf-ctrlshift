---
title: Engineering & Tech Programme Scholarship (ETPS)
permalink: /explore/events/etps/
description: ""
third_nav_title: Events
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
		width: 500px !important

	
	}
	.desktop-only{
	display: block !important
	}
	.mobile-only{
	display: none !important
	}
	.etsp-header-entries{
	text-align: center;
font-family: Lato,sans-serif;
font-size: 1.25rem;
line-height: 2rem;
	margin-top: 80px;
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
	top: 590px
	}
	.carousel\_\_viewport{
	overflow-y: visible
	}
	.carousel{
	padding-bottom: 400px
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
	.etsp-header-entries{width: 80%; margin: 50px auto 30px}
	@media only screen and (max-width: 1280px) {
	.carousel{
 padding-bottom: 580px;
	}
	}
@media only screen and (max-width: 768px) {
		.etsp-header-entries{width:100%; margin-left: 0}
		.content ol.carousel\_\_viewport>li{
	height: 230px
	}
	.carousel{
 padding-bottom: 690px;
	}
	.carousel\_\_navigation{
 top: 306px !important;
	}
	.video-content{top: 320px}
}
	.video-series-header-entries{font-weight: auto}
	</style>
<div class="video-series">
    <img class="desktop-only video-series-header-img" src="https://raw.githubusercontent.com/isomerpages/psd-ste-whats-next/staging/images/ETPS/etsp-title-desktop.png">
	 <img class="mobile-only video-series-header-img" src="https://raw.githubusercontent.com/isomerpages/psd-ste-whats-next/staging/images/ETPS/etsp-title-mobile.png">
</div>
 <img width="100%" class="desktop-only" src="https://raw.githubusercontent.com/isomerpages/psd-ste-whats-next/staging/images/ETPS/etsp-image-1-desktop.png">
	 <img width="100%" class="mobile-only" src="https://raw.githubusercontent.com/isomerpages/psd-ste-whats-next/staging/images/ETPS/etsp-image-1-mobile.png">

<div class="etsp-header-entries">
Whether it's preventing another outbreak, navigating our urban landscape or having enough power to charge your smartphones - there is always someone behind it. STE+P Up uncovers never-seen-before projects and efforts of STE professionals who shape the way we eat, play and live.
</div>
<div class="col-lg-12 pb-lg-1 who-says-title">
										   <div style="text-align: center" class="text-center">
										       <h1 style="color: #0037cc; margin-top: 50px" class="title-section text-blue">Inspiring the Next Generation of STE Innovators</h1>
												  </div>
								  </div>
									 <img width="100%" class="desktop-only" src="https://raw.githubusercontent.com/isomerpages/psd-ste-whats-next/staging/images/ETPS/etsp-image-2-desktop.png">
	 <img width="100%" class="mobile-only" src="https://raw.githubusercontent.com/isomerpages/psd-ste-whats-next/staging/images/ETPS/etsp-image-2-mobile.png">
<style>
	.section-1-container{
		margin-top: 80px
	}
	.section-1-row-1{
	margin: 0 36px ;
	display: flex
	}
</style>
<div class="section-1-container">
	<div class="section-1-row-1">
		<div class="section-1-row-1-col-1">
			<img width="100%" class="desktop-only" src="https://raw.githubusercontent.com/isomerpages/psd-ste-whats-next/staging/images/ETPS/etsp-image-3-desktop.png">
		</div>
		<div class="section-1-row-1-col-2">
			<img width="100%" class="desktop-only" src="https://raw.githubusercontent.com/isomerpages/psd-ste-whats-next/staging/images/ETPS/etsp-icon-1-desktop.png">
			<p>From motivating narratives to valuable insights into their work, these stellar STE ambassadors laid the foundation for these outstanding students to explore the limitless prospects of the STE world and how they can be part of the change to better living in Singapore.</p>
		</div>
	</div>
	<div class="section-1-row-2">
		<div class="section-1-row-2-col-1">
			<img width="100%" class="desktop-only" src="https://raw.githubusercontent.com/isomerpages/psd-ste-whats-next/staging/images/ETPS/etsp-icon-2-desktop.png">
			<p>From motivating narratives to valuable insights into their work, these stellar STE ambassadors laid the foundation for these outstanding students to explore the limitless prospects of the STE world and how they can be part of the change to better living in Singapore.</p>
		</div>
		<div class="section-1-row-2-col-2">
			<img width="100%" class="desktop-only" src="https://raw.githubusercontent.com/isomerpages/psd-ste-whats-next/staging/images/ETPS/etsp-image-4-desktop.png">
		</div>
	</div>
</div>
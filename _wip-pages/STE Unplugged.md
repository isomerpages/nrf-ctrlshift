---
title: STE Unplugged
permalink: /wip-pages/ste-unplugged/
variant: markdown
description: ""
---
<style>

.mainContainer {
	margin: 16px;
	display: flex;
	position: relative;
	flex-direction: column;
	}
	
	.contentText{
		padding-bottom:32px;
	}
	
	.catBtn {
	border: 0;
	background-color: transparent;
	display: flex;
	flex-wrap: wrap;
	width: 100%;
	max-width: 800px;
	}
	
	.divWrapper {
	width: 100%;
	max-width: 786px;
	height: 100%;
	max-height: 124px;
	display: flex;
	flex-wrap: wrap;
	}
	
	.frontDiv {
	transition: 0.1s linear;
	height: auto;
	max-height: 124px;
	width: 100%;
	}
	
	.imgFront,
	.imgBack {
	height: 100%;
	width: 100%;
	}
	
	.backDiv {
	position: absolute;
	z-index: -1;
	top: 0px;
	left: 0px;
	transition: 0.1s ease-in-out;
	width: 100%;
	max-width: 813px;
	height: auto;
	max-height: 135px;
	}
	
	.catBtn:active .frontDiv {
	transform: translate(14px, 14px);
	}
	
	.catBtn:active .backDiv {
	opacity: 0;
	}
	
	.desktopBtn {
	display: flex;
	}
	
	.mobileBtn {
	display: none;
	}
	
@media screen and (max-width:860px) {
	
	.catBtn:active .frontDiv {
	transform: translate(10px, 10px);
	}
}
	
@media screen and (max-width:500px) {
	
	.desktopBtn {
	display: none;
	}
	
	.mobileBtn {
	display: flex;
	}
	
	.divWrapper{
	max-width: 79vw;
	}
}
	
@media screen and (max-width:350px) {
	
	.divWrapper{
	max-width: 77vw;
	}
}
	
	a[href$=".pdf"]:before{
	display:none;
	}
	
	a[href$=".pdf"]{
	margin:0;
	}
	
	a{
	color:black!important;
	}
</style>
![](/images/stories/2024%20Stories%20%20%20STE%20Unplugged/CtrlShift_Editorial_Theme1_CoverImage_Website.jpg)

<div class="mainContainer">
	<div class="contentText">
		<p>Remember those brainy innovators from our <a target="_blank" href="https://www.ctrlshift.gov.sg/explore/video-series/">STE+P Up Video Series</a> , guiding you through groundbreaking Public Service projects? Ever wondered how they got to where they are now?</p>
		<p>Discover the inside scoop in STE Unplugged as we blend passion for invention with personal tales, and shine a light on the movers and shakers in our nation's STE scene!</p>
	</div>
	<a target="_blank" href="/files/STE_Unplugged.pdf" class="catBtn desktopBtn">
		<div class="divWrapper">
			<div class="frontDiv">
				<img src="/images/Editorial%20Template/CTA_Btn_X2.png" class="imgFront">
			</div>
			<div class="backDiv">
				<img src="/images/Editorial%20Template/CTA_Vector.png" class="imgBack">
			</div>
		</div>
	</a>
	<a target="_blank" href="/files/STE_Unplugged.pdf" class="catBtn mobileBtn">
		<div class="divWrapper">
			<div class="frontDiv">
				<img src="/images/Editorial%20Template/CTA_Btn_Mobile_X2.png" class="imgFront">
			</div>
			<div class="backDiv">
				<img src="/images/Editorial%20Template/cta_vector_mobile_x2.png" class="imgBack">
			</div>
		</div>
	</a>
</div>
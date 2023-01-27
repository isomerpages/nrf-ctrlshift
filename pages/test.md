---
title: test
permalink: /test/
description: ""
---
![](/images/who%20runs%20the%20world.png)

![](/images/giphy.gif)

<div class="wrap-collabsible">
  <input id="collapsible" class="toggle" type="checkbox" checked>
	<label for="collapsible" class="lbl-toggle">NANYANG POLYTECHNIC</label>
  <div class="collapsible-content">
    <div class="content-inner">
			<p> 6 January 2023 
			<br> 1 - 10pm 
			<br> Beside Food Connect </p>
    </div>
  </div>
</div>

<div class="wrap-collabsible">
	<input id="collapsible-2" class="toggle-2" type="checkbox" checked>
	<label for="collapsible-2" class="lbl-toggle-2">TEMASEK POLYTECHNIC</label>
  <div class="collapsible-content-2">
    <div class="content-inner-2">
			<p> 6 January 2023 
			<br> 2 - 8.30pm
			<br> The Plaza </p>
    </div>
  </div>
</div>

<div class="wrap-collabsible">
	<input id="collapsible-3" class="toggle-3" type="checkbox" checked>
	<label for="collapsible-3" class="lbl-toggle-3">NGEE ANN POLYTECHNIC</label>
  <div class="collapsible-content-3">
    <div class="content-inner-3">
			<p> 7 January 2023 
			<br> 10am - 4pm
			<br>The Atrium</p>
    </div>
  </div>
</div>

<style>
		input[type='checkbox'] { 
			display: none; 
		}
		.wrap-collabsible { 
			margin: 1.2rem 0; 
		} 
		.lbl-toggle, .lbl-toggle-2, .lbl-toggle-3 { 
			display: block; 
			font-weight: bold; 
			font-family: "Din Black"; 
			font-size: 1.5rem; 
			text-transform: uppercase; 
			text-align: center; 
			padding: 1rem; 
			color: #FFFFFF; 
			background: #75D200; 
			cursor: pointer; 
			border-radius: 7px; 
			transition: all 0.25s ease-out; 
		} 
	  .lbl-toggle-2 {
				background: #00C5E4;
	}
	   .lbl-toggle-3 {
				background: #FFD700;
		}
		.lbl-toggle:hover, .lbl-toggle-2:hover, .lbl-toggle-3:hover { 
			color: #FFF; 
		} 
		.lbl-toggle::before, .lbl-toggle-2::before, .lbl-toggle-3::before  { 
			content: ' '; 
			display: inline-block; 
			border-top: 5px solid transparent; 
			border-bottom: 5px solid transparent;
			border-left: 5px solid currentColor; 
			vertical-align: middle; 
			margin-right: .7rem; 
			transform: translateY(-2px); 
			transition: transform .2s ease-out; 
		}
		.toggle:checked + .lbl-toggle::before,  .toggle-2:checked + .lbl-toggle-2::before, .toggle-3:checked + .lbl-toggle-3::before {
			transform: rotate(90deg) translateX(-3px); 
		} 
		.collapsible-content,  .collapsible-content-2, .collapsible-content-3 { 
			max-height: 0px; 
			overflow: hidden;
			transition: max-height .25s ease-in-out; 
		} 
		.toggle:checked + .lbl-toggle + .collapsible-content,  .toggle-2:checked + .lbl-toggle-2 + .collapsible-content-2, .toggle-3:checked + .lbl-toggle-3 + .collapsible-content-3 { 
			max-height: 350px;
		} 
		.toggle:checked+.lbl-toggle { 
			border-bottom-right-radius: 0; 
			border-bottom-left-radius: 0; 
		} 
		.collapsible-content .content-inner, .collapsible-content-2 .content-inner-2, .collapsible-content-3 .content-inner-3 {
			background: #FFFFFF; 
			border-bottom: 1px solid #75D200; 
			border-bottom-left-radius: 7px ; 
			border-bottom-right-radius: 7px; 
	    border-right: 1px solid #75D200; 
			border-left: 1px solid #75D200;
			padding: .5rem 1rem; 
			display: block; 
			font-weight: bold; 
			font-family: "Din Black"; 
			font-size: 1.2rem;  
			text-align: left; 
			padding: 1rem; 
			color: #FFFFFF; 
			background: #75D200; 
		}
		.collapsible-content-2 .content-inner-2 {
				border-bottom: 1px solid  #00C5E4;
				border-right: 1px solid  #00C5E4;
				border-left: 1px solid #00C5E4;
				background: #00C5E4;
		}
			.collapsible-content-3 .content-inner-3 {
				border-bottom: 1px solid  #FFD700;
				border-right: 1px solid  #FFD700;
				border-left: 1px solid #FFD700;
				background: #FFD700;
		}
		.collapsible-content p { 
			margin-bottom: 0;
		}
		.who-says {
			display: block;
			font-weight: bold; 
			font-family: "Din Black"; 
			font-size: 60px;
			text-align: center; 
			padding: 2.5rem; 
			color: #0037CC;
			line-height: 72px; 
	}
	 .container-truck {
        display: flex;
        align-items: center;
        justify-content: center
      }
      img {
        max-width: 100%
      }
      .truck, .challenge {
        flex-basis: 50%
      }
      .about-truck-head, .challenge-head {
			display: block;
			font-weight: bold; 
			font-family: "Din Black"; 
			font-size: 2.5rem;
			text-align: left; 
			padding-left: 2rem; 
			color: #0037CC;
      }
		 .about-truck-para, .challenge-para {
				display: block;
				font-weight: bold; 
				font-family: "Din 2014"; 
				font-size: 1rem;
				line-height: 1;
				text-align: left; 
				padding-left: 2rem; 
				color: #000000;
      }
	.container-challenge {
        display: flex;
        align-items: center;
        justify-content: center
	
</style>

<div class="who-says"> 
	<p>Who says Science+Tech+Engineering has to be boring?</p>
</div>


  <div class="container-truck">
      <div class="truck">
        <img src="https://images.unsplash.com/photo-1600664356348-10686526af4f?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1475&q=80">
      </div>
      <div class="truck">
        <p class="about-truck-head">About our CTRL+SHIFT truck</p>
				<p class="about-truck-para"> Never seen a STE engineered truck before? 
					<br>Now you can. Organised by the Public Sector Science & Technology Policy & Plans Office (S&TPPO) on behalf of the Public Service, CTRL+SHIFT is a rebranding campaign that aims to demystify misconceptions and shift the perspectives of students and influencers alike for the Science, Technology and Engineering (STE) courses/ careers in the public sector. </p>
      </div>
    </div>
		
  <div class="container-challenge">
		<div class="challenge">
					<p class="challenge-head">Up for the challenge? Come find us.</p>
					<p class="challenge-para"> To kickstart our campaign, we will be infiltrating the upcoming polytechnic open houses and university career fairs with our event truck.
						<br> Upon completion of an online survey, students can redeem giveaways such as Bubble Tea or have their pictures taken at the Holographics photo booth by Holograil. </p>
				</div>    
		<div class="challenge">
					<img src="https://images.unsplash.com/photo-1600664356348-10686526af4f?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1475&q=80">
				</div>
    </div>
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="utf-8">
	<title>CSS Zen Garden: The Beauty of CSS Design</title>

	<link rel="stylesheet" media="screen" href="css/style.css">
	<link rel="alternate" type="application/rss+xml" title="RSS" href="http://www.csszengarden.com/zengarden.xml">

	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<meta name="author" content="Dave Shea">
	<meta name="description" content="A demonstration of what can be accomplished visually through CSS-based design.">
	<meta name="robots" content="all">


	<!--[if lt IE 9]>
	<script src="script/html5shiv.js"></script>
	<![endif]-->
</head>

<!--



	View source is a feature, not a bug. Thanks for your curiosity and
	interest in participating!

	Here are the submission guidelines for the new and improved csszengarden.com:

	- CSS3? Of course! Prefix for ALL browsers where necessary.
	- go responsive; test your layout at multiple screen sizes.
	- your browser testing baseline: IE9+, recent Chrome/Firefox/Safari, and iOS/Android
	- Graceful degradation is acceptable, and in fact highly encouraged.
	- use classes for styling. Don't use ids.
	- web fonts are cool, just make sure you have a license to share the files. Hosted 
	  services that are applied via the CSS file (ie. Google Fonts) will work fine, but
	  most that require custom HTML won't. TypeKit is supported, see the readme on this
	  page for usage instructions: https://github.com/mezzoblue/csszengarden.com/

	And a few tips on building your CSS file:

	- use :first-child, :last-child and :nth-child to get at non-classed elements
	- use ::before and ::after to create pseudo-elements for extra styling
	- use multiple background images to apply as many as you need to any element
	- use the Kellum Method for image replacement, if still needed. http://goo.gl/GXxdI
	- don't rely on the extra divs at the bottom. Use ::before and ::after instead.

		
-->

<body id="css-zen-garden">
<div class="page-wrapper">

	<section class="intro" id="zen-intro">
		<header role="banner">
			<h1>CSS Zen Garden</h1>
			<h2>The Beauty of <abbr title="Cascading Style Sheets">CSS</abbr> Design</h2>
		</header>

		<div class="summary" id="zen-summary" role="article">
			<p>A demonstration of what can be accomplished through <abbr title="Cascading Style Sheets">CSS</abbr>-based design. Select any style sheet from the list to load it into this page.</p>
			<p>Download the example <a href="/examples/index" title="This page's source HTML code, not to be modified.">html file</a> and <a href="/examples/style.css" title="This page's sample CSS, the file you may modify.">css file</a></p>
		</div>

		<div class="preamble" id="zen-preamble" role="article">
			<h3>The Road to Enlightenment</h3>
			<p>Littering a dark and dreary road lay the past relics of browser-specific tags, incompatible <abbr title="Document Object Model">DOM</abbr>s, broken <abbr title="Cascading Style Sheets">CSS</abbr> support, and abandoned browsers.</p>
			<p>We must clear the mind of the past. Web enlightenment has been achieved thanks to the tireless efforts of folk like the <abbr title="World Wide Web Consortium">W3C</abbr>, <abbr title="Web Standards Project">WaSP</abbr>, and the major browser creators.</p>
			<p>The CSS Zen Garden invites you to relax and meditate on the important lessons of the masters. Begin to see with clarity. Learn to use the time-honored techniques in new and invigorating fashion. Become one with the web.</p>
		</div>
	</section>

	<div class="main supporting" id="zen-supporting" role="main">
		<div class="explanation" id="zen-explanation" role="article">
			<h3>So What is This About?</h3>
			<p>There is a continuing need to show the power of <abbr title="Cascading Style Sheets">CSS</abbr>. The Zen Garden aims to excite, inspire, and encourage participation. To begin, view some of the existing designs in the list. Clicking on any one will load the style sheet into this very page. The <abbr title="HyperText Markup Language">HTML</abbr> remains the same, the only thing that has changed is the external <abbr title="Cascading Style Sheets">CSS</abbr> file. Yes, really.</p>
			<p><abbr title="Cascading Style Sheets">CSS</abbr> allows complete and total control over the style of a hypertext document. The only way this can be illustrated in a way that gets people excited is by demonstrating what it can truly be, once the reins are placed in the hands of those able to create beauty from structure. Designers and coders alike have contributed to the beauty of the web; we can always push it further.</p>
		</div>

		<div class="participation" id="zen-participation" role="article">
			<h3>Participation</h3>
			<p>Strong visual design has always been our focus. You are modifying this page, so strong <abbr title="Cascading Style Sheets">CSS</abbr> skills are necessary too, but the example files are commented well enough that even <abbr title="Cascading Style Sheets">CSS</abbr> novices can use them as starting points. Please see the <a href="http://www.mezzoblue.com/zengarden/resources/" title="A listing of CSS-related resources"><abbr title="Cascading Style Sheets">CSS</abbr> Resource Guide</a> for advanced tutorials and tips on working with <abbr title="Cascading Style Sheets">CSS</abbr>.</p>
			<p>You may modify the style sheet in any way you wish, but not the <abbr title="HyperText Markup Language">HTML</abbr>. This may seem daunting at first if you&#8217;ve never worked this way before, but follow the listed links to learn more, and use the sample files as a guide.</p>
			<p>Download the sample <a href="/zengarden-sample.html" title="This page's source HTML code, not to be modified.">HTML</a> and <a href="/zengarden-sample.css" title="This page's sample CSS, the file you may modify.">CSS</a> to work on a copy locally. Once you have completed your masterpiece (and please, don&#8217;t submit half-finished work) upload your <abbr title="Cascading Style Sheets">CSS</abbr> file to a web server under your control. <a href="http://www.mezzoblue.com/zengarden/submit/" title="Use the contact form to send us your CSS file">Send us a link</a> to an archive of that file and all associated assets, and if we choose to use it we will download it and place it on our server.</p>
		</div>

		<div class="benefits" id="zen-benefits" role="article">
			<h3>Benefits</h3>
			<p>Why participate? For recognition, inspiration, and a resource we can all refer to showing people how amazing <abbr title="Cascading Style Sheets">CSS</abbr> really can be. This site serves as equal parts inspiration for those working on the web today, learning tool for those who will be tomorrow, and gallery of future techniques we can all look forward to.</p>
		</div>

		<div class="requirements" id="zen-requirements" role="article">
			<h3>Requirements</h3>
			<p>Where possible, we would like to see mostly <abbr title="Cascading Style Sheets, levels 1 and 2">CSS 1 &amp; 2</abbr> usage. <abbr title="Cascading Style Sheets, levels 3 and 4">CSS 3 &amp; 4</abbr> should be limited to widely-supported elements only, or strong fallbacks should be provided. The CSS Zen Garden is about functional, practical <abbr title="Cascading Style Sheets">CSS</abbr> and not the latest bleeding-edge tricks viewable by 2% of the browsing public. The only real requirement we have is that your <abbr title="Cascading Style Sheets">CSS</abbr> validates.</p>
			<p>Luckily, designing this way shows how well various browsers have implemented <abbr title="Cascading Style Sheets">CSS</abbr> by now. When sticking to the guidelines you should see fairly consistent results across most modern browsers. Due to the sheer number of user agents on the web these days &#8212; especially when you factor in mobile &#8212; pixel-perfect layouts may not be possible across every platform. That&#8217;s okay, but do test in as many as you can. Your design should work in at least IE9+ and the latest Chrome, Firefox, iOS and Android browsers (run by over 90% of the population).</p>
			<p>We ask that you submit original artwork. Please respect copyright laws. Please keep objectionable material to a minimum, and try to incorporate unique and interesting visual themes to your work. We&#8217;re well past the point of needing another garden-related design.</p>
			<p>This is a learning exercise as well as a demonstration. You retain full copyright on your graphics (with limited exceptions, see <a href="http://www.mezzoblue.com/zengarden/submit/guidelines/">submission guidelines</a>), but we ask you release your <abbr title="Cascading Style Sheets">CSS</abbr> under a Creative Commons license identical to the <a href="http://creativecommons.org/licenses/by-nc-sa/3.0/" title="View the Zen Garden's license information.">one on this site</a> so that others may learn from your work.</p>
			<p role="contentinfo">By <a href="http://www.mezzoblue.com/">Dave Shea</a>. Bandwidth graciously donated by <a href="http://www.mediatemple.net/">mediatemple</a>. Now available: <a href="http://www.amazon.com/exec/obidos/ASIN/0321303474/mezzoblue-20/">Zen Garden, the book</a>.</p>
		</div>

		<footer>
			<a href="http://validator.w3.org/check/referer" title="Check the validity of this site&#8217;s HTML" class="zen-validate-html">HTML</a>
			<a href="http://jigsaw.w3.org/css-validator/check/referer" title="Check the validity of this site&#8217;s CSS" class="zen-validate-css">CSS</a>
			<a href="http://creativecommons.org/licenses/by-nc-sa/3.0/" title="View the Creative Commons license of this site: Attribution-NonCommercial-ShareAlike." class="zen-license">CC</a>
			<a href="http://mezzoblue.com/zengarden/faq/#aaa" title="Read about the accessibility of this site" class="zen-accessibility">A11y</a>
			<a href="https://github.com/mezzoblue/csszengarden.com" title="Fork this site on Github" class="zen-github">GH</a>
		</footer>

	</div>


	<aside class="sidebar" role="complementary">
		<div class="wrapper">

			<div class="design-selection" id="design-selection">
				<h3 class="select">Select a Design:</h3>
				<nav role="navigation">
					<ul>
					<li>
						<a href="?cssfile=/216/216.css" class="design-name">Fountain Kiss</a> by						<a href="http://jeremycarlson.com" class="designer-name">Jeremy Carlson</a>
					</li>					<li>
						<a href="?cssfile=/215/215.css" class="design-name">A Robot Named Jimmy</a> by						<a href="http://meltmedia.com/" class="designer-name">meltmedia</a>
					</li>					<li>
						<a href="?cssfile=/214/214.css" class="design-name">Verde Moderna</a> by						<a href="http://www.mezzoblue.com/" class="designer-name">Dave Shea</a>
					</li>					<li>
						<a href="?cssfile=/213/213.css" class="design-name">Under the Sea!</a> by						<a href="http://www.ericstoltz.com/" class="designer-name">Eric Stoltz</a>
					</li>					<li>
						<a href="?cssfile=/212/212.css" class="design-name">Make ’em Proud</a> by						<a href="http://skybased.com/" class="designer-name">Michael McAghon and Scotty Reifsnyder</a>
					</li>					<li>
						<a href="?cssfile=/211/211.css" class="design-name">Orchid Beauty</a> by						<a href="#" class="designer-name">Kevin Addison</a>
					</li>					<li>
						<a href="?cssfile=/210/210.css" class="design-name">Oceanscape</a> by						<a href="http://www.pixel-house.com.au/" class="designer-name">Justin Gray</a>
					</li>					<li>
						<a href="?cssfile=/209/209.css" class="design-name">CSS Co., Ltd.</a> by						<a href="http://www.benklemm.de/" class="designer-name">Benjamin Klemm</a>
					</li>					</ul>
				</nav>
			</div>

			<div class="design-archives" id="design-archives">
				<h3 class="archives">Archives:</h3>
				<nav role="navigation">
					<ul>
						<li class="next">
							<a href="?cssfile=/214/214.css&amp;page=1">
								Next Designs <span class="indicator">&rsaquo;</span>
							</a>
						</li>
						<li class="viewall">
							<a href="http://www.mezzoblue.com/zengarden/alldesigns/" title="View every submission to the Zen Garden.">
								View All Designs							</a>
						</li>
					</ul>
				</nav>
			</div>

			<div class="zen-resources" id="zen-resources">
				<h3 class="resources">Resources:</h3>
				<ul>
					<li class="view-css">
						<a href="/214/214.css" title="View the source CSS file of the currently-viewed design.">
							View This Design&#8217;s <abbr title="Cascading Style Sheets">CSS</abbr>						</a>
					</li>
					<li class="css-resources">
						<a href="http://www.mezzoblue.com/zengarden/resources/" title="Links to great sites with information on using CSS.">
							<abbr title="Cascading Style Sheets">CSS</abbr> Resources						</a>
					</li>
					<li class="zen-faq">
						<a href="http://www.mezzoblue.com/zengarden/faq/" title="A list of Frequently Asked Questions about the Zen Garden.">
							<abbr title="Frequently Asked Questions">FAQ</abbr>						</a>
					</li>
					<li class="zen-submit">
						<a href="http://www.mezzoblue.com/zengarden/submit/" title="Send in your own CSS file.">
							Submit a Design						</a>
					</li>
					<li class="zen-translations">
						<a href="http://www.mezzoblue.com/zengarden/translations/" title="View translated versions of this page.">
							Translations						</a>
					</li>
				</ul>
			</div>
		</div>
	</aside>


</div>

<!--

	These superfluous divs/spans were originally provided as catch-alls to add extra imagery.
	These days we have full ::before and ::after support, favour using those instead.
	These only remain for historical design compatibility. They might go away one day.
		
-->
<div class="extra1" role="presentation"></div><div class="extra2" role="presentation"></div><div class="extra3" role="presentation"></div>
<div class="extra4" role="presentation"></div><div class="extra5" role="presentation"></div><div class="extra6" role="presentation"></div>

</body>
</html>

@import url(http://fonts.googleapis.com/css?family=Droid+Sans);
html,body,div,span,applet,object,iframe,h1,h2,h3,h4,h5,h6,p,blockquote,pre,a,abbr,acronym,address,big,cite,code,del,dfn,em,img,ins,kbd,q,s,samp,small,strike,strong,sub,sup,tt,var,b,u,i,center,dl,dt,dd,ol,ul,li,fieldset,form,label,legend,table,caption,tbody,tfoot,thead,tr,th,td,article,aside,canvas,details,embed,figure,figcaption,footer,header,hgroup,menu,nav,output,ruby,section,summary,time,mark,audio,video{margin:0;padding:0;border:0;font-size:100%;font:inherit;vertical-align:baseline}article,aside,details,figcaption,figure,footer,header,hgroup,menu,nav,section{display:block}body{line-height:1}ol,ul{list-style:none}blockquote,q{quotes:none}blockquote:before,blockquote:after,q:before,q:after{content:'';content:none}table{border-collapse:collapse;border-spacing:0}

body{
	font-family: 'Droid Sans', sans-serif;
	font-size: 20px;
	line-height: 1.25;
	font-weight: 300;
	background: rgb(32,33,37) url(../images/background.png) top center;
	color: #ffffff;
}

p, h1, h2, h3{
	margin-bottom: 25px;
}

h1,h2,h3{
	color: #ffffff;
	font-weight: 700;
	text-shadow: 0 3px 3px #000;
}

h1{ font-size: 200%; }
h2{ font-size: 175%; }
h3{ font-size: 150%; }

a{
	color: #df4f56;
	text-decoration: none;
}

	.page-wrapper{
		width: 100%;
		margin: 0 auto;
	}
	
	.intro{
	}
	
	.intro h1{
		position: absolute;
		left: 0;
		width: 100%;
		height: 673px;
		background:  url(../images/header-picture3.png) no-repeat; 
		background-size: cover;
		text-indent: -5000px;
		z-index: 1000;
	}
	
	.intro h2{
		text-align: center;
		position: absolute;
		width: 100%;
		top: -10px;
		z-index: 900;
	}
			.summary p:first-child{
				padding-top: 280px;
				padding-left: 380px;
				font-size: 65%;
				width: 300px;
				margin: 0;
			}
			
			.summary p:last-child{
				margin-left: 380px;
				margin-top: -1px;
				font-size: 65%;
				width: 300px;
				
			}
			
		.preamble h3{
			text-indent: -5000px;
		}
		
		.preamble h3:after{
			content: '';
			background: url(../images/preamble.png);
			display: block;
			width: 462px;
			height: 32px;
			z-index: 1010;
			margin-left: 20px;
		}

		
		.explanation h3{
			text-indent: -5000px;
		}
		
		.explanation h3:after{
			content: '';
			background: url(../images/explanation.png);
			display: block;
			width: 421px;
			height: 36px;
			z-index: 1010;	
			margin-left: 585px;
			margin-top: -371px;
		}
		
		.participation h3{
			text-indent: -5000px;
		}
		
			.participation h3:after{
			content: '';
			background: url(../images/participation.png);
			display: block;
			margin-top: -290px;
			margin-left: 20px;
			width: 219px;
			height: 32px;
			z-index: 1010;	
		}
		
		.benefits h3{
			text-indent: -5000px;
		}
		
			.benefits h3:after{
			content: '';
			background: url(../images/benefits.png);
			display: block;
			width: 130px;
			height: 32px;
			margin-top: -220px;
			margin-left: 20px;
			z-index: 1010;	
		}
		
		.requirements h3{
			text-indent: -5000px;
		}
		
		.requirements h3:after{
			content: '';
			background: url(../images/requirements.png);
			display: block;
			width: 197px;
			height: 32px;
			z-index: 1010;	
			margin-left: 780px;
			margin-top: -220px
		}
		
		aside.sidebar ul li{
			margin-bottom: 6px;
		}
		
		.design-selection{
			margin-left: 220px;
		}
		
		.design-selection h3{
			text-indent: -5000px;
		}
		
			.design-selection h3:after{
			content: '';
			background: url(../images/design.png);
			display: block;
			width: 266px;
			height: 32px;
			z-index: 1010;	
			margin-left: 5px;
			
		}
		
		.design-archives{
			position: static;
			margin-left: 830px;
			margin-top: -335px;
			margin-bottom: 308px;
		} 
		
		.design-archives h3{
			text-indent: -5000px;
		}
		
		.design-archives h3:after{
			content: '';
			background: url(../images/archives.png) no-repeat;
			display: block;
			width: 266px;
			height: 32px;
			z-index: 1010;	
			
		}
		
		.zen-resources{
			position: static;
			margin-left: 830px;
			margin-top: -308px;
			
		} 
		
			.zen-resources h3{
			text-indent: -5000px;
		}
		
			.zen-resources h3:after{
			content: '';
			background: url(../images/resources.png) no-repeat;
			display: block;
			width: 162px;
			height: 32px;
			z-index: 1010;	
			
		}
	
		.preamble p{
			display: block;
			margin-left: 20px;
			width: 462px;
			font-size: 80%;
		}	
		
		
		.explanation p{
			width: 462px;
			font-size: 80%;
			left: 585px;
			top: -300px;
			display: block;
		}
		
		.participation p{
			width: 462px;
			font-size: 80%;
			top: -220px;
			left: 20px;
			display: block
		}
		
		.benefits p{
			width: 462px;
			font-size: 80%;
			top: -150px;
			left: 20px;
			display: block
		}
		
		
		.requirements p{
			display: block;
			top: -150px;
			left: 350px;
			width: 630px;
			font-size: 80%;
			text-align: right;
		}
		
		
		.participation:after{
		content: '';
		background: url(../images/line2.png) no-repeat;
		display: block;
		width: 320px;
		height: 280px;
		position: absolute;
		top: 880px;
		left: 606px;
		z-index: 110;
	}
		
		.requirements:after{
		content: '';
		background: url(../images/big-line.png);
		display: block;
		width: 809px;
		height: 20px;
		position: absolute;
		top: 2070px;
		left: 160px;
		z-index: 100;
	}
		
	footer{
		text-align: center;
		margin-bottom: 20px;
		margin-top: -65px;
		font-size: 125%;
	}	
	
	
	h3, p{
		position: relative;
		z-index: 1000;
	}
	
@media screen and (max-width: 978px){
	.page-wrapper{
		width: 978px;
	}
	
	.intro h1{
		width: 463px;
		height: 76px;
		background: url(../images/CZG.png);
		margin-top: 110px;
		margin-left: 100px;
	}
	
	.intro h2{
		text-indent: -5000px;
	}
	
	.summary{
			width: auto;
			position: static;
			opacity: 1;
			height: auto;
			clear: both;
	}
	
	.intro header:after{
		content: '';
		display: block;
		height: 657px;
		width: 978px;
		background: url(../images/city.png) fixed center center no-repeat;
		background-size: cover;
	}
	
	.intro .summary p{
		background: none;
		text-indent: 0;
		width: 300px;
		height: auto;
		text-align: left;
		margin-top: -745px;
		margin-left: -108px;
		margin-bottom: 20px;
		font-size: 60%;
	}
	
		.summary p:last-child{
				margin-left: 272px;
				margin-top: -21px;
				font-size: 60%;
				width: 300px;
				margin-bottom: -200px;
				
			}
	
	aside.sidebar ul li{
			margin-bottom: 6px;
		}
		
		.design-selection{
			left: -20px;
			font-size: 80%;
			width: 300px;
		}
		
		.design-selection h3{
			text-indent: -5000px;
		}
		
			.design-selection h3:after{
			content: '';
			background: url(../images/design2.png);
			display: block;
			width: 233px;
			height: 28px;
			z-index: 1010;	
			margin-left: -5px;
			
		}
		
		.design-archives{
			position: static;
			margin-left: 600px;
			margin-top: -312px;
			margin-bottom: 308px;
			font-size: 80%;
		} 
		
		.design-archives h3{
			text-indent: -5000px;
		}
		
		.design-archives h3:after{
			content: '';
			background: url(../images/archives2.png) no-repeat;
			display: block;
			width: 128px;
			height: 28px;
			z-index: 1010;
				
			
		}
		
		.zen-resources{
			position: static;
			margin-left: 600px;
			margin-top: -308px;
			font-size: 80%;
			
		} 
		
			.zen-resources h3{
			text-indent: -5000px;
		}
		
			.zen-resources h3:after{
			content: '';
			background: url(../images/resources2.png) no-repeat;
			display: block;
			width: 142px;
			height: 28px;
			z-index: 1010;	
			
		}

	footer{
		text-align: center;
		margin-bottom: 20px;
		margin-top: -65px;
		font-size: 125%;
	}		
	

		.preamble h3{
			text-indent: -5000px;
		}
		
		.preamble h3:after{
			content: '';
			background: url(../images/preamble2.png);
			display: block;
			width: 404px;
			height: 28px;
			margin-left: 20px;
			margin-top: 400px;
			z-index: 1010;
		}

		
		.explanation h3{
			text-indent: -5000px;
		}
		
		.explanation h3:after{
			content: '';
			background: url(../images/explanation2.png);
			display: block;
			width: 327px;
			height: 28px;
			z-index: 1010;	
			margin-left: 535px;
			margin-top: -338px;
		}
		
		.participation h3{
			text-indent: -5000px;
		}
		
			.participation h3:after{
			content: '';
			background: url(../images/participation2.png);
			display: block;
			margin-top: -290px;
			margin-left: 20px;
			width: 192px;
			height: 28px;
			z-index: 1010;	
		}
		
		.benefits h3{
			text-indent: -5000px;
		}
		
			.benefits h3:after{
			content: '';
			background: url(../images/benefits2.png);
			display: block;
			width: 114px;
			height: 28px;
			margin-top: -220px;
			margin-left: 20px;
			z-index: 1010;	
		}
		
		.requirements h3{
			text-indent: -5000px;
		}
		
		.requirements h3:after{
			content: '';
			background: url(../images/requirements2.png);
			display: block;
			width: 172px;
			height: 28px;
			z-index: 1010;	
			margin-left: 620px;
			margin-top: -220px
		}
	
			.preamble p{
			display: block;
			margin-left: 20px;
			width: 400px;
			font-size: 70%;
		}	
		
		
		.explanation p{
			width: 400px;
			font-size: 70%;
			margin-left: -50px;
			top: -285px;
			display: block;
		}
		
		.participation p{
			width: 400px;
			font-size: 70%;
			top: -235px;
			left: 20px;
			display: block
		}
		
		.benefits p{
			width: 400px;
			font-size: 70%;
			top: -150px;
			left: 20px;
			display: block
		}
		
		
		.requirements p{
			display: block;
			top: -150px;
			left: 190px;
			width: 600px;
			font-size: 70%;
			text-align: right;
		} 
		
		.participation:after{
		content: '';
		background: url(../images/line2.png) no-repeat;
		display: block;
		width: 320px;
		height: 280px;
		position: absolute;
		top: 860px;
		left: 546px;
		z-index: 110;
	}
	
	.requirements:after{
		content: '';
		background: url(../images/big-line.png);
		display: block;
		width: 809px;
		height: 20px;
		position: absolute;
		top: 1955px;
		left: 65px;
		z-index: 100;
	}
}

@media screen and (max-width: 748px){
	.page-wrapper{
		width: auto;
		margin: 0 10px;
	}
	
	.intro h1{
		width: 350px;
		height: 57px;
		background: url(../images/CZG2.png);
		margin-top: 100px;
		margin-left: 15px;
	}
	
	.intro h2{
		text-indent: -5000px;
	}
	
	
	.intro header:after{
		content: '';
		display: block;
		height: 657px;
		width: 109%;
		margin-left: -10px;
		background: url(../images/city.png) fixed center center no-repeat;
		background-size:cover;
	}
	
	.intro .summary p{
		background: none;
		text-indent: 0;
		width: 225px;
		height: auto;
		text-align: left;
		margin-top: -775px;
		margin-left: -248px;
		margin-bottom: 20px;
		font-size: 50%;
	}
	
		.summary p:last-child{
				margin-left: 132px;
				margin-top: -20px;
				font-size: 50%;
				width: 225px;
				margin-bottom: -200px;
			}
			
		.preamble h3{
			text-indent: -5000px;
		}
		
		.preamble h3:after{
			content: '';
			background: url(../images/preamble3.png);
			display: block;
			width: 346px;
			height: 24px;
			margin-left: 10px;
			z-index: 1010;
		}

		
		.explanation h3{
			text-indent: -5000px;
		}
		
		.explanation h3:after{
			content: '';
			background: url(../images/explanation3.png);
			display: block;
			width: 292px;
			height: 25px;
			z-index: 1010;	
			margin-left: 10px;
			margin-top: -40px;
		}
		
		.participation h3{
			text-indent: -5000px;
		}
		
			.participation h3:after{
			content: '';
			background: url(../images/participation3.png);
			display: block;
			margin-top: -40px;
			margin-left: 10px;
			width: 171px;
			height: 25px;
			z-index: 1010;	
		}
		
		.benefits h3{
			text-indent: -5000px;
		}
		
			.benefits h3:after{
			content: '';
			background: url(../images/benefits3.png);
			display: block;
			width: 102px;
			height: 25px;
			margin-top: -40px;
			margin-left: 10px;
			z-index: 1010;	
		}
		
		.requirements h3{
			text-indent: -5000px;
		}
		
		.requirements h3:after{
			content: '';
			background: url(../images/requirements3.png);
			display: block;
			width: 154px;
			height: 25px;
			z-index: 1010;	
			margin-left: 10px;
			margin-top: -40px
		}
	
			.preamble p{
			display: block;
			margin-left: 10px;
			width: 350px;
			font-size: 68%;
		}	
		
		
		.explanation p{
			width: 350px;
			font-size: 68%;
			left: 55px;
			top: -2px;
			display: block;
		}
		
		.participation p{
			width: 350px;
			font-size: 68%;
			top: -2px;
			left: 10px;
			display: block
		} 
		
		.benefits p{
			width: 350px;
			font-size: 68%;
			top: -2px;
			left: 10px;
			display: block
		}
		
		
		.requirements p{
			display: block;
			top: -2px;
			left: 10px;
			width: 350px;
			font-size: 68%;
			text-align: left;
		} 

		.participation:after{
		background: none;
		display: none;
	}
	
	.requirements:after{
		content: '';
		background: url(../images/small-line.png);
		display: block;
		width: 336px;
		height: 20px;
		position: absolute;
		top: 2400px;
		left: 15px;
		z-index: 100;
	}
	
	footer{
		text-align:center;
		margin-bottom: 20px;
		margin-top: 55px;
		font-size: 100%;
	}
	
		aside.sidebar ul li{
			margin-bottom: 6px;
		}
		
		.design-selection{
			margin-left: 10px;
			font-size: 75%;
		}
		
		.design-selection h3{
			text-indent: -5000px;
		}
		
			.design-selection h3:after{
			content: '';
			background: url(../images/design3.png);
			display: block;
			width: 208px;
			height: 25px;
			z-index: 1010;	
			margin-left: -4px;
			
		}
		
		.design-archives{
			position: static;
			margin-left: 10px;
			margin-top: -15px;
			margin-bottom: 308px;
			font-size: 75%;
		} 
		
		.design-archives h3{
			text-indent: -5000px;
		}
		
		.design-archives h3:after{
			content: '';
			background: url(../images/archives3.png) no-repeat;
			display: block;
			width: 144px;
			height: 25px;
			z-index: 1010;	
			
		}
		
		.zen-resources{
			position: static;
			margin-left: 10px;
			margin-top: -308px;
			font-size: 75%;
			
		} 
		
			.zen-resources h3{
			text-indent: -5000px;
		}
		
			.zen-resources h3:after{
			content: '';
			background: url(../images/resources3.png) no-repeat;
			display: block;
			width: 127px;
			height: 25px;
			z-index: 1010;	
			
		}
		
}



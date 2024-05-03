---
layout: default
title: awa awa
nav_order: 4
---

<img src="assets/img/edtech.png" alt="Workshop Title Slide" width="100%">

# EdTech Inc., Revisited

<script type="text/javascript" src="turnjs4/extras/jquery.min.1.7.js"></script>
<script type="text/javascript" src="turnjs4/extras/modernizr.2.5.3.min.js"></script>

<div class="container" style="width=100%">
<div class="flipbook" style="overflow: hidden">
<div style="background-image:url(assets/img/zines/all_ai_is_local/page1.png); background-size: 100% 100%;"></div>
<div style="background-image:url(assets/img/zines/all_ai_is_local/page2.png); background-size: 100% 100%;"></div>
<div style="background-image:url(assets/img/zines/all_ai_is_local/page3.png); background-size: 100% 100%;"></div>
<div style="background-image:url(assets/img/zines/all_ai_is_local/page4.png); background-size: 100% 100%;"></div>
<div style="background-image:url(assets/img/zines/all_ai_is_local/page5.png); background-size: 100% 100%;"></div>
<div style="background-image:url(assets/img/zines/all_ai_is_local/page6.png); background-size: 100% 100%;"></div>
<div style="background-image:url(assets/img/zines/all_ai_is_local/page7.png); background-size: 100% 100%;"></div>
<div style="background-image:url(assets/img/zines/all_ai_is_local/page8.png); background-size: 100% 100%;"></div>
<div style="background-image:url(assets/img/zines/all_ai_is_local/page9.png); background-size: 100% 100%;"></div>
<div style="background-image:url(assets/img/zines/all_ai_is_local/page10.png); background-size: 100% 100%;"></div>
<div style="background-image:url(assets/img/zines/all_ai_is_local/page11.png); background-size: 100% 100%;"></div>
<div style="background-image:url(assets/img/zines/all_ai_is_local/page12.png); background-size: 100% 100%;"></div>
<div style="background-image:url(assets/img/zines/all_ai_is_local/page13.png); background-size: 100% 100%;"></div>
<div style="background-image:url(assets/img/zines/all_ai_is_local/page14.png); background-size: 100% 100%;"></div>
<div style="background-image:url(assets/img/zines/all_ai_is_local/page15.png); background-size: 100% 100%;"></div>
<div style="background-image:url(assets/img/zines/all_ai_is_local/page16.png); background-size: 100% 100%;"></div>
<div style="background-image:url(assets/img/zines/all_ai_is_local/page17.png); background-size: 100% 100%;"></div>
<div style="background-image:url(assets/img/zines/all_ai_is_local/page18.png); background-size: 100% 100%;"></div>
<div style="background-image:url(assets/img/zines/all_ai_is_local/page19.png); background-size: 100% 100%;"></div>
<div style="background-image:url(assets/img/zines/all_ai_is_local/page20.png); background-size: 100% 100%;"></div>
</div>
</div>

<script type="text/javascript">

function loadApp() {
	$('.flipbook').turn({
			width: $('.container').width() ,
			height: $('.container').width()*0.697777778,
			elevation: 0,
			gradients: true,
			autoCenter: true
	});
}

yepnope({
	test : Modernizr.csstransforms,
	yep: ['turnjs4/lib/turn.js'],
	nope: ['turnjs4/lib/turn.html4.min.js'],
	both: ['turnjs4/basic.css'],
	complete: loadApp
});

$( window ).on( "resize", function() {
  $('.flipbook').turn('size', $('.container').width(), $('.container').width()*0.697777778)
} );
</script>
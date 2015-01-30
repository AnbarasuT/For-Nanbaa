Index.html
==========

<!Doctype html>
<html>
<head>
	<title>imth-K-6-word-apart-ICON-1</title>
	<meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1">
	<meta name="apple-mobile-web-app-capable" content="yes">
	<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no" />
        <meta name="HandheldFriendly" content="true" />
        <link rel="stylesheet" href="stylesheets/app.css" />
       	<script type="text/javascript" src="javascripts/jquery-1.10.2.min.js"></script>
	<script type="text/javascript" src="javascripts/jquery-ui.js"></script>
	 <script type="text/javascript" src="javascripts/jquery.ui.touch-punch.js"></script>
	<script src="javascripts/vendor-nojquery-min.js"></script>
	<!--<script src="javascripts/test-harness.js"></script>-->
        <script type="text/javascript" src="javascripts/activity.js"></script>
</head>
<body></body>
</html>





App.css
========

/*! normalize.css v2.1.2 | MIT License | git.io/normalize */ article,aside,details,figcaption,figure,footer,header,hgroup,main,nav,section,summary{display:block}
audio,canvas,video{display:inline-block}
audio:not([controls]){display:none;height:0}
[hidden]{display:none}
html{font-family:sans-serif;-ms-text-size-adjust:100%;-webkit-text-size-adjust:100%}
body{margin:0}
a:focus{outline:thin dotted}
a:active,a:hover{outline:0}
h1{font-size:2em;margin:.67em 0}
abbr[title]{border-bottom:1px dotted}
b,strong{font-weight:700}
dfn{font-style:italic}
hr{-moz-box-sizing:content-box;box-sizing:content-box;height:0}
mark{background:#ff0;color:#000}
code,kbd,pre,samp{font-family:monospace,serif;font-size:1em}
pre{white-space:pre-wrap}
q{quotes:"\201C" "\201D" "\2018" "\2019"}
small{font-size:80%}
sub,sup{font-size:75%;line-height:0;position:relative;vertical-align:baseline}
sup{top:-.5em}
sub{bottom:-.25em}
img{border:0}
svg:not(:root){overflow:hidden}
figure{margin:0}
fieldset{border:1px solid silver;margin:0 2px;padding:.35em .625em .75em}
legend{border:0;padding:0}
button,input,select,textarea{font-family:inherit;font-size:100%;margin:0; text-align: center;}
button,input{line-height:normal}
button,select{text-transform:none}
button,html input[type=button],input[type=reset],input[type=submit]{-webkit-appearance:button;cursor:pointer}
button[disabled],html input[disabled]{cursor:default}
input[type=checkbox],input[type=radio]{box-sizing:border-box;padding:0}
input[type=search]{-webkit-appearance:textfield;-moz-box-sizing:content-box;-webkit-box-sizing:content-box;box-sizing:content-box}
input[type=search]::-webkit-search-cancel-button,input[type=search]::-webkit-search-decoration{-webkit-appearance:none}
button::-moz-focus-inner,input::-moz-focus-inner{border:0;padding:0}
textarea{overflow:auto;vertical-align:top}
table{border-collapse:collapse;border-spacing:0}
@font-face{font-family:'Gill Sans Infant';src:url(../fonts/font/gilsbrg.eot);src:url(../fonts/font/gilsbrg.eot) format('embedded-opentype'),url(../fonts/font/gilsbrg.woff) format('woff'),url(../fonts/font/gilsbrg.ttf) format('truetype');font-style:normal}
@font-face{font-family:'Gill Sans Infant';src:url(../fonts/font/gilsbit.eot);src:url(../fonts/font/gilsbit.eot) format('embedded-opentype'),url(../fonts/font/gilsbit.woff) format('woff'),url(../fonts/font/gilsbit.ttf) format('truetype');font-style:italic}
@font-face{font-family:'Gill Sans Infant';src:url(../fonts/font/gilsbbd.eot);src:url(../fonts/font/gilsbbd.eot) format('embedded-opentype'),url(../fonts/font/gilsbbd.woff) format('woff'),url(../fonts/font/gilsbbd.ttf) format('truetype');font-style:normal}
@font-face{font-family:'Gill Sans Infant';src:url(../fonts/font/gilsbbdi.eot);src:url(../fonts/font/gilsbbdi.eot) format('embedded-opentype'),url(../fonts/font/gilsbbdi.woff) format('woff'),url(../fonts/font/gilsbbdi.ttf) format('truetype');font-style:italic}
#modal-container .modal-lightbox{position:absolute;top:0;left:0;width:1024px;height:768px;background:#000;opacity:.8;-ms-filter:alpha(Opacity=80);filter:alpha(opacity=80)}
#modal-container .modal-wrapper{display:table-cell;vertical-align:middle}
#modal-container .modal{overflow-y:scroll;overflow-x:hidden;max-height:600px;position:relative;margin:0 auto;width:460px;background:#fff;opacity:1;-ms-filter:none;filter:none;border:2px solid #7ea0c6;background:#a4d264;background:-moz-radial-gradient(center,circle farthest-side,#597ca5 0,#45638d 100%);background:-webkit-gradient(radial,center center,0,center center,100%,color-stop(0%,#597ca5),color-stop(65%,#82bc54),color-stop(100%,#45638d));background:-webkit-radial-gradient(center,circle farthest-side,#597ca5 0,#3d5485 100%);background:-o-radial-gradient(center,circle farthest-side,#597ca5 0,#45638d 100%);background:-ms-radial-gradient(center,circle farthest-side,#597ca5 0,#45638d 100%);background:radial-gradient(circle at center,#597ca5 0,#45638d 100%)}
#modal-container .modal-header{padding:0 10px;color:#fff;text-shadow:0 1px 0 rgba(0,0,0,.7);font-size:30px}
#modal-container .modal-body{padding:20px 50px;color:#fff;font-size:20px;line-height:1.4em;text-shadow:0 1px 0 rgba(0,0,0,.7)}
#modal-container .modal-body img{min-height:120px;width:360px}
#modal-container .modal-body h1,#modal-container .modal-body h2,#modal-container .modal-body h3{font-family:Gill Sans,sans-serif;line-height:1.4em;text-align:center;}
#modal-container .modal-header .close-button{cursor:pointer}
#modal-container.instructions,#modal-container.score,#modal-container.save,#modal-container.error,#modal-container.info{z-index:1000;position:absolute;display:table!important;top:0;left:0;width:1024px;height:768px;margin:0 auto}
#modal-container.save .modal-message{display:none;color:#fff;text-align:center;width:100%;height:100%;padding-top:20%;font-size:40px;background:rgba(0,0,0,.6);position:absolute;top:0;left:0}
#modal-container.save .modal-body{text-align:center}
#modal-container.save .modal-body .button-container{display:inline-block;padding:20px 30px;margin:0 10px}
#modal-container.score{text-align:center}
#modal-container.score .score-container{margin-top:-20px;min-width:90px;margin:8px;display:inline-block;}
#modal-container.score .score-container .score-title{font-size:18px;padding-top:10px}
#modal-container.score .score-container .score-box{background:rgba(255,255,255,.2);height:90px;min-width:90px;font-size:60px;line-height:90px}
*{-webkit-box-sizing:border-box;-moz-box-sizing:border-box;box-sizing:border-box;-webkit-tap-highlight-color:rgba(0,0,0,0)}
html{-ms-content-zooming:none}
html,body{width:100%;height:704px;font-family:'Gill Sans Infant','Gill Sans','Gill Sans MT',Calibri,sans-serif;/*background:#222*/}
body{-webkit-backface-visibility:hidden;-moz-backface-visibility:hidden;-ms-backface-visibility:hidden;backface-visibility:hidden;-webkit-user-select:none;-moz-user-select:none;-ms-user-select:none;user-select:none}
body .debug-outline #interactive-container{background-image:url(../images/ui.jpg);background-repeat:no-repeat;background-position:center top}
body .debug-outline #interactive-container div{-webkit-box-shadow:inset 0 0 2px #df8784;box-shadow:inset 0 0 2px #df8784}
#interactive-container{position:relative;width:1024px;height:698px;margin:0 auto;overflow:hidden;/*-webkit-box-shadow:0 0 20px #000;box-shadow:0 0 20px #000*/}

#page-container{position:absolute;top:0;left:0;width:1024px;height:698px;overflow:hidden}
#page-container1{position:absolute;top:70px;left:50px;width:900px;height:600px; border: 1px solid transferent;}
.page{position:absolute;top:0;left:0;width:1024px;height:698px}
#menu-container{position:absolute;top:678px;left:0;opacity:1;-ms-filter:alpha(Opacity=100);filter:alpha(opacity=100);text-shadow:0 1px 0 rgba(255,255,255,.3)}
#menu-container .inactive{opacity:.2;-ms-filter:alpha(Opacity=20);filter:alpha(opacity=20)}
#menu-container #navigation-container{position:absolute;top:12px;height:75px;width:1024px}
#menu-container #navigation-container #navigation{width:500px;text-align:center;margin:0 auto}
#menu-container #navigation-container #navigation .previous,#menu-container #navigation-container #navigation .next,#menu-container #navigation-container #navigation #navigation-list-container{position:relative;display:inline-block;margin:0 5px}
#menu-container #navigation-container #navigation .previous .navigation-list,#menu-container #navigation-container #navigation .next .navigation-list,#menu-container #navigation-container #navigation #navigation-list-container .navigation-list{text-align:center}
#menu-container #navigation-container #navigation .previous .navigation-list .navigation-item,#menu-container #navigation-container #navigation .next .navigation-list .navigation-item,#menu-container #navigation-container #navigation #navigation-list-container .navigation-list .navigation-item{display:inline-block;width:60px;position:relative;margin:0 5px}
#menu-container #navigation-container #navigation .previous,#menu-container #navigation-container #navigation .next,#menu-container #navigation-container #navigation .navigation-item{cursor:pointer;padding:25px 20px}
#menu-container #tools-container{position:absolute;top:0;width:1024px;height:0;text-align:center}
#menu-container #tools-container #tool-toggle{z-index:1;position:absolute;cursor:pointer;top:13px;right:30px;width:60px;height:60px;text-decoration:none}
#menu-container #tools-container #tool-list-container{position:absolute;bottom:0;right:30px}
#menu-container #tools-container #tool-list-container .toolsFadeIn{-webkit-animation-name:fadeIn;-moz-animation-name:fadeIn;-o-animation-name:fadeIn;-ms-animation-name:fadeIn;animation-name:fadeIn}
#menu-container #tools-container #tool-list-container .toolsFadeOut{-webkit-animation-name:fadeOut;-moz-animation-name:fadeOut;-o-animation-name:fadeOut;-ms-animation-name:fadeOut;animation-name:fadeOut}
#menu-container #tools-container #tool-list-container .tool-item{position:relative;cursor:pointer;bottom:0;font-size:12px;margin:10px 0;width:80px;height:80px}
#menu-container #instructions-button-container{position:absolute;top:0;width:1024px;height:0;text-align:center}
#menu-container #instructions-button-container #instructions-button{z-index:1;position:absolute;top:0;cursor:pointer;right:200px;width:60px;height:60px;text-decoration:none;color:#000;text-align:center;padding-top:25px}
#menu-container #score-button-container{position:absolute;top:0;width:1024px;height:0;text-align:center}
#menu-container #score-button-container #score-button{z-index:1;position:absolute;top:0;right:116px;width:60px;cursor:pointer;height:60px;text-decoration:none;color:#000;text-align:center;padding-top:25px}
#menu-container #save-button-container{position:absolute;top:0;width:1024px;height:0;text-align:center}
#menu-container #save-button-container #save-button{z-index:1;cursor:pointer;position:absolute;top:13px;left:30px;width:60px;height:60px;text-decoration:none;color:#000;text-align:center}
.animated{-webkit-animation-duration:.3s;-moz-animation-duration:.3s;-o-animation-duration:.3s;-ms-animation-duration:.3s;animation-duration:.3s;-webkit-animation-fill-mode:both;-moz-animation-fill-mode:both;-o-animation-fill-mode:both;-ms-animation-fill-mode:both;animation-fill-mode:both}
.slideInRight{-webkit-animation-name:slideInRight;-moz-animation-name:slideInRight;-o-animation-name:slideInRight;-ms-animation-name:slideInRight;animation-name:slideInRight}
.slideInLeft{-webkit-animation-name:slideInLeft;-moz-animation-name:slideInLeft;-o-animation-name:slideInLeft;-ms-animation-name:slideInLeft;animation-name:slideInLeft}
.slideOutLeft{-webkit-animation-name:slideOutLeft;-moz-animation-name:slideOutLeft;-o-animation-name:slideOutLeft;-ms-animation-name:slideOutLeft;animation-name:slideOutLeft}
.slideOutRight{-webkit-animation-name:slideOutRight;-moz-animation-name:slideOutRight;-o-animation-name:slideOutRight;-ms-animation-name:slideOutRight;animation-name:slideOutRight}
.fadeIn{-webkit-animation-name:fadeIn;-moz-animation-name:fadeIn;-o-animation-name:fadeIn;-ms-animation-name:fadeIn;animation-name:fadeIn}
.fadeOut{-webkit-animation-name:fadeOut;-moz-animation-name:fadeOut;-o-animation-name:fadeOut;-ms-animation-name:fadeOut;animation-name:fadeOut}
#swipe-arrow-container{position:absolute;top:0;left:-150px;width:1324px;height:0;opacity:.5;-ms-filter:alpha(Opacity=50);filter:alpha(opacity=50);-webkit-transition-property:opacity,-webkit-transform;-moz-transition-property:opacity,-moz-transform;-o-transition-property:opacity,-o-transform;-ms-transition-property:opacity,-ms-transform;transition-property:opacity,transform;-webkit-transition-duration:.3;-moz-transition-duration:.3;-o-transition-duration:.3;-ms-transition-duration:.3;transition-duration:.3}
#swipe-arrow-container div{background:#999;font-size:200%;-webkit-border-radius:9999px;border-radius:9999px;color:#fff;position:absolute;top:240px;padding-top:50px;width:150px;height:150px}
#swipe-arrow-container :first-child{left:0;text-align:right;padding-right:5px}
#swipe-arrow-container :last-child{right:0;text-align:left;padding-left:10px}
@-moz-keyframes slideInRight{0%{-webkit-transform:translateX(-1024px);-moz-transform:translateX(-1024px);-o-transform:translateX(-1024px);-ms-transform:translateX(-1024px);transform:translateX(-1024px)}
100%{-webkit-transform:translateX(0);-moz-transform:translateX(0);-o-transform:translateX(0);-ms-transform:translateX(0);transform:translateX(0)}
}
@-webkit-keyframes slideInRight{0%{-webkit-transform:translateX(-1024px);-moz-transform:translateX(-1024px);-o-transform:translateX(-1024px);-ms-transform:translateX(-1024px);transform:translateX(-1024px)}
100%{-webkit-transform:translateX(0);-moz-transform:translateX(0);-o-transform:translateX(0);-ms-transform:translateX(0);transform:translateX(0)}
}
@-o-keyframes slideInRight{0%{-webkit-transform:translateX(-1024px);-moz-transform:translateX(-1024px);-o-transform:translateX(-1024px);-ms-transform:translateX(-1024px);transform:translateX(-1024px)}
100%{-webkit-transform:translateX(0);-moz-transform:translateX(0);-o-transform:translateX(0);-ms-transform:translateX(0);transform:translateX(0)}
}
@-ms-keyframes slideInRight{0%{-webkit-transform:translateX(-1024px);-moz-transform:translateX(-1024px);-o-transform:translateX(-1024px);-ms-transform:translateX(-1024px);transform:translateX(-1024px)}
100%{-webkit-transform:translateX(0);-moz-transform:translateX(0);-o-transform:translateX(0);-ms-transform:translateX(0);transform:translateX(0)}
}
@keyframes slideInRight{0%{-webkit-transform:translateX(-1024px);-moz-transform:translateX(-1024px);-o-transform:translateX(-1024px);-ms-transform:translateX(-1024px);transform:translateX(-1024px)}
100%{-webkit-transform:translateX(0);-moz-transform:translateX(0);-o-transform:translateX(0);-ms-transform:translateX(0);transform:translateX(0)}
}
@-moz-keyframes toolsSlideRight{0%{-webkit-transform:translateX(-1024px);-moz-transform:translateX(-1024px);-o-transform:translateX(-1024px);-ms-transform:translateX(-1024px);transform:translateX(-1024px)}
100%{-webkit-transform:translateX(0px);-moz-transform:translateX(0px);-o-transform:translateX(0px);-ms-transform:translateX(0px);transform:translateX(0px)}
}
@-webkit-keyframes toolsSlideRight{0%{-webkit-transform:translateX(-1024px);-moz-transform:translateX(-1024px);-o-transform:translateX(-1024px);-ms-transform:translateX(-1024px);transform:translateX(-1024px)}
100%{-webkit-transform:translateX(0px);-moz-transform:translateX(0px);-o-transform:translateX(0px);-ms-transform:translateX(0px);transform:translateX(0px)}
}
@-o-keyframes toolsSlideRight{0%{-webkit-transform:translateX(-1024px);-moz-transform:translateX(-1024px);-o-transform:translateX(-1024px);-ms-transform:translateX(-1024px);transform:translateX(-1024px)}
100%{-webkit-transform:translateX(0px);-moz-transform:translateX(0px);-o-transform:translateX(0px);-ms-transform:translateX(0px);transform:translateX(0px)}
}
@-ms-keyframes toolsSlideRight{0%{-webkit-transform:translateX(-1024px);-moz-transform:translateX(-1024px);-o-transform:translateX(-1024px);-ms-transform:translateX(-1024px);transform:translateX(-1024px)}
100%{-webkit-transform:translateX(0px);-moz-transform:translateX(0px);-o-transform:translateX(0px);-ms-transform:translateX(0px);transform:translateX(0px)}
}
@keyframes toolsSlideRight{0%{-webkit-transform:translateX(-1024px);-moz-transform:translateX(-1024px);-o-transform:translateX(-1024px);-ms-transform:translateX(-1024px);transform:translateX(-1024px)}
100%{-webkit-transform:translateX(0px);-moz-transform:translateX(0px);-o-transform:translateX(0px);-ms-transform:translateX(0px);transform:translateX(0px)}
}
@-moz-keyframes toolsSlideLeft{0%{-webkit-transform:translateX(0px);-moz-transform:translateX(0px);-o-transform:translateX(0px);-ms-transform:translateX(0px);transform:translateX(0px)}
100%{-webkit-transform:translateX(-1024px);-moz-transform:translateX(-1024px);-o-transform:translateX(-1024px);-ms-transform:translateX(-1024px);transform:translateX(-1024px)}
}
@-webkit-keyframes toolsSlideLeft{0%{-webkit-transform:translateX(0px);-moz-transform:translateX(0px);-o-transform:translateX(0px);-ms-transform:translateX(0px);transform:translateX(0px)}
100%{-webkit-transform:translateX(-1024px);-moz-transform:translateX(-1024px);-o-transform:translateX(-1024px);-ms-transform:translateX(-1024px);transform:translateX(-1024px)}
}
@-o-keyframes toolsSlideLeft{0%{-webkit-transform:translateX(0px);-moz-transform:translateX(0px);-o-transform:translateX(0px);-ms-transform:translateX(0px);transform:translateX(0px)}
100%{-webkit-transform:translateX(-1024px);-moz-transform:translateX(-1024px);-o-transform:translateX(-1024px);-ms-transform:translateX(-1024px);transform:translateX(-1024px)}
}
@-ms-keyframes toolsSlideLeft{0%{-webkit-transform:translateX(0px);-moz-transform:translateX(0px);-o-transform:translateX(0px);-ms-transform:translateX(0px);transform:translateX(0px)}
100%{-webkit-transform:translateX(-1024px);-moz-transform:translateX(-1024px);-o-transform:translateX(-1024px);-ms-transform:translateX(-1024px);transform:translateX(-1024px)}
}
@keyframes toolsSlideLeft{0%{-webkit-transform:translateX(0px);-moz-transform:translateX(0px);-o-transform:translateX(0px);-ms-transform:translateX(0px);transform:translateX(0px)}
100%{-webkit-transform:translateX(-1024px);-moz-transform:translateX(-1024px);-o-transform:translateX(-1024px);-ms-transform:translateX(-1024px);transform:translateX(-1024px)}
}
@-moz-keyframes slideInLeft{0%{-webkit-transform:translateX(1024px);-moz-transform:translateX(1024px);-o-transform:translateX(1024px);-ms-transform:translateX(1024px);transform:translateX(1024px)}
100%{-webkit-transform:translateX(0);-moz-transform:translateX(0);-o-transform:translateX(0);-ms-transform:translateX(0);transform:translateX(0)}
}
@-webkit-keyframes slideInLeft{0%{-webkit-transform:translateX(1024px);-moz-transform:translateX(1024px);-o-transform:translateX(1024px);-ms-transform:translateX(1024px);transform:translateX(1024px)}
100%{-webkit-transform:translateX(0);-moz-transform:translateX(0);-o-transform:translateX(0);-ms-transform:translateX(0);transform:translateX(0)}
}
@-o-keyframes slideInLeft{0%{-webkit-transform:translateX(1024px);-moz-transform:translateX(1024px);-o-transform:translateX(1024px);-ms-transform:translateX(1024px);transform:translateX(1024px)}
100%{-webkit-transform:translateX(0);-moz-transform:translateX(0);-o-transform:translateX(0);-ms-transform:translateX(0);transform:translateX(0)}
}
@-ms-keyframes slideInLeft{0%{-webkit-transform:translateX(1024px);-moz-transform:translateX(1024px);-o-transform:translateX(1024px);-ms-transform:translateX(1024px);transform:translateX(1024px)}
100%{-webkit-transform:translateX(0);-moz-transform:translateX(0);-o-transform:translateX(0);-ms-transform:translateX(0);transform:translateX(0)}
}
@keyframes slideInLeft{0%{-webkit-transform:translateX(1024px);-moz-transform:translateX(1024px);-o-transform:translateX(1024px);-ms-transform:translateX(1024px);transform:translateX(1024px)}
100%{-webkit-transform:translateX(0);-moz-transform:translateX(0);-o-transform:translateX(0);-ms-transform:translateX(0);transform:translateX(0)}
}
@-moz-keyframes slideOutLeft{0%{-webkit-transform:translateX(0);-moz-transform:translateX(0);-o-transform:translateX(0);-ms-transform:translateX(0);transform:translateX(0)}
100%{-webkit-transform:translateX(-1024px);-moz-transform:translateX(-1024px);-o-transform:translateX(-1024px);-ms-transform:translateX(-1024px);transform:translateX(-1024px)}
}
@-webkit-keyframes slideOutLeft{0%{-webkit-transform:translateX(0);-moz-transform:translateX(0);-o-transform:translateX(0);-ms-transform:translateX(0);transform:translateX(0)}
100%{-webkit-transform:translateX(-1024px);-moz-transform:translateX(-1024px);-o-transform:translateX(-1024px);-ms-transform:translateX(-1024px);transform:translateX(-1024px)}
}
@-o-keyframes slideOutLeft{0%{-webkit-transform:translateX(0);-moz-transform:translateX(0);-o-transform:translateX(0);-ms-transform:translateX(0);transform:translateX(0)}
100%{-webkit-transform:translateX(-1024px);-moz-transform:translateX(-1024px);-o-transform:translateX(-1024px);-ms-transform:translateX(-1024px);transform:translateX(-1024px)}
}
@-ms-keyframes slideOutLeft{0%{-webkit-transform:translateX(0);-moz-transform:translateX(0);-o-transform:translateX(0);-ms-transform:translateX(0);transform:translateX(0)}
100%{-webkit-transform:translateX(-1024px);-moz-transform:translateX(-1024px);-o-transform:translateX(-1024px);-ms-transform:translateX(-1024px);transform:translateX(-1024px)}
}
@keyframes slideOutLeft{0%{-webkit-transform:translateX(0);-moz-transform:translateX(0);-o-transform:translateX(0);-ms-transform:translateX(0);transform:translateX(0)}
100%{-webkit-transform:translateX(-1024px);-moz-transform:translateX(-1024px);-o-transform:translateX(-1024px);-ms-transform:translateX(-1024px);transform:translateX(-1024px)}
}
@-moz-keyframes slideOutRight{0%{-webkit-transform:translateX(0);-moz-transform:translateX(0);-o-transform:translateX(0);-ms-transform:translateX(0);transform:translateX(0)}
100%{-webkit-transform:translateX(1024px);-moz-transform:translateX(1024px);-o-transform:translateX(1024px);-ms-transform:translateX(1024px);transform:translateX(1024px)}
}
@-webkit-keyframes slideOutRight{0%{-webkit-transform:translateX(0);-moz-transform:translateX(0);-o-transform:translateX(0);-ms-transform:translateX(0);transform:translateX(0)}
100%{-webkit-transform:translateX(1024px);-moz-transform:translateX(1024px);-o-transform:translateX(1024px);-ms-transform:translateX(1024px);transform:translateX(1024px)}
}
@-o-keyframes slideOutRight{0%{-webkit-transform:translateX(0);-moz-transform:translateX(0);-o-transform:translateX(0);-ms-transform:translateX(0);transform:translateX(0)}
100%{-webkit-transform:translateX(1024px);-moz-transform:translateX(1024px);-o-transform:translateX(1024px);-ms-transform:translateX(1024px);transform:translateX(1024px)}
}
@-ms-keyframes slideOutRight{0%{-webkit-transform:translateX(0);-moz-transform:translateX(0);-o-transform:translateX(0);-ms-transform:translateX(0);transform:translateX(0)}
100%{-webkit-transform:translateX(1024px);-moz-transform:translateX(1024px);-o-transform:translateX(1024px);-ms-transform:translateX(1024px);transform:translateX(1024px)}
}
@keyframes slideOutRight{0%{-webkit-transform:translateX(0);-moz-transform:translateX(0);-o-transform:translateX(0);-ms-transform:translateX(0);transform:translateX(0)}
100%{-webkit-transform:translateX(1024px);-moz-transform:translateX(1024px);-o-transform:translateX(1024px);-ms-transform:translateX(1024px);transform:translateX(1024px)}
}
@-moz-keyframes fadeIn{0%{opacity:0;-ms-filter:alpha(Opacity=0);filter:alpha(opacity=0)}
100%{opacity:1;-ms-filter:none;filter:none}
}
@-webkit-keyframes fadeIn{0%{opacity:0;-ms-filter:alpha(Opacity=0);filter:alpha(opacity=0)}
100%{opacity:1;-ms-filter:none;filter:none}
}
@-o-keyframes fadeIn{0%{opacity:0;-ms-filter:alpha(Opacity=0);filter:alpha(opacity=0)}
100%{opacity:1;-ms-filter:none;filter:none}
}
@-ms-keyframes fadeIn{0%{opacity:0;-ms-filter:alpha(Opacity=0);filter:alpha(opacity=0)}
100%{opacity:1;-ms-filter:none;filter:none}
}
@keyframes fadeIn{0%{opacity:0;-ms-filter:alpha(Opacity=0);filter:alpha(opacity=0)}
100%{opacity:1;-ms-filter:none;filter:none}
}
@-moz-keyframes fadeOut{0%{opacity:1;-ms-filter:none;filter:none}
100%{opacity:0;-ms-filter:alpha(Opacity=0);filter:alpha(opacity=0)}
}
@-webkit-keyframes fadeOut{0%{opacity:1;-ms-filter:none;filter:none}
100%{opacity:0;-ms-filter:alpha(Opacity=0);filter:alpha(opacity=0)}
}
@-o-keyframes fadeOut{0%{opacity:1;-ms-filter:none;filter:none}
100%{opacity:0;-ms-filter:alpha(Opacity=0);filter:alpha(opacity=0)}
}
@-ms-keyframes fadeOut{0%{opacity:1;-ms-filter:none;filter:none}
100%{opacity:0;-ms-filter:alpha(Opacity=0);filter:alpha(opacity=0)}
}
@keyframes fadeOut{0%{opacity:1;-ms-filter:none;filter:none}
100%{opacity:0;-ms-filter:alpha(Opacity=0);filter:alpha(opacity=0)}
}
/*!
 *  Font Awesome 3.0.2
 *  the iconic font designed for use with Twitter Bootstrap
 *  -------------------------------------------------------
 *  The full suite of pictographic icons, examples, and documentation
 *  can be found at: http://fortawesome.github.com/Font-Awesome/
 *
 *  License
 *  -------------------------------------------------------
 *  - The Font Awesome font is licensed under the SIL Open Font License - http://scripts.sil.org/OFL
 *  - Font Awesome CSS, LESS, and SASS files are licensed under the MIT License -
 *    http://opensource.org/licenses/mit-license.html
 *  - The Font Awesome pictograms are licensed under the CC BY 3.0 License - http://creativecommons.org/licenses/by/3.0/
 *  - Attribution is no longer required in Font Awesome 3.0, but much appreciated:
 *    "Font Awesome by Dave Gandy - http://fortawesome.github.com/Font-Awesome"

 *  Contact
 *  -------------------------------------------------------
 *  Email: dave@davegandy.com
 *  Twitter: http://twitter.com/fortaweso_me
 *  Work: Lead Product Designer @ http://kyruus.com
 */ @font-face{font-family:Icons;src:url(../fonts/icons//icons.eot);src:url(../fonts/icons//icons.eot) format('embedded-opentype'),url(../fonts/icons//icons.woff) format('woff'),url(../fonts/icons//icons.ttf) format('truetype');font-weight:400;font-style:normal}
.icon-save:before{content:"\f0c7"}
.icon-restart:before{content:"\f01c"}
.icon-score:before{content:"\f029"}
.icon-instructions:before{content:"\f0e5"}
.icon-tool-list:before{content:"\f013"}
.navigation-item .icon-navigation-dot:before{content:"\f10c"}
.navigation-item.visited .icon-navigation-dot:before,.navigation-item.active .icon-navigation-dot:before{content:"\f111";opacity:.4}
.navigation-item.active .icon-navigation-dot:before{opacity:1}
[class^=icon-],[class*=" icon-"]{font-family:Icons;font-weight:400;font-style:normal;text-decoration:inherit;-webkit-font-smoothing:antialiased;display:inline;width:auto;height:auto;line-height:normal;vertical-align:baseline;background-image:none;background-position:0 0;background-repeat:repeat;margin-top:0}
.icon-white,.nav-pills>.active>a>[class^=icon-],.nav-pills>.active>a>[class*=" icon-"],.nav-list>.active>a>[class^=icon-],.nav-list>.active>a>[class*=" icon-"],.navbar-inverse .nav>.active>a>[class^=icon-],.navbar-inverse .nav>.active>a>[class*=" icon-"],.dropdown-menu>li>a:hover>[class^=icon-],.dropdown-menu>li>a:hover>[class*=" icon-"],.dropdown-menu>.active>a>[class^=icon-],.dropdown-menu>.active>a>[class*=" icon-"],.dropdown-submenu:hover>a>[class^=icon-],.dropdown-submenu:hover>a>[class*=" icon-"]{background-image:none}
[class^=icon-]:before,[class*=" icon-"]:before{text-decoration:inherit;display:inline-block;speak:none}
a [class^=icon-],a [class*=" icon-"]{display:inline-block}
.icon-large:before{vertical-align:-10%;font-size:1.3333333333333333em}
.btn [class^=icon-],.nav [class^=icon-],.btn [class*=" icon-"],.nav [class*=" icon-"]{display:inline}
.btn [class^=icon-].icon-large,.nav [class^=icon-].icon-large,.btn [class*=" icon-"].icon-large,.nav [class*=" icon-"].icon-large{line-height:.9em}
.btn [class^=icon-].icon-spin,.nav [class^=icon-].icon-spin,.btn [class*=" icon-"].icon-spin,.nav [class*=" icon-"].icon-spin{display:inline-block}
.nav-tabs [class^=icon-],.nav-pills [class^=icon-],.nav-tabs [class*=" icon-"],.nav-pills [class*=" icon-"]{}
.nav-tabs [class^=icon-],.nav-pills [class^=icon-],.nav-tabs [class*=" icon-"],.nav-pills [class*=" icon-"],.nav-tabs [class^=icon-].icon-large,.nav-pills [class^=icon-].icon-large,.nav-tabs [class*=" icon-"].icon-large,.nav-pills [class*=" icon-"].icon-large{line-height:.9em}
li [class^=icon-],.nav li [class^=icon-],li [class*=" icon-"],.nav li [class*=" icon-"]{display:inline-block;width:1.25em;text-align:center}
li [class^=icon-].icon-large,.nav li [class^=icon-].icon-large,li [class*=" icon-"].icon-large,.nav li [class*=" icon-"].icon-large{width:1.5625em}
ul.icons{list-style-type:none;text-indent:-.75em}
ul.icons li [class^=icon-],ul.icons li [class*=" icon-"]{width:.75em}
.icon-muted{color:#eee}
.icon-border{border:solid 1px #eee;padding:.2em .25em .15em;-webkit-border-radius:3px;-moz-border-radius:3px;border-radius:3px}
.icon-2x{font-size:2em}
.icon-2x.icon-border{border-width:2px;-webkit-border-radius:4px;-moz-border-radius:4px;border-radius:4px}
.icon-3x{font-size:3em}
.icon-3x.icon-border{border-width:3px;-webkit-border-radius:5px;-moz-border-radius:5px;border-radius:5px}
.icon-4x{font-size:4em}
.icon-4x.icon-border{border-width:4px;-webkit-border-radius:6px;-moz-border-radius:6px;border-radius:6px}
.pull-right{float:right}
.pull-left{float:left}
[class^=icon-].pull-left,[class*=" icon-"].pull-left{margin-right:.3em}
[class^=icon-].pull-right,[class*=" icon-"].pull-right{margin-left:.3em}
.btn [class^=icon-].pull-left.icon-2x,.btn [class*=" icon-"].pull-left.icon-2x,.btn [class^=icon-].pull-right.icon-2x,.btn [class*=" icon-"].pull-right.icon-2x{margin-top:.18em}
.btn [class^=icon-].icon-spin.icon-large,.btn [class*=" icon-"].icon-spin.icon-large{line-height:.8em}
.btn.btn-small [class^=icon-].pull-left.icon-2x,.btn.btn-small [class*=" icon-"].pull-left.icon-2x,.btn.btn-small [class^=icon-].pull-right.icon-2x,.btn.btn-small [class*=" icon-"].pull-right.icon-2x{margin-top:.25em}
.btn.btn-large [class^=icon-],.btn.btn-large [class*=" icon-"]{margin-top:0}
.btn.btn-large [class^=icon-].pull-left.icon-2x,.btn.btn-large [class*=" icon-"].pull-left.icon-2x,.btn.btn-large [class^=icon-].pull-right.icon-2x,.btn.btn-large [class*=" icon-"].pull-right.icon-2x{margin-top:.05em}
.btn.btn-large [class^=icon-].pull-left.icon-2x,.btn.btn-large [class*=" icon-"].pull-left.icon-2x{margin-right:.2em}
.btn.btn-large [class^=icon-].pull-right.icon-2x,.btn.btn-large [class*=" icon-"].pull-right.icon-2x{margin-left:.2em}
.icon-spin{display:inline-block;-moz-animation:spin 2s infinite linear;-o-animation:spin 2s infinite linear;-webkit-animation:spin 2s infinite linear;animation:spin 2s infinite linear}
@-moz-keyframes spin{0%{-moz-transform:rotate(0deg)}
100%{-moz-transform:rotate(359deg)}
}
@-webkit-keyframes spin{0%{-webkit-transform:rotate(0deg)}
100%{-webkit-transform:rotate(359deg)}
}
@-o-keyframes spin{0%{-o-transform:rotate(0deg)}
100%{-o-transform:rotate(359deg)}
}
@-ms-keyframes spin{0%{-ms-transform:rotate(0deg)}
100%{-ms-transform:rotate(359deg)}
}
@keyframes spin{0%{transform:rotate(0deg)}
100%{transform:rotate(359deg)}
}
@-moz-document url-prefix(){.icon-spin{height:.9em}
.btn .icon-spin{height:auto}
.icon-spin.icon-large{height:1.25em}
.btn .icon-spin.icon-large{height:.75em}
}
.icon-glass:before{content:"\f000"}
.icon-music:before{content:"\f001"}
.icon-search:before{content:"\f002"}
.icon-envelope:before{content:"\f003"}
.icon-heart:before{content:"\f004"}
.icon-star:before{content:"\f005"}
.icon-star-empty:before{content:"\f006"}
.icon-user:before{content:"\f007"}
.icon-film:before{content:"\f008"}
.icon-th-large:before{content:"\f009"}
.icon-th:before{content:"\f00a"}
.icon-th-list:before{content:"\f00b"}
.icon-ok:before{content:"\f00c"}
.icon-remove:before{content:"\f00d"}
.icon-zoom-in:before{content:"\f00e"}
.icon-zoom-out:before{content:"\f010"}
.icon-off:before{content:"\f011"}
.icon-signal:before{content:"\f012"}
.icon-cog:before{content:"\f013"}
.icon-trash:before{content:"\f014"}
.icon-home:before{content:"\f015"}
.icon-file:before{content:"\f016"}
.icon-time:before{content:"\f017"}
.icon-road:before{content:"\f018"}
.icon-download-alt:before{content:"\f019"}
.icon-download:before{content:"\f01a"}
.icon-upload:before{content:"\f01b"}
.icon-inbox:before{content:"\f01c"}
.icon-play-circle:before{content:"\f01d"}
.icon-repeat:before{content:"\f01e"}
.icon-refresh:before{content:"\f021"}
.icon-list-alt:before{content:"\f022"}
.icon-lock:before{content:"\f023"}
.icon-flag:before{content:"\f024"}
.icon-headphones:before{content:"\f025"}
.icon-volume-off:before{content:"\f026"}
.icon-volume-down:before{content:"\f027"}
.icon-volume-up:before{content:"\f028"}
.icon-qrcode:before{content:"\f029"}
.icon-barcode:before{content:"\f02a"}
.icon-tag:before{content:"\f02b"}
.icon-tags:before{content:"\f02c"}
.icon-book:before{content:"\f02d"}
.icon-bookmark:before{content:"\f02e"}
.icon-print:before{content:"\f02f"}
.icon-camera:before{content:"\f030"}
.icon-font:before{content:"\f031"}
.icon-bold:before{content:"\f032"}
.icon-italic:before{content:"\f033"}
.icon-text-height:before{content:"\f034"}
.icon-text-width:before{content:"\f035"}
.icon-align-left:before{content:"\f036"}
.icon-align-center:before{content:"\f037"}
.icon-align-right:before{content:"\f038"}
.icon-align-justify:before{content:"\f039"}
.icon-list:before{content:"\f03a"}
.icon-indent-left:before{content:"\f03b"}
.icon-indent-right:before{content:"\f03c"}
.icon-facetime-video:before{content:"\f03d"}
.icon-picture:before{content:"\f03e"}
.icon-pencil:before{content:"\f040"}
.icon-map-marker:before{content:"\f041"}
.icon-adjust:before{content:"\f042"}
.icon-tint:before{content:"\f043"}
.icon-edit:before{content:"\f044"}
.icon-share:before{content:"\f045"}
.icon-check:before{content:"\f046"}
.icon-move:before{content:"\f047"}
.icon-step-backward:before{content:"\f048"}
.icon-fast-backward:before{content:"\f049"}
.icon-backward:before{content:"\f04a"}
.icon-play:before{content:"\f04b"}
.icon-pause:before{content:"\f04c"}
.icon-stop:before{content:"\f04d"}
.icon-forward:before{content:"\f04e"}
.icon-fast-forward:before{content:"\f050"}
.icon-step-forward:before{content:"\f051"}
.icon-eject:before{content:"\f052"}
.icon-chevron-left:before{content:"\f053"}
.icon-chevron-right:before{content:"\f054"}
.icon-plus-sign:before{content:"\f055"}
.icon-minus-sign:before{content:"\f056"}
.icon-remove-sign:before{content:"\f057"}
.icon-ok-sign:before{content:"\f058"}
.icon-question-sign:before{content:"\f059"}
.icon-info-sign:before{content:"\f05a"}
.icon-screenshot:before{content:"\f05b"}
.icon-remove-circle:before{content:"\f05c"}
.icon-ok-circle:before{content:"\f05d"}
.icon-ban-circle:before{content:"\f05e"}
.icon-arrow-left:before{content:"\f060"}
.icon-arrow-right:before{content:"\f061"}
.icon-arrow-up:before{content:"\f062"}
.icon-arrow-down:before{content:"\f063"}
.icon-share-alt:before{content:"\f064"}
.icon-resize-full:before{content:"\f065"}
.icon-resize-small:before{content:"\f066"}
.icon-plus:before{content:"\f067"}
.icon-minus:before{content:"\f068"}
.icon-asterisk:before{content:"\f069"}
.icon-exclamation-sign:before{content:"\f06a"}
.icon-gift:before{content:"\f06b"}
.icon-leaf:before{content:"\f06c"}
.icon-fire:before{content:"\f06d"}
.icon-eye-open:before{content:"\f06e"}
.icon-eye-close:before{content:"\f070"}
.icon-warning-sign:before{content:"\f071"}
.icon-plane:before{content:"\f072"}
.icon-calendar:before{content:"\f073"}
.icon-random:before{content:"\f074"}
.icon-comment:before{content:"\f075"}
.icon-magnet:before{content:"\f076"}
.icon-chevron-up:before{content:"\f077"}
.icon-chevron-down:before{content:"\f078"}
.icon-retweet:before{content:"\f079"}
.icon-shopping-cart:before{content:"\f07a"}
.icon-folder-close:before{content:"\f07b"}
.icon-folder-open:before{content:"\f07c"}
.icon-resize-vertical:before{content:"\f07d"}
.icon-resize-horizontal:before{content:"\f07e"}
.icon-bar-chart:before{content:"\f080"}
.icon-twitter-sign:before{content:"\f081"}
.icon-facebook-sign:before{content:"\f082"}
.icon-camera-retro:before{content:"\f083"}
.icon-key:before{content:"\f084"}
.icon-cogs:before{content:"\f085"}
.icon-comments:before{content:"\f086"}
.icon-thumbs-up:before{content:"\f087"}
.icon-thumbs-down:before{content:"\f088"}
.icon-star-half:before{content:"\f089"}
.icon-heart-empty:before{content:"\f08a"}
.icon-signout:before{content:"\f08b"}
.icon-linkedin-sign:before{content:"\f08c"}
.icon-pushpin:before{content:"\f08d"}
.icon-external-link:before{content:"\f08e"}
.icon-signin:before{content:"\f090"}
.icon-trophy:before{content:"\f091"}
.icon-github-sign:before{content:"\f092"}
.icon-upload-alt:before{content:"\f093"}
.icon-lemon:before{content:"\f094"}
.icon-phone:before{content:"\f095"}
.icon-check-empty:before{content:"\f096"}
.icon-bookmark-empty:before{content:"\f097"}
.icon-phone-sign:before{content:"\f098"}
.icon-twitter:before{content:"\f099"}
.icon-facebook:before{content:"\f09a"}
.icon-github:before{content:"\f09b"}
.icon-unlock:before{content:"\f09c"}
.icon-credit-card:before{content:"\f09d"}
.icon-rss:before{content:"\f09e"}
.icon-hdd:before{content:"\f0a0"}
.icon-bullhorn:before{content:"\f0a1"}
.icon-bell:before{content:"\f0a2"}
.icon-certificate:before{content:"\f0a3"}
.icon-hand-right:before{content:"\f0a4"}
.icon-hand-left:before{content:"\f0a5"}
.icon-hand-up:before{content:"\f0a6"}
.icon-hand-down:before{content:"\f0a7"}
.icon-circle-arrow-left:before{content:"\f0a8"}
.icon-circle-arrow-right:before{content:"\f0a9"}
.icon-circle-arrow-up:before{content:"\f0aa"}
.icon-circle-arrow-down:before{content:"\f0ab"}
.icon-globe:before{content:"\f0ac"}
.icon-wrench:before{content:"\f0ad"}
.icon-tasks:before{content:"\f0ae"}
.icon-filter:before{content:"\f0b0"}
.icon-briefcase:before{content:"\f0b1"}
.icon-fullscreen:before{content:"\f0b2"}
.icon-group:before{content:"\f0c0"}
.icon-link:before{content:"\f0c1"}
.icon-cloud:before{content:"\f0c2"}
.icon-beaker:before{content:"\f0c3"}
.icon-cut:before{content:"\f0c4"}
.icon-copy:before{content:"\f0c5"}
.icon-paper-clip:before{content:"\f0c6"}
.icon-save:before{content:"\f0c7"}
.icon-sign-blank:before{content:"\f0c8"}
.icon-reorder:before{content:"\f0c9"}
.icon-list-ul:before{content:"\f0ca"}
.icon-list-ol:before{content:"\f0cb"}
.icon-strikethrough:before{content:"\f0cc"}
.icon-underline:before{content:"\f0cd"}
.icon-table:before{content:"\f0ce"}
.icon-magic:before{content:"\f0d0"}
.icon-truck:before{content:"\f0d1"}
.icon-pinterest:before{content:"\f0d2"}
.icon-pinterest-sign:before{content:"\f0d3"}
.icon-google-plus-sign:before{content:"\f0d4"}
.icon-google-plus:before{content:"\f0d5"}
.icon-money:before{content:"\f0d6"}
.icon-caret-down:before{content:"\f0d7"}
.icon-caret-up:before{content:"\f0d8"}
.icon-caret-left:before{content:"\f0d9"}
.icon-caret-right:before{content:"\f0da"}
.icon-columns:before{content:"\f0db"}
.icon-sort:before{content:"\f0dc"}
.icon-sort-down:before{content:"\f0dd"}
.icon-sort-up:before{content:"\f0de"}
.icon-envelope-alt:before{content:"\f0e0"}
.icon-linkedin:before{content:"\f0e1"}
.icon-undo:before{content:"\f0e2"}
.icon-legal:before{content:"\f0e3"}
.icon-dashboard:before{content:"\f0e4"}
.icon-comment-alt:before{content:"\f0e5"}
.icon-comments-alt:before{content:"\f0e6"}
.icon-bolt:before{content:"\f0e7"}
.icon-sitemap:before{content:"\f0e8"}
.icon-umbrella:before{content:"\f0e9"}
.icon-paste:before{content:"\f0ea"}
.icon-lightbulb:before{content:"\f0eb"}
.icon-exchange:before{content:"\f0ec"}
.icon-cloud-download:before{content:"\f0ed"}
.icon-cloud-upload:before{content:"\f0ee"}
.icon-user-md:before{content:"\f0f0"}
.icon-stethoscope:before{content:"\f0f1"}
.icon-suitcase:before{content:"\f0f2"}
.icon-bell-alt:before{content:"\f0f3"}
.icon-coffee:before{content:"\f0f4"}
.icon-food:before{content:"\f0f5"}
.icon-file-alt:before{content:"\f0f6"}
.icon-building:before{content:"\f0f7"}
.icon-hospital:before{content:"\f0f8"}
.icon-ambulance:before{content:"\f0f9"}
.icon-medkit:before{content:"\f0fa"}
.icon-fighter-jet:before{content:"\f0fb"}
.icon-beer:before{content:"\f0fc"}
.icon-h-sign:before{content:"\f0fd"}
.icon-plus-sign-alt:before{content:"\f0fe"}
.icon-double-angle-left:before{content:"\f100"}
.icon-double-angle-right:before{content:"\f101"}
.icon-double-angle-up:before{content:"\f102"}
.icon-double-angle-down:before{content:"\f103"}
.icon-angle-left:before{content:"\f104"}
.icon-angle-right:before{content:"\f105"}
.icon-angle-up:before{content:"\f106"}
.icon-angle-down:before{content:"\f107"}
.icon-desktop:before{content:"\f108"}
.icon-laptop:before{content:"\f109"}
.icon-tablet:before{content:"\f10a"}
.icon-mobile-phone:before{content:"\f10b"}
.icon-circle-blank:before{content:"\f10c"}
.icon-quote-left:before{content:"\f10d"}
.icon-quote-right:before{content:"\f10e"}
.icon-spinner:before{content:"\f110"}
.icon-circle:before{content:"\f111"}
.icon-reply:before{content:"\f112"}
.icon-github-alt:before{content:"\f113"}
.icon-folder-close-alt:before{content:"\f114"}
.icon-folder-open-alt:before{content:"\f115"}
.ir{background-color:transparent;border:0;overflow:hidden;*text-indent:-9999px}
.ir:before{content:"";display:block;width:0;height:100%}
.hidden{display:none!important;visibility:hidden}
.visuallyhidden{border:0;clip:rect(0 0 0 0);height:1px;margin:-1px;overflow:hidden;padding:0;position:absolute;width:1px}
.visuallyhidden.focusable:active,.visuallyhidden.focusable:focus{clip:auto;height:auto;margin:0;overflow:visible;position:static;width:auto}
.invisible{visibility:hidden}
.clearfix:before,.clearfix:after{content:" ";display:table}
.clearfix:after{clear:both}
.clearfix{*zoom:1}
@media print{*{background:transparent!important;color:#000!important;box-shadow:none!important;text-shadow:none!important}
a,a:visited{text-decoration:underline}
a[href]:after{content:" (" attr(href) ")"}
abbr[title]:after{content:" (" attr(title) ")"}
.ir a:after,a[href^="javascript:"]:after,a[href^="#"]:after{content:""}
pre,blockquote{border:1px solid #999;page-break-inside:avoid}
thead{display:table-header-group}
tr,img{page-break-inside:avoid}
img{max-width:100%!important}
@page{margin:.5cm}
p,h2,h3{orphans:3;widows:3}
h2,h3{page-break-after:avoid}
}
.geom2d{font-size:24px}
.geom2d canvas{position:absolute;top:100px;left:30px}
.geom2d .slider-container{background:url(../images/slider-bg-1.png) no-repeat 50% 50%;position:absolute;left:920px;top:20px;width:52px;height:672px;-webkit-background-size:100%;-moz-background-size:100%;background-size:100%}
.geom2d .ui-slider{position:relative;width:52px;height:612px;margin:30px 0;border-style:none}
.geom2d .ui-slider .ui-slider-handle{width:41px;height:41px;background:url(../images/slider-icon-1.png) no-repeat 50% 50%;-webkit-background-size:100%;-moz-background-size:100%;background-size:100%;border-style:none;position:absolute;z-index:100;margin:0 0 -24px 5px}
.geom2d .slider-label{-webkit-transform:rotate(90deg);-moz-transform:rotate(90deg);-o-transform:rotate(90deg);-ms-transform:rotate(90deg);transform:rotate(90deg);position:absolute;left:800px;top:400px;width:400px}
.geom2d .legend{position:absolute;top:100px;left:600px}
.geom2d .showhide{background-image:url(../images/toggle.png);-webkit-background-size:cover;-moz-background-size:cover;background-size:cover;width:100px;height:55px}
.geom2d .showhide.shown{background-image:url(../images/toggle.png)}
.geom2d table{font-size:18pt;color:#0e3000;margin:30px 0 0 -70px}
.geom2d table th{width:150px}
.geom2d table td,.geom2d table th{padding:20px 10px;border:3px solid #f0f505}
.geom2d .right-sidebar{position:absolute;top:0;left:83%;height:100%;width:17%;background-color:#fff;opacity:.4;-ms-filter:"alpha(Opacity=40)";filter:alpha(opacity=40);z-index:0}
/*.page{background: -webkit-radial-gradient(center,circle farthest-side,#9ECE61 0,#669D40 100%); background:-moz-radial-gradient(center,circle farthest-side,#9ECE61 0,#669D40 100%);background:-o-radial-gradient(center,circle farthest-side,#9ECE61 0,#669D40 100%);background:-ms-radial-gradient(center,circle farthest-side,#9ECE61 0,#669D40 100%);}*/

body{background: -webkit-radial-gradient(center,circle farthest-side,#9ECE61 0,#669D40 100%);}



.vkBtn{vertical-align:middle; text-align:center; display:table-cell; border: 1px solid #fff; top:100px;}

  @font-face{font-family:'GillSansInfant'; src:url(../fonts/font/gilsbbd.ttf)}
  @font-face{font-family:'GillSansReg'; src:url(../fonts/font/gilsbrg.ttf)}
  @font-face{font-family:'mclarenregular'; src:url(../fonts/font/McLarenRegular.ttf)}

 #btnStart{font-family:'GillSansInfant'; color:#fff; background:-webkit-gradient(linear,left top,left bottom,color-stop(0,#a0cf62),color-stop(1,#6fae47));background:-webkit-linear-gradient(top,#75D018 0,#3B6214 100%);background:-moz-linear-gradient(top,#a0cf62 0,#6fae47 100%);background:-o-linear-gradient(top,#a0cf62 0,#6fae47 100%);background:-ms-linear-gradient(top,#a0cf62 0,#6fae47 100%);background:linear-gradient(top,#a0cf62 0,#6fae47 100%);}

@font-face{font-family:'myFontfamily'; src:url(../fonts/font/GilSandsRegular.ttf)}

.head
{
position:absolute;
border:0px solid #000;
width:1024px;
height:120px;
text-align:center;
top:0px;
line-height: 75px;

color:#fff;
/*font-family:GillSansInfant;*/
font-size:28px;
}

.activity{
position:absolute;
border-radius: 10px;
text-align:center;
width: 150px;
left: 400px;
color:#fff;
/*font-family:GillSansInfant;*/
font-size:28px;
cursor: pointer;
background-image: -webkit-gradient(linear,left top,left bottom,color-stop(0,#fff260),color-stop(1,#e1b516));
background-image: -webkit-linear-gradient(top,#fff260 0,#e1b516 100%);
background-image: -moz-linear-gradient(top,#fff260 0,#e1b516 100%);
background-image: -o-linear-gradient(top,#fff260 0,#e1b516 100%);
background-image: -ms-linear-gradient(top,#fff260 0,#e1b516 100%);
background-image: linear-gradient(top,#fff260 0,#e1b516 100%);
}


#btnStart span{
    display: inline-table;
    position: absolute;
    top: 0px;
    bottom: 0px;
    margin: auto;
    width: 100%;
    text-align: center;
    border: 0px solid #000;
    /*font-family:GillSansInfant;*/
}

.closeBtn, .closeBtn1{
    display: block;
    position: absolute;
    right: 10px;
    top: 2px;
    font-size: 35px;
    z-index: 100;
    font-family: Icons;
    width: 30px;
    height: 30px;
}

.vcloseBtn{
    display: block;
    position: absolute;
    right: 5px;
    top: 0px;
    cursor: pointer;
    font-size: 16pt;
    z-index: 100;
    /*font-family:GillSansInfant;*/
}


.inst{
    position: absolute;
    right: 150px;
    bottom: 20px;
    width: 40px;
    height: 38px;
    background: url(../images/quiz_btn.png) no-repeat;
    cursor: pointer;
}

#containerMain
{
    position: absolute;
    left: 0px;
    right: 0px;
    top: 90px;
    margin: auto;
    width: 1024px;
    height: 350px;
    color: #ff0080;
    border-top: solid 3px #27ccb7;
    border-bottom: solid 3px #27ccb7;
    background-image: -webkit-linear-gradient(top,#d7ffbd, #d7ffbd 100%);
    /* border: 1px solid #000; */
}

.container1{
    position: absolute;
    width: 200px;
    height:200px;
    left:132px;
    top: 9px;
    font-family: GillSansReg;
    font-size: 21px;
    text-align: center;
    background-image: url("../images/balls_basket5.png");
    background-size:contain;
    background-repeat: no-repeat;
    z-index: 10;
    
}
.container2{
    position: absolute;
    width: 800px;
    height: 295px;
    left: 0px;
    top: 0px;
    bottom: 0px;
    right: 0px;
    margin: auto;
    background-size: contain;
    background-repeat: no-repeat;
    background-image: url("../images/4blue_3red.jpg");
    /*background-size: 100% 100%;*/
    
}
.container3{
    position: absolute;
    width: 200px;
    height:200px;
    left:683px;
    top: 9px;
    background-size: contain;
    background-repeat: no-repeat;
    background-image: url("../images/questionmark.png");
    
}

#scatterContainer{
    position: absolute;
    left: 0px;
    top: 500px;
    width: 1024px;
    height: 200px;
    border-top:  4px solid #fff;
    border-bottom:  4px solid #fff;
}

.question{
    display: block;
    position: absolute;
    top: 0px;
    bottom: 0px;
    width: 545px;
    height: 190px;
    border: 2px solid #7ea0c6;
    left: 35px;
    right: 0px;
    margin: auto;
    background: -moz-radial-gradient(center,circle farthest-side,#597CA5 0,#45638D 100%);
    background: -webkit-radial-gradient(center,circle farthest-side,#597CA5 0,#3D5485 100%);
    background: -webkit-gradient(radial,center center,0,center center,100%,color-stop(0%,#597CA5),color-stop(65%,#82BC54),color-stop(100%,#45638D));
    color: #fff;
    padding: 20px 35px 35px;
    font-size: 20px; 
    text-align: left;
    z-index: 10001;
    text-shadow: 0px 2px #000;
}
/*.ins_text {
  padding-top: 30px;
  padding-left: 8px;
  font-family: myFontfamily;
}*/
.info-text{line-height:27px;}

#blocker{
    display: block;
    position: fixed;
    left: -25%;
    top: -25%;
    width: 150%;
    height: 150%;
    background: rgba(0,0,0,0.5);
    z-index: 10001;
}
#vkey_blocker{
    display: block;
    position: absolute;
    width: 1024px;
    height: 768px;
    left: 0px;
    right: 0px;
    margin: auto;
    top: 0px;
    background: rgba(0,0,0,0);
    z-index: 2000;
}


.block_obj {
    background-image:url(../images/tile-yellow.png);
    background-size: 100% 100%;
    background-repeat: no-repeat;
    width: 30px;
    height:30px;
}

.contentFeedback{
	width: 100%;
	height: 44px;
	/*background-color: rgba(47,47,47,0.5);*/
	position: absolute;
	bottom: 0;
	overflow: hidden;
	margin-bottom: 0px;
}

.btReset,.btInfo,.btFeedback{
	float: right;
	/*background-color: red;*/
	width: 34px;
	height: 34px;
	cursor: pointer;
	-webkit-tap-highlight-color:rgba(0,0,0,0);
	-webkit-tap-highlight-background:<background>;
}


.btReset{margin-right: 50px; cursor: default;}

.icoReset{background-image: url('../images/btResetOn@2x.png'); background-repeat: no-repeat;  opacity:0.5;}


.icoResetMove{
	-webkit-animation: reset 1s;
}


@-webkit-keyframes reset {
	0%{
		-webkit-transform: rotate(0deg);
		background-image: url('../images/btResetOn@2x.png');
	}

	50%{
		
		background-image: url('../images/btResetOff@2x.png');
		
	}

	100%{
		-webkit-transform: rotate(-360deg);
		background-image: url('../images/btResetOn@2x.png');
	}

}


.btInfo,.btFeedback{margin-right: 12px; margin-left: 5px;}


.btFeedback{
	cursor: default;
}


.icoReset,.icoFeed{
	background-position: center center;
	background-size: 100%;
	width: 34px;
	height: 34px;
}

.icoInfo{
	width: 29px;
	height: 31px;
	background-position: center center;
	background-size: 100%;
        opacity: 0.6;
}


.icoInfo{background-image: url('../images/btInfoOn.png'); background-repeat: no-repeat;}
.icoInfoMove{background-image: url('../images/btInfoOff.png'); background-repeat: no-repeat;}


.icoFeed{background-image: url('../images/btFeedOff@2x.png');}

.icoFeedMove{background-image: url('../images/btFeedOn@2x.png');}


.score{
	float: right;
	height: 34px;
	width: 130px;
	border-radius: 20px;
	background-color: rgba(27,27,27,0.2);
	overflow: hidden;
	margin-right: 12px;
	display: none;
}


#contCorrect,#contIncorrect{
	width: 49%;
	height: 100%;
	/*background-color: yellow;*/
	float: left;
	text-align: center;
	vertical-align: middle;
	/*font-family: 'GillSans-Light';*/
	font-size: 18px;
	padding-top: 7px;
}

.equal {
padding-left: 10px;
padding-right: 10px;
}

#box_1,#box_2,#box_3,#box_4,#box_5,#box_6,#box_7{
width: 35px;
height: 32px;
font-family: GillSansReg;
text-align: center;
font-size: 21px;
max-width: 65px;
min-width: 15px;
margin-left: 2px;
margin-right: 2px;
background-color: #d3ecb3;
border: 1px dashed #000;
padding-bottom: 2px;}


.tilesContainer
{
    position: absolute;
    left: 0px;
    top: 540px;
    width: 1024px;
    padding-top: 12px;
    padding-right: 20px;
    padding-left: 120px;
    background-image: -webkit-linear-gradient(top,#007369,#008c72 100%);
    border-top: solid 3px #fff;
    border-bottom: solid 3px #fff;
}
.tile
{
    float: left;
    width: 62px;
    height: 62px;
    border-radius: 10px;
    background: #ffc150;
    border: 2px solid #fff; 
    font-size: 40px;
    color: #000;
    /*text-shadow: 2px 2px 0 #d37c00;*/
    /*text-shadow: red;*/
    margin-right: 17px;
    margin-bottom: 14px;
    text-align: center;
    /*background-image: -webkit-linear-gradient(top,#fd9929 0,#e1b516 100%);*/
    font-family: 'mclarenregular';
}

.symbol1 
{
    float: left;
    width: 60px;
    height: 60px;
    border-radius: 10px;
    /*border: 1px solid #000;*/
    font-size: 48px;
    color:#fff;
    text-shadow: 2px 2px 0 #d37c00;
    text-shadow: red;   
    margin-right: 25px; 
    margin-bottom: 14px;
    text-align: center;
    background-image: -webkit-linear-gradient(top,#fd9929 0,#e1b516 100%);
    padding-top: 2px;
}

.symbol2
{
    float: left;
    width: 60px;
    height: 60px;
    border-radius: 10px;
    /*border: 1px solid #000;*/
    font-size: 48px;
    color:#fff;
    text-shadow: 2px 2px 0 #d37c00;
    text-shadow: red;   
    margin-right: 25px; 
    margin-bottom: 14px;
    text-align: center;
    background-image: -webkit-linear-gradient(top,#fd9929 0,#e1b516 100%);
    padding-top: 2px;
}
.inputcontainer
{
    position: absolute;
    top: 440px;
    left: 0px;
    background: #02a676;
    width: 545px;
    height: 100px;
    padding-left: 75px;
    padding-top: 20px;
    /* border-bottom: 1px solid #ffffff; */
}
.inputBox
{
    float: left;
    width: 62px;
    height: 62px;
    margin-left: 22px;
    background: #ffc150;
    border-radius: 10px;
    border: 1px dashed #2f5941;
    font-size: 48px;
}
.inputBox1 {
    float: left;
    width: 60px;
    height: 60px;
    margin-left: 22px;
    background-color: #ff8e30;
    border-radius: 10px;
    border: 2px solid #fff;
    font-size: 48px;
    color: #000;
    /*text-shadow: 2px 2px 0 #d37c00;*/
    /*font-size: 40px;*/
    text-align: center;
    /*background-image: -webkit-linear-gradient(top,#f37606 0,#dd603d 100%);*/
    font-family: 'mclarenregular';
    font-weight: bold;
    line-height: 60px;
}
#two{
    font-size: 50px;
}
.input1
{
    float: left;
    width: 60px;
    height: 60px;
    margin-left: 22px;
    background: #fff;
    border-radius: 10px;
    border: 1px solid #000;
    font-size: 48px;
}
.content {
    position: absolute;
    height: 90px;
    top: 0px;
    left: 0px;
    right: 0px;
    background-color: #02a676;
    border-top:  solid 3px #27ccb7;
    width: 1024px;
    /* box-shadow: 0px 1px 0px; */
}
.txt{position: absolute; text-align: left; left:3px;color: #fff; font-size: 24px;  padding-top: 16px;
    padding-left: 200px;}

.content1
{
    position: absolute;
    width: 500px;
    height: 100px;
    padding-top: 36px;
    padding-left: 154px;
    background-color: #02a676;
    /* float: left; */
    top: 440px;
    left: 540px;
    font-size: 24px;
    /* border-bottom: 2px solid #ffffff; */
    /* border-radius: 15px; */
    color: #fff;
}
.content1 .inputBox
{
    float: left;
    width: 62px;
    height: 62px;
    margin-left: 10px;
    margin-right: 10px;
    margin-top: -16px;
    background: #ffc150;
    border-radius: 10px;
    border: 1px dashed #004000;
    font-size: 48px;
}

#first
{
    float: left;
    margin-left:-75px;
}
#second
{
    float: left;
}

#tapQAudio{
    position: absolute;
    top: 23px;
    left: 720px;
    width: 50px;
    height: 50px;
    background: url('../images/audioICON.png') no-repeat;
    background-size: 100% 100%;
}
#tapQAudio1{
    position: absolute;
    top: 25px;
    left: 20px;
    width: 50px;
    height: 50px;
    background: url('../images/audioICON.png') no-repeat;
    background-size: 100% 100%;
}

.kitten1_1{
    position: absolute;
    width: 142px;
    height: 125px;
    top: 18px;
    left: 285px;
    font-family: GillSansReg;
    font-size: 21px;
    text-align: center;
    border-radius: 20px;
    /* border: 2px solid #ffff00; */
    background-image: url("../images/kitten_head.png");
    background-size: contain;
    background-repeat: no-repeat;
}



Activity.js
===========

/* This is a activity javascript based on spinner.js
 * ----SingleSpinner 0.8
 * developed by Lapiz
 */

var pageContainer, menuContainer, page0, diceCanvas, btnSpin, dice,  savedState ,tilesContainer;
var numTiles = 10;
var audinst=new Audio('audio/instruct.mp3');
var ansTop = new Audio('audio/ansPart0.mp3');
var ansEmpty = new Audio('audio/ansPart1.mp3');
var answered = new Audio();
var mytile =new Array("1","2","3","4","5","6","7","8","9","10");
$(document).ready(
    function(){
	
	setTimeout(function(){
		$('body').css({'-webkit-transform':'scale(1)'});  
	  },500);
            
            document.onkeydown = function(){
      if(window.event && window.event.keyCode == 9) 
      { // Capture and remap TAB
      window.event.keyCode = 9;
      }
      if(window.event && window.event.keyCode == 9) 
        { // New action for TAB
	  //alert('The TAB key was pressed');
	return false; 
	}
}


	//$('body').css({'-webkit-transform':'scale(0.91)'});
	//This function is called after the page loads. We are adding the all the elements to the html here.
        var table=["<div id=\"blocker\" onclick=\"instruct()\" ></div><div class=\"question\"><div style=\"position:absolute; left:2%; top:6%; opacity:0.6;\" ><div><img src=\"images/btInfoOn.png\" width=\"30px\" height=\"30px\" /></div></div><span style=\"text-align:left; font-family:myFontfamily; left:8.5%; font-size:30px;  line-height:1.4em; width:450px; position:absolute; top:45px;\">Fill in the equation and the sentence.</span><i style=\"float:right; opacity: .6;\" class=\"closeBtn icon icon-emove\" onclick=\"instruct()\" >&#x000D7;</i><div style=\"position:absolute;  left:43%; top:60%;\" onclick=\"AudioState()\"><img src=\"images/audioICON.png\" width=\"50px\" height=\"50px\" /></div></div>"];
        pageContainer = $("<div id=\"interactive-container\" />");
        menuContainer = $("<div id=\"page-container\" />");
	menuContainer1 = $("<div id=\"page-container1\" />");
        footerContainer = $("<div class=\"container\"><div class=\"contentFeedback\"><div class=\"btReset\"><div class=\"icoReset\"></div></div><div class=\"btInfo\"><div id=\"icoinf\" onclick=\"openInst()\" class=\"icoInfo\"></div></div><div class=\"btFeedback\"><div class=\"icoFeed\"></div></div><div class=\"score\"><div id=\"contCorrect\">0 </div><div id=\"contIncorrect\">0 </div></div></div></div></div>");
	page0 = $("<div id=\"page-0\" class=\"page\" />");
	
	Partimage = $("<div id=\"containerMain\"><div class=\"container2\"></div></div>");
	
	tilesContainer = $('<div class="tilesContainer"></div>');
	inputcontainer = $('<div class="content"><span class=\"txt\">There are 7 birds altogether. 3 birds are red. <br/>How many blue birds are there?<div id="tapQAudio" onclick=\"AudioTop()\"></div></div></div><div class="inputcontainer"><div class="inputBox dropbox"></div><div class="inputBox inputBox1" id="two">&#x02212; </div><div class="inputBox dropbox"></div><div class="inputBox inputBox1"  id="four">=</div><div class="inputBox dropbox" ></div></div><div class="content1"><div id="first"><span id="sp">There are</span><div id="tapQAudio1" onclick=\"playAnsAudio()\"></div></div><div class="inputBox dropbox" ></div> <div id="second"><span id="sp1">blue birds.</span></div></div>');
        page0.append(table[0]);
	
	page0.append(footerContainer);
	page0.append(Partimage);
	page0.append(inputcontainer);
        menuContainer.append(page0);
	page0.append(tilesContainer);
	pageContainer.append(menuContainer1);
	pageContainer.append(menuContainer);
        $('body').append(pageContainer);
        
	
 ///------------------------------///
 
//$('.inputcontainer').find('#two').addClass('input1');
//$('.inputcontainer').find('#four').addClass('input1');
toggleClassButton($(this),'icoInfoMove');
$(".icoInfo").on('click',function () {
$('.question,#blocker').show();
toggleClassButton($(".icoInfo"),'icoInfoMove');
$('#icoinf').css('background-image', 'url('+'./images/btInfoOn.png'+')');

});

LoadTiles();
ApplyDraggables();


    //$('.icoReset').css({'opacity':'1'});

$(".icoReset").bind('click',resetfn);

/*Saved state*/
    eventBroker = _({}).extend(require('chaplin/lib/event_broker'));    
    setTimeout(function(){
	eventBroker.publishEvent("#fetch", { type : 'state' }, function(state) {
	if (state) {
		_.each(JSON.parse(state), function(value, key, list) {
                    if(key == "inputVal") {
		    savedState = value;
		    $('.inputcontainer').html(value);
		    
		}
		if(key == "inputVal1") {
		    savedState = value;
		    $('.content1').html(value);
    		}
	if(key == "resetstatus") {
		    savedState = value;
		    $('.icoReset').css('opacity', value);
		}	
		ApplyDraggables();
		$('.dropbox').find('.tile').draggable("destroy");
		 $('.dropbox').find('.tile').draggable({
		zIndex: 10000,
		stop: function (){
		    console.log($(this).html());
		    $(this).remove();
		    //$('.dropbox').find('.tile').remove();
		    $(this).removeAttr('style');
		}
		});
		   
		//CheckDropComplete();
		
                });
	}
    },1000);
});
eventBroker.subscribeEvent('#doSave', function(state) {
    var state = {};
    state = {"inputVal":$('.inputcontainer').html(),"inputVal1":$('.content1').html(),"resetstatus":$('.icoReset').css("opacity")};
    var message = {
	    type : 'state',
	    data : JSON.stringify(state)
    };
    eventBroker.publishEvent("#save", message);
});
    audinst.play();
    try{
	ansTop.pause();
	ansTop.currentTime = 0
    }
    catch(e){}
});
function instruct(){
        try{
	    audinst.currentTime = 0
	}catch(e){};
        try{audinst.pause()}catch(e){}
	$('.question,#blocker').hide();
	$('.icoInfo').css({'opacity':'1'});
	try {
		$('#instructions-button-container').unbind('click',openInst);
	} catch(e){}
		$('#instructions-button-container').bind('click',openInst);
}

function openInst(){
     audinst.play();
     try{ansTop.pause()}catch(e){}
	 try{ansEmpty.pause();}catch(e){}
     try{answered.pause();}catch(e){}
	 try{ansTop.currentTime = 0}catch(e){};
	 try{ansEmpty.currentTime = 0}catch(e){};
	try{answered.currentTime = 0}catch(e){};
	$('.question,#blocker').show();
	$('.icoInfo').css({'opacity':'0.5'});
}

function toggleClassButton(element,className){
	
	var currentButton=element;
	if(!currentButton.hasClass(className)){
		currentButton.addClass(className);
	}else{
		currentButton.removeClass(className);	
	}
}
function LoadTiles(){
    for(var tile=0; tile<numTiles; tile++)
    {
	$('.tilesContainer').append('<div  id="aa'+tile+'" class="tile">'+mytile[tile]+'</div>');
	
    }
    $(".tilesContainer").find("#aa20").removeClass('tile');
    $(".tilesContainer").find("#aa21").removeClass('tile');
    
}

function CheckDropComplete(){
    if ($('.dropbox').length>=1) {
	  $('.icoReset').css({'opacity':'1'});
	 
    }
    else{
	$('.icoReset').css({'opacity':'0.5'});  
    }
}

function ApplyDraggables(){
    try{
    $('.tile').draggable("destroy");
    
    $('.dropbox').droppable("destroy");
    }
    catch(e){}
    $('.tile').draggable({
	helper:"clone",revert:"invalid",
	zIndex: 10000,
    });

    $('.dropbox').droppable({
	
	drop:function (event, ui){
	    $(this).html($(ui.helper).clone().removeAttr('style').removeClass('ui-draggable').removeClass('ui-draggable-dragging').css({'z-index':'9999','left':'-1px','top':'-1px'}).draggable());
	    $(this).find('.tile').draggable({
		zIndex: 10000,
		stop: function (){
		    $(this).remove();
		    //CheckDropComplete();
		     isSingle();
		},
	    });
	 
    //$('.tile').draggable("destroy");
    
    //$('.dropbox').droppable("destroy");
    
    
	CheckDropComplete();
	isSingle();
	},accept:'.tile'
	
    }); 
}

function resetfn(){
    if ($('.icoReset').css('opacity')==1) {
	$('.icoReset').removeClass('icoResetMove');
	try{ansTop.pause()}catch(e){}
	try{ansEmpty.pause();}catch(e){}
	try{ansTop.currentTime = 0}catch(e){};
	try{ansEmpty.currentTime = 0}catch(e){};
	try{answered.pause();}catch(e){}
	try{answered.currentTime = 0}catch(e){};
	var to=setTimeout(function(){
	    clearInterval(to);
	    $('.icoReset').addClass('icoResetMove');
            $(".icoReset").css({'opacity':'0.5'});
	    
	},200);
        setTimeout(function(){    
            $('.dropbox').html('');
	    $('.dropbox').css({'border':'1px dashed #000'});
	    $('.icoReset').css({'opacity':'0.5'});
	    ApplyDraggables()
        },100);
	 $("#sp").text("There are");
	$("#sp1").text("blue birds.");
    }
}
function gotPic(event) {
    
        if(event.target.files.length == 1 && event.target.files[0].type.indexOf("image/") == 0) {
	    console.log(event.target.files[0]);
           var file    = event.target.files[0];
	    var reader  = new FileReader();
	    reader.onloadend = function () {
		 $("#photoHolder").css("background-image", 'url('+reader.result+')');
	      }
	    
	      if (file) {
		reader.readAsDataURL(file);
	      } else {
		$("#photoHolder").css("background-image", "");
	      }
        }
	}

function saveFunction(){
    eventBroker.publishEvent("#doSave");
}

function AudioState() {
    if (audinst.paused == false) {
	audinst.pause();
	audinst.currentTime = 0;
	audinst.play();
    }
    else{
	audinst.play()
    }
}

function AudioTop() {
    if (ansTop.paused == false) {
	ansTop.pause();
	try{ansTop.currentTime = 0}catch(e){}
	ansTop.play();
    }
    else{
	ansTop.play()
    }
	try{audinst.pause();}catch(e){}
	try{ansEmpty.pause();}catch(e){}
	try{answered.pause();}catch(e){}
	$('#tapAudio').css({'pointer-events':'auto'});
	try{audinst.currentTime = 0}catch(e){};
	try{ansEmpty.currentTime = 0}catch(e){};
	try{answered.currentTime = 0}catch(e){};
}



function playAnsAudio() {
	try{ansTop.currentTime = 0}catch(e){};
        try{ansTop.pause()}catch(e){}
    //$(this).css({'pointer-events':'none'});
    var droppedNumber = $('.content1').find('.tile').text();

    if(droppedNumber=="")
    {
	try{ansEmpty.pause();}catch(e){}
	ansEmpty.play();
	try{ansEmpty.currentTime = 0}catch(e){};
	ansEmpty.addEventListener('ended', function (){
	$('#tapAudio').css({'pointer-events':'auto'});
	});
    }
    else {
	
        answered.src="audio/ans_"+droppedNumber+".mp3";
	try{ansTop.pause()}catch(e){}
	try{audinst.pause();}catch(e){}
	try{ansEmpty.pause();}catch(e){}
	try{ansTop.currentTime = 0}catch(e){};
	try{audinst.currentTime = 0}catch(e){};
	try{ansEmpty.currentTime = 0}catch(e){};
	try{answered.pause();}catch(e){}
	try{answered.currentTime = 0}catch(e){};
        answered.play();
	//$('#tapAudio').css({'pointer-events':'auto'});
	answered.addEventListener('ended', function (){
	    $('#tapAudio').css({'pointer-events':'auto'});
	    try {answered.currentTime = 0;} catch(e) {}
	});
    }
}


function isSingle() {
    var curVal = $('.content1').find('.tile').text();
    console.log(curVal)
	if (curVal == 1) {
	    $("#sp").text("There is");
	    $("#sp1").text("blue bird.");
	}
	else{
	    $("#sp").text("There are");
	    $("#sp1").text("blue birds.");
	}
}

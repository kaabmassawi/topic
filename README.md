<?xml version="1.0" encoding="UTF-8" ?>
<!DOCTYPE html>
<html dir='rtl' xmlns='http://www.w3.org/1999/xhtml' xmlns:b='http://www.google.com/2005/gml/b' xmlns:data='http://www.google.com/2005/gml/data' xmlns:expr='http://www.google.com/2005/gml/expr'>
<head>
<meta charset='utf-8'/>
<b:if cond='data:blog.url == data:blog.homepageUrl'><link href='https://plus.google.com/u/0/+iHussam' rel='author'/></b:if>
<b:if cond='data:blog.pageType == &quot;index&quot;'>
    <title><data:blog.pageTitle/></title>
<b:else/>
    <b:if cond='data:blog.pageType == &quot;error_page&quot;'>
        <title>404: الصفحة غير موجودة ~ <data:blog.title/></title>
    <b:else/>
        <title><data:blog.pageName/> ~ <data:blog.title/></title>
    </b:if>
</b:if>
<meta content='width=device-width,initial-scale=1,minimum-scale=1,maximum-scale=1' name='viewport'/>
<meta content='text/html; charset=UTF-8' http-equiv='Content-Type'/>
<meta content='blogger' name='generator'/>
<link expr:href='data:blog.homepageUrl + &quot;favicon.ico&quot;' rel='icon' type='image/x-icon'/>
<link expr:href='data:blog.url' rel='canonical'/>
<link expr:href='data:blog.homepageUrl + &quot;feeds/posts/default&quot;' expr:title='data:blog.title + &quot; - Atom&quot;' rel='alternate' type='application/atom+xml'/>
<link expr:href='data:blog.homepageUrl + &quot;feeds/posts/default?alt=rss&quot;' expr:title='data:blog.title + &quot; - RSS&quot;' rel='alternate' type='application/rss+xml'/>
<link expr:href='&quot;http://www.blogger.com/feeds/&quot; + data:blog.blogId + &quot;/posts/default&quot;' expr:title='data:blog.title + &quot; - Atom&quot;' rel='alternate' type='application/atom+xml'/>
<link href='http://www.blogger.com/openid-server.g' rel='openid.server'/>
<link expr:href='data:blog.homepageUrl' rel='openid.delegate'/>
<b:if cond='data:blog.pageType == &quot;item&quot;'>
<b:if cond='data:blog.postImageThumbnailUrl'>
<link expr:href='data:blog.postImageThumbnailUrl' rel='image_src'/>
</b:if>
<b:if cond='data:blog.metaDescription != &quot;&quot;'>
<meta expr:content='data:blog.metaDescription' name='description'/>
<b:else/>
<meta expr:content='data:blog.pageName + &quot; - &quot; + data:blog.title' name='description'/>
</b:if>
</b:if>
<b:if cond='data:blog.url == data:blog.homepageUrl'>
<meta content='DESCRIPTION HERE' name='description'/>
<meta content='KEYWORDS HERE' name='keywords'/>
</b:if>
<meta content='YOURFBAPPSID' property='fb:app_id'/>
<meta content='YOURFBUSERID' property='fb:admins'/>
<b:if cond='data:blog.pageType == &quot;error_page&quot;'>
<title>Page Not Found</title>
<meta content='5;/' http-equiv='refresh'/>
</b:if>

<link href='https://googledrive.com/host/0Bxyf5AC_ilPwZFpoRVdjVDhVcjQ' rel='stylesheet' type='text/css'/>
<link href='http://fonts.googleapis.com/css?family=Oswald:400,300,700|Electrolize' rel='stylesheet' type='text/css'/>
<link href='http://fonts.googleapis.com/earlyaccess/droidarabickufi.css' rel='stylesheet'/>



&lt;style type=&quot;text/css&quot;&gt;
&lt;!-- /*<b:skin><![CDATA[

/*
-----------------------------------------------
Blogger Template Style
Name:     ideaofmaine
Designer: Houssam Baha
URL:      www.ar1web.com
----------------------------------------------- */


/* CSS Reset */
html,body,div,span,applet,object,iframe,h1,h2,h3,h4,h5,h6,p,blockquote,pre,a,abbr,acronym,address,big,cite,code,del,dfn,em,img,ins,kbd,q,s,samp,small,strike,strong,sub,sup,tt,var,b,u,i,center,dl,dt,dd,ol,ul,li,fieldset,form,label,legend,table,caption,tbody,tfoot,thead,tr,th,td,article,aside,canvas,details,embed,figure,figcaption,footer,header,hgroup,menu,nav,output,ruby,section,summary,time,mark,audio,video{margin:0;padding:0;border:0;font-size:100%;font:inherit;vertical-align:baseline;}

/* CSS HTML5 */
article,aside,details,figcaption,figure,footer,header,hgroup,menu,nav,section{display:block;}body{line-height:1;display:block;}*{margin:0;padding:0;}html{display:block;}ol,ul{list-style:none;}blockquote,q{quotes:none;}blockquote:before,blockquote:after,q:before,q:after{background:transparent;}table{border-collapse:collapse;border-spacing:0;}

/* CSS Framework */
.navbar,.post-feeds,.feed-links{display:none;}
.section,.widget{margin:0 0 0 0;padding:0 0 0 0;}
strong,b{font-weight:bold;}
cite,em,i{font-style:italic;}
a:link{color:#0fa9cd;text-decoration:none;outline:none;transition:all 0.25s;}
a:visited{color:#637182;text-decoration:none;}
a:link:hover{color:#444;text-decoration:none;}
a:visited:hover{color:#444;text-decoration:none;}
a img{border:none;border-width:0;outline:none;}
img{max-width:100%;vertical-align:middle;border:0;}
abbr,acronym{border-bottom:1px dotted;cursor:help;}
sup,sub{vertical-align:baseline;position:relative;top:-.4em;font-size:86%;}
sub{top:.4em;}small{font-size:86%;}
kbd{font-size:80%;border:1px solid #b4babe;padding:2px 5px;border-bottom-width:2px;}
mark{background-color:#ffce00;color:#182025;}
p,blockquote,pre,table,figure,hr,form,ol,ul,dl{margin:1.5em 0;}
hr{height:1px;border:none;background-color:#46515e;}

/* CSS Blog Heading */
h1,h2,h3,h4,h5,h6{font-weight:700;line-height:normal;margin:0 0 0.6em;}
h1{font-size:200%}
h2{font-size:180%}
h3{font-size:160%}
h4{font-size:140%}
h5{font-size:120%}
h6{font-size:100%}

/* CSS Form */
input,button,select,textarea{font:'Open Sans';font-size:100%;line-height:normal;vertical-align:baseline;}
textarea{display:block;box-sizing:border-box;}
pre,code{font-family:'Open Sans';color:#46515e;}
pre{white-space:pre;word-wrap:normal;overflow:auto;}
blockquote{margin-right:2em;margin-left:2em;padding:1em 1em;font-size:100%;background:#fff9e7;color:#444;border:2px solid #f0ebda;}
.awal{float:right;color:#0fa9cd;background:#fff;line-height:30px;padding-top:1px;padding-left:5px;font-family:times;font-size:50px;}

/* CSS List */
ul,dl{margin:.5em 3em .5em 0em}
ol{list-style:decimal outside}
ul{list-style:disc outside}
li{margin:.5em 0}
dt{font-weight:bold}
dd{margin:0 2em .5em 0}

/* CSS List Custom */
.post ul li span{position:relative;display:block;padding:5px 8px;margin-bottom:10px;background:#fafafa;color:#666;text-decoration:none;transition:all .3s ease-out;}
.post ul li span:hover{background:#f9f9f9;}
ol {counter-reset:li;list-style: none;font:15px 'Open Sans', 'lucida sans';
padding:0;margin-bottom:4em;text-shadow: 0 1px 0 rgba(255,255,255,.5);}
ol ol {margin:0 2em 0 0;}
.post ol li{position:relative;display:block;padding:.4em .8em .4em .4em;
margin:.5em 2.5em .5em 0;background:#fafafa;color:#666;text-decoration:none;
transition:all .3s ease-out;}
.post ol li:hover{background:#f9f9f9;}
.post ol li:before{content:counter(li);counter-increment:li;position:absolute; 
right:-2.5em;top:50%;margin-top:-1em;background:#0fa9cd;color:#fff;height:2em;width:2em;
line-height:2em;text-align:center;font-weight:bold;}
.post ol li:after{position:absolute; content:'';border: .5em solid transparent;
right:-1em;top:50%;margin-top:-.5em;transition:all .3s ease-out;}
.post ol li:hover:after{right:-.5em;border-right-color:#0fa9cd;}
.post ol li span{position:relative;display:block;padding:5px 8px;margin-bottom:10px;background:#fafafa;color:#666;text-decoration:none;transition:all .3s ease-out;}
.post ol li span:hover{background:#f9f9f9;}


/* CSS Post Table */
body {
background: #f7f7f7 url(http://2.bp.blogspot.com/-sTBqwB8nafI/U8kTMlEg17I/AAAAAAAAEZY/x5nQm-DXejw/s0/p6.png) repeat scroll top left;
color:#444;font-family:'Open Sans';font-size:13px;font-weight:400;text-align:right;}
body#layout #outer-wrapper, body#layout .post-inner, body#layout .sidebar {
padding:0 0 0 0;}
body#layout .top-tab-widget-menu ul {display:none;}
.post-body table th, .post-body table td, .post-body table caption{border:none;padding:.8em .12em;text-align:right;vertical-align:top;}
.post-body table.tr-caption-container {border:none;}
.post-body th{font-weight:700;}
.post-body tr{background:#f0f0f0;transition:all 0.3s ease-in-out;}
.post-body tr:hover {background:#e9e9e9;}
.post-body table caption{border:none;font-style:italic;}
.post-body table{text-align:center;margin:0 auto;margin-top:10px;margin-bottom:10px;}
.post-body th{vertical-align:top;text-align:right;font-size:13px;padding:0;border:none;}
.post-body th span{padding:8px 12px;background:#0fa9cd;color:#fff;}
.post-body td{vertical-align:top;text-align:right;font-size:13px;padding:0;border:none;}
.post-body td span{padding:8px 12px;color:#666;}
.post-body table.tr-caption-container td {border:none;padding:0;}
.post-body table.tr-caption-container, .post-body table.tr-caption-container img, .post-body img {max-width:100%;height:auto;}
.post-body td.tr-caption {color:#666;font-size:80%;padding:0!important;}
img {max-width:100%;height:auto;border:none;}
table {max-width:100%;}
body#layout #wrapper, body#layout .post-inner, body#layout .sidebar-inner {
padding:0 0 0 0;}
body#layout .tably {float:right;width:79px;}
body#layout .header-wrapper {margin-top:40px;}
body#layout #navigation {float:left;width:50%;}
body#layout .tably {float:right;width:100%;}
.ct-wrapper {margin:0;padding:0;}
.clear {clear:both;}
.clear:after {visibility:hidden;display:block;font-size:0;content:" ";clear:both;
height:0;}
#navbar-iframe {display:none !important;}
header,nav,section,aside,article,footer {display:block;}

/* CSS Global Wrapper */
#outer-wrapper {width:1015px;overflow:hidden;margin:0 auto;padding:0;}

#post-wrapper {float:right;width:70%;max-width:700px;margin:0 0 10px;}
.post-inner {padding:15px 0 0 15px;}
.blogouter-wrapper {overflow:hidden;position:relative;width:100%;}

#header-wrapper {width:100%;margin:0 auto;margin-bottom:15px;overflow:hidden;}
#header {float:right;width:100%;max-width:257px;}
.header-left {float:left;padding:0;overflow:hidden;margin:0;width:100%;
max-width:728px;}
.header-wrapper2 {position:relative;z-index:999;}
#sidebar-wrapper {float:left;width:30%;max-width:300px;margin:0 auto;}
.sidebar-inner {padding:15px 0;}
 
/*--------Footer----------*/



#PopularPosts1 img {
    border: 5px solid #ccc;
    float: left;
    margin: 15px;
    -webkit-transition: margin 0.5s ease-out;
    -moz-transition: margin 0.5s ease-out;
    -o-transition: margin 0.5s ease-out;
}
#PopularPosts1 img:hover {
    margin-top: 2px;
}

/*-------------Topnav--------*/
#topnav{
width:100%;
margin:0;
padding:0;
background:#55606f;
height: 45px;
border-bottom: 5px solid #EE5F70;
}
#topnav ul{
width: 990px;
margin: 0 auto;
padding: 0;
overflow: hidden;
}
/* This button was generated using CSSButtonGenerator.com */
#topnav ul li {
float: right;
padding: 0 10px 0 10px;
display: block;
margin: 10px 0;
-webkit-transition: all 1s ease .2s;
-moz-transition: all 1s ease .2s;
-o-transition: all 1s ease .2s;
-pie-transition: all 1s ease .2s;
transition: all 1s ease .2s;
}
#topnav ul li a{
margin: 5px;
padding: 0;
color: #fff;
font: normal 12px Electrolize,ges;
text-shadow: 1px 1px 0 #000;
line-height: 2.2em;
}
#topnav ul li span{text-align:center;margin:0;padding:0;color:#00C0F0;text-shadow: 0 1px 0 #000;font:normal 11px tahoma;}
#topnav ul li:hover, #topnav ul li.active {
color: #CCC;
-webkit-transition: all 1s ease .2s;
-moz-transition: all 1s ease .2s;
-o-transition: all 1s ease .2s;
-pie-transition: all 1s ease .2s;
transition: all 1s ease .2s;
}
#topnav ul li a:hover, #topnav ul li.active a {
color: #B0BABE;
}



@font-face {
font-family: 'ges';
src: url('https://dl.dropboxusercontent.com/u/83505058/ge-ss-med-webfont.eot');
src: url('https://dl.dropboxusercontent.com/u/83505058/ge-ss-med-webfont.eot?') format('embedded-opentype'),
url('https://dl.dropboxusercontent.com/u/83505058/ge-ss-med-webfont.woff') format('woff'),
url('https://dl.dropboxusercontent.com/u/83505058/ge-ss-med-webfont.ttf') format('truetype'); }
@font-face {
@font-face {
font-family: 'GESSTwoMediumRegular';
src: url('https://dl.dropboxusercontent.com/u/83505058/ge-ss-med-webfont.eot');
src: url('https://dl.dropboxusercontent.com/u/83505058/ge-ss-med-webfont.eot?') format('embedded-opentype'),
url('https://dl.dropboxusercontent.com/u/83505058/ge-ss-med-webfont.woff') format('woff'),
url('https://dl.dropboxusercontent.com/u/83505058/ge-ss-med-webfont.ttf') format('truetype'); 
}

#main-home{width:100%;height:auto;padding:20px 0;margin:20px 0 0;margin-bottom:30px;overflow:hidden}
#main-left{float:left;width:46%;}
#main-right{float:right;width:46%;margin-right: 20px;}
#gleft .widge

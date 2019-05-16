# Welford-Bouquet1
One page website of Welford Bouquet: https://newwebsite541.wordpress.com/
Used media screens to make it responsive with the Wordpress CMS for desktop, laptop, tablet and mobile. Other features of the site have the hover on the 'Whitby' box, all of the other boxes and the social media buttons currently link to the homepage and have added the website accordingly to the design.


/*General*/

-------

.entry-title {
	display: none;
}

.site-main {
	width: 100%;
	padding: 0;
	border-right: 0;
}

.site-title {
	font-size: 25px;
}

.search-navigation {
	border-top: 0;
}

.site-top {
	display: none;
}

.main-navigation .nav-menu>li+li {
	border-left: 0;
}

.social-navigation {
	display: none;
}

.site-footer {
	display: none;
}

/*Sass*/

$primary-color: #79787b;

--------

/*Main Content HTML*/

--------

<div class="home-two-column">
<div class="home-two-column-left"><a href="https://newwebsite541.wordpress.com/140-2/"><img class="alignnone" src="https://newwebsite541.files.wordpress.com/2019/05/202b78d3-d59e-44e2-97c0-8c86ca0264ed.jpeg?w=1024" alt="" width="1024" height="1024" data-id="138"></a></div>
<div class="home-two-column-right">
<a href="https://newwebsite541.wordpress.com/140-2/">
<h5>Take a look</h5>
<h1>THE
WHITBY
RANGE</h1>
<hr style="width:20%;">
</a>
</div>
</div>

<div class="home-three-column-left">
<a href="https://newwebsite541.wordpress.com/140-2/">
<div class="home-three-column-left-inner">
<div class="home-three-column-left-border">
<h5>THE MAKING</h5>
Our yarn is 100% British.
</div>
</div>
</a> 
</div>

<div class="home-three-column-center">
<a href="https://newwebsite541.wordpress.com/140-2/">
<div class="home-three-column-center-inner">
<div class="home-three-column-center-border">
<h5>OUR STORY</h5>
A family run business.
</div>
</div>
</a>
</div>

<div class="home-three-column-right">
<a href="https://newwebsite541.wordpress.com/140-2/">
<div class="home-three-column-right-inner">
<div class="home-three-column-right-border">
<h5>COMMISSIONS</h5>
Furnishing &amp; upholstery.
</div>
</div>
</a>
</div>

<div class="favourites-text" style="margin-bottom:50px;">
<h5>OUR FAVORITES</h5>
<h5 style="font-style:italic;color:#b1ada2;font-family:Quattrocento Sans, sans-serif;">Lorem ipsum dolor sit amet.</h5>
</div>

<div class="sale-tag">
<h5>Sale</h5>
</div>
<div class="home-four-column-left"><a href="https://wordpress.com/customize/newwebsite541.wordpress.com"><img class="alignnone" src="//newwebsite541.files.wordpress.com/2019/05/6c0bf6f0-1ba5-4fd7-a275-e9e1d1e66578.jpeg" alt="" width="3957" height="3957"></a>
<h5>WEST CLIFF</h5>
<div class="home-four-new-price">
<h5><span style="text-decoration:line-through;color:#000;">£290.00</span>£250.00</h5>
</div>
</div>

<div class="home-four-column-center-left"><a href="https://wordpress.com/customize/newwebsite541.wordpress.com"><img class="alignnone" src="https://newwebsite541.files.wordpress.com/2019/05/a17c32d8-48d6-4a2a-b824-ec1a48a666e7.jpeg" alt="" width="3840" height="3840"></a>
<h5>ESK</h5>
<div class="home-four-price">
<h5>£110.00</h5>
</div>
</div>

<div class="home-four-column-center-right"><a href="https://wordpress.com/customize/newwebsite541.wordpress.com"><img class="alignnone" src="https://newwebsite541.files.wordpress.com/2019/05/f50279af-be40-4512-af63-fe16ff61cb7d.jpeg?w=869" alt="" width="869" height="869"></a>
<h5>SANDSEND</h5>
<div class="home-four-price">
<h5>£360.00</h5>
</div>
</div>

<div class="home-four-column-right"><a href="https://wordpress.com/customize/newwebsite541.wordpress.com"><img class="alignnone" src="https://newwebsite541.files.wordpress.com/2019/05/faabf634-0eb4-46cd-860f-80cf09dcd153.jpeg" alt="" width="3512" height="3555"></a>
<h5>WEST CLIFF CUSHION</h5>
<div class="home-four-price">
<h5>£250.00</h5>
</div>
</div>

-------

/*Footer Content HTML*/

-------

<div class="footer-nav">
	<ul>
	<li><a href="/.">FAQ</a></li>
  <li><a href="/.">DELIVERY &amp; RETURNS</a></li>
	<li><a href="/.">TERMS &amp; CONDITIONS</a></li>
	<li><a href="/.">CONTACT US</a></li>
	</ul>
</div>
<div class="footer-social">
		<ul>
			<li><a href="/."><img src="https://newwebsite541.files.wordpress.com/2019/05/twitter-bird-light-gray-1.png" style="width:70px;border:solid 1px #555;border-radius:50%;padding:7px;height:70px;float:left;margin:0 30px;"></a></li>
			<li><a href="/."><img src="https://newwebsite541.files.wordpress.com/2019/05/images.png" style="width:70px;border:solid 1px #555;border-radius:50%;padding:20px;height:70px;float:left;margin:0 30px;"></a></li>
			<li><a href="/."><img src="https://newwebsite541.files.wordpress.com/2019/05/instagram-grey.e650c656.png" style="width:70px;border:solid 1px #555;border-radius:50%;padding:20px;height:70px;float:left;margin:0 30px;"></a></li>
	</ul>
</div>
<div class="footer-text">
	<p>COPYRIGHT 2017</p>
<h5>Made in Yorkshire	</h5>
</div>

-------

/*Main Content CSS*/

-------

/*Two column*/

@media screen and (min-width: 1400px) {
	.home-two-column-right {
		width: 50%;
		background: #dcdcdc;
		float: left;
		padding: 0 10px;
		text-align: center;
		color: #fff;
		height: 610px;
		padding-top: 80px;
		margin-bottom: 30px;
	}
	
	.home-two-column-right a {
		color: #fff;
	}
	
	.home-two-column-right a:hover {
		color: #dcdcdc;
	}
	
	.home-two-column-right h5 {
		padding: 35px 0 0;
		font-size: 26px;
		font-family: "Quattrocento Sans", sans-serif;
		font-style: italic;
	}
	
	.home-two-column-right h1 {
		font-size: 70px;
	}
	
	.home-two-column-left img {
		float: right;
	}
}

@media screen and (max-width: 1399px) and (min-width: 1080px) {
	.home-two-column-right {
		width: 50%;
		background: #8fb1a3;
		float: left;
		padding: 0 10px;
		text-align: center;
		color: #fff;
		height: 460px;
		padding-top: 60px;
		margin-bottom: 30px;
	}
	
	.home-two-column-right a {
		color: #fff;
	}
	
	.home-two-column-right a:hover {
		color: #dcdcdc;
	}
	
	.home-two-column-right h5 {
		padding: 35px 0 0;
		font-family: "Quattrocento Sans", sans-serif;
		font-style: italic;
	}
}

@media screen and (max-width: 1079px) and (min-width: 960px) {
	.home-two-column-right {
		width: 50%;
		background: #8fb1a3;
		float: left;
		padding: 0 10px;
		text-align: center;
		color: #dcdcdc;
		height: 400px;
		padding-top: 40px;
		margin-bottom: 30px;
	}
	
	.home-two-column-right a {
		color: #fff;
	}
	
	.home-two-column-right a:hover {
		color: #dcdcdc;
	}
	
	.home-two-column-right h5 {
		padding: 35px 0 0;
		font-family: "quattrocentro sans";
		font-style: italic;
	}
}

@media screen and (max-width: 959px) and (min-width: 840px) {
	.home-two-column-right {
		width: 50%;
		background: #8fb1a3;
		float: left;
		padding: 0 10px;
		text-align: center;
		color: #dcdcdc;
		height: 341px;
		padding-top: 7px;
		margin-bottom: 30px;
	}
	
	.home-two-column-right a {
		color: #fff;
	}
	
	.home-two-column-right a:hover {
		color: #dcdcdc;
	}
	
	.home-two-column-right h5 {
		padding: 28px 0 0;
		font-family: "Quattrocento Sans", sans-serif;
		font-style: italic;
	}
}

@media screen and (max-width: 839px) and (min-width: 768px) {
	.home-two-column-right {
		width: 50%;
		background: #8fb1a3;
		float: left;
		padding: 0 10px;
		text-align: center;
		color: #dcdcdc;
		height: 304px;
	}
	
	.home-two-column-right a {
		color: #fff;
	}
	
	.home-two-column-right a:hover {
		color: #dcdcdc;
	}
	
	.home-two-column-right h5 {
		padding: 18px 0 0;
		font-family: "Quattrocento Sans", sans-serif;
		font-style: italic;
	}
}

@media screen and (max-width: 767px) {
	.home-two-column-right {
		width: 100%;
		background: #8fb1a3;
		float: left;
		padding: 0 10px;
		text-align: center;
		color: #dcdcdc;
		padding-top: 20px;
		margin-bottom: 30px;
	}
	
	.home-two-column-right a {
		color: #fff;
	}
	
	.home-two-column-right h5 {
		padding: 20px 0 0;
		font-family: "Quattrocento Sans", sans-serif;
		font-style: italic;
	}
	
	.home-two-column-left {
		width: 100%;
		float: left;
	}
}

@media screen and (min-width: 768px) {
	.home-two-column-left {
		width: 50%;
		float: left;
		padding: 0 10px;
	}
}

/*Three column*/

@media screen and (min-width: 1080px) {
	.home-three-column-left {
		width: 32.333%;
		float: left;
		clear: both;
		text-align: center;
		background-image: url('https://newwebsite541.files.wordpress.com/2019/05/f34bb6cf-725a-4f6f-b63c-c4a2b20858fe.jpeg');
		background-position: center;
		background-size: cover;
		padding-top: 160px;
		margin-right: 7px;
	}
	
	.home-three-column-left-inner {
		background: #fff;
		margin: 7px;
		padding: 7px;
	}
	
	.home-three-column-left-border {
		border: solid 1px #b1adb6;
	}
	
	.home-three-column-left-border h5 {
		font-size: 19px;
		margin-top: 22px;
		margin-bottom: 4px;
		color: #b1adb6;
	}
	
	.home-three-column-left-border p {
		font-size: 16px;
		color: $primary-color;
	}
	
	.home-three-column-center {
		width: 32.3333%;
		float: left;
		padding: 0;
		text-align: center;
		background-image: url('https://newwebsite541.files.wordpress.com/2019/05/37664ec3-c026-468e-97a2-30c0e130d97e.jpeg');
		background-position: center;
		background-size: cover;
		padding-top: 160px;
		margin: 0 7px;
	}
	
	.home-three-column-center-inner {
		background: #fff;
		margin: 7px;
		padding: 7px;
	}
	
	.home-three-column-center-border {
		border: solid 1px #b1adb6;
	}
	
	.home-three-column-center-border h5 {
		font-size: 19px;
		margin-top: 22px;
		margin-bottom: 4px;
		color: #b1adb6;
	}
	
	.home-three-column-center-border p {
		font-size: 16px;
		color: $primary-color;
	}
	
	.home-three-column-right {
		width: 32.3333%;
		float: left;
		padding: 0;
		text-align: center;
		background-image: url('https://newwebsite541.files.wordpress.com/2019/05/d7e61fbb-0273-43c9-a610-859a8e0bd996.jpeg');
		background-position: center;
		background-size: cover;
		padding-top: 160px;
		margin-left: 7px;
		margin-bottom: 60px;
	}
	
	.home-three-column-right-inner {
		background: #fff;
		margin: 7px;
		padding: 7px;
	}
	
	.home-three-column-right-border {
		border: solid 1px #b1adb6;
	}
	
	.home-three-column-right-border h5 {
		font-size: 19px;
		margin-top: 22px;
		margin-bottom: 4px;
		color: #b1adb6;
	}
	
	.home-three-column-right-border p {
		font-size: 16px;
		color: $primary-color;
	}
}

@media screen and (min-width: 960px) and (max-width: 1079px) {
	.home-three-column-left {
		width: 32.333%;
		float: left;
		clear: both;
		text-align: center;
		background-image: url('https://newwebsite541.files.wordpress.com/2019/05/f34bb6cf-725a-4f6f-b63c-c4a2b20858fe.jpeg');
		background-position: center;
		background-size: cover;
		padding-top: 160px;
		margin-right: 6px;
	}
	
	.home-three-column-left-inner {
		background: #fff;
		margin: 7px;
		padding: 7px;
	}
	
	.home-three-column-left-border {
		border: solid 1px #b1adb6;
	}
	
	.home-three-column-left-border h5 {
		font-size: 19px;
		margin-top: 22px;
		margin-bottom: 4px;
		color: #b1adb6;
	}
	
	.home-three-column-left-border p {
		font-size: 16px;
		color: $primary-color;
	}
	
	.home-three-column-center {
		width: 32.3333%;
		float: left;
		padding: 0;
		text-align: center;
		background-image: url('https://newwebsite541.files.wordpress.com/2019/05/37664ec3-c026-468e-97a2-30c0e130d97e.jpeg');
		background-position: center;
		background-size: cover;
		padding-top: 160px;
		margin: 0 6px;
	}
	
	.home-three-column-center-inner {
		background: #fff;
		margin: 7px;
		padding: 7px;
	}
	
	.home-three-column-center-border {
		border: solid 1px #b1adb6;
	}
	
	.home-three-column-center-border h5 {
		font-size: 19px;
		margin-top: 22px;
		margin-bottom: 4px;
		color: #b1adb6;
	}
	
	.home-three-column-center-border p {
		font-size: 16px;
		color: $primary-color;
	}
	
	.home-three-column-right {
		width: 32.3333%;
		float: left;
		padding: 0;
		text-align: center;
		background-image: url('https://newwebsite541.files.wordpress.com/2019/05/d7e61fbb-0273-43c9-a610-859a8e0bd996.jpeg');
		background-position: center;
		background-size: cover;
		padding-top: 160px;
		margin-left: 6px;
		margin-bottom: 60px;
	}
	
	.home-three-column-right-inner {
		background: #fff;
		margin: 7px;
		padding: 7px;
	}
	
	.home-three-column-right-border {
		border: solid 1px #b1adb6;
	}
	
	.home-three-column-right-border h5 {
		font-size: 19px;
		margin-top: 22px;
		margin-bottom: 4px;
		color: #b1adb6;
	}
	
	.home-three-column-right-border p {
		font-size: 16px;
		color: $primary-color;
	}
}

@media screen and (min-width: 840px) and (max-width: 959px) {
	.home-three-column-left {
		width: 32.333%;
		float: left;
		clear: both;
		text-align: center;
		background-image: url('https://newwebsite541.files.wordpress.com/2019/05/f34bb6cf-725a-4f6f-b63c-c4a2b20858fe.jpeg');
		background-position: center;
		background-size: cover;
		padding-top: 120px;
		margin-right: 5px;
	}
	
	.home-three-column-left-inner {
		background: #fff;
		margin: 7px;
		padding: 7px;
	}
	
	.home-three-column-left-border {
		border: solid 1px #b1adb6;
	}
	
	.home-three-column-left-border h5 {
		font-size: 19px;
		margin-top: 22px;
		margin-bottom: 4px;
		color: #b1adb6;
	}
	
	.home-three-column-left-border p {
		font-size: 16px;
		color: $primary-color;
	}
	
	.home-three-column-center {
		width: 32.3333%;
		float: left;
		padding: 0;
		text-align: center;
		background-image: url('https://newwebsite541.files.wordpress.com/2019/05/37664ec3-c026-468e-97a2-30c0e130d97e.jpeg');
		background-position: center;
		background-size: cover;
		padding-top: 120px;
		margin: 0 5px;
	}
	
	.home-three-column-center-inner {
		background: #fff;
		margin: 7px;
		padding: 7px;
	}
	
	.home-three-column-center-border {
		border: solid 1px #b1adb6;
	}
	
	.home-three-column-center-border h5 {
		font-size: 19px;
		margin-top: 22px;
		margin-bottom: 4px;
		color: #b1adb6;
	}
	
	.home-three-column-center-border p {
		font-size: 16px;
		color: $primary-color;
	}
	
	.home-three-column-right {
		width: 32.3333%;
		float: left;
		padding: 0;
		text-align: center;
		background-image: url('https://newwebsite541.files.wordpress.com/2019/05/d7e61fbb-0273-43c9-a610-859a8e0bd996.jpeg');
		background-position: center;
		background-size: cover;
		padding-top: 120px;
		margin-left: 5px;
		margin-bottom: 60px;
	}
	
	.home-three-column-right-inner {
		background: #fff;
		margin: 7px;
		padding: 7px;
	}
	
	.home-three-column-right-border {
		border: solid 1px #b1adb6;
	}
	
	.home-three-column-right-border h5 {
		font-size: 19px;
		margin-top: 22px;
		margin-bottom: 4px;
		color: #b1adb6;
	}
	
	.home-three-column-right-border p {
		font-size: 16px;
		color: $primary-color;
	}
}

@media screen and (min-width: 768px) and (max-width: 839px) {
	.home-three-column-left {
		width: 32.333%;
		float: left;
		clear: both;
		text-align: center;
		background-image: url('https://newwebsite541.files.wordpress.com/2019/05/f34bb6cf-725a-4f6f-b63c-c4a2b20858fe.jpeg');
		background-position: center;
		background-size: cover;
		padding-top: 90px;
		margin-right: 4.33px;
		padding-bottom: 10px;
	}
	
	.home-three-column-left a {
		opacity: 1;
	}
	
	.home-three-column-left a:hover {
		opacity: .5;
	}
	
	.home-three-column-left-inner {
		background: #fff;
		margin: 7px;
		padding: 7px;
		margin-top: 23px;
	}
	
	.home-three-column-left-border {
		border: solid 1px #b1adb6;
	}
	
	.home-three-column-left-border h5 {
		font-size: 19px;
		margin-top: 22px;
		margin-bottom: 4px;
		color: #b1adb6;
	}
	
	.home-three-column-left-border p {
		font-size: 16px;
		color: $primary-color;
	}
	
	.home-three-column-center {
		width: 32.3333%;
		float: left;
		padding: 0;
		text-align: center;
		background-image: url('https://newwebsite541.files.wordpress.com/2019/05/37664ec3-c026-468e-97a2-30c0e130d97e.jpeg');
		background-position: center;
		background-size: cover;
		padding-top: 90px;
		margin: 0 4.33px;
		padding-bottom: 10px;
	}
	
	.home-three-column-center-inner {
		background: #fff;
		margin: 7px;
		padding: 7px;
		margin-top: 23px;
	}
	
	.home-three-column-center-border {
		border: solid 1px #b1adb6;
	}
	
	.home-three-column-center-border h5 {
		font-size: 19px;
		margin-top: 22px;
		margin-bottom: 4px;
		color: #b1adb6;
	}
	
	.home-three-column-center-border p {
		font-size: 16px;
		color: $primary-color;
	}
	
	.home-three-column-right {
		width: 32.3333%;
		float: left;
		padding: 0;
		text-align: center;
		background-image: url('https://newwebsite541.files.wordpress.com/2019/05/d7e61fbb-0273-43c9-a610-859a8e0bd996.jpeg');
		background-position: center;
		background-size: cover;
		padding-top: 90px;
		margin-left: 4.33px;
		margin-bottom: 60px;
	}
	
	.home-three-column-right-inner {
		background: #fff;
		margin: 7px;
		padding: 7px;
	}
	
	.home-three-column-right-border {
		border: solid 1px #b1adb6;
	}
	
	.home-three-column-right-border h5 {
		font-size: 19px;
		margin-top: 22px;
		margin-bottom: 4px;
		color: #b1adb6;
	}
	
	.home-three-column-right-border p {
		font-size: 16px;
		color: $primary-color;
	}
}

@media screen and (max-width: 767px) and (min-width: 500px) {
	.home-three-column-left {
		width: 100%;
		float: none;
		clear: both;
		text-align: center;
		background-image: url('https://newwebsite541.files.wordpress.com/2019/05/f34bb6cf-725a-4f6f-b63c-c4a2b20858fe.jpeg');
		background-position: center;
		background-size: cover;
		padding-top: 220px;
		padding-bottom: 10px;
		margin-bottom: 20px;
	}
	
	.home-three-column-left-inner {
		background: #fff;
		margin: 7px 100px;
		padding: 7px;
	}
	
	.home-three-column-left-border {
		border: solid 1px #000;
	}
	
	.home-three-column-left-border h5 {
		font-size: 19px;
		margin-top: 10px;
		margin-bottom: 4px;
	}
	
	.home-three-column-center {
		width: 100%;
		float: none;
		padding: 0;
		text-align: center;
		background-image: url('https://newwebsite541.files.wordpress.com/2019/05/37664ec3-c026-468e-97a2-30c0e130d97e.jpeg');
		background-position: center;
		background-size: cover;
		padding-top: 220px;
		padding-bottom: 10px;
		margin-bottom: 20px;
	}
	
	.home-three-column-center-inner {
		background: #fff;
		margin: 7px 100px;
		padding: 7px;
	}
	
	.home-three-column-center-border {
		border: solid 1px #000;
	}
	
	.home-three-column-center-border h5 {
		font-size: 19px;
		margin-top: 10px;
		margin-bottom: 4px;
	}
	
	.home-three-column-right {
		width: 100%;
		float: none;
		padding: 0;
		text-align: center;
		background-image: url('https://newwebsite541.files.wordpress.com/2019/05/d7e61fbb-0273-43c9-a610-859a8e0bd996.jpeg');
		background-position: center;
		background-size: cover;
		padding-top: 220px;
		margin-bottom: 60px;
		padding-bottom: 10px;
	}
	
	.home-three-column-right-inner {
		background: #fff;
		margin: 7px 100px;
		padding: 7px;
	}
	
	.home-three-column-right-border {
		border: solid 1px #000;
	}
	
	.home-three-column-right-border h5 {
		font-size: 19px;
		margin-top: 10px;
		margin-bottom: 4px;
	}
}

@media screen and (max-width: 499px) {
	.home-three-column-left {
		width: 100%;
		float: none;
		clear: both;
		text-align: center;
		background-image: url('https://newwebsite541.files.wordpress.com/2019/05/f34bb6cf-725a-4f6f-b63c-c4a2b20858fe.jpeg');
		background-position: center;
		background-size: cover;
		padding-top: 100px;
		padding-bottom: 10px;
		margin-bottom: 20px;
	}
	
	.home-three-column-left-inner {
		background: #fff;
		margin: 7px 10px;
		padding: 7px;
	}
	
	.home-three-column-left-border {
		border: solid 1px #000;
	}
	
	.home-three-column-left-border h5 {
		font-size: 19px;
		margin-top: 10px;
		margin-bottom: 4px;
	}
	
	.home-three-column-center {
		width: 100%;
		float: none;
		padding: 0;
		text-align: center;
		background-image: url('https://newwebsite541.files.wordpress.com/2019/05/37664ec3-c026-468e-97a2-30c0e130d97e.jpeg');
		background-position: center;
		background-size: cover;
		padding-top: 100px;
		padding-bottom: 10px;
		margin-bottom: 20px;
	}
	
	.home-three-column-center-inner {
		background: #fff;
		margin: 7px 10px;
		padding: 7px;
	}
	
	.home-three-column-center-border {
		border: solid 1px #000;
	}
	
	.home-three-column-center-border h5 {
		font-size: 19px;
		margin-top: 10px;
		margin-bottom: 4px;
	}
	
	.home-three-column-right {
		width: 100%;
		float: none;
		padding: 0;
		text-align: center;
		background-image: url('https://newwebsite541.files.wordpress.com/2019/05/d7e61fbb-0273-43c9-a610-859a8e0bd996.jpeg');
		background-position: center;
		background-size: cover;
		padding-top: 100px;
		margin-bottom: 60px;
		padding-bottom: 10px;
	}
	
	.home-three-column-right-inner {
		background: #fff;
		margin: 7px 10px;
		padding: 7px;
	}
	
	.home-three-column-right-border {
		border: solid 1px #000;
	}
	
	.home-three-column-right-border h5 {
		font-size: 19px;
		margin-top: 10px;
		margin-bottom: 4px;
	}
}

/*Favourites*/

.favourites-text h5 {
	text-align: center;
	margin-bottom: 8px;
}

/*Four column*/

@media screen and (min-width: 960px) {
	.home-four-column-left {
		width: 24%;
		text-align: center;
		float: left;
		margin-right: 5.5px;
	}
	
	.home-four-column-left h5 {
		margin-bottom: 8px;
	}
	
	.home-four-column-center-left {
		width: 24%;
		text-align: center;
		float: left;
		margin: 0 5.5px;
	}
	
	.home-four-column-center-left h5 {
		margin-bottom: 8px;
	}
	
	.home-four-column-center-right {
		width: 24%;
		text-align: center;
		float: left;
		margin: 0 5.5px;
	}
	
	.home-four-column-center-right h5 {
		margin-bottom: 8px;
	}
	
	.home-four-column-right {
		width: 24%;
		text-align: center;
		float: left;
		margin-left: 5.5px;
	}
	
	.home-four-column-right h5 {
		margin-bottom: 8px;
	}
	
	.sale-tag {
		width: 5%;
		background: black;
		text-align: center;
		margin-left: 90px;
		border: solid 1px #000;
		color: #fff;
		border-radius: 100px;
		margin-bottom: -24px;
		height: 48px;
		position: relative;
	}
	
	.sale-tag h5 {
		margin-top: 12px;
		font-size: 14px;
		font-style: italic;
		font-family: "Quattrocento Sans", sans-serif;
	}
	
	.home-four-price h5 {
		color: #b1ada2;
		font-size: 17px;
	}
	
	.home-four-new-price h5 {
		color: #8fb1a3;
		font-size: 17px;
	}
}

@media screen and (max-width: 959px) and (min-width: 840px) {
	.home-four-column-left {
		width: 49%;
		text-align: center;
		float: left;
		margin-right: 7px;
	}
	
	.home-four-column-left h5 {
		margin-bottom: 8px;
	}
	
	.home-four-column-center-left {
		width: 49%;
		text-align: center;
		float: left;
		margin-left: 7px;
		margin-bottom: 20px;
	}
	
	.home-four-column-center-left h5 {
		margin-bottom: 8px;
	}
	
	.home-four-column-center-right {
		width: 49%;
		text-align: center;
		float: left;
		margin-right: 7px;
	}
	
	.home-four-column-center-right h5 {
		margin-bottom: 8px;
	}
	
	.home-four-column-right {
		width: 49%;
		text-align: center;
		float: left;
		margin-left: 7px;
	}
	
	.home-four-column-right h5 {
		margin-bottom: 8px;
	}
	
	.sale-tag {
		width: 7%;
		background: black;
		text-align: center;
		margin-left: 145px;
		border: solid 1px #000;
		color: #fff;
		border-radius: 100px;
		margin-bottom: -24px;
		height: 48px;
		position: relative;
	}
	
	.sale-tag h5 {
		margin-top: 12px;
		font-size: 14px;
		font-style: italic;
		font-family: "Quattrocento Sans", sans-serif;
	}
	
	.home-four-price h5 {
		color: #b1ada2;
		font-size: 17px;
	}
	
	.home-four-new-price h5 {
		color: #8fb1a3;
		font-size: 17px;
	}
}

@media screen and (max-width: 839px) and (min-width: 768px) {
	.home-four-column-left {
		width: 49%;
		text-align: center;
		float: left;
		margin-right: 6px;
	}
	
	.home-four-column-left h5 {
		margin-bottom: 8px;
	}
	
	.home-four-column-center-left {
		width: 49%;
		text-align: center;
		float: left;
		margin-left: 6px;
		margin-bottom: 20px;
	}
	
	.home-four-column-center-left h5 {
		margin-bottom: 8px;
	}
	
	.home-four-column-center-right {
		width: 49%;
		text-align: center;
		float: left;
		margin-right: 6px;
	}
	
	.home-four-column-center-right h5 {
		margin-bottom: 8px;
	}
	
	.home-four-column-right {
		width: 49%;
		text-align: center;
		float: left;
		margin-left: 6px;
	}
	
	.home-four-column-right h5 {
		margin-bottom: 8px;
	}
	
	.sale-tag {
		width: 8%;
		background: black;
		text-align: center;
		margin-left: 135px;
		border: solid 1px #000;
		color: #fff;
		border-radius: 100px;
		margin-bottom: -24px;
		height: 48px;
		position: relative;
	}
	
	.sale-tag h5 {
		margin-top: 12px;
		font-size: 14px;
		font-style: italic;
		font-family: "Quattrocento Sans", sans-serif;
	}
	
	.home-four-price h5 {
		color: #b1ada2;
		font-size: 17px;
	}
	
	.home-four-new-price h5 {
		color: #8fb1a3;
		font-size: 17px;
	}
}

@media screen and (max-width: 767px) {
	.home-four-column-left {
		width: 100%;
		text-align: center;
		float: left;
		margin-bottom: 30px;
	}
	
	.home-four-column-left h5 {
		margin-bottom: 8px;
	}
	
	.home-four-column-center-left {
		width: 100%;
		text-align: center;
		float: left;
		margin-bottom: 30px;
	}
	
	.home-four-column-center-left h5 {
		margin-bottom: 8px;
	}
	
	.home-four-column-center-right {
		width: 100%;
		text-align: center;
		float: left;
		margin-bottom: 30px;
	}
	
	.home-four-column-center-right h5 {
		margin-bottom: 8px;
	}
	
	.home-four-column-right {
		width: 100%;
		text-align: center;
		float: left;
	}
	
	.home-four-column-right h5 {
		margin-bottom: 8px;
	}
	
	.sale-tag {
		width: 62px;
		background: black;
		text-align: center;
		margin-left: 300px;
		border: solid 1px #000;
		color: #fff;
		border-radius: 100px;
		margin-bottom: -35px;
		height: 62px;
		position: relative;
		margin: 0 45% -30px;
	}
	
	.sale-tag h5 {
		margin-top: 18px;
		font-size: 17px;
		font-style: italic;
		font-family: "Quattrocento Sans", sans-serif;
	}
	
	.home-four-price h5 {
		color: #b1ada2;
		font-size: 17px;
	}
	
	.home-four-new-price h5 {
		color: #8fb1a3;
		font-size: 17px;
	}
}


-------

--------

/*Footer Content CSS*/

--------


@media screen and (min-width: 700px) {
	.footer-nav {
		border: 1px solid #ccc;
		border-width: 1px 0;
		list-style: none;
		margin: 0;
		padding: 0;
		text-align: center;
		height: 48px;
	}
	
	.footer-nav li {
		display: inline;
	}
	
	.footer-nav a {
		display: inline-block;
		padding: 10px 20px;
	}
	
	.footer-widget-inner .widget {
		width: 100%;
	}
	
	.footer-widget {
		border: 0;
	}
	
	.footer-social {
		list-style: none;
		margin: 0;
		padding: 0;
		text-align: center;
		height: 48px;
		margin-top: 15px;
	}
	
	.footer-social li {
		display: inline;
	}
	
	.footer-social a {
		display: inline-block;
		padding: 10px 5px;
	}
	
	.footer-text {
		clear: both;
		text-align: center;
		margin-top: 75px;
	}
	
	.footer-text p {
		color: #555;
		margin-bottom: 15px;
	}
	
	.footer-text h5 {
		font-style: italic;
	}
}

@media screen and (max-width: 699px) and (min-width: 493px) {
	.footer-nav {
		border: 1px solid #ccc;
		border-width: 1px 0;
		list-style: none;
		margin: 0;
		padding: 0;
		text-align: center;
		height: 84px;
	}
	
	.footer-nav li {
		display: inline;
	}
	
	.footer-nav a {
		display: inline-block;
		padding: 10px 20px;
	}
	
	.footer-widget-inner .widget {
		width: 100%;
	}
	
	.footer-widget {
		border: 0;
	}
	
	.footer-social {
		list-style: none;
		margin: 0;
		padding: 0;
		text-align: center;
		height: 48px;
		margin-top: 15px;
	}
	
	.footer-social li {
		display: inline;
	}
	
	.footer-social a {
		display: inline-block;
		padding: 7px 5px;
	}
	
	.footer-text {
		clear: both;
		text-align: center;
		margin-top: 70px;
	}
	
	.footer-text p {
		color: #555;
		margin-bottom: 15px;
	}
	
	.footer-text h5 {
		font-style: italic;
	}
}

@media screen and (max-width: 492px) and (min-width: 396px) {
	.footer-nav {
		border: 1px solid #ccc;
		border-width: 1px 0;
		list-style: none;
		margin: 0;
		padding: 0;
		text-align: center;
		height: 84px;
	}
	
	.footer-nav li {
		display: inline;
	}
	
	.footer-nav a {
		display: inline-block;
		padding: 10px 20px;
	}
	
	.footer-widget-inner .widget {
		width: 100%;
	}
	
	.footer-widget {
		border: 0;
	}
	
	.footer-social {
		list-style: none;
		margin: 0;
		padding: 0;
		text-align: center;
		height: 48px;
		margin-top: 15px;
	}
	
	.footer-social li {
		display: inline;
	}
	
	.footer-social a {
		display: inline-block;
		padding: 10px 5px;
	}
	
	.footer-text {
		clear: both;
		text-align: center;
		margin-top: 140px;
	}
	
	.footer-text p {
		color: #555;
		margin-bottom: 15px;
	}
	
	.footer-text h5 {
		font-style: italic;
	}
}

@media screen and (max-width: 395px) and (min-width: 333px) {
	.footer-nav {
		border: 1px solid #ccc;
		border-width: 1px 0;
		list-style: none;
		margin: 0;
		padding: 0;
		text-align: center;
		height: 130px;
	}
	
	.footer-nav li {
		display: inline;
	}
	
	.footer-nav a {
		display: inline-block;
		padding: 10px 20px;
	}
	
	.footer-widget-inner .widget {
		width: 100%;
	}
	
	.footer-widget {
		border: 0;
	}
	
	.footer-social {
		list-style: none;
		margin: 0;
		padding: 0;
		text-align: center;
		height: 48px;
		margin-top: 15px;
	}
	
	.footer-social li {
		display: inline;
	}
	
	.footer-social a {
		display: inline-block;
		padding: 10px 5px;
	}
	
	.footer-text {
		clear: both;
		text-align: center;
		margin-top: 160px;
	}
	
	.footer-text p {
		color: #555;
		margin-bottom: 15px;
	}
	
	.footer-text h5 {
		font-style: italic;
	}
}

@media screen and (max-width: 332px) and (min-width: 316px) {
	.footer-nav {
		border: 1px solid #ccc;
		border-width: 1px 0;
		list-style: none;
		margin: 0;
		padding: 0;
		text-align: center;
		height: 130px;
	}
	
	.footer-nav li {
		display: inline;
	}
	
	.footer-nav a {
		display: inline-block;
		padding: 10px 20px;
	}
	
	.footer-widget-inner .widget {
		width: 100%;
	}
	
	.footer-widget {
		border: 0;
	}
	
	.footer-social {
		list-style: none;
		margin: 0;
		padding: 0;
		text-align: center;
		height: 48px;
		margin-top: 15px;
	}
	
	.footer-social li {
		display: inline;
	}
	
	.footer-social a {
		display: inline-block;
		padding: 10px 0;
	}
	
	.footer-text {
		clear: both;
		text-align: center;
		margin-top: 160px;
	}
	
	.footer-text p {
		color: #555;
		margin-bottom: 15px;
	}
	
	.footer-text h5 {
		font-style: italic;
	}
}

@media screen and (max-width: 315px) {
	.footer-nav {
		border: 1px solid #ccc;
		border-width: 1px 0;
		list-style: none;
		margin: 0;
		padding: 0;
		text-align: center;
		height: 180x;
	}
	
	.footer-nav li {
		display: inline;
	}
	
	.footer-nav a {
		display: inline-block;
		padding: 10px 20px;
	}
	
	.footer-widget-inner .widget {
		width: 100%;
	}
	
	.footer-widget {
		border: 0;
	}
	
	.footer-social {
		list-style: none;
		margin: 0;
		padding: 0;
		text-align: center;
		height: 48px;
		margin-top: 15px;
	}
	
	.footer-social li {
		display: inline;
	}
	
	.footer-social a {
		display: inline-block;
		padding: 10px 0;
	}
	
	.footer-text {
		clear: both;
		text-align: center;
		margin-top: 255px;
	}
	
	.footer-text p {
		color: #555;
		margin-bottom: 15px;
	}
	
	.footer-text h5 {
		font-style: italic;
	}
}

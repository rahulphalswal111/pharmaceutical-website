# pharmaceutical-website
# A pharmaceutical website(only front end) designed using html,css and javascript using only div tags

# author rahul phalswal
# created @10-10-2020

========html part

<!DOCTYPE html>
<html>

<head>
	<title>jtg project</title>
	<meta charset="UTF-8">
	<meta name="description" content="Free Web tutorials">
	<meta name="keywords" content="HTML, CSS, JavaScript">
	<meta name="author" content="Rahul">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">

	<link rel="stylesheet" href="style.css">
</head>

<body>
	<!---header-->

	<div class="header">
		<div class="prod">
			<a href="#" style="text-decoration: none;">Products</a>
			<span>|</span>
			<a href="#">Resources</a>
		</div>
		<div class="att2">
			<a href="#">My Account</a>
			<span>|</span>
			<a href="#">Cart (0)</a>
		</div>
	</div>

	<!-----navigation----->
	<div class="main-nav">
		<div class="nav">
			<div class="left-nav">
				<img src="resources\dnb logo.png" class="logo">
				<h2 class="review">Credibility Review</h2>
			</div>
			<div class="right-nav">
				<div class="talk">
					<div class="call">
						<img src="resources\phone.png" />
					</div>
					<div class="text-no">
						<span class="text">Talk to a credit advisor</span>
						<span class="no">1.800.700.2733</span>
					</div>
				</div>
			</div>
		</div>
	</div>

	<!--main-content of body-->

	<div class="main-content">
		<div class="navbar">
			<div>
				HOME
				<img src="resources\more_arrow.png">
			</div>
			<div>
				Search
				<img src="resources\more_arrow.png">
			</div>
			<div>
				Marketplace
				<img src="resources\more_arrow.png">
			</div>
			<div>
				Pharmaceutical
				<img src="resources\more_arrow.png">
			</div>
			<div>
				Product Delivery
			</div>
		</div>
		<div class="search-bar">
			<div id="company-name">
				<img src="resources\logo.png">
			</div>
			<div id="search-bar-right">
				<div class="search-box1" style="display:flex">
					<div>

						<input autocomplete="on" id="search" class="search-box" name="q" placeholder="Loreum lpsum company"
							required="required" type="text">
					</div>
					<div>
						<button type="submit" id="searchbutton" class="search-button" onclick="mySearchfunction()"></button>
					</div>
				</div>
				<div class="search-text" style="color:white">
					Search for in depth information on 8,562 products and services across formulation and manufacturing
				</div>
			</div>
		</div>
		<!--slider-->
		<div class="slider">
			<div class="carousel"
				data-flickity='{ "fullscreen": true, "lazyLoad": 1,"autoPlay": true , "prevNextButtons": false}'>
				<div class="carousel-cell">
					<img class="carousel-cell-image" src="resources/cycle_img1.png">
				</div>
				<div class="carousel-cell">
					<img class="carousel-cell-image" src="resources/cycle_img2.png">
				</div>
				<div class="carousel-cell">
					<img class="carousel-cell-image" src="resources/cycle_img1.png">
				</div>
				<div class="carousel-cell">
					<img class="carousel-cell-image" src="resources/cycle_img2.png">
				</div>

			</div>
		</div>
		<div class="see-through-me">
			Glass Beakers and Containers
		</div>
		<div class="grid-container">
			<!--row 1-->
			<!--column1-->
			<div class="grid-item">
				<div class="categories-p-tag">
					<div class="heading">Categories</div>
					<div class="categories-item">
						<p>Analytical Instrumentation</p>
						<p>Packaging</p>
						<p>Process Control</p>
						<p>Contract Service</p>
						<p>Manufacturing</p>
						<p>Ingredients</p>
					</div>
				</div>
			</div>
			<!--column2-->
			<div class="grid-item">
				<div class="heading" style="padding-left:28px">Featured Company Profiles</div>
				<div class="partition">
					<div class="left-partition">
						<!--first company-->
						<div>
							<div class="flex-container">
								<div>
									<img src='resources\Adelphi_Coldstream_icon.png' class='iconDetails'>
								</div>
								<div>
									<div class="flex-icon-heading">
										Adelphi Coldstream
									</div>
									<div>
										<p>Company Description donec vulputate, mag eleifend
											porttitor vehiculat lectus elit et enim
											<span class="dots">...</span><span class="more">Thanks for reading.This is a assignment project
												for Josh Technology group for the role of front end developer</span>
											<button onclick="myreadFunction()" class="myBtn"><a>more
													&nbsp <img src="resources\more_arrow.png"></a></button>
										</p>
									</div>
								</div>
							</div>
						</div>
						<!--second-company-->
						<div>
							<div class="flex-container">
								<div>
									<img src='resources\placeholder_48x48.png' class='iconDetails'>
								</div>
								<div>
									<div class="flex-icon-heading">
										Company Name
									</div>
									<div>
										<p>Company Description donec vulputate, mag eleifend
											porttitor vehiculat lectus elit et enim
											<span class="dots">...</span><span class="more">Thanks for reading.This is a assignment project
												for Josh Technology group for the role of front end developer</span>
											<a onclick="myreadFunction()" class="myBtn">more &nbsp <img src="resources\more_arrow.png"></a>
										</p>
									</div>
								</div>
							</div>

						</div>
						<!--third-company-->
						<div>
							<div class="flex-container">
								<div>
									<img src='resources\placeholder_48x48.png' class='iconDetails'>
								</div>
								<div>
									<div class="flex-icon-heading">
										Company Name
									</div>
									<div>
										<p>Company Description donec vulputate, mag eleifend
											porttitor vehiculat lectus elit et enim
											<span class="dots">...</span><span class="more">Thanks for reading.This is a assignment project
												for Josh Technology group for the role of front end developer</span>
											<a onclick="myreadFunction()" class="myBtn">more &nbsp <img src="resources\more_arrow.png"></a>
										</p>
									</div>
								</div>
							</div>
						</div>
					</div>
					<div class="right-partition">
						<!--fourth company-->
						<div>
							<div class="flex-container" style="padding-left:17px">
								<div>
									<img src='resources\placeholder_48x48.png' class='iconDetails'>
								</div>
								<div>
									<div class="flex-icon-heading">
										Company Name
									</div>
									<div>
										<p>Company Description donec vulputate, mag eleifend
											porttitor vehiculat lectus elit et enim
											<span class="dots">...</span><span class="more">Thanks for reading.This is a assignment project
												for Josh Technology group for the role of front end developer</span>
											<a onclick="myreadFunction()" class="myBtn">more &nbsp <img src="resources\more_arrow.png"></a>
										</p>
									</div>
								</div>
							</div>
						</div>
						<!--advertisement1-->
						<div class="advertisement1">
							<img src="resources\ad_180x150.png">
						</div>
					</div>
				</div>

			</div>

			<!--row2-->
			<!--column1-->
			<div class="grid-item">
				<!--advertisement2-->
				<div class="advertisement2">
					<img src="resources\ad_160x600.png" alt="advertisement here">
				</div>
			</div>
			<!--column2-->
			<div class="grid-item">
				<div class="articles" style="padding-bottom:1px">
					<div class="heading" id="featured-articles">
						Featured Articles
					</div>
					<div class="partition">
						<div class="left-partition" style="padding-right:5px">
							<!--first article-->
							<div>
								<div class="flex-container">
									<div>
										<img src='resources\Untitled-1.png' class='iconDetails2'>
									</div>
									<div>
										<div class="flex-icon-heading">
											Article Title <span id="article-date"><span>&nbsp| &nbsp</span>
												June 26,2012</span>
										</div>
										<div>
											<p>Donec vulputate, magna eleifend
												porttitor vehiculat lectus elit et enim pulvinar non suscipit
												<span class="dots">...</span><span class="more">Thanks for reading.This is a assignment project
													for Josh Technology group for the role of front end developer</span>
												<a onclick="myreadFunction()" class="myBtn">read more</a>
											</p>
										</div>
									</div>
								</div>
								<!--second article-->
								<div class="flex-container">
									<div>
										<img src='resources\Untitled-1.png' class='iconDetails2'>
									</div>
									<div>
										<div class="flex-icon-heading">
											Article Title
											<span id="article-date"><span>&nbsp| &nbsp</span> June
												26,2012</span>
										</div>
										<div>
											<p>Donec vulputate, magna eleifend
												porttitor vehiculat lectus elit et enim pulvinar non suscipit
												<span class="dots">...</span><span class="more">Thanks for reading.This is a assignment project
													for Josh Technology group for the role of front end developer</span>
												<a onclick="myreadFunction()" class="myBtn">read more</a>
											</p>
										</div>
									</div>
								</div>
								<!--third article-->
								<div class="flex-container">
									<div>
										<img src='resources\Untitled-1.png' class='iconDetails2'>
									</div>
									<div>
										<div class="flex-icon-heading">
											Article Title
											<span id="article-date"><span>&nbsp| &nbsp</span> June
												26,2012</span>
										</div>
										<div>
											<p>Donec vulputate, magna eleifend
												porttitor vehiculat lectus elit et enim pulvinar non suscipit
												<span class="dots">...</span><span class="more">Thanks for reading.This is a assignment project
													for Josh Technology group for the role of front end developer</span>
												<a onclick="myreadFunction()" class="myBtn">read more</a>
											</p>
										</div>
									</div>
								</div>
							</div>

						</div>
						<div class="right-partition" style="margin-left:-10px">
							<!--fourth article-->
							<div class="flex-container">
								<div>
									<img src='resources\Untitled-1.png' class='iconDetails2'>
								</div>
								<div>
									<div class="flex-icon-heading">
										Article Title
										<span id="article-date"><span>&nbsp| &nbsp</span> June
											26,2012</span>
									</div>
									<div>
										<p class="read-more">Donec vulputate, magna eleifend
											porttitor vehiculat lectus elit et enim pulvinar non suscipit
											<span class="dots">...</span><span class="more">Thanks for reading.This is a assignment project
												for Josh Technology group for the role of front end developer</span>
											<a onclick="myreadFunction()" class="myBtn">read more &nbsp <img
													src="resources\more_arrow.png"></a>
										</p>
									</div>
								</div>
							</div>
							<!--fifth article-->
							<div class="flex-container">
								<div>
									<img src='resources\Untitled-1.png' class='iconDetails2'>
								</div>
								<div>
									<div class="flex-icon-heading">
										Article Title
										<span id="article-date"><span>&nbsp| &nbsp</span>
											June 26,2012</span>
									</div>
									<div>
										<p>Donec vulputate, magna eleifend
											porttitor vehiculat lectus elit et enim pulvinar non suscipit
											<span class="dots">...</span><span class="more">Thanks for reading.This is a assignment project
												for Josh Technology group for the role of front end developer</span>
											<a onclick="myreadFunction()" class="myBtn">read more &nbsp <img
													src="resources\more_arrow.png"></a>
										</p>
									</div>
								</div>
							</div>
							<!--sixth article-->
							<div class="flex-container">
								<div>
									<img src='resources\Untitled-1.png' class='iconDetails2'>
								</div>
								<div>
									<div class="flex-icon-heading">
										Article Title
										<span id="article-date"><span>&nbsp | &nbsp</span>
											June 26,2012</span>
									</div>
									<div>
										<p>Donec vulputate, magna eleifend
											porttitor vehiculat lectus elit et enim pulvinar non suscipit
											<span class="dots">...</span><span class="more">Thanks for reading.This is a assignment project
												for Josh Technology group for the role of front end developer</span>
											<a onclick="myreadFunction()" class="myBtn">read more &nbsp <img
													src="resources\more_arrow.png"></a>
										</p>
									</div>
								</div>
							</div>
						</div>
					</div>
				</div>
				<div class="grid-container3">
					<!--featured whitepaper-->
					<div class="grid-item3">
						<div class="whitepaper">
							<div class="heading1" style="padding-bottom:5px;border-bottom:solid black 1px">
								Featured Whitepapers
							</div>
							<!--paper1-->
							<div class="flex-container3">
								<div>
									<img src='resources\whitepaper1.png' class='whitepaper-image'>
								</div>
								<div>
									<div class="whitepaper-icon-heading">
										Whitepaper Title
									</div>
									<div>
										<p>Donec vulputate, magna eleifend
											porttitor, vehiculat lectus elit et
											enim pulvinar non suscipiterat elit,
											cursus vehicula quam a arcu
											vestibulum molestie
											<span class="dots">...</span>
											<a href="/images/myw3schoolsimage.jpg" download>download &nbsp<img
													src="resources/more_arrow.png"></a>
										</p>
									</div>
								</div>
							</div>
							<!--paper2-->
							<div class="flex-container3">
								<div>
									<img src='resources\whitepaper2.png' class='whitepaper-image'>
								</div>
								<div>
									<div class="whitepaper-icon-heading">
										Whitepaper Title
									</div>
									<div>
										<p>Donec vulputate, magna eleifend
											porttitor, vehiculat lectus elit
											et enim pulvinar non
											suscipiterat elit, cursus
											vehicula quam a arcu vestibulum
											molestie
											<span class="dots">...</span>
											<a href="/images/myw3schoolsimage.jpg" download>download &nbsp<img
													src="resources/more_arrow.png"></a>
										</p>
									</div>
								</div>
							</div>


							<!--paper3-->
							<div class="flex-container3">
								<div>
									<img src='resources\whitepaper3.png' class='whitepaper-image'>
								</div>
								<div>
									<div class="whitepaper-icon-heading">
										Whitepaper Title
									</div>
									<div>
										<p>Donec vulputate, magna
											eleifend
											porttitor, vehiculat lectus
											elit et enim pulvinar non
											suscipiterat elit, cursus
											vehicula quam a arcu
											vestibulum molestie
											<span class="dots">...</span>
											<a href="/images/myw3schoolsimage.jpg" download>download &nbsp<img
													src="resources/more_arrow.png"></a>
										</p>
									</div>
								</div>
							</div>


							<!--paper4-->
							<div class="flex-container3">
								<div>
									<img src='resources\whitepaper4.png' class='whitepaper-image'>
								</div>
								<div>
									<div class="whitepaper-icon-heading">
										Whitepaper Title
									</div>
									<div>
										<p>Donec vulputate, magna
											eleifend
											porttitor, vehiculat
											lectus elit et enim
											pulvinar non
											suscipiterat elit,
											cursus vehicula quam a
											arcu vestibulum molestie
											<span class="dots">...</span><a href="/images/myw3schoolsimage.jpg" download>download &nbsp<img
													src="resources/more_arrow.png"></a>
										</p>
									</div>
								</div>
							</div>




							<!--paper5-->
							<div class="flex-container3">
								<div>
									<img src='resources\whitepaper_placeholder.png' class='whitepaper-image'>
								</div>
								<div>
									<div class="whitepaper-icon-heading">
										Whitepaper Title
									</div>
									<div>
										<p>Donec vulputate,
											magna eleifend
											porttitor, vehiculat
											lectus elit et enim
											pulvinar non
											suscipiterat elit,
											cursus vehicula quam
											a arcu vestibulum
											molestie
											<span class="dots">...</span>
											<a href="/images/myw3schoolsimage.jpg" download>download &nbsp<img
													src="resources/more_arrow.png"></a>
									</div>
								</div>
							</div>


						</div>

					</div>
					<!--featured videos-->
					<div class="grid-item3">
						<div class="videos">
							<div class="heading1" style="margin-left:2px">
								Featured Videos
							</div>
							<!--main video with screen-->
							<div class="video-frame">
								<iframe width="auto%" height="168px" src="https://www.youtube.com/embed/FEIFzQPmo7E" frameborder="0"
									allow="accelerometer; autoplay=1; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
									allowfullscreen></iframe>
							</div>

							<div class="flex-container3" style="padding-left:2px">
								<div class="whitepaper-icon-heading">Featured:Title of Video</div>
								<p>Video description donec vulputate, eleifend portitor, vehiculat ac scelerisque tortor neque bibendum
									cursus vehicula quam a arcu vestibulum molestiedolor ac scel erisque tortor neque bibendum magna
									dolor.</p>
							</div>

						</div>
						<!--video image1-->
						<div class="flex-container4">
							<img src="resources\video_placeholder.png" class="video-image">
							<div>
								<div class="video-heading">
									Title
								</div>
								<p>Donec vulputate magna, eleifend portitor, vehicular ac...<a href="#">watch</a></p>
							</div>

						</div>
						<!--video image2-->
						<div class="flex-container4">
							<img src="resources\video_placeholder.png" class="video-image">
							<div>
								<div class="video-heading">
									Title
								</div>
								<p>Donec vulputate magna, eleifend portitor, vehicular ac...<a href="#">watch</a></p>
							</div>

						</div>
						<!--video image3-->
						<div class="flex-container4">
							<img src="resources\video_placeholder.png" class="video-image">
							<div>
								<div class="video-heading">
									Title
								</div>
								<p>Donec vulputate magna, eleifend portitor, vehicular ac...<a href="#">watch</a></p>
							</div>

						</div>
					</div>

				</div>
			</div>
		</div>
		<div class="advertisement3">
			<div class="add3">
				<div style="align-self: center;margin-left: 96px">
					<img src="resources\ad_768x90.png">
				</div>
			</div>
		</div>
	</div>
	<!--footer section-->
	<div class="footer">
		<div class="col" style="padding-left:24px">
			<p class="footer-heading">Products</p>
			<a href="#">Build Business Credit</a>
			<a href="#">Great Credit Reports</a>
			<a href="#">FREE Company Data</a>
			<a href="#">Establish Business Credit</a>
			<a href="#">D & B Credibility Review</a>
			<a href="#">Search for D&B D-U-N-S&reg;</a>
		</div>
		<div class="col" style="padding-left:17px">
			<p class="footer-heading">Our Network</p>
			<a href="#">Partners</a>
			<a href="#">Affiliates</a>
			<a href="#">Blog</a>
			<a href="#">D&B International</a>
			<a href="#">CrediblityLIVE</a>

		</div>
		<div class="col" style="padding-left:41px">
			<p class="footer-heading">Our Company</p>
			<a href="#">About Us</a>
			<a href="#">Careers</a>
			<a href="#">Contacts Us</a>
			<a href="#">Company History</a>
			<a href="#">Testimonials</a>
			<a href="#">Credit Resources</a>
		</div>
		<div class="col" style="padding-left:43px">
			<p class="footer-heading">Site Links</p>
			<a href="#">Home</a>
			<a href="#">Site Map</a>
			<a href="#">Glossary</a>
			<a href="#">Privacy Policy</a>
			<a href="#">Terms of Service</a>

		</div>
		<div class="col" id="footer-image">
			<img src="resources\footerimage.jpeg">
		</div>
	</div>
	<script src="https://code.jquery.com/jquery-3.5.1.js"></script>
	<link rel="stylesheet" href="https://unpkg.com/flickity@2/dist/flickity.min.css">
	<script src="https://unpkg.com/flickity@2/dist/flickity.pkgd.min.js"></script>
	<script>
		/*google search funtion*/
		function mySearchfunction() {
			var q = document.getElementById("search").value;
			window.open('http://google.com/search?q=' + q);
		};
		/*read more function for company*/
		$(document).ready(function () {
			$(".myBtn").click(function () {
				$(this).prev().toggle();
				$(this).siblings('.dots').toggle();
			});
		});

	</script>
	<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
</body>

</html>

# css part

body{
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
}

/*header*/
.header{
  margin-left:12.2%;
  margin-right:15.4%;
  display: flex;
  justify-content: flex-end;
  background-color: #ffffff;
  margin: 0px auto;
}


.prod{
  margin-top: 0px; 
  margin-left: 0px;
  padding-left: 15px; 
  margin-right: 20px;
}
.att2{
  margin-top:0px;
    padding-bottom:3px;
    padding-right: 15px;
    padding-left: 20px;
  margin-right: 220px;
  background-color: #eee;
}
.prod a,.att2 a
{
  margin: 5px;
  padding-right:2px;
  font-size: 14px;
  line-height: 2px;
  font-weight: 250;
  text-decoration: none;
  color:#007FFF;

}
.prod a{
  font-weight: bold;
}
.att2 a{
  font-size: 13px;
}
.prod span,
.att2 span{
  font-size:14px;
  color: blue;
}


/*----company logo---*/
.main-nav{
  width: 100%;
  position: relative;
  height: 60px;
}
.nav{
    margin: 0px auto;
    display: flex;
  background-color: #ffffff;
}

.left-nav{
  width: 50%;
  display: flex;
  justify-content: flex-end;
  flex-direction: row;
  margin-bottom: 1.2%;
}
.left-nav .logo{
  margin-right: 15px;
  width:34%;
  padding-bottom:3px;
}
.left-nav .review{ 
  letter-spacing: 2px;
  color: #000080;
  font-weight: 300;
  margin-left: 10px;
  margin-top: 15px;
  padding-right:0px; 
  font-size: 25px;
  padding-left: 23px;
}
.right-nav{
  width: 50%;
  display: flex;
  justify-content: space-around;
}

.talk{
  display: flex;
  margin-top: 7px;
  margin-bottom: 5px;
  margin-left: 30px;
}
.call{
  padding-top:0px; 
  height: 35px;
  width: 15px;
  transform: rotate('130deg');
  color:blue;
  margin-top: 17px;
  margin-left: 22px;
}
.text-no{
  display: flex;
  flex-direction: column;
  margin: 0px auto;
  margin-top: 11px;
}
.text{
  padding-left: 11px;
  margin-left: 10px;
  padding-bottom: 0px;
  margin-top: 7px;
  font-size: 13px;
}
.no{
     color:#007FFF;
  padding-left: 10px;
  margin-left: 10px;
  font-weight: 700;
  font-size: 20px;
}
/*header completed*/
.main-content{
  background-image: url("resources/bkg.png");
}
/*navbar*/
.navbar{
  display:flex;
  margin-top:25px;
  margin-left:12.2%;
  margin-right:15.4%;
  background-color: #11516f;
  color:white;
  height:38px;
  padding-left:21px;
}
.navbar > div{
  margin-top:13px;
  text-align: center;
  font-size: 12px;
  margin-right:6px;
}
/*search-bar*/
.search-bar{
  display:flex;
  margin-left:12.2%;
  margin-right:15.4%;
  background-image: url("resources/search_bk.png");
}

#company-name{
  width:50%;
  margin:0px auto 2px 43px;
  padding-top:35px;
  padding-bottom: 30px;
}
#search-button{
  float:right;
  padding-right:20px;
}
#search-bar-right{
  margin-left:32px;
  padding-left:0px;
}
.search-box{
  margin-left:15px;
  margin-right:7px;
  width:371px;
  height:40px;
  border:none;
  margin-top:39px;
  border-radius: 10px;
}
.search-button{
  margin-top:37px;
  height:47px;
  width:63px;
  background-image: url('resources/search.png');
}
.search-text{
  margin-top:8px;
  padding-left:20px;
  font-size:14px;
}
/*slider part*/

.slider{
  position: relative;
}
.carousel {
  margin-left:12.2%;
  margin-right:15.4%;
    position: relative;
}

.carousel img{
    width:100%;
    z-index: 10;
}

.carousel-cell {
  width: 100%;
  height: auto;
  margin-right: 0px;
  display: flex;
  align-items: center;
  justify-content: center;
    z-index: 10;
}

.carousel.is-fullscreen .carousel-cell {
  height: 100%;
    z-index: 10;
}

.carousel-cell-image {
  display: block;
  max-height: 100%;
    z-index: 10;
}

.carousel.is-fullscreen .carousel-cell-image {
  max-width: 100%;
    z-index: 10;
}

.flickity-page-dots {
    display: flex;
    justify-content: flex-end;
    height: 50px;
    position: relative;
    bottom: 50px;
    width: 97.7%;
    padding: 0px 11px 0px 11px;
    list-style: none;
    text-align: center;
    line-height: 1;
    background: black;
    opacity: 0.57;
    z-index: 10;
}

.flickity-page-dots .dot {
    display: inline-block;
    width: 6.5px;
    height: 5.5px;
    margin: 21px 4px;
    background: #ffffff;
    border-radius: 50%;
    opacity: 0.7;
    cursor: pointer;
    z-index: 10;
}
.see-through-me{
  margin-left:12.2%;
  margin-right:15.4%;
  padding-left:15px;
  margin-top:0px;
  color:white;
  background-color: black;
  opacity: 0.57%;
  margin-bottom:-10px;
}
/*grid part*/
.grid-container{
  display: grid;
  grid-template-columns: 19.5% 78%;
  grid-gap: 20px;
  background-color:#ffffff;
  margin-top:0px;
  margin-left:12.2%;
  margin-right:15.4%;
  margin-bottom:0px;
  padding:7px 20px 1px 20px;
}
.grid-item{
  background-color:#fafafa;
  padding-bottom:0px;
}
.categories-item{
  padding-top:7px;
}
.categories-p-tag{
  padding-left:16px;
}
.categories-p-tag p{
  margin:0px 0px 0px 0px;
  padding:0px 0px 0px 0px;
  line-height: 25px;
  font-size: 13px;
}
.partition{
  display:grid;
  grid-template-columns: 50% 50%;
  grid-gap: 0px;
}
.partition-left{
  padding-right: 15px;
}
.heading{
  padding-top:23px;
  font-weight:bold;
  font-size: 15px;
  padding-bottom: 5px;
  color:#06628d;
  border-bottom: solid #eeeeee 1px;
}
/*icon and text */
.iconDetails {
margin: 3px 9px 0px 1px;
float:left;
height:48px;
width:48px; 
} 
.partition p{
  margin: 0px 0px 0px 0px;
  padding: 0px 0px 0px 0px;
  font-size: 11px;
  line-height: 15px;
}
.myBtn{
  border:none;
}
.more {display: none;}
.flex-container{
  display:flex;
  margin: auto 0px 0px 0px;
  padding:12px 10px 20px 28px;
  border-bottom: solid #eeeeee 1px;
}
.flex-container  a{
  color:#06628d;
  text-decoration: none;
}
.flex-icon-heading{
  font-weight: bold;
  font-size:12px;
  margin-top:1px;
  margin-bottom:8px;
}
/*advertisement*/
.advertisement1{
  display:flex;
  height:auto;
  margin-left:20px;
  padding-top:15px;
  padding-bottom:15px;
  align-self: center;
  background-color: skyblue;
  padding-left:80px;
}
.advertisement2{
  display: flex;
  justify-content:center;
  padding-left: 0px 0px auto 2px;
  margin-top:4px;
}
.advertisement3{
  display:flex;
  margin:auto 15.4% auto 12.2%;
  background-color:#ffffff;
  padding-top:42px;
  padding-bottom: 40px;
}
.add3{
  display: flex;
  padding-top:2px;
  width:100%;
  height:130px;
  background-color: #ecf9ff;
}
/*featured article section*/
#featured-articles{
  padding-left:28px;
  padding-top:25px;
}
#article-date{
  color:gray
}
.iconDetails2{
margin: 4px 8px 0px 0px;
float:left;
padding-left:1px;
height:48px;
width:48px; 
}
/*featured whitepaper and videos*/
.heading1{
  padding-top:17px;
  font-weight:bold;
  font-size: 15px;
  border-bottom:solid #eeeeee 1px;
  padding-bottom: 5px;
  color:#06628d;
}
.grid-container3{
  display:grid;
  grid-template-columns: 48.5% 48.5%;
  padding:0px 0px 0px 0px;
  margin:23px 0px 2px 0px;
  column-gap: 20px;
  background-color:#ffffff;
}
.grid-item3{
  background-color:#fafafa;
  padding-right:10px;
}
.flex-container3{
  border-bottom:solid #eeeeee 1px;
  margin-top:5px;
  margin-bottom:0px;
  padding-bottom: 18px;
  padding-top:7px;

}
.whitepaper{
  padding-left:29px;
  padding-top:7px;
  padding-right:2px;
}
.videos{
  padding-left:28px;
  padding-top:8px;
}
.video-frame{
  display:flex;
  padding-top:17px;
}
.whitepaper-image{
margin: 0px 10px 0px 0px;
padding-right:10px;
padding-top:5px;
float:left;
height:80px;
width:60px; 
}
.whitepaper-icon-heading{
  padding-top:2px;
  font-weight: bold;
  font-size:12px;
  margin-bottom: 10px;
}
.grid-container3 p{
  margin:0px 5px 0px 0px;
  font-size:11.5px;
  padding:0px 5px 0px 0px;
  line-height: 15px;
  background-color: #fafafa;
}
.grid-container3 a{
  color:#06628d;
  text-decoration: none;
}
.video-image{
  margin:6px 12px auto 28px;
  float:left;
}
.flex-container4{
  display: flex;
  border-bottom:solid #eeeeee 1px;
  margin-top:10px;
  padding-bottom:20px;
}
.video-heading{
  padding-top:10px;
  font-weight:bold;
  font-size: small;
  margin-bottom: 8px;
}
/*footer*/
.footer{
  display:flex;
  margin-left:12.4%;
  margin-right:15%;
  display:flex;
}
.footer-heading{
  font-weight: bold;
  padding-bottom: 5px;
  font-size: 14px;
}
.col{
  flex-direction: column;
  padding:20px 0px 0px 24px;
  text-align:justify;
}
.col a{
  display: block;
  text-decoration: none;
  color:black;
  font-size:13px;
  line-height: 18.9px;
  margin-top:1px;
}
#footer-image{
padding-left:52px;
padding-top:56px;
border-left:solid #eeeeee 1px;
margin-left:53px;
}

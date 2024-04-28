# Final-Project
[Upl<!DOCTYPE html>
<html>
    <head>
        <title> About Us Section</title>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <link rel="stylesheet"  href="https://pro.fontawesome.com/releases/v6.0.0-beta1/css/all.css">
    </head>
    <body>
        <div class="Section">
            <div class="container">
                <div class="content-section">
                    <div class="title">
                        <h1>About Us</h1>
                    </div>
                    <div class="content">
                    <h3>This website is to Inspire you plan the next adventure.</h3>
                       <p>  We provide detailed guides and resources for campgrounds across the State of Georgia,
                          along with gear recommendations from our team of experienced campers.
                Our goal is to make trip planning easy by consolidating the best information about destinations, 
and camping skills into one place.<br> We also aim to build an inclusive community rooted in a shared appreciation for nature.
Whether you're a backcountry veteran or just getting started camping,
 you'll find something useful in our pages. We're campers serving campers, <br>
 so the content comes from direct experience in the outdoors."
The focus is on being a comprehensive trip planning resource,<br>
 providing value through guides and gear advice,and nurturing a community around a shared love of camping.</p>
              <div class="button">
                <a href="">Read More</a>
              </div>
              <div class="image-section">
                <img src="images/image one.jpg.jpeg"> 
             </div>
                <div class="social">
                
                <a href=""><i class="fa-brands fa-facebook"></i></a>
                <a href=""><i class="fa-brands fa-twitter"></i></a>
                <a href=""><i class="fa-brands fa-instagram"></i></a>
            </div>
        </div>
        </div>
       
    </div>
</div>
    </body>
    <footer>
		<p>&copy; 2024,Jack Otieno </p>
	</footer>
</html>


<style>
@import url('https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');
</style>
* {margin: 0px;
    padding: 0px;
    box-sizing: border-box;
    font-family: 'poppins',sans-serif;
}
.Section{
width: 100%;
min-height: 100vh;
background-color: #ddd;    
}
.container{
    width: 80%;
    display: block;
    margin: auto;
    padding-top: 100px;
}
.content-section{
    float:left;
    width: 55%;
}
.image-section{ 
    float: right;
    width: 20%; /* Adjust the width as needed */
    margin-left: 20px; /* Add some space between the text and the image */
}

.image-section img{
    width: 100%; /* Make the image fill its container */
    height: auto;
}

.content-section.title {
    text-transform: uppercase;
    font-size: 28px;
}
.content-section .content h3{
    margin-top: 20px;
    color: #5d5d5d;
}
.content-section.content p{
    margin-top: 10px;
    font-family: sans-serif;
    font-size: 17px;
    line-height: 1.5;
}
.content-section.content.button{
    margin-top: 30px;
}
.content-section.content.button a{
    background-color:#3d3d3d;
    padding: 12px 40px;
    text-decoration: none;
    color: #fff;
    font-size: 25px;
    letter-spacing: 1.5px;
}
.content-section.content.button a:hover{
background-color: #a52a2a;
color: #fff;
}
.content-section.social{
    margin-top: 40px  40px;
}
.content-section.i{
    color: #a52a2a;
    font-size: 30px;
    padding: 0px 10px;
}
.content-section.content i:hover{
    color: #3d3d3d;
}
<!DOCTYPE html>
<html>
<head>
  <title> "Campfire Adventures in Atlanta</title>
</head>
<body>

<h1>Camping Expedition</h1>
<p> When it comes to camping near Atlanta, Georgia, there are several options to consider. 
    Some of the best national forest campgrounds near Atlanta include Lake Winfield Scott, 
    Desoto Falls Recreational Area, Tallulah River Campground, Deep Hole Recreation Area,
     and Lake Rabun Beach Recreation Area.<br> Additionally, there are numerous other campgrounds and camping sites within an hour of Atlanta that offer a variety of experiences for outdoor enthusiasts.
     <br>These locations provide opportunities for camping in natural settings and enjoying the great outdoors</p>

</body>
</html>
<!DOCTYPE html>
<html lang="en">

<body>
    <header>
        <h1>Chastain Park</h1>
        <img src="images/camping1.ico.jpg" alt="Chastain Park ">
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About Us</a></li>
                <li><a href="#facilities">Facilities</a></li>
                <li><a href="#activities">Activities</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="home">
        <h2>Welcome to Adventure Camping!</h2>
        <p>Experience nature like never before with our camping site.</p>
        <a href="#about" class="btn">Learn More</a>
    </section>

    <section id="about">
        <h2>About Us</h2>
        <p>We are dedicated to providing unforgettable outdoor experiences for adventurers of all ages.</p>
        <a href="#facilities" class="btn">Our Facilities</a>
    </section>

    <section id="facilities">
        <h2>Facilities</h2>
        <ul>
            <li>Spacious Campsites</li>
            <li>Clean Restrooms and Showers</li>
            <li>Fire Pits</li>
            <li>Picnic Areas</li>
            <li>Hiking Trails</li>
        </ul>
        <a href="#activities" class="btn">Explore Activities</a>
    </section>

    <section id="activities">
        <h2>Activities</h2>
        <ul>
            <li>Hiking</li>
            <li>Fishing</li>
            <li>Canoeing</li>
            <li>Wildlife Watching</li>
            <li>Stargazing</li>
        </ul>
        <a href="#contact" class="btn">Contact Us</a>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <p>For inquiries and reservations, please contact us at:</p>
        <address>
            Adventure Camping<br>
            Bonfire Adventure<br>
            Chastain park<br>
            Phone: 555-123-4567<br>
            Email: info@chastainbonfire.com
        </address>
    </section>

    <footer>
        <p>&copy; 2024 chastain Camping. All rights reserved.</p>
    </footer>

</body>
</html>

<!DOCTYPE html>
<html>
<head>
<title>Chattahoochee River Park</title>
</head>
<p>The Chattahoochee River National Recreation Area in Atlanta has received positive reviews from outdoor enthusiasts.<br>
     Visitors particularly appreciate the park's varied pursuits, <br>
     including hiking trails, and the gorgeous scenery that provides a peaceful escape from the city's busy atmosphere.<br>
      The park is open daily from dawn to dusk, offering a natural retreat for locals and tourists alike 1. <br>
    For more detailed visitor reviews and experiences,<br>
     you can explore platforms like TripAdvisor and Yelp to gain insights into others' experiences at the park.</p>
<body>

<img src="images/camping4.jpg" alt="My Image">

</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Form</title>
    <style>
        /* Basic styling for the form */
        form {
            max-width: 400px;
            margin: 0 auto;
        }
        input[type="text"], input[type="tel"], input[type="email"] {
            width: 100%;
            padding: 10px;
            margin-bottom: 15px;
            border: 1px solid #ccc;
            border-radius: 4px;
            box-sizing: border-box;
        }
        input[type="submit"] {
            background-color: #4CAF50;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 4px;
            cursor: pointer;
        }
        input[type="submit"]:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>

<h2>Contact Form</h2>

<form action="#" method="post">
    <label for="first_name">First Name:</label>
    <input type="text" id="first_name" name="first_name" required>

    <label for="last_name">Last Name:</label>
    <input type="text" id="last_name" name="last_name" required>

    <label for="phone_number">Phone Number:</label>
    <input type="tel" id="phone_number" name="phone_number" pattern="[0-9]{3}-[0-9]{3}-[0-9]{4}" placeholder="Format: 123-456-7890" required>

    <label for="email">Email Address:</label>
    <input type="email" id="email" name="email" required>

    <input type="submit" value="Submit">
</form>
<p>Be assured that personal infomation will not be shared with a third party</p>

</body>
<footer>
    <p>&copy; 2024,Jack Otieno </p>
</footer>
</html>

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Summer 2024  Bonfire Adventures Camping </title>
    <link rel="stylesheet" href="events.styles.css">
</head>

<body>
    <div class="container">
        <h1>Summer 2024  Bonfire Adventures Camping</h1>

        <div class="event">
            <h2>Adventure Weekend</h2>
            <img src="images/camping2.jpg" alt="my Favorite tent" width="250" height="250" >
            <p class="date">June 15-17, 2024</p>
            <p class="location">Piedmont National Wildlife Refuge</p>
            <p>Join us for a weekend of hiking, camping, and wildlife spotting in the beautiful Piedmont National Wildlife Refuge.</p>
        </div>

        <div class="event">
            <h2>Lakefront Campfire Cookout</h2>
            <img src="images/camping3.jpg" alt="my Favorite tent" width="250" height="250"  >
            <p class="date">July 4, 2024</p>
            <p class="location">Lake Lanier</p>
            <p>Celebrate Independence Day with a lakeside campfire cookout featuring delicious food, live music, and fireworks.</p>
        </div>

        <div class="event">
            <h2>Family Nature Exploration</h2>
            <img src="images/camping4.jpg" alt="my Favorite tent"width=250 height="250" >
            <p class="date">August 10-12, 2024</p>
            <p class="location">Chattahoochee National Forest</p>
            <p>Bring the whole family for a weekend of outdoor adventures, including guided nature hikes, wildlife encounters, and stargazing.</p>
        </div>
    </div>
</body>
<footer>
    <p>&copy; 2024,Jack Otieno </p>
</footer>
</html>

body {
    font-family: Arial, sans-serif;
    background-color: #53a0ae;
    color: blue;
    margin: 0;
    padding: 0;
}

.container {
    max-width: 800px;
    margin: 20px auto;
    padding: 20px;
    background-color: #fff;
    border-radius: 8px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    
    

h1 {
    color: #a40c11;
    text-align: center;
    margin-bottom: 30px;
}

.event {
    background-color: #afcda9;
    padding: 20px;
    margin-bottom: 20px;
    border-radius: 8px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
   


}
.aside img {
    display: block;
    width: 100%; /* Make images fill the aside container */
    margin-bottom: 10px;}

h2 {
    color: #ef1b1bbd;
    margin-top: 0;
}

.date {
    color: #e1e10c;
    font-style: italic;
}

.location {
    color: #d81a56;
    margin-bottom: 10px;
}

p {
    color: #e70e0e;
    line-height: 1.6;
}

<!DOCTYPE html>
<html lang="en">

<head>
	<meta charset="utf-8">
	<title>Bonfire Camping Adventures</title>
	<link rel="shortcut icon" href="images/camping1.ico.jpg">
	<link rel="stylesheet" href="styles.css.css">
	<style>
       
        @media screen and (max-width: 600px) {
            /* Adjust styles for smaller screens here */
            body {
                font-size: 14px; 
            }
        }
    </style>
</head>
<body>
	<header>
		<img src="images/camping1.ico.jpg" alt="my Favorite tent" height="80">
		<h2>Bonfire Camping Adventures</h2>
		<h3><span class="shadow"></span>Creating Lifelong memories. </h3>
	</header>

	<nav id="nav_menu">
		<ul>	
		<li><a href="index.html" class="active">Home</a></li>
		<li><a href="events.html.html">Events</a></li>
		<li><a href="contact.html">Contacts</a></li>
		<li><a href="about us.html"> About Us</a></li>
			<li><a href="mission.html">Mission</a></li>				
	<main>
		<section>
			
			<article>
				<h2>Why Camping is exciting in Georgia.</h2>
				<img src="images/camping2.jpg" alt="our spacious tents ">
				
				<p>Camping in Georgia offers a multitude of benefits and experiences that make it an excellent choice for outdoor enthusiast.<ol>
					<ol>Georgia boasts diverse landscapes, including mountains, forests, coastal areas, and rivers, providing campers with a wide range of scenic environments to explore and enjoy.</ol>
					<ol>From hiking and fishing to kayaking and rock climbing, Georgia offers an abundance of outdoor activities for campers of all interests and skill levels.</ol>
					<ol>Georgia generally enjoys a mild climate, making it suitable for camping year-round. Summers are warm and inviting for activities like swimming and camping, while mild winters allow for cozy campfires and comfortable outdoor experiences.</ol>
					<ol>Georgia is home to numerous state parks, national forests, and private campgrounds, offering a variety of camping options ranging from rustic tent sites to fully equipped RV parks with amenities.</ol>
					<ol>Georgia's diverse ecosystems support a wide array of wildlife, providing campers with opportunities to observe birds, mammals, reptiles, and other fascinating creatures in their natural habitats.</ol>
				</ol></p>
				<p><a href="camping.html">Read more.</a>&nbsp;<b>and like our facebook page for more!</b></p>
			</article>
			
			<h2>Our camping Packages</h2>
			<ul>
				<li>Family Package: $195</li>
				<li>Couples Package: $499</li>
				<li>Clubs Package: $799</li>
			</ul>
		</section>
		
		<aside>
			<h2>Camping sites</h2>
			<h3>Chastain Park<br><a href="chastain.html.html">Within Atlanta’s northwest city limits</a></h3>
			<img src="images/bonfire.jpg" alt="Chastain Park">
			<h3>Chattahoochee River Park<br><a href="Chattahoochee River Park.html">the north end of Metro Atlanta</a></h3>
			<img src="images/camping3.jpg" alt="Chattahoochee River Park">
			<h3>Piedmont Park<br><a href="piedmontpark.html">the heart of Midtown Atlanta</a></h3>
			<img src="images/camping4.jpg" alt="Piedmont Park">
			
		</aside>
	</main>
	<footer>
		<p>&copy; 2024,Jack Otieno </p>
	</footer>
</body>
</html>

/*!
 * SlickNav Responsive Mobile Menu v1.0.10
 * (c) 2016 Josh Cope
 * licensed under MIT
 */
!function(e,t,n){function a(t,n){this.element=t,this.settings=e.extend({},i,n),this.settings.duplicate||n.hasOwnProperty("removeIds")||(this.settings.removeIds=!1),this._defaults=i,this._name=s,this.init()}var i={label:"MENU",duplicate:!0,duration:200,easingOpen:"swing",easingClose:"swing",closedSymbol:"&#9658;",openedSymbol:"&#9660;",prependTo:"body",appendTo:"",parentTag:"a",closeOnClick:!1,allowParentLinks:!1,nestedParentLinks:!0,showChildren:!1,removeIds:!0,removeClasses:!1,removeStyles:!1,brand:"",animations:"jquery",init:function(){},beforeOpen:function(){},beforeClose:function(){},afterOpen:function(){},afterClose:function(){}},s="slicknav",o="slicknav";Keyboard={DOWN:40,ENTER:13,ESCAPE:27,LEFT:37,RIGHT:39,SPACE:32,TAB:9,UP:38},a.prototype.init=function(){var n,a,i=this,s=e(this.element),r=this.settings;if(r.duplicate?i.mobileNav=s.clone():i.mobileNav=s,r.removeIds&&(i.mobileNav.removeAttr("id"),i.mobileNav.find("*").each(function(t,n){e(n).removeAttr("id")})),r.removeClasses&&(i.mobileNav.removeAttr("class"),i.mobileNav.find("*").each(function(t,n){e(n).removeAttr("class")})),r.removeStyles&&(i.mobileNav.removeAttr("style"),i.mobileNav.find("*").each(function(t,n){e(n).removeAttr("style")})),n=o+"_icon",""===r.label&&(n+=" "+o+"_no-text"),"a"==r.parentTag&&(r.parentTag='a href="#"'),i.mobileNav.attr("class",o+"_nav"),a=e('<div class="'+o+'_menu"></div>'),""!==r.brand){var l=e('<div class="'+o+'_brand">'+r.brand+"</div>");e(a).append(l)}i.btn=e(["<"+r.parentTag+' aria-haspopup="true" role="button" tabindex="0" class="'+o+"_btn "+o+'_collapsed">','<span class="'+o+'_menutxt">'+r.label+"</span>",'<span class="'+n+'">','<span class="'+o+'_icon-bar"></span>','<span class="'+o+'_icon-bar"></span>','<span class="'+o+'_icon-bar"></span>',"</span>","</"+r.parentTag+">"].join("")),e(a).append(i.btn),""!==r.appendTo?e(r.appendTo).append(a):e(r.prependTo).prepend(a),a.append(i.mobileNav);var c=i.mobileNav.find("li");e(c).each(function(){var t=e(this),n={};if(n.children=t.children("ul").attr("role","menu"),t.data("menu",n),n.children.length>0){var a=t.contents(),s=!1,l=[];e(a).each(function(){return e(this).is("ul")?!1:(l.push(this),void(e(this).is("a")&&(s=!0)))});var c=e("<"+r.parentTag+' role="menuitem" aria-haspopup="true" tabindex="-1" class="'+o+'_item"/>');if(r.allowParentLinks&&!r.nestedParentLinks&&s)e(l).wrapAll('<span class="'+o+"_parent-link "+o+'_row"/>').parent();else{var d=e(l).wrapAll(c).parent();d.addClass(o+"_row")}r.showChildren?t.addClass(o+"_open"):t.addClass(o+"_collapsed"),t.addClass(o+"_parent");var p=e('<span class="'+o+'_arrow">'+(r.showChildren?r.openedSymbol:r.closedSymbol)+"</span>");r.allowParentLinks&&!r.nestedParentLinks&&s&&(p=p.wrap(c).parent()),e(l).last().after(p)}else 0===t.children().length&&t.addClass(o+"_txtnode");t.children("a").attr("role","menuitem").click(function(t){r.closeOnClick&&!e(t.target).parent().closest("li").hasClass(o+"_parent")&&e(i.btn).click()}),r.closeOnClick&&r.allowParentLinks&&(t.children("a").children("a").click(function(t){e(i.btn).click()}),t.find("."+o+"_parent-link a:not(."+o+"_item)").click(function(t){e(i.btn).click()}))}),e(c).each(function(){var t=e(this).data("menu");r.showChildren||i._visibilityToggle(t.children,null,!1,null,!0)}),i._visibilityToggle(i.mobileNav,null,!1,"init",!0),i.mobileNav.attr("role","menu"),e(t).mousedown(function(){i._outlines(!1)}),e(t).keyup(function(){i._outlines(!0)}),e(i.btn).click(function(e){e.preventDefault(),i._menuToggle()}),i.mobileNav.on("click","."+o+"_item",function(t){t.preventDefault(),i._itemClick(e(this))}),e(i.btn).keydown(function(t){var n=t||event;switch(n.keyCode){case Keyboard.ENTER:case Keyboard.SPACE:case Keyboard.DOWN:t.preventDefault(),n.keyCode===Keyboard.DOWN&&e(i.btn).hasClass(o+"_open")||i._menuToggle(),e(i.btn).next().find('[role="menuitem"]').first().focus()}}),i.mobileNav.on("keydown","."+o+"_item",function(t){var n=t||event;switch(n.keyCode){case Keyboard.ENTER:t.preventDefault(),i._itemClick(e(t.target));break;case Keyboard.RIGHT:t.preventDefault(),e(t.target).parent().hasClass(o+"_collapsed")&&i._itemClick(e(t.target)),e(t.target).next().find('[role="menuitem"]').first().focus()}}),i.mobileNav.on("keydown",'[role="menuitem"]',function(t){var n=t||event;switch(n.keyCode){case Keyboard.DOWN:t.preventDefault();var a=e(t.target).parent().parent().children().children('[role="menuitem"]:visible'),s=a.index(t.target),r=s+1;a.length<=r&&(r=0);var l=a.eq(r);l.focus();break;case Keyboard.UP:t.preventDefault();var a=e(t.target).parent().parent().children().children('[role="menuitem"]:visible'),s=a.index(t.target),l=a.eq(s-1);l.focus();break;case Keyboard.LEFT:if(t.preventDefault(),e(t.target).parent().parent().parent().hasClass(o+"_open")){var c=e(t.target).parent().parent().prev();c.focus(),i._itemClick(c)}else e(t.target).parent().parent().hasClass(o+"_nav")&&(i._menuToggle(),e(i.btn).focus());break;case Keyboard.ESCAPE:t.preventDefault(),i._menuToggle(),e(i.btn).focus()}}),r.allowParentLinks&&r.nestedParentLinks&&e("."+o+"_item a").click(function(e){e.stopImmediatePropagation()})},a.prototype._menuToggle=function(e){var t=this,n=t.btn,a=t.mobileNav;n.hasClass(o+"_collapsed")?(n.removeClass(o+"_collapsed"),n.addClass(o+"_open")):(n.removeClass(o+"_open"),n.addClass(o+"_collapsed")),n.addClass(o+"_animating"),t._visibilityToggle(a,n.parent(),!0,n)},a.prototype._itemClick=function(e){var t=this,n=t.settings,a=e.data("menu");a||(a={},a.arrow=e.children("."+o+"_arrow"),a.ul=e.next("ul"),a.parent=e.parent(),a.parent.hasClass(o+"_parent-link")&&(a.parent=e.parent().parent(),a.ul=e.parent().next("ul")),e.data("menu",a)),a.parent.hasClass(o+"_collapsed")?(a.arrow.html(n.openedSymbol),a.parent.removeClass(o+"_collapsed"),a.parent.addClass(o+"_open"),a.parent.addClass(o+"_animating"),t._visibilityToggle(a.ul,a.parent,!0,e)):(a.arrow.html(n.closedSymbol),a.parent.addClass(o+"_collapsed"),a.parent.removeClass(o+"_open"),a.parent.addClass(o+"_animating"),t._visibilityToggle(a.ul,a.parent,!0,e))},a.prototype._visibilityToggle=function(t,n,a,i,s){function r(t,n){e(t).removeClass(o+"_animating"),e(n).removeClass(o+"_animating"),s||d.afterOpen(t)}function l(n,a){t.attr("aria-hidden","true"),p.attr("tabindex","-1"),c._setVisAttr(t,!0),t.hide(),e(n).removeClass(o+"_animating"),e(a).removeClass(o+"_animating"),s?"init"==n&&d.init():d.afterClose(n)}var c=this,d=c.settings,p=c._getActionItems(t),u=0;a&&(u=d.duration),t.hasClass(o+"_hidden")?(t.removeClass(o+"_hidden"),s||d.beforeOpen(i),"jquery"===d.animations?t.stop(!0,!0).slideDown(u,d.easingOpen,function(){r(i,n)}):"velocity"===d.animations&&t.velocity("finish").velocity("slideDown",{duration:u,easing:d.easingOpen,complete:function(){r(i,n)}}),t.attr("aria-hidden","false"),p.attr("tabindex","0"),c._setVisAttr(t,!1)):(t.addClass(o+"_hidden"),s||d.beforeClose(i),"jquery"===d.animations?t.stop(!0,!0).slideUp(u,this.settings.easingClose,function(){l(i,n)}):"velocity"===d.animations&&t.velocity("finish").velocity("slideUp",{duration:u,easing:d.easingClose,complete:function(){l(i,n)}}))},a.prototype._setVisAttr=function(t,n){var a=this,i=t.children("li").children("ul").not("."+o+"_hidden");n?i.each(function(){var t=e(this);t.attr("aria-hidden","true");var i=a._getActionItems(t);i.attr("tabindex","-1"),a._setVisAttr(t,n)}):i.each(function(){var t=e(this);t.attr("aria-hidden","false");var i=a._getActionItems(t);i.attr("tabindex","0"),a._setVisAttr(t,n)})},a.prototype._getActionItems=function(e){var t=e.data("menu");if(!t){t={};var n=e.children("li"),a=n.find("a");t.links=a.add(n.find("."+o+"_item")),e.data("menu",t)}return t.links},a.prototype._outlines=function(t){t?e("."+o+"_item, ."+o+"_btn").css("outline",""):e("."+o+"_item, ."+o+"_btn").css("outline","none")},a.prototype.toggle=function(){var e=this;e._menuToggle()},a.prototype.open=function(){var e=this;e.btn.hasClass(o+"_collapsed")&&e._menuToggle()},a.prototype.close=function(){var e=this;e.btn.hasClass(o+"_open")&&e._menuToggle()},e.fn[s]=function(t){var n=arguments;if(void 0===t||"object"==typeof t)return this.each(function(){e.data(this,"plugin_"+s)||e.data(this,"plugin_"+s,new a(this,t))});if("string"==typeof t&&"_"!==t[0]&&"init"!==t){var i;return this.each(function(){var o=e.data(this,"plugin_"+s);o instanceof a&&"function"==typeof o[t]&&(i=o[t].apply(o,Array.prototype.slice.call(n,1)))}),void 0!==i?i:this}}}(jQuery,document,window);
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Camping Website Mission Statement</title>
<style>
  body {
    font-family: Arial, sans-serif;
    background-color: #f0f0f0;
    padding: 20px;
  }

  .mission {
    background-color: #2aeb2a;
    border-radius: 10px;
    padding: 20px;
    box-shadow: 0 0 10px rgba(173, 202, 69, 0.1);
  }

  h2 {
    color: #333;
  }

  p {
    color: #666;
    line-height: 1.6;
  }
</style>
</head>
<body>

<div class="mission">
  <h2>Our Mission</h2>
  <p>Bonfire Camping Adventures inspire and enable outdoor adventure.<br> 
    By providing the most comprehensive online resource for campers to plan trips, gear up,<br>
     and connect with fellow camping enthusiasts. <br> 
     We are committed to cultivating an inclusive community rooted in a shared love of nature. </p>

</body>
<footer>
  <p>&copy; 2024,Jack Otieno </p>
</footer>
</html>

<!DOCTYPE html>
<html>
<head>
<title>Piedmont Park</title>
</head>

<body>

<h1>Piedmont Park</h1>

<img src="images/bonfire.jpg" alt="Piedmont park Image">

<p>Welcome to Piedmont Park! We have lush green spaces, walking trails,<br>
     a playground, and more for you to enjoy.The park offers a variety of activities,<br>
      including walking trails, green spaces, and a playground. <br>
      Visitors appreciate the peaceful escape it provides from the city's bustling atmosphere.<br>
       For more detailed reviews and experiences, <br>
    you can explore platforms like TripAdvisor and Yelp to gain insights into others' experiences at the park</p>

<h2>Park Hours</h2>
<p>The park is open every day from 8am to dusk.</p>

<h2>Amenities</h2>  
<ul>
  <li>Walking/Hiking Trails</li>
  <li>Playground</li> 
  <li>Picnic Areas</li>
  <li>Basketball Courts</li>
</ul>

</body>
</html>
/*!
 * SlickNav Responsive Mobile Menu v1.0.10
 * (c) 2016 Josh Cope
 * licensed under MIT
 */.slicknav_btn,.slicknav_nav .slicknav_item{cursor:pointer}.slicknav_menu,.slicknav_menu *{box-sizing:border-box}.slicknav_btn{position:relative;display:block;vertical-align:middle;float:right;padding:.438em .625em;line-height:1.125em}.slicknav_btn .slicknav_icon-bar+.slicknav_icon-bar{margin-top:.188em}.slicknav_menu .slicknav_menutxt{display:block;line-height:1.188em;float:left;color:#fff;font-weight:700;text-shadow:0 1px 3px #000}.slicknav_menu .slicknav_icon{float:left;width:1.125em;height:.875em;margin:.188em 0 0 .438em}.slicknav_menu .slicknav_icon:before{background:0 0;width:1.125em;height:.875em;display:block;content:"";position:absolute}.slicknav_menu .slicknav_no-text{margin:0}.slicknav_menu .slicknav_icon-bar{display:block;width:1.125em;height:.125em;-webkit-border-radius:1px;-moz-border-radius:1px;border-radius:1px;-webkit-box-shadow:0 1px 0 rgba(0,0,0,.25);-moz-box-shadow:0 1px 0 rgba(0,0,0,.25);box-shadow:0 1px 0 rgba(0,0,0,.25)}.slicknav_menu:after,.slicknav_menu:before{content:" ";display:table}.slicknav_menu:after{clear:both}.slicknav_nav li,.slicknav_nav ul{display:block}.slicknav_nav .slicknav_arrow{font-size:.8em;margin:0 0 0 .4em}.slicknav_nav .slicknav_item a{display:inline}.slicknav_nav .slicknav_row,.slicknav_nav a{display:block}.slicknav_nav .slicknav_parent-link a{display:inline}.slicknav_menu{*zoom:1;font-size:16px;background:#4c4c4c;padding:5px}.slicknav_nav,.slicknav_nav ul{list-style:none;overflow:hidden;padding:0}.slicknav_menu .slicknav_icon-bar{background-color:#fff}.slicknav_btn{margin:5px 5px 6px;text-decoration:none;text-shadow:0 1px 1px rgba(255,255,255,.75);-webkit-border-radius:4px;-moz-border-radius:4px;border-radius:4px;background-color:#222}.slicknav_nav{clear:both;color:#fff;margin:0;font-size:.875em}.slicknav_nav ul{margin:0 0 0 20px}.slicknav_nav .slicknav_row,.slicknav_nav a{padding:5px 10px;margin:2px 5px}.slicknav_nav .slicknav_row:hover{-webkit-border-radius:6px;-moz-border-radius:6px;border-radius:6px;background:#ccc;color:#fff}.slicknav_nav a{text-decoration:none;color:#fff}.slicknav_nav a:hover{-webkit-border-radius:6px;-moz-border-radius:6px;border-radius:6px;background:#ccc;color:#222}.slicknav_nav .slicknav_txtnode{margin-left:15px}.slicknav_nav .slicknav_item a,.slicknav_nav .slicknav_parent-link a{padding:0;margin:0}.slicknav_brand{float:left;color:#fff;font-size:18px;line-height:30px;padding:7px 12px;height:44px}
/* the styles for the elements */
* {
	margin: 0;
	padding: 0;
}
html {
	background-color: rgb(144, 198, 108);
}
body {
	font-family: Arial, Helvetica, sans-serif;
    font-size: 100%;
    width: 800px;
    margin: 0 auto;
    border: 3px solid #931420;
    background-color: #eff86e;
}
a:focus, a:hover {
	font-style: italic;
}
/* the styles for the navigation menu */
#nav_menu ul {
	list-style-type: none;
	margin: 0;
	padding: 0;
	position: relative;
}
#nav_menu ul li {
	float: left;
}
#nav_menu ul li a {
    display: block;
    width: 160px;
    text-align: center;
    padding: 1em 0;
    text-decoration: none;
    background-color: #7e9662;
    color: white;
    font-weight: bold;
}
  
  /* Add a background color on hover */
   #nav_menu :hover {
	background-color: #3e8e41;
  }
/* the styles for the header */
header {
	padding: 1.5em 0 2em 0;
	border-bottom: 3px solid #6d9314;
	background-image: linear-gradient(
	    30deg, #72e5bd 0%, #73f6ae 30%, white 50%, #f6bb73 80%, #f6bb73 100%);
}
header h2 {
	font-size: 175%;
	color: #800000;
}
header h3 {
	font-size: 130%;
	font-style: italic;
}
header img {
	float: left;
	padding: 0 30px;
	width: 100px;
	height: 80px;
}
.shadow {
	text-shadow: 2px 2px 2px #800000;
}
/* the styles for the section */
section {
	width: 525px;
	float: right;
	padding: 0 20px 20px 20px;
}
section h1 {
	font-size: 150%;
	padding: .5em 0 .25em 0;
	margin: 0;
}
section h2 {
	color: #800000;
	font-size: 130%;
	padding: .5em 0 .25em 0;
}
section p {
	padding-bottom: .5em;
}
section blockquote {
	padding: 0 2em;
	font-style: italic;
}
section ul {
	padding: 0 0 .25em 1.25em;
}
section li {
	padding-bottom: .35em;
}

/* the styles for the article */
article {
	padding: .5em 0;
	border-top: 2px solid #a7cb6e;
	border-bottom: 2px solid #2d8000;
}
article h2 {
	padding-top: 0;
}
article h3 {
	font-size: 105%;
	padding-bottom: .25em;
}
article img {
	float: right;
	margin: 0;
	height: 250px;
	width: 250px;
}

/* the styles for the aside */
aside {
	width: 215px;
	float: right;
	padding: 0 0 20px 20px;
}
aside h2 {
	color: #33800081;
	font-size: 130%;
	padding: .5em 0 .25em 0;
}
aside h3 {
	font-size: 105%;
	padding-bottom: .25em;
}
aside img {width: 150px;
	height: 120px;
	padding-bottom: 1em;
}

/* the styles for the footer */
footer {
	background-color: #63bc5bdd;
	clear: both;
	background-image: linear-gradient(
	    30deg, #72e5bd 0%, #73f6ae 30%, white 50%, #bda485 80%, #f0cb9f 100%);

}
footer p {
	text-align: right;
	color: rgba(12, 12, 11, 0.779);
	padding: 1em 0;
	font-style: italic;
}
@media (min-width:600px) {
	p{
		font-size: 1.5rem;
		line-height: 1.5;
	}
}
oading about us.html…]()

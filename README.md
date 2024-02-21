<!DOCTYPE html>
<html>
<head>
    <meta name="viewpoint" content="with=device-width, initial-scale=1.0">
    <title>Dead Poet's Novel</title>
    <link rel="stylesheet" href="style.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Roboto+Slab:wght@300;400;600&display=swap" rel="stylesheet">
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">

</head>
<body>
<section class="header">
    <nav>
         <a href="index.html"><img src="Images/logo1.png"></a>
            <div class="nav-links" id="navLinks">
                <i class="fa fa-times" onclick="hideMenu()" ></i>
                <ul>
                    <li><a href="">HOME</a></li>
                    <li><a href="">ABOUT</a></li>
                    <li><a href="">GET A QUOTE</a></li>
                    <li><a href="">REVIEWS</a></li>
                    <li><a href="">SUPPORT</a></li>
                </ul>
            </div>
            <i class="fa fa-bars" onclick="showMenu()"></i>
     </nav>
<div class="text-box">
    <h1>YOUR FICTIONAL STORY HUB</h1>
    <p>Webnovel provides genres of stories, fan fictions, light novels and comic books!
       <br> Get newest web novels and original books.
    </p>
    <a href="" class="hero-btn">To know more visit our page</a>
</div>
</section>
 <!-----Course----->
 <section class="course">
    <h1>The best place for readers</h1>
    <p>We made sure that we have awesome stories to read with easy ways to find them.<br> With a constantly improving set of tools to support the authors on their road to becoming successful.</p>

    <div class="row">
        <div class="course-col">
            <h3>Popular</h3>
            <p>Dead Poet's Novel offers most liked, enjoyed webnovels admired by most people.</p>
        </div>
        <div class="course-col">
            <h3>Trending</h3>
            <p>Dead Poet's Novel shows the top trending webnovels on daily basis, weekly and monthly. </p>
        </div>
        <div class="course-col">
            <h3>Weekly Top Pick</h3>
            <p>Dead Poet's Novel picks the top webnovels that was liked and enjoyed by the web fanfiction.</p>
        </div>
    </div>
</section>
<!--campus-->
<section class="novels">
    <h1>Great Lists</h1>
    <p>Check out the public lists to find great stories, from best rated to trending.</p>
    
    <div class="row">
        <div class="Anime">
            <img src="Images/anime.png">
            <div class="layer">
                <h3>ANIME</h3>
            </div>
        </div>
        <div class="Anime">
            <img src="Images/sci-fi.png">
            <div class="layer">
                <h3>SCI-FI</h3>
            </div>
        </div>
        <div class="Anime">
            <img src="Images/fictional.png">
            <div class="layer">
                <h3>FICTIONAL</h3>
            </div>
        </div>
    </div>
</section>
<!--facilites-->
<section class="facilities">
    <h1>Our Top Pick</h1>

    <div class="row">
        <div class="facilities-col">
            <img src="Images/top pick top.jpg">
            <h3>Top Pick of the Day</h3>
        </div>
        <div class="facilities-col">
            <img src="Images/top picks.png">
            <h3>Top 10 Picks of the Week</h3>
        </div>
        <div class="facilities-col">
            <img src="Images/top pick of the month.jpg">
            <h3>Top 10 Most Anticipated</h3>
        </div>
    </div>
</section>
<!--testimonials-->
<section class="reviews">
    <h1>Members Success Stories</h1><br>
    <h2>Publishers of our community</h2>
    <div class="row">
        <div class="reviews-col">
            <img src="Images/user1.png">
            <div>
                <p>Dead Poet's novel is the best place for web fiction for both authors and readers alike. Thanks to Royal Road, I managed to become a full time author even while in University.</p>
                <h3>Alex D</h3>
            </div>
        </div>
        <div class="reviews-col">
            <img src="Images/user2.png">
            <div>
                <p>Publishing on Dead Poet's novel has allowed me to escape the cruel corporate world where pants-wearing is mandatory to now embrace my hermit lifestyle that does not require pants.</p>
                <h3>Leonard</h3>
            </div>
        </div>
        <div class="reviews-col">
            <img src="Images/user3.png">
            <div>
                <p>Dead Poet's novel has helped me evolve my [Reader] class into the [Full-time Author] class allowing me to escape the crushing student debt debuff!</p>
                <h3>George</h3>
            </div>
        </div>
    </div>

</section>

<!--Call to action-->
<section class="cta">
    <h1>To Know More About Our Website</h1>
    <a href="" class="hero-btn">CONTACT US</a>

</section>

<!--footer-->
<section class="footer">
    <h4>ABOUT US</h4>
    <p>DEAD POET'S NOVEL is the home of web novels and fan fictions!
        <br> In our amazing community, you can find various talented individuals who write as a hobby or even professionally, 
        artists who create art for them, and many, many readers who provide valuable feedback and encouragement.</p>
</section>



<!------JavaScript for Toggle Menu------>

<script>
    var navLinks = document.getElementById("navLinks");
    function showMenu(){
        navLinks.style.right = "0";
    }
    function hideMenu(){
        navLinks.style.right = "-200px";
    }
</script>


</body>
</html>

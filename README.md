<!DOCTYPE html>
<html lang="en"></html>
<head>
    <link rel="stylesheet" href="style.css">
</head>
<header>
    <nav class="navbar">
        <ul class="links-container">
            <li class="travel"><a href="#travel">Travel</a></li>
            <li class="explore"><a href="#explore-section">Explore</a></li>
            <li class="hero"><a href="#hero-section"><img src="img/logo.png" class="logo" alt=""></a></li>
            <li class="service"><a href="#services">Services</a></li>
            <li class="book-now"><a href="#booknow">Book Now</a></li>
        </ul>
    </nav>
</header>
<main class="hero-section" id="hero-section">

    <div class="hero-section-content" data-aos="fade-up">
        <h1 class="hero-section-title">wonderful experience</h1>
        <p class="hero-section-sub-heading">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
    </div>

    <!-- scroll down img -->
    <img src="img/down arrow.png" class="scroll-down-icon" alt="scroll down indicator">
</main>
<div class="background">
    <img src="img/img1.png" class="background-image" alt="hero-section image">


    <!-- grid -->
    

</div>
<section class="explore-section" id="explore-section">
    <h1 class="section-title" data-aos="fade-up">Explore the world</h1>
    <p class="section-para" data-aos="fade-up">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut rutrum
        sem augue, vitae bibendum nibh tempor nec. Aenean quis commodo lectus, in rhoncus lorem</p>

    <!-- grid -->

    <div class="tours-container">
        <div class="tour-card" data-aos="fade-up">
            <img src="img/australia.png" class="tour-img" alt="tour-image">
            <div class="tour-body">
                <h3 class="tour-name">Australia</h3>
                <p class="tour-action">View city</p>
            </div>
        </div>

        <div class="tour-card" data-aos="fade-up">
            <img src="img/maldives.png" class="tour-img" alt="tour-image">
            <div class="tour-body">
                <h3 class="tour-name">Maldives</h3>
                <p class="tour-action">View city</p>
            </div>
        </div>

        <div class="tour-card" data-aos="fade-up">
            <img src="img/paris.png" class="tour-img" alt="tour-image">
            <div class="tour-body">
                <h3 class="tour-name">Paris</h3>
                <p class="tour-action">View city</p>
            </div>
        </div>

        <div class="tour-card" data-aos="fade-up">
            <img src="img/dubai.png" class="tour-img" alt="tour-image">
            <div class="tour-body">
                <h3 class="tour-name">Dubai</h3>
                <p class="tour-action">View city</p>
            </div>
        </div>

        <div class="tour-card" data-aos="fade-up">
            <img src="img/india.png" class="tour-img" alt="tour-image">
            <div class="tour-body">
                <h3 class="tour-name">India</h3>
                <p class="tour-action">View city</p>
            </div>
        </div>

        <div class="tour-card" data-aos="fade-up">
            <img src="img/italy.png" class="tour-img" alt="tour-image">
            <div class="tour-body">
                <h3 class="tour-name">Italy</h3>
                <p class="tour-action">View city</p>
            </div>
        </div>
    </div>
</section>
<section class="services-section" id="services">
    <h1 class="section-title" data-aos="fade-up">Why Us ?</h1>
    <p class="section-para" data-aos="fade-up">Lorem ipsum dolor sit amet, consectetur adipiscing elit. </p>

    <!-- services grid -->
    <div class="serives-grid">
        <div class="service-card" data-aos="fade-up">
            <div class="circle"></div>
            <i class="fa-solid fa-earth-americas card-icon"></i>
            <p class="service-text">We are based all over the world</p>
        </div>
        <div class="service-card" data-aos="fade-up">
            <div class="circle"></div>
            <i class="fa-solid fa-coins card-icon"></i>
            <p class="service-text">Travel the World,Without thinking</p>
        </div>
        <div class="service-card" data-aos="fade-up">
            <div class="circle"></div>
            <i class="fa-solid fa-book-open card-icon"></i>
            <p class="service-text">Get to know about local cultures</p>
        </div>
        <div class="service-card" data-aos="fade-up">
            <div class="circle"></div>
            <i class="fa-solid fa-person-snowboarding card-icon"></i>
            <p class="service-text">Have you best experience</p>
        </div>
    </div>
    html{
    scroll-behavior: smooth;
}

body{
    font-family: 'Poppins', sans-serif;
    background: #161813;
    overflow-x: hidden;
}

.navbar{
    position: fixed;
    top: 0;
    left: 0;
    z-index: 9;
    width: 100%;
    height: 100px;
    padding: 20px 10vw;
}

.navbar.bg{
    background: #161813;
}

.links-container{
    display: flex;
    align-items: center;
    justify-content: center;
    list-style: none;
}

.logo{
    height: 50px;
    margin-top: 10px;
}

.link-item{
    margin: 0 20px;
    transition: .5s;
}

.link-item a{
    color: #fff;
    text-decoration: none;
    padding: 20px;
}

.link-item:hover{
    transform: scale(1.2);
}
.hero-section{
    width: 100%;
    height: 100vh;
    position: relative;
    display: flex;
    justify-content: center;
    align-items: center;
    color: #fff;
}

.hero-section-title{
    font-family: 'Roboto Slab', serif;
    font-weight: 300;
    font-size: 80px;
    text-align: center;
    text-transform: capitalize; 
}

.hero-section-sub-heading{
    text-align: center;
    text-transform: capitalize;
    margin: 20px 0;
    font-size: 20px;
}

.scroll-down-icon{
    position: absolute;
    bottom: 10%;
    left: 50%;
    transform: translateX(-50%);
    width: 20px;
    animation: down ease 1s infinite;
}

@keyframes down{
    from { bottom: 10% }
    to { bottom: 8% }
}
.background{
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    z-index: -1;
}

.background-image{
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    object-fit: cover;
    z-index: -2;
}

.background::before, .background::after{
    content: '';
    position: absolute;
    left: 0;
    width: 100%;
    height: 50%;
}

.background::before{
    top: 0;
    left: 0;
    background: var(--gradient-top);
}

.background::after{
    bottom: 0;
    background: var(--gradient-bottom);
}

.grid-slider{
    width: 100%;
    height: 100%;
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    grid-template-rows: repeat(2, 1fr);
}

.grid-item{
    width: 100%;
    height: 100%;
    background: #000;
    opacity: 1;
    transition: .5s;
}

.grid-item.hide{
    opacity: 0;
}
.explore-section{
    position: relative;
    width: 100%;
    padding: 80px 10vw;
    color: #fff;
}

.section-title{
    font-size: 30px;
    font-weight: 400;
    text-align: center;
    text-transform: capitalize;
}

.section-para{
    width: 50%;
    min-width: 300px;
    display: block;
    margin: 30px auto;
    text-align: center;
    line-height: 25px;
    opacity: 0.6;
}

.tours-container{
    position: relative;
    width: 100%;
    height: 600px;
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    grid-template-rows: repeat(2, 1fr);
    grid-gap: 20px;
    margin-top: 100px;
}

.tour-card{
    width: 100%;
    height: 100%;
    position: relative;
    border-radius: 20px;
    box-shadow: 0;
    overflow: hidden;
    padding: 10px;
    display: flex;
    align-items: end;
}

.tour-card:nth-child(2){
    grid-row: span 2;
}

.tour-card:last-child{
    grid-column: span 2;
}

.tour-img{
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    object-fit: cover;
    transition: .5s;
    z-index: -1;
}

.tour-card:hover .tour-img{
    opacity: 0.8;
    transform: scale(1.1);
}

.tour-name{
    font-weight: 300;
}

.tour-action{
    margin-left: 20px;
    font-size: 14px;
    position: relative;
}

.tour-action::before{
    content: '';
    position: absolute;
    left: -20px;
    top: 2px;
    background: url('img/pin.png');
    width: 15px;
    height: 15px;
    background-size: contain;
}
.services-section{
    color: #fff;
    padding: 80px 10vw;
}

.serives-grid{
    width: 100%;
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    grid-gap: 20px;
}

.service-card{
    margin-top: 100px;
    width: 100%;
    height: 250px;
    border-radius: 20px;
    border: 1px solid #2D2D2D;
    background: #161813;
    padding: 10px;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    gap: 20px;
    overflow: hidden;
    position: relative;
}

.card-icon{
    text-align: center;
    font-size: 60px;
    z-index: 1;
}

.service-text{
    text-align: center;
    padding: 0 20px;
    z-index: 1;
}

.circle{
    position: absolute;
    top: 0%;
    left: 0%;
    width: 100%;
    height: 100%;
    clip-path: circle(0% at 100% 100%);
    transition: .5s;
}

.service-card:nth-child(1) .circle{
    background: url(img/img5.png);
    background-size: cover;
}

.service-card:nth-child(2) .circle{
    background: url(img/img2.png);
    background-size: cover;
}

.service-card:nth-child(3) .circle{
    background: url(img/img6.png);
    background-size: cover;
}

.service-card:nth-child(4) .circle{
    background: url(img/img4.png);
    background-size: cover;
}

.service-card:hover .circle{
    clip-path: circle(141.4% at 100% 100%);
}

.travel-grid{
    width: 100%;
    columns: 3;
    column-gap: 20px;
    margin-top: 200px;
}

.travel-grid img{
    width: 100%;
    height: auto;
    object-fit: cover;
    margin-bottom: 20px;
    border-radius: 10px;
}

.bg-circle{
    z-index: -1;
    position: absolute;
    width: 500px;
    height: 500px;
    border-radius: 50%;
    background: var(--sphere-gradient-one);
    right: -250px;
}
.book-section{
    position: relative;
    display: flex;
    padding: 0 10vw;
    align-items: center;
    width: 100%;
    height: 100vh;
    gap: 30px;
}

.book-now-img{
    position: absolute;
    width: 50%;
    right: 0;
}

.book-content{
    width: 50%;
    color: #fff;
}

.book-now-title{
    font-size: 50px;
    font-weight: 300;
    width: 300px;
}

.book-now-text{
    width: 300px;
    opacity: 0.5;
    line-height: 25px;
    margin: 30px 0;
}

.book-now{
    position: relative;
    padding: 10px 20px;
    outline: none;
    border: none;
    background: #000;
    text-transform: capitalize;
    color: #fff;
    border-radius: 20px;
    border-top-left-radius: 0;
    border-bottom-left-radius: 0;
    font-size: 18px;
    cursor: pointer;
    overflow: hidden;
}

.book-now::before{
    content: '';
    position: absolute;
    top: -10px;
    left: -30px;
    width: 20px;
    height: 200%;
    background: #fff;
    opacity: 0.2;
    transform: rotate(5deg);
    transition: .5s;
}

.book-now:hover::before{
    left: 100%;
}

.bg-circle-2{
    z-index: -1;
    position: absolute;
    width: 250px;
    height: 250px;
    border-radius: 50%;
    background:  var(--sphere-gradient-two);
    left: -125px;
    bottom: -100px;
}

.footer{
    width: 100%;
    padding: 100px 10vw;
    background: #000;
    display: flex;
    justify-content: space-evenly;
    flex-wrap: wrap;
    align-items: center;
    position: relative;
}

.footer-logo{
    width: 100px;
    opacity: 0.3;
}

.footer-text{
    color: #fff;
    opacity: 0.5;
    font-size: 20px;
}

.footer-text p{
    margin: 20px 0;
}

.copyright-line{
    width: 100%;
    background: #000;
    color: #fff;
    text-transform: capitalize;
    text-align: center;
    position: absolute;
    bottom: 0;
    left: 0;
    padding: 10px 0;
}
@media screen and (max-width: 996px) {
    .link-item{
        margin: 0 10px;
    }
    .hero-section-title{
        font-size: 60px;
    }
    .tours-container{
        height: 900px;
        grid-template-columns: repeat(2, 1fr);
        grid-template-rows: repeat(4, 1fr);
    }
    .tour-card:last-child{
        grid-column: span 1;
    }
    .tour-card:nth-child(3){
        grid-row: span 2;
    }
    .serives-grid{
        grid-template-columns: repeat(2, 1fr);
    }
    .service-card:nth-child(3), .service-card:nth-child(4){
        margin-top: 0;
    }
    .travel-grid{
        columns: 2;
    }
    .book-now-img{
        width: 40%;
    }
    .footer-logo{
        width: 70px;
    }
    .footer-text{
        font-size: 16px;
    }
}

/* much smaller device */

@media screen and (max-width:798px){
    .navbar{
        height: auto;
    }

    .link-item{
        margin-top: 80px;
        text-align: center;
    }
    .link-item:nth-child(3){
        margin: -50px -30px 0 -30px;
    }
    .link-item a{
        padding: 10px;
        margin: auto;
        display: block;
    }

    .section-title{
        font-size: 50px;
    }
    .grid-slider{
        grid-template-rows: repeat(3, 1fr);
        grid-template-columns: repeat(2, 1fr);
    }
    .hero-section-sub-heading{
        font-size: 16px;
    }
    .section-para{
        width: 100%;
    }
    .tours-container{
        height: 1200px;
        grid-template-columns: repeat(1, 1fr);
        grid-template-rows: repeat(6, 1fr);
    }
    .tour-card:nth-child(2){
        grid-row: auto;
    }
    .tour-card:last-child{
        grid-column: span 1;
    }
    .tour-card:nth-child(3){
        grid-row: span 1;
    }
    .serives-grid{
        grid-template-columns: repeat(1, 1fr);
    }
    .service-card:nth-child(2){
        margin-top: 0;
    }
    .travel-grid{
        columns: 1;
    }
    .book-section{
        height: auto;
        padding: 80px 10vw;
    }
    .bg-circle{
        display: none;
    }
    .bg-circle-2{
        z-index: 2;
    }
    .book-now-img{
        width: 100%;
        opacity: 0.3 !important;
    }
    .book-content{
        width: 100%;
        z-index: 2;
        text-align: center;
    }
    .book-now-title, .book-now-text{
        width: 100%;
    }
}

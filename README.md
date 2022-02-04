# sunnyside
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        * {
            margin: 0;
            padding: 0;
        }

        .site-wrapper {

            background-image: url(image-header.jpg);
        }
    </style>

    <link rel="stylesheet" href="./style.scss">

    <link rel="preconnect" href="https://fonts.gstatic.com">
    <link
        href="https://fonts.googleapis.com/css2?family=Barlow:wght@600&family=Fraunces:ital,wght@0,900;1,700&family=PT+Sans+Narrow:wght@700&display=swap"
        rel="stylesheet">
    <link rel="icon" types="image/png" sizes="32*32" href="./images/favicon-32x32.png">


    <title>sunnyside agency | Frontend Mentor Challange</title>
</head>

<body>


    <div class="site-wrapper">




        <section class="hero-section" id="herosection" < nav class="main-navber">
            <div class="logo navber-logo">

                <svg width="124" height="24" xmins="http://www.w3.org/2000/svg"></svg>

            </div>
            <ul class="navbar hidden-navbar" id="mainNavber">
                <li>
                    <a href="" class="main-navbar-link"> About </a>
                </li>
                <li>
                    <a href="" class="main-navbar-link"> Services</a>
                </li>
                <li>
                    <a href="" class="main-navbar-link"> Projects </a>
                </li>
                <li>
                    <a href="" class="main-navbar-link  main-navbar-link-active"> Contact </a>
                </li>
            </ul>

            <div class="hero-cover">
                <div>
                    <h1 class="hero-cover-title">We are creatives</h1>
                    <div class="hero-cover-arrow">
                        <svg width="36" heights="114"> xmins="http://www.w3.org/2000/svg"></svg>

                    </div>
                </div>
            </div>



            </nav>
        </section>


        <section class="about-section" id="aboutSection">
            <div class="about-row">
                <div class="about-box about-box-text">
                    <div class="inner">
                        <h2>Transform your brand</h2>
                        <p>we are a full-service creative agency specializing in helping brands grow fast.
                            engage your clients through compelling visuals that do nmost of the marketing for you. </p>
                        <a href="#" class="yellow">Learn more</a>
                    </div>

                </div>
                <div class="about-box about-box-image">
                    <picture>
                        <source media="(min-width:650px)" srcset="./images/desktop/image-transform.jpg">
                        <source media="(min-width:4650px)" srcset="./images/mobile/image-tranform.jpg">
                        <img src="./images/desktop/image-transform.jpg" alt="image">

                    </picture>
                </div>
                <div class="about-box about-box-text">
                    <div class="inner">
                        <h2>Transform your brand</h2>
                        <p>we are a full-service creative agency specializing in helping brands grow fast.
                            engage your clients through compelling visuals that do nmost of the marketing for you. </p>
                        <a href="#" class="yellow">Learn more</a>
                    </div>
                </div>


            </div>



        </section>




        <section class="services-section" id="serviceSection">
            <div class="services">
                <div class="service">
                    <div class="service-image">
                        <picture>
                    </div>
                    <div class="service-info green">
                        <h3>Graphic design</h3>
                        <p>Great design makes you memorable.We deliver artwork that underscores your brand message and
                            capture</p>
                    </div>


                </div>


                <div classs="service">
                    <div class="service-image">
                        <picture>
                            <source media="(min-width:650px)" srcset="./images/desktop/image-photography.jpg">
                            <source media="(min-width:4650px)" srcset="./images/mobile/image-photography.jpg">
                            <img src="./images/desktop/image-.photography.jpg" alt="image">

                        </picture>
                    </div>
                    <div class="service-info blue">
                        <h3>photography</h3>
                        <p>Increase your credibility by getting the most stunning</p>
                    </div>

                </div>


        </section>




        <section class="testimonials-section" id="testimonialsSection">
            <div class="test-header">client testimonials</div>
            <div class="testimonials">
                <div class="testimonial">
                    <img src="./images/image-emily.jpg" alt="image">
                </div>
                <div class="testi-info">
                    <p>We put our trust in sunnyside and they delivered,making sure our needs were met and deadlines
                        were</p>
                    <div class="name">Emily R</div>
                    <div class="designation">Marketing Directir</div>
                </div>
            </div>




            <div class="testimonial">
                <img src="./images/image-thomas.jpg" alt="image">
            </div>
            <div class="testi-info">
                <p>Sunnyside's enthuasiasm coupled with their keen inter</p>
                <div class="name">Thomas S.</div>
                <div class="designation">cheif operating officer</div>
            </div>
    </div>



    <div class="testimonial">
        <img src="./images/image-jennie.jpg" alt="image">
    </div>
    <div class="testi-info">
        <p>Incredible end result our sales increased over 400,</p>
        <div class="name">Jennie F.</div>
        <div class="designation">Bussiness owner</div>
    </div>
    </div>
    </section>



    <section class="project-section" id="projectsSection">
        <div class="projects">
            <div class="project">
                <picture>
                    <source media="(min-width:650px)" srcset="./images/desktop/image-gallery-sugarcubes.jpg">
                    <source media="(min-width:4650px)" srcset="./images/mobile/image-gallery-sugarcubes.jpg">
                    <img src="./images/desktop/image-gallery-sugarcubes.jpg" alt="image">
                </picture>
                <div class="project-info">
                    <a href="" class="project-title">Sugarcubes</a>
                </div>
            </div>
            <div class="project">
                <picture>
                    <source media="(min-width:650px)" srcset="./images/desktop/image-gallery-orange.jpg">
                    <source media="(min-width:4650px)" srcset="./images/mobile/image-gallery-orange.jpg">
                    <img src="./images/desktop/image-gallery-orange.jpg" alt="image">
                </picture>
                <div class="project-info">
                    <a href="" class="project-title">Orange</a>
                </div>
            </div>

            <div class="project">
                <picture>
                    <source media="(min-width:650px)" srcset="./images/desktop/image-gallery-milkbottles.jpg">
                    <source media="(min-width:4650px)" srcset="./images/mobile/image-gallery-milkbottles.jpg">
                    <img src="./images/desktop/image-gallery-milkbottles.jpg" alt="image">
                </picture>
                <div class="project-info">
                    <a href="" class="project-title">Milkbottles</a>
                </div>
            </div>

            <div class="project">
                <picture>
                    <source media="(min-width:650px)" srcset="./images/desktop/image-gallery-cone.jpg">
                    <source media="(min-width:4650px)" srcset="./images/mobile/image-gallery-cone.jpg">
                    <img src="./images/desktop/image-gallery-cone.jpg" alt="image">
                </picture>
                <div class="project-info">
                    <a href="" class="project-title">Cone</a>
                </div>
            </div>

        </div>

    </section>


    <footer class="main-footer">

        <div class="footer-logo">
            <svg width="124" heights="24" xmins="http://www.w3.org/2000/svg"></svg>

        </div>

        <ul class="footer-navbar">
            <li>
                <a href="" class="footer-navbar-link"> About </a>
            </li>
            <li>
                <a href="" class="footer-navbar-link"> Services</a>
            </li>
            <li>
                <a href="" class="footer-navbar-link"> Projects </a>
            </li>

        </ul>



        <ul class="footer-social">
            </li><a href="#" class="footer-social-icon">
                <svg width="20" heights="20" xmins="http://www.w3.org/2000/svg">
                    <path
                        d="C:\Users\urmis\Downloads\sunnyside-agency-landing-page-main\__downloads__\images\icon-facebook.svg">
                    </path>
                </svg>
            </a>
            </li>
            <li>
                <a href="#" class="footer-social-icon">
                    <svg width="20" heights="20" xmins="http://www.w3.org/2000/svg">
                        <path
                            d="C:\Users\urmis\Downloads\sunnyside-agency-landing-page-main\__downloads__\images\icon-hamburger.svg">
                        </path>
                    </svg>

                </a>
            </li>
            <li>
                <a href="#" class="footer-social-icon">
                    <svg width="20" heights="20" xmins="http://www.w3.org/2000/svg">
                        <path
                            d="C:\Users\urmis\Downloads\sunnyside-agency-landing-page-main\__downloads__\images\icon-instagram.svg">
                        </path>
                    </svg>
                </a>
            </li>
            <li>
                <a href="#" class="footer-social-icon">
                    <svg width="20" heights="20" xmins="http://www.w3.org/2000/svg">
                        <path
                            d="C:\Users\urmis\Downloads\sunnyside-agency-landing-page-main\__downloads__\images\icon-pinterest.svg">
                        </path>
                    </svg>
                </a>
            </li>
        </ul>
    </footer>



















</body>

</html>

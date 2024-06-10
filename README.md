<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cool Responsive Portfolio Website Design</title>

    <!-- swiper css -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/swiper@9/swiper-bundle.min.css" />

    <!-- box icons -->
    <link href='https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css' rel='stylesheet'>

    <!-- custom css -->
    <link rel="stylesheet" href="css/style.css">
</head>

<body>

    <!-- header design -->
    <header class="header">
        <a href="#" class="logo">PORTFOLIO.</a>

        <nav class="navbar">
            <a href="#home" class="active">Home</a>
            <a href="#about">About</a>
            <a href="#services">Services</a>
            <a href="#portfolio">Portfolio</a>
            <a href="#contact">Contact</a>
        </nav>

        <div class="bx bx-moon" id="darkMode-icon"></div>

        <div class="bx bx-menu" id="menu-icon"></div>
    </header>

    <!-- home section design -->
    <section class="home" id="home">
        <div class="home-content">
            <h3>Hello, I am</h3>
            <h1>Kaleb Woldesadik</h1>
            <p>
                I'm a Computer Science Major i loves to create beautiful and functional tools
                for people who want to make a difference in the world.
            </p>
            <p>Currently I'm a student at Southern Illinois University Edwardsville, where I'm i gaining knowledge
                to be able to turn my idea into reality.</p>

            <div class="social-media">
                <a href="https://www.facebook.com/profile.php?id=100063815215891"><i class='bx bxl-facebook'></i></a>
                <a href="#"><i class='bx bxl-twitter'></i></a>
                <a href="https://www.instagram.com/kalebtabesso/"><i class='bx bxl-instagram-alt'></i></a>
                <a href="https://www.linkedin.com/in/kaleb-woldetsadik-957278232/"><i class='bx bxl-linkedin'></i></a>
            </div>

            <a href="" class="btn">Download CV</a>
        </div>

        <div class="profession-container">
            <div class="profession-box">
                <div class="profession" style="--i:0;">
                    <i class='bx bx-code-alt'></i>
                    <h3>Web Developer</h3>
                </div>
                <div class="profession" style="--i:1;">
                    <i class='bx bx-camera'></i>
                    <h3>Photographer</h3>
                </div>
                <div class="profession" style="--i:2;">
                    <i class='bx bx-palette'></i>
                    <h3>Web Designer</h3>
                </div>
                <div class="profession" style="--i:3;">
                    <i class='bx bx-video-recording'></i>
                    <h3>Web Design</h3>
                </div>

                <div class="circle"></div>
            </div>

            <div class="overlay"></div>
        </div>

        <div class="home-img">
            <img src="kaleb.png" alt="">
        </div>
    </section>

    <!-- about section design -->
    <section class="about" id="about">
        <div class="about-img">
            <img src="about.png" alt="">
        </div>

        <div class="about-content">
            <h2 class="heading">About <span>Me</span></h2>
            <h3>
                Hi there, welcome to my website! I'm Kaleb,
                a passionate web developer who enjoys learning new technologies
                and solving problems with code!
            </h3>
            <p>
                This website is my personal blog where I write about web development
                topics that interest me and inspire me.
            </p>
            <p>
                Thank you for visiting my website and getting to know me better. I hope you
                enjoyed reading my blog posts and
                found
                them useful and informative. If you want to read more of my posts, subscribe
                to my newsletter where I send
                weekly
                updates on web development trends and tips. If you have any feedback or
                suggestions, please let me know. I'd love to hear from you.
            </p>
            <a href="#" class="btn">Read More</a>
        </div>
    </section>

    <!-- services section design -->
    <section class="services" id="services">
        <header class="services-header">
            <h2 class="heading">My <span class="highlight">Services</span></h2>
        </header>
    
        <div class="services-container">
            <article class="services-box">
                <i class='bx bx-code-alt' role="img" aria-label="Web Development"></i>
                <h3>Web Development</h3>
                <p>Building modern, responsive, and engaging websites with a focus on user-friendly design and robust functionality. Every project is crafted to meet your business needs and delight your visitors.</p>
                <a href="#web-development-details" class="btn">Learn More</a>
            </article>
            <article class="services-box">
                <i class='bx bxs-paint' role="img" aria-label="Graphic Design"></i>
                <h3>Graphic Design</h3>
                <p>Creative designs that speak to your audience with clarity. From logos to full brand packages, we deliver visual storytelling that elevates your brand's aesthetic and identity.</p>
                <a href="#graphic-design-details" class="btn">Discover More</a>
            </article>
            <article class="services-box">
                <i class='bx bx-bar-chart-alt' role="img" aria-label="Digital Marketing"></i>
                <h3>Digital Marketing</h3>
                <p>Strategic marketing campaigns that drive results. Leverage the power of SEO, content marketing, and social media to grow your audience and increase conversions.</p>
                <a href="#digital-marketing-details" class="btn">Explore Services</a>
            </article>
        </div>
    </section>
    

    <!-- portfolio section design -->
    <section class="portfolio" id="portfolio">
        <h2 class="heading">Latest <span>Project</span></h2>

        <div class="portfolio-container">
            <div class="portfolio-box">
                <img src="images/portfolio1.jpg" alt="">

                <div class="portfolio-layer">
                    <h4>Web Design</h4>
                    <p></p>
                    <a href="#"><i class='bx bx-link-external'></i></a>
                </div>
            </div>
            <div class="portfolio-box">
                <img src="images/portfolio2.jpg" alt="">

                <div class="portfolio-layer">
                    <h4>Web Design</h4>
                    <p></p>
                    <a href="#"><i class='bx bx-link-external'></i></a>
                </div>
            </div>
            <div class="portfolio-box">
                <img src="images/portfolio3.jpg" alt="">

                <div class="portfolio-layer">
                    <h4>Web Design</h4>
                    <p></p>
                    <a href="#"><i class='bx bx-link-external'></i></a>
                </div>
            </div>
            <div class="portfolio-box">
                <img src="images/portfolio4.jpg" alt="">

                <div class="portfolio-layer">
                    <h4>Web Design</h4>
                    <p></p>
                    <a href="#"><i class='bx bx-link-external'></i></a>
                </div>
            </div>
            <div class="portfolio-box">
                <img src="images/portfolio5.jpg" alt="">

                <div class="portfolio-layer">
                    <h4>Web Design</h4>
                    <p></p>
                    <a href="#"><i class='bx bx-link-external'></i></a>
                </div>
            </div>
            <div class="portfolio-box">
                <img src="images/portfolio6.jpg" alt="">

                <div class="portfolio-layer">
                    <h4>Web Design</h4>
                    <p></p>
                    <a href="#"><i class='bx bx-link-external'></i></a>
                </div>
            </div>
        </div>
    </section>

    <!-- testimonial design -->
    <div class="testimonial-container">
        <h2 class="heading">Valuable <span>Testimonial</span></h2>

        <div class="testimonial-wrapper">
            <div class="testimonial-box mySwiper">
                <div class="testimonial-content swiper-wrapper">
                    <div class="testimonial-slide swiper-slide">
                        <img src="images/testimonial1.jpg" alt="">
                        <h3>Jackson Levi</h3>
                        <p></p>
                    </div>
                    <div class="testimonial-slide swiper-slide">
                        <img src="images/testimonial2.jpg" alt="">
                        <h3>Flora Ocean</h3>
                        <p></p>
                    </div>
                    <div class="testimonial-slide swiper-slide">
                        <img src="images/testimonial3.jpg" alt="">
                        <h3>Julian Grayson</h3>
                        <p></p>
                    </div>
                </div>

                <div class="swiper-button-next"></div>
                <div class="swiper-button-prev"></div>
                <div class="swiper-pagination"></div>
            </div>
        </div>
    </div>

    <!-- contact section design -->
    <section class="contact" id="contact">
        <h2 class="heading">Contact <span>Me!</span></h2>

        <form action="#">
            <div class="input-box">
                <input type="text" placeholder="Full Name">
                <input type="email" placeholder="Email Address">
            </div>
            <div class="input-box">
                <input type="number" placeholder="Mobile Number">
                <input type="text" placeholder="Email Subject">
            </div>
            <textarea name="" id="" cols="30" rows="10" placeholder="Your Message"></textarea>
            <input type="submit" value="Send Message" class="btn">
        </form>
    </section>

    <!-- footer design -->
    <footer class="footer">
        <div class="footer-text">
            <p>Copyright Kaleb Tagesse &copy; 2024 | All Rights Reserved.</p>
        </div>

        <div class="footer-iconTop">
            <a href="#home"><i class='bx bx-up-arrow-alt'></i></a>
        </div>
    </footer>


    <!-- scroll reveal -->
    <script src="https://unpkg.com/scrollreveal"></script>

    <!-- swiper js -->
    <script src="https://cdn.jsdelivr.net/npm/swiper@9/swiper-bundle.min.js"></script>

    <!-- custom js -->
    <script src="js/script.js"></script>
</body>

</html>

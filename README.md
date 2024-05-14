# jeevam10.github.io<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Model Portfolio</title>
    <style>
        /* CSS Styles */
        /* Reset CSS */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            background-color: black;
            color: white;
        }

        header {
            background-color: #333;
            color: #fff;
            padding: 20px;
        }

        header h1 {
            margin: 0;
        }

        nav ul {
            list-style: none;
        }

        nav ul li {
            display: inline;
            margin-right: 20px;
        }

        nav ul li a {
            color: #fff;
            text-decoration: none;
        }

        .container {
            max-width: 960px;
            margin: auto;
            padding: 20px;
        }

        section {
            padding: 20px 0; /* Reduced padding here */
        }

        section h2 {
            margin-bottom: 20px;
        }

        section p {
            margin-bottom: 30px;
        }

        #image-gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
            grid-gap: 20px;
        }

        #image-gallery img {
            max-width: 100%;
        }

        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 20px;
        }

        /* Slideshow CSS */
        .mySlides {
            display: none;
        }

        .fade {
            animation-name: fade;
            animation-duration: 1.5s;
        }

        @keyframes fade {
            from {opacity: .4} 
            to {opacity: 1}
        }

        .slideshow-container {
            position: relative;
            max-width: 100%;
        }

        .prev, .next {
            cursor: pointer;
            position: absolute;
            top: 50%;
            width: auto;
            padding: 16px;
            margin-top: -22px;
            color: white;
            font-weight: bold;
            font-size: 18px;
            transition: 0.6s ease;
            border-radius: 0 3px 3px 0;
            user-select: none;
            background-color: rgba(0, 0, 0, 0.5);
        }

        .prev:hover, .next:hover {
            background-color: rgba(0, 0, 0, 0.8);
        }

        .next {
            right: 0;
            border-radius: 3px 0 0 3px;
        }

        /* Additional styles */
        .about-me {
            background-color: #333;
            color: white;
            padding: 20px;
            margin-bottom: 30px;
        }

        .physical-characteristics {
            background-color: #333;
            color: white;
            padding: 20px;
            margin-bottom: 30px;
        }

        .contact {
            background-color: #333;
            color: white;
            padding: 20px;
        }
    </style>
</head>
<body>

    <header>
        <h1>Model Portfolio</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#gallery">Gallery</a></li>
                <li><a href="#about">About Me</a></li>
                <li><a href="#characteristics">Physical Characteristics</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="home">
        <div class="container">
            <h2>Welcome to My Portfolio</h2>
            <p>As a 19-year-old student pursuing engineering with a focus on artificial intelligence, I am captivated by the intersection of technology and creativity. Modeling, to me, represents a canvas where I can express myself artistically, embodying diverse characters and narratives. Beyond the allure of the runway, modeling allows me to challenge societal norms of beauty, celebrating diversity and individuality. Through each pose and expression, I aim to contribute to the vibrant tapestry of the fashion industry, where innovation meets artistry,Below are some pictures of me taken on an iphone and just represent a gist of the art i want to portray.</p>
        </div>
    </section>

    <section id="gallery">
        <div class="container"> <!-- Removed margin-top: 100px; -->
            <h2>Gallery</h2>
            <div id="image-gallery" class="slideshow-container">
                <div class="mySlides fade">
                    <img src="WhatsApp Image 2024-05-14 at 10.50.19 PM.jpeg" style="width:100%">
                </div>
                <div class="mySlides fade">
                    <img src="WhatsApp Image 2024-05-14 at 10.50.26 PM (1).jpeg" style="width:100%">
                </div>
                <div class="mySlides fade">
                    <img src="WhatsApp Image 2024-05-14 at 10.50.27 PM (1).jpeg" style="width:100%">
                </div>
                <div class="mySlides fade">
                    <img src="WhatsApp Image 2024-05-14 at 10.50.27 PM.jpeg" style="width:100%">
                </div>
                <div class="mySlides fade">
                    <img src="WhatsApp Image 2024-05-14 at 10.50.21 PM.jpeg" style="width:100%">
                </div>
                <div class="mySlides fade">
                    <img src="WhatsApp Image 2024-05-14 at 10.50.26 PM.jpeg" style="width:100%">
                </div>

                <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
                <a class="next" onclick="plusSlides(1)">&#10095;</a>
            </div>
        </div>
    </section>

    <section id="about" class="about-me">
        <div class="container">
            <h2>About Me</h2>
            <p>
                In addition to my academic pursuits in engineering, I lead a multifaceted life enriched with diverse passions. I find solace in the melodies of the piano, where each key strikes a chord of creativity and introspection. On the field, whether it's football or basketball, I thrive in the camaraderie of teamwork and the exhilaration of competition. A regular at the gym, I embrace the discipline of fitness, sculpting both body and mind. Photography, for me, is more than just a hobby—it's a lens through which I capture moments of beauty and significance, reflected in my dedicated online portfolio. Delving into the realms of philosophy, I explore the depths of thought and perspective, channeling my insights into various blog platforms. Through my diverse interests, I aspire to bring a unique blend of athleticism, creativity, and intellectual depth to the world of modelin</p>
        </div>
    </section>

    <section id="characteristics" class="physical-characteristics">
        <div class="container">
            <h2>Physical Characteristics</h2>
            <p>Age:19 </p>
               <p>Height:6'3 (feet and inches)</p> Height:6'3 (feet and inches)
               <p> Body weight:78kg</p>
                <p>Health complications or allergies: No</p>
               <p> DOB:21/10/04</p>
            
        </div>
    </section>

    <section id="contact" class="contact">
        <div class="container">
            <h2>For further inquiries</h2>
            <p>Email: jeevamchivate010@gmail.com</p>
            <p>Phone: 8484075966</p>
                <p>Instagram:https://www.instagram.com/_jeevam_/</p>
               <p> Linkedin:https://www.linkedin.com/in/jeevam-chivate-279bb5257/
            </p>
        </div>
    </section>

    <footer>
        <p>&copy; 2024 Model Portfolio. All rights reserved.</p>
    </footer>

    <script>
        // JavaScript for Slideshow
        var slideIndex = 1;
        showSlides(slideIndex);

        function plusSlides(n) {
            showSlides(slideIndex += n);
        }

        function showSlides(n) {
            var i;
            var slides = document.getElementsByClassName("mySlides");
            if (n > slides.length) {slideIndex = 1}
            if (n < 1) {slideIndex = slides.length}
            for (i = 0; i < slides.length; i++) {
                slides[i].style.display = "none";
            }
            slides[slideIndex-1].style.display = "block";
        }
    </script>

</body>
</html>

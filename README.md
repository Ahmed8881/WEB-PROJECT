<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="icon" href="icon.ico" type="image/x-icon">
    <script src="https://kit.fontawesome.com/2882665ba0.js" crossorigin="anonymous"></script>
    <title>Cloud Gaming - Play Games 🎮😊</title>
    <style>
        .submain2 {
            max-width: 50%;
        }

        .submain2 img {
            max-width: 100%;
        }

        .google {
            width: 100px;
        }

        .google img {
            max-width: 100%;
            max-height: 100%;
        }

        * {
            padding: 0;
            margin: 0;
        }

        body {
            font-family: Arial, sans-serif;
        }

        header {
            top: 0;
            z-index: 1000;
            position: sticky;
            backdrop-filter: blur(100px);
            display: flex;
            align-items: center;
            justify-content: space-between;
            height: 80px;
            color: white;
            padding: 0 20px;
        }

        .heading {
            width: 100%;
            display: flex;
            align-items: center;
            justify-content: space-between;
            font-size: xx-large;
            font-style: italic;
            color: #3ac4f2;
            font-weight: bolder;
            text-shadow: 1px 1px 5px #e22b90;
        }

        .navbar ul {
            display: flex;
            list-style-type: none;
        }

        .navbar li {
            padding: 0 20px;
            font-size: 1.4em;
        }

        .navbar li a {
            color: white;
            text-decoration: none;
        }

        .navbar li a:hover {
            color: #3ac4f2;
            cursor: pointer;
        }
        .background {
            z-index: 0;
            top: 0;
            height: 1050px;
            /* width: 100%; */
            right: 0;
            bottom: 0;
            left: 0;
            background-image: url(peakpx\ \(1\).jpg);
            background-size: cover;
            filter: blur(8px);
            position: absolute;
            background-position: left;
            filter: brightness(50%);
        }

        .content {
            width: 100%;
            height: 900px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            position: absolute;
            margin: auto;
            text-align: center;
        }

        .submain {
            margin-left: 10px;
            width: 60%;
            display: flex;
            flex-direction: column;
            justify-content: center;
        }

        .head {
            font-size: 3.5em;
            font-weight: bold;
            font-style: italic;
            margin-bottom: 40px;
        }

        .head_text {
            color: #3ac4f2;
            text-shadow: 1px 1px 5px #e22b90;
        }

        .para {
            text-align: left;
            font-size: 1.5em;
            padding: 0 30px;
            line-height: 1.5;
            margin-bottom: 50px;
        }


        .pic {
            transform: rotateZ(-10deg);
            padding: 0 10px;
            text-align: center;

        }

        .button {
            width: fit-content;
            padding: 15px 30px;
            font-size: x-large;
            border-radius: 10px;
            color: white;
            background: linear-gradient(to bottom right, #1b0932, #3ac4f2, #7a55c2);
            border: none;
            display: flex;
            justify-content: center;

        }

        .button:hover {
            background: linear-gradient(to bottom right, #7a55c2, #3ac4f2, #1b0932);
            cursor: pointer;

        }

        .buttons {
            display: flex;
            justify-content: center;
        }

        .submain2 {
            display: flex;
            justify-content: right;
            filter: brightness(95%);
            flex-direction: column;
        }

        .image_text {
            justify-content: center;
            font-size: xx-large;
            font-weight: bolder;
            font-style: italic;
            font-family: 'Raleway', sans-serif;
            display: flex;
            color: #22d6ff;
            text-shadow: 1px 1px 5px #e22b90;
        }

        footer {
            display: flex;
            background: #0f0222;
            color: white;
            text-align: center;
            padding-top: 30px;
            flex-direction: column;
        }

        .upper {
            display: flex;
            height: fit-content;
        }

        .baseline {
            justify-content: center;
            font-size: small;
            background: #080014;
            display: flex;
            padding: 10px;
            margin-top: 10px;
            align-items: center;
        }

        .about {
            width: 30%;
            text-align: left;
            line-height: 1.3;
            justify-content: center;
            display: flex;
            flex-direction: column;
            margin-left: 5vw;
        }

        .title {
            font-size: larger;
            margin-bottom: 10px;
        }

        .logo_align {
            display: flex;
            align-items: baseline;
            width: full;
            justify-content: center;

        }

        .header {
            display: flex;
            flex-direction: row;
            justify-content: flex-start;
        }

        footer li {
            text-decoration: none;
            line-height: 2;
            list-style: none;
            font-size: large;
        }

        footer li:hover {
            color: #3ac4f2;
            cursor: pointer;
        }

        .icons {
            width: full;
            text-align: left;
            justify-content: center;
            text-align: left;
            display: flex;
            flex-direction: column;
            display: flex;
            align-items: center;

            .title {
                margin-bottom: 0;
            }
        }

        .icons ul {
            display: flex;
        }

        .icons ul li {
            display: flex;
            margin-left: 1vw;
            font-size: x-large;
        }

        .youtube i {
            border-radius: 8px;
            justify-content: center;
            color: #A0AEC0;
            margin-left: 3px;
            cursor: pointer;
        }

        .youtube i:hover {
            color: #FF0000;
        }

        .linkedin i {
            color: #A0AEC0;
            cursor: pointer;
        }

        .linkedin i:hover {
            color: #32CD32;
        }

        .github i {
            color: #A0AEC0;
            border-radius: 50%;
            width: 100%;
            cursor: pointer;
        }

        .github i:hover {
            color: #000000;
        }

        .facebook i {
            color: #A0AEC0;
            cursor: pointer;
        }

        .facebook i:hover {
            color: #0000FF;
        }

        .google {
            cursor: pointer;
            margin-bottom: 5px;
        }

        .google:hover {
            filter: brightness(80%);
        }

        .features {
            display: flex;
            width: 100%;
            background: #080014;
            height: 800px;
            margin-top: 950px;
            flex-direction: column;
        }

        .feature {
            width: 100%;
            padding-top: 50px;
            display: flex;
        }

        .grid {
            display: flex;
            flex-direction: row;
            color: white;
            margin-top: 100px;
            text-align: center;
            padding: 0 5vw;
            ;

            .feature1 {
                display: flex;
                padding-top: 30px;
                width: 30%;
                height: 100px;
                flex-direction: column;
                justify-content: space-between;
                line-height: 1.5;
                font-size: large;
            }

            .feature2 {
                display: flex;
                width: 30%;
                height: 100px;
                flex-direction: column;
                justify-content: space-between;
                line-height: 1.5;
                font-size: large;
                margin-left: 5vw;
            }

            .feature3 {
                display: flex;
                width: 30%;
                height: 100px;
                flex-direction: column;
                justify-content: space-between;
                line-height: 1.5;
                font-size: large;
                margin-left: 5vw;
            }

            .gridimage {
                margin-bottom: 40px;
            }
        }

        .choose {
            background-image: url(peakpx\ \(1\).jpg);
            background-attachment: fixed;
            background-position: right;
            backdrop-filter: blur(10px);
            padding: 1vh 5vw;
            height: 700px;
        }

        .whychoose {
            margin-bottom: 50px;
            margin-top: 20px;
        }

        .gridtable {
            justify-content: center;
            width: 100%;
            padding-top: 50px;
            display: flex;
            flex-direction: row;

            .text {

                display: flex;
                color: white;
                width: 40%;
                line-height: 1.5;
                font-size: large;
            }

            .imaging {

                display: flex;
                width: 50%;
                width: 500px;
                height: 320px;
                margin-right: 50px;
            }
        }

        .gridtable2 .imaging {
            width: 500px;
            height: 320px;
            overflow: hidden;
        }

        .gridtable2 .imaging img {
            width: 100%;
            height: 100%;
        }

        .choose::before {
            content: "";
            position: absolute;
            top: 0;
            right: 0;
            bottom: 0;
            left: 0;
            background: url(peakpx\ \(1\).jpg);
            background-size: cover;
            filter: brightness(10%);
            opacity: 0.7;
            z-index: -1;
        }

        .upload {
            height: 80opx;
            padding-top: 30px;
            width: 100%;
            color: white;
            justify-content: center;
            background: #080014;

            .gridtable2 {
                display: flex;
                padding: 50px 5vw;

            }

            .text {
                display: flex;
                width: 45%;
                padding: 0 3vw;
                font-size: larger;
                line-height: 1.5;
            }

            .imaging {
                box-shadow: 0px 0px 10px 10px #3ac4f2;
            }
        }

        @media only screen and (min-width: 250px) and (max-width: 768px) {
            .ic{
                display: none;
            }
            .empty{
                display: none;
            }
            .heading{
                width: 25%;
            }
            .google {
                width: 100px;
            }

            .background {
                height: 1050px;
            }

            .navbar {
                display: none;
            }

            .submain2 img {
                display: none;
            }

            .heading {
                font-size: medium;
            }

            .content {
                flex-direction: column;
                font-size: x-small;
                width: 100%;
                justify-content: center;

                .para {
                    width: 100%;
                    text-align: left;
                }

                .button {
                    padding: 10px 10px;
                    font-size: medium;
                }
            }

            .image_text {
                margin-top: 30px;
                font-size: x-large;
            }

            .features {
                height: fit-content;
            }

            .grid {
                height: 100%;
                flex-direction: column;

                .feature1 {
                    width: 100%;
                    height: 300px;
                    margin-bottom: 100px;
                }

                .feature2 {
                    height: 300px;
                    width: 100%;
                    margin-left: 0;
                    margin-bottom: 100px;
                }

                .feature3 {
                    height: fit-content;
                    margin-left: 0;
                    height: 300px;
                    width: 100%;
                    margin-bottom: 150px;
                }
            }

            .choose {
                text-align: center;
                height: fit-content;
                padding-left: 0;
                padding-right: 0;
                justify-content: center;
                width: 100%;

                .gridtable {
                    flex-direction: column;
                }

                .imaging {
                    width: 100%;
                    height: 200px;
                    overflow: hidden;
                    justify-content: center;
                }

                .text {
                    text-align: justify;
                    font-size: medium;
                    justify-content: center;
                    width: 100%;
                }

                .innerone {
                    margin: 20px 0;
                    ;
                    width: 75%;
                }
            }

            .upload {
                display: flex;
                overflow: hidden;
                width: 100%;
                justify-content: center;
                height: fit-content;
                flex-direction: column;

                .whychoose {
                    font-size: x-large;
                    text-align: center;
                    padding: 10px 0;
                }

                .image_text {
                    font-size: x-large;
                }

                .gridtable2 {
                    flex-direction: column-reverse;
                    width: 100%;
                    text-align: center;

                    .text {
                        font-size: medium;
                        width: 90%;
                        margin: 30px 0;
                    }

                    .imaging {
                        display: flex;
                        width: auto;
                        height: 200px;


                    }

                    .imaged {
                        display: flex;
                        width: 90%;
                        justify-content: center;
                    }
                }
            }

            footer {
                height: fit-content;
                overflow: hidden;

                .upper {
                    width: 90%;
                    flex-direction: column;

                    .about {
                        width: 100%;
                        margin-bottom: 30px;
                        height: 100%;
                    }

                    .n {
                        display: none;
                    }
                }

                .icons {
                    .title {
                        width: 90%;
                        text-align: left;
                    }

                }
            }
        }
        .side {
    transform:translateX(100%);
    backdrop-filter: blur(100px);
    height: 100vh;
    width: 100%;
    overflow: hidden;
    top: 0;
    left: 0;
    z-index: 10;
    position: absolute;
    display:none;
    flex-direction: row;
}

.sidebar { 
    display: flex;
    width: 60%;
    right: 0;
    display: flex;
}

.sideul {
    background-color:#0f0222;
    display: flex;
    flex-direction: column;
    width: 100%;
    height: 100%;
    align-items: start;
}

.sideli {
    padding: 30px 0;
    width: 100%;
    font-size: 1.5em;
    border: 1px solid #fff;
    list-style: none;
    text-align: center;
}

.cross {
    color: #22d6ff;
            text-shadow: 1px 1px 5px #e22b90;
    padding: 30px 0px;
    width: 100%;
    font-size: 2.5em;
    border: 1px solid #fff;
    background: transparent;
    list-style: none;
    display:flex;
    margin-right: 10px;
    justify-content: end;
}

.a {
    color: #22d6ff;
            text-shadow: 1px 1px 5px #e22b90;
    text-decoration: none;
}
.ic{
    color: #22d6ff;
            text-shadow: 1px 1px 5px #e22b90;
    display: flex;
    font-size: xx-large;
    width: 75%;
    text-align: end;
    justify-content: end;
}
.empty {
    display: flex;
    width: 40%;
    overflow: hidden;
    height: 100%; 
    background: rgba(255, 253, 253, 0.5); 
    filter: blur(20px);
    filter: brightness(40%);
}
        @media screen and (min-width: 769px) and (max-width:1240px) {
            .heading{
                width: 25%;
            }
            .google {
                width: 150px;
            }

            .navbar {
                display: none;
            }

            .content {
                flex-direction: column;

                .submain2 {
                    .image_text {
                        margin-top: 50px;
                    }
                }

                .submain2 img {
                    display: none;

                }
            }

            .features {

                .feature1,
                .feature2,
                .feature3 {
                    font-size: larger;
                }

                .image_text {
                    font-size: xxx-large;
                }
            }

            .choose {
                .image_text {
                    font-size: xxx-large;
                }

                text-align: center;
                height: fit-content;
                padding-left: 0;
                padding-right: 0;
                justify-content: center;
                width: 100%;

                .gridtable {
                    flex-direction: column;
                }

                .imaging {
                    width: 100%;
                    height: 300px;
                    overflow: hidden;
                    justify-content: center;
                }

                .text {
                    text-align: justify;
                    font-size: x-large;
                    justify-content: center;
                    width: 100%;
                }

                .innerone {
                    margin: 20px 0;
                    ;
                    width: 75%;
                }
            }

            .upload {
                display: flex;
                overflow: hidden;
                width: 100%;
                justify-content: center;
                height: fit-content;
                flex-direction: column;

                .whychoose {
                    font-size: x-large;
                    text-align: center;
                    padding: 10px 0;
                }

                .image_text {
                    font-size: xxx-large;
                }

                .gridtable2 {
                    flex-direction: column-reverse;
                    width: 100%;
                    text-align: center;

                    .text {
                        font-size: x-large;
                        width: 90%;
                        margin: 30px 0;
                    }

                    .imaging {
                        display: flex;
                        width: auto;
                        height: 200px;
                        height: 300px;

                    }

                    .imaged {
                        display: flex;
                        width: 90%;
                        justify-content: center;
                    }
                }
            }

            footer {
                height: fit-content;
                overflow: hidden;
                font-size: larger;

                .upper {
                    width: 90%;
                    flex-direction: column;

                    .about {
                        width: 100%;
                        margin-bottom: 30px;
                        height: 100%;
                    }

                    .n {
                        display: none;
                    }
                }

                .icons {
                    .title {
                        width: 90%;
                        text-align: left;
                    }
                }
            }

            .baseline {
                font-size: medium;
            }
        }

        @media screen and (min-width:1600px) {
            .ic{
                display: none;
            }
            .empty{
                display: none;
            }
            .heading{
                width: 25%;
            }
            .sidebar {
                display: none;
            }
            .google {
                width: 150px;
            }

            .content {
                .head {
                    font-size: 5em;
                }

                .para {
                    font-size: 1.9em;
                }
            }

            header {
                height: 120px;
                font-size: x-large;
            }

            .heading {
                font-size: xxx-large;
            }

            .background {
                height: 1100px;
            }

            .image_text {
                font-size: 4em;
            }

            .features {

                .feature1,
                .feature2,
                .feature3 {

                    font-size: 1.7em;
                }
            }

            .choose {
                height: fit-content;

                .text {
                    font-size: 1.7em;
                }

                .imaging {
                    width: fit-content;
                    height: 500px;
                }
            }

            .upload {
                height: fit-content;

                .text {
                    font-size: 1.7em;
                }

                .imaging {
                    width: fit-content;
                    height: 500px;
                }
            }

            footer {
                .n ul li {
                    font-size: 1.1em;
                }

                font-size: 1.5em;
            }

            .baseline {
                font-size: large;
            }
        }

        @media screen and (min-width:2400px) {
            .ic{
                display: none;
            }
            .empty{
                display: none;
            }
            .heading{
                width: 25%;
            }
            .sidebar {
                display: none;
            }
            .google {
                width: 200px;
            }

            .content {
                .head {
                    font-size: 7em;
                }

                .para {
                    font-size: 3em;
                }

                .button {
                    font-size: xxx-large;
                }
            }

            header {
                height: 120px;
                font-size: xx-large;
            }

            .heading {
                font-size: 2em;
            }

            .background {
                height: 1050px;
            }

            .image_text {
                font-size: 6em;
            }

            .features {

                .feature1,
                .feature2,
                .feature3 {

                    font-size: 2.5em;
                }
            }

            .choose {
                height: fit-content;

                .text {
                    font-size: 2.5em;
                }

                .imaging {
                    width: fit-content;
                    height: 800px;
                }
            }

            .upload {
                height: fit-content;

                .text {
                    font-size: 2.5em;
                }

                .imaging {
                    width: fit-content;
                    height: 800px;
                }
            }

            footer {
                .n ul li {
                    font-size: 1.2em;
                }

                font-size: 2em;
            }

            .logo_align {
                display: none;
            }

            .baseline {
                font-size: xx-large;
            }
        }
        @media screen and (min-width:1240px) and (max-width:1600px) {
            .empty{
                display: none;
            }
            .heading{
                width: 25%;
            }
            .sidebar {
                display: none;
            }
            .ic{
                display: none;
            }
        }
    </style>
</head>

<body>
    <header>
        <div class="heading">
            <div class="pic"><img height="40px" src="game.png" alt=""></div> Cloud Gaming
        </div>
        <div class="ic"><i id="bar" class="fa-solid fa-bars icon"></i></div>
        <div id="slidebar" class="side">
            <div id="empty" class="empty"></div>
            <nav class="sidebar">
                <ul class="sideul">
                    <li class="cross"><i
                        id="cross" class="fa-solid fa-xmark cursor-pointer" style="color: #ffffff;"></i></li>
                    <li  class="sideli"><a class="a" href="index.html"> Home</a></li>
                <li class="sideli"><a class="a"  href="game.html">Games</a></li>
                <li class="sideli"><a class="a"  href="contact.html"> Contact Us</a></li>
                <li class="sideli"><a class="a"  href="aboutus.html"> About Us</a></li>
                <li class="sideli"><a class="a" href="login.html"> Signup/Login</a></li>
            </ul>
        </nav>
            </div>
        <nav class="navbar">
            <ul>
                <li><a href="index.html"> Home</a></li>
            <li><a href="game.html">Games</a></li>
                <li><a href="contact.html"> Contact Us</a></li>
                <li><a href="aboutus.html"> About Us</a></li>
                <li><a href="login.html"> Signup/Login</a></li>
            </ul>
        </nav>
    </header>
    <div class="background"></div>
    <div class="content">
        <div class="submain">
            <div class="head">
                Welcome to <span class="head_text">Cloud Gaming</span>
            </div>
            <div class="para">
                <p>Level Up Gaming Conquer dynamic landscapes, engage in strategic battles, and join a thriving
                    community for an immersive gaming adventure.</p>
            </div>
            <div class="buttons">
                <button class="button">
                    Get Started
                </button>
            </div>
        </div>
        <div class="submain2">
            <img class="image" src="right image.png" alt="">
            <div class="image_text">
                Level Up Your Gaming Experience
            </div>
        </div>
    </div>
    <div class="features">
        <div class="image_text feature">
            Cloud Gaming Features
        </div>
        <div class="grid">
            <div class="feature1">
                <div>
                    <img class="gridimage" width="100px" src="play.png" alt="">
                </div>
                Unlock endless gaming possibilities anywhere, anytime! Enjoy non-stop access to a vast library of
                thrilling games with our user-friendly platform. Elevate your gaming experience with limitless
                entertainment and explore a world of excitement on demand
            </div>
            <div class="feature2">
                <div><img width="180px" src="3507978.png" alt=""></div>
                Discover daily uploads of brand-new games! Your next favorite awaits. Stay at the forefront of gaming
                with our constantly expanding library. Find, play, and love the latest releases every day
            </div>
            <div class="feature3">
                <div>
                    <img class="gridimage" width="150px" src="responsive-devices.png" alt="">
                </div>
                Experience gaming freedom on any device—PCs, mobile phones, and tablets. Play your favorite games
                seamlessly across platforms. Dive into an immersive world of entertainment. Unleash the excitement
                across all your devices with ease.
            </div>
        </div>
    </div>
    <div class="choose">
        <div class="bg"></div>
        <div class="image_text whychoose">
            Why Choose Cloud Gaming
        </div>
        <div class="gridtable">

            <div class="imaging"><img src="https://www.playfusion.org/images/slider/slider2.jpg" alt="">
            </div>

            <div class="text">
                <p class="innerone">

                    Indulge in an extensive collection of over 100 top-notch games, immersing yourself in the ultimate
                    gaming experience. Join the largest community of gamers on an advanced multiplayer network, playing
                    with
                    friends. Showcase your skills on the battlefield, embark on exciting co-op adventures, and unleash
                    your
                    creativity by crafting imaginative worlds.
                    <br> With a broad spectrum of games spanning every genre and
                    continuous additions to our collection, there's always something fresh and thrilling to experience.
                    Discover a constant influx of new games available daily on Play Fusion Studio, complemented by a
                    carefully curated selection of indie gems and blockbuster titles. This ensures a diverse and
                    ever-evolving gaming library, promising an exciting journey for every gamer.
                </p>
            </div>
        </div>
    </div>
    <div class="upload">
        <div class="image_text whychoose">
            Upload Games on Cloud Gaming
        </div>
        <div class="gridtable2">


            <div class="text">
                <p>

                    Indulge in an extensive collection of over 100 top-notch games, immersing yourself in the ultimate
                    gaming experience. Join the largest community of gamers on an advanced multiplayer network, playing
                    with
                    friends. Showcase your skills on the battlefield, embark on exciting co-op adventures, and unleash
                    your
                    creativity by crafting imaginative worlds.
                    <br> With a broad spectrum of games spanning every genre and
                    continuous additions to our collection, there's always something fresh and thrilling to experience.
                    Discover a constant influx of new games available daily on Cloud Gaming, complemented by a
                    carefully curated selection of indie gems and blockbuster titles. This ensures a diverse and
                    ever-evolving gaming library, promising an exciting journey for every gamer.
                </p>
            </div>
            <div class="imaged">

                <div class="imaging"><img src="images.jpeg" alt="">
                </div>
            </div>
        </div>
    </div>
    <footer>
        <div class="upper">
            <div class="about">
                <div class="header">
                    <div class="title">
                        Cloud Gaming
                    </div>
                    <div class="pic logo_align"><img height="20px" src="game.png" alt=""></div>
                </div>
                <p>Cloud Gaming is an online gaming platform that gives you access to thousands of online games, ranging
                    from single to complex, to Test, Buy, Play and have fun with friends and family</p>
            </div>
            <div class="about n nav">
                <nav>
                    <ul>
                        <li>Home</li>
                        <li>Games</li>
                        <li>Terms & Conditions</li>
                        <li>Contact Us</li>
                    </ul>
                </nav>
            </div>
            <div class="icons nav">
                <div class="title">Social Media</div>
                <div class="icons">
                    <ul>
                        <li>
                            <div class="youtube">
                                <i class="fa fa-youtube-play" aria-hidden="true"></i>
                            </div>
                        </li>
                        <li>
                            <div class="linkedin">
                                <i class="fa fa-linkedin-square" aria-hidden="true"></i>
                            </div>
                        </li>
                        <li>
                            <div class="github">
                                <i class="fa fa-github" aria-hidden="true"></i>
                            </div>
                        </li>
                        <li>
                            <div class="facebook">
                                <i class="fa fa-facebook-square" aria-hidden="true"></i>
                            </div>
                        </li>
                    </ul>
                </div>
                <div class="images">
                    <div class="google"><img src="google.png" alt=""></div>
                    <div class="google"><img src="apple.png" alt=""></div>
                </div>
            </div>

        </div>
        <div class="baseline">Copyright © 2023 Cloud Gaming - All Rights Reserved</div>
    </footer>
    <script>
        var button = document.getElementById('bar');
        var sidebar = document.getElementById('slidebar');
        var crosssymbol = document.getElementById('cross');
        var empty = document.getElementById('empty');
    
        button.addEventListener('click', function () {
            sidebar.style.display = 'flex';
            // Add transition properties
            sidebar.style.transition = 'transform 0.4s ease-in-out';
            sidebar.style.transform = 'translateX(0%)';

        });
    
        crosssymbol.addEventListener('click', function () {
            // Add transition properties
            sidebar.style.transition = 'transform 0.4s ease-in-out';
            sidebar.style.transform = 'translateX(100%)';
    
            setTimeout(function () {
                sidebar.style.transition = 'none';
                sidebar.style.display = 'none';
            }, 400);
        });
    
        empty.addEventListener('click', function () {
            sidebar.style.transition = 'transform 0.4s ease-in-out';
            sidebar.style.transform = 'translateX(100%)';
    
            setTimeout(function () {
                sidebar.style.transition = 'none';
                sidebar.style.display = 'none';
            }, 400);
        });
    </script>
    
</body>

</html>

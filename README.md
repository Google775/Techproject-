<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bharath Website</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css" integrity="sha512-z3gLpd7yknf1YoNbCzqRKc4qyor8gaKU1qmn+CShxbuBusANI9QpRohGBreCFkKxLhei6S9CQXFEbbKuqLg0DA==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <link rel="stylesheet" href="stylesheet.css"> 
</head>
<body>
    <style>
                transform: scale(1.2);
        transition:1s;
    }
   
    .skills{
        background-color: black;
        color: antiquewhite;
    padding-top: 10px;
        
    }

    .title h2{
        padding-top: 3 0px;
    }
    .box{
        display: flex;  
        align-items: center;
        justify-content: center;
    }

    .card{
         height: 300px;
         width: 270px;
         color: white;
         background: gray;
         border-radius: 10px;
         margin: 12px;
    }
    .para .button{
        background-color: black;
        color: antiquewhite;
        border-radius: 30px;
        padding: 10px 20px;
        text-decoration: none;
    
        

    }
    .card h4{
        text-align: center;
        font-size: 20px;
        letter-spacing: 1px;
        margin-top: 10px;
        word-spacing: 3px;

    }
    .para .button:hover{
       background-color: transparent;
       border: 2px solid black;
       cursor: pointer;
       transition: 0.2s;
    }
    .card i{
        color: rgb(1, 1, 1);
        font-size: 40px;
        text-align: center;
        margin: 15px 0px;
        display: block;
    }
    .foot{
        background: rgb(0, 0, 0);
        height: 30%;
        width: 100%;
        color: white;
        text-align: center;
        padding-top: 20px;
        
    }
    
    .foot .btn1:hover{
        background-color: transparent;
       border: 2px solid rgb(85, 0, 254);
       cursor: pointer;
       transition: 0.2s;
    }
    .foot .btn1{
        background-color: rgb(101, 7, 253);
        color: antiquewhite;
        border-radius: 30px;
        padding: 10px 20px ;
        text-decoration: none;
        font-weight: bold;
    }
    .details{
        width: 100%;
        display: inline-block;
        background-color: rgb(0, 0, 0);
        justify-content: center;
    }
    .details .author{
        font-size: 25px;
        color: white;
        font-weight: bold;
    margin-left: 39%;
    
        }.details .reach{
            font-size: 15px;
            font-weight: bold;
            color: white;
        }

    .details .reach{
        color: white;
        font-size: 15px;
        margin-left: 44%;
    }
    .details .social-media a{

        width: 30px;
        height: 30px;
        display: inline-flex;
        text-decoration: none;
        background-color: rgb(85, 0, 255);
        border-radius: 50%;
        color: white;
        align-items: center;
        justify-content: center;
        margin: 10px 10px;
        font-size: 20px;
    }
    .details .social-media .insta{
     background-color: rgb(244, 9, 126);
    }
    .details .social-media .whats{
        background-color: rgb(0, 163, 8);
       }
       .details .social-media .mail{
        background-color: red;
       }
    .details .social-media{
        padding-left: 39%;
    }
    .details .social-media .linkdn:hover{
        background-color: transparent;
        border: 1px solid rgb(89, 0, 255);
    cursor: pointer;
    transform: scale(1.3);
    transition: 0.5s;
    }
    .details .social-media .insta:hover {
        background-color: transparent;
        border: 1px solid rgb(255, 0, 0);
    cursor: pointer;
    transform: scale(1.3);
    transition: 0.5s;
    }
    .details .social-media .whats:hover {
        background-color: transparent;
        border: 1px solid rgb(0, 161, 13);
    cursor: pointer;
    transform: scale(1.3);
    transition: 0.5s;
    }
    .details .social-media .mail:hover {
        background-color: transparent;
        border: 1px solid rgb(255, 0, 0);
    cursor: pointer;
    transform: scale(1.3);
    transition: 0.5s;
    }
    .social-media .copy{
        font-size: 10px;
        color: white;
        font-weight: bold;
    margin-left:10%;   
    }
    
    </style>
        <div class="hero">
            <h2 class="name">Bharath <span>Annamalai</span></h2>
            <nav style="float: right;">
    <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#about">About me</a></li>
        <li><a href="#skills">Skills</a></li>
        <li><a href="#details">Contact</a></li>
    </ul>
    <a href="#" class="btn">Subscribe</a>
</nav>
<div class="content">
    <h3>Hello My Name is</h3>
    <h1>Bharath <span>Annamalai</span></h1>
    <h4>I'm a Full Stack Developer</h4>
    <div class="subscribe">
        <form>
            <input type="text" name="name" placeholder="Enter your name">
            <input type="button" value="Let's Start"> 
        </form>
    </div>
</div>
</div>
<section class="aboutme" id="about">
    <div class="main">
        <img src="img3.jpg" alt="not in image">
        <div class="about_content">
        <h2 style="color: red;">About me</h2>
        <h1>Full Stack Developer</h1>
        <p>I'm a Full Stack Developer in Java.I finish my course in Gtech computer technology with experience staff.</p>
    <a href="#" class="btn_">Let's Talk</a> 
    </div>
    </div>
</section>
<div class="skills" id="skills">
    <div class="title">
        <h2 style="text-align: center;">Skills</h2>
        <div class="box">
            <div class="card">
                <i class="fa-brands fa-java"></i>
                <h4 style="text-align: center;">Java development</h4>
                <div class="para">
                    <p style="text-align: center;">Create ATM Transaction using JAVA
                    <br><br><br><a class="button" href="#">Read more</a></p>
                
                </div>
            </div>
            <div class="card">
                <i class="fa-brands fa-html5"></i>
                <h4 style="text-align: center;">Frontend development</h4>
                <div class="para">
                    <p style="text-align: center;">Create Responsive websit using HTML,CSS
                        <br><br><a class="button" href="#">Read more</a></p>
                
                </div>
            </div>
            <div class="card">
                <i class="fa-solid fa-database"></i>
                <h4 style="text-align: center;">backend  development</h4>
                <div class="para">
                    <p style="text-align: center;">Create Responsive Database using SQL
                        <br><br><br><a class="button" href="#">Read more</a></p>
                
                </div>
            </div>
        </div>
    </div>
</div>
<div class="foot">
    <h2>Do you want to see about my CV<i class="fa-solid fa-down-left fa-bounce"></i></h2>
    <a class="btn1" href="#">Download CV</a>
</div>

<div class="details" id="details">
    <h2 class="author">Bharath Annamalai</h2>
    <p class="reach">Reach me out</p>
    <div class="social-media">
        <a class="linkdn" href="#"><i class="fa-brands fa-linkedin"></i></a>
        <a class="insta" href="#"><i class="fa-brands fa-instagram"></i></a>
        <a class="whats" href="https://wa.me/919344885384"><i class="fa-brands fa-whatsapp"></i></a>
        <a class="mail" href="#"><i class="fa-regular fa-envelope"></i></a>
        <p class="copy">CopyLeft @</p>
</div>
</div>
</body>
</html>

# Portfolio-website
<!DOCTYPE html>
<html>
<head>
    <title>My Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            color: whitesmoke;
            background-image: url(https://www.curtainsjs.com/images/intro-background.jpg);
            background-repeat: no-repeat;
            background-size: 100%;
            margin: 0;
            padding: 0;
        }
        
        header {
            
            text-align: center;
            padding: 20px;
        }
        
        h1 {
            margin: 0;
        }
        u{
            color:maroon;
        }
        nav {
            
            text-align: center;
            padding: 10px;
        }
        
        img{
            margin-top:10px;
            width:200px;
            height:200px;
            border-radius: 100%;
            border-left: 500px;
        }
        a{
            color:olive;
        }
        div{
            padding-top:75px;
            padding-right:250px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Moulika Manaswini Topella</h1>
        <p>Web Developer</p>
        <img src="https://i.pinimg.com/originals/64/e9/db/64e9db8d0b6e4e501b177549fcb449db.jpg">
        <p><u><b>About me:</b></u></p>
        <p>Enthusiastic and self-motivated individual with a strong work ethic.</p>
        <p> A dedicated team player known for fostering positive collaboration.</p>
        <p> Well-organized, adaptable, and committed to continuous learning for professional growth.</p>
        <p style="color:navy;"><b>My Skills</b>: Python|C|Frontend web development|Machine Learning</p>
    <div>
    <img style="width:50px;height:50px;padding-left: 300px;" src="https://as1.ftcdn.net/v2/jpg/02/24/13/60/1000_F_224136019_9kwW97uwluMgeoWikGx1ckCiBUDfaEOZ.jpg" >
    <a href="education.html">Education details</a>
    <img style="width:50px;padding-left:50px;height:50px;" src="https://previews.123rf.com/images/bestvectorstock/bestvectorstock1808/bestvectorstock180810960/107156890-achievement-vector-icon-isolated-on-transparent-background-achievement-logo-concept.jpg">
    <a href="achievements.html">acomplishments</a>
    <img style="width:50px;padding-left:100px;height:50px;" src="https://www.freepnglogos.com/uploads/silver-email-logo-png-5.png">
    <a href="contact.html">Contact</a>
    </div>
</header>
</body>
</html>
education.html :
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Education Details</title>
    <style>
        body {
            background-image: url('https://unbounce.com/photos/Gradient-Background.png');
            font-family: Arial, sans-serif;
            margin: 20px;
        }

        header {
            text-align: center;
            padding: 20px;
            background-color: #c71585;
            color: #ffffff;
        }

        section {
            margin-top: 20px;
        }

        h2 {
            color: #3498db;
        }

        ul {
            list-style-type: solid circle;
            padding: 0;
        }
        h1{
            color:#191970;
        }
        h3{
            color:#6b8e23;
        }
        h4{
         color:	#800080;   
        }
        b{
            color:	#a0522d;
        }
        li {
            margin-bottom: 10px;
        }
    </style>
</head>

<body>

    <header>
        <h1>My Education Details</h1>
    </header>

    <section>
        <h2>Educational Qualifications</h2>
        <ul>
            <li>
                <h3><u>SCHOOLING</u></h3>
                <h4><p><u>SSC<br></u></p></h4>
                <p><b>Year:</b> 2018 - 2019</p>
                <p><b>School name : </b>Sri chaitanya techno school</p>
                <p><b>Place : </b>Amalapuram</p>
                <p><b>CGPA : </b>10.0</p>
            </li>
            <li>
                <h3><u>SECONDARY EDUCATION</u></h3>
                <h4><p><u>INTERMEDIATE<br></u></p></h4>
                <p><b>Year:</b> 2019 - 2021</p>
                <p><b>College name : </b>Aditya Junior college</p>
                <p><b>Place : </b>Amalapuram</p>
                <p><b>Marks : </b>981</p>
            </li>
            <li>
                <h3><u>GRADUATION</u></h3>
                <h4><p><u>BACHELOR OF TECHNOLOGY<br></u></p></h4>
                <p><b>Year:</b> 2021 - 2025</p>
                <p><b>College name : </b>Vishnu Institute of Technology</p>
                <p><b>Place : </b>Bhimavaram</p>
                <p><b>CGPA : </b>9.04</p>
            </li>
        </ul>
    </section>

</body>

</html>
achievements.html :

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Certificates</title>
    <style>
        body {
            background-image: url('https://png.pngtree.com/thumb_back/fh260/background/20210501/pngtree-aesthetic-violet-gold-marble-phone-wallpaper-image_691080.jpg');
            font-family: 'Arial', sans-serif;
            margin: 20px;
            background-color: #f4f4f4;
            text-align: center;
        }
        h1 {
            color: #333;
        }
        #certificates {
            display: flex;
            justify-content: center;
            gap: 20px;
            flex-wrap: wrap;
        }
        .certificate {
            background-color: #fff;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            border-radius: 8px;
            overflow: hidden;
            width: 250px;
            margin: 10px;
        }
        .certificate img {
            max-width: 100%;
            height: auto;
            border-bottom: 1px solid #ddd;
        }
    </style>
</head>
<body>
    <h1>My Certificates</h1>

    <div id="certificates">
        <!-- Replace the placeholder paths with your actual certificate image paths -->
        <div class="certificate">
            <img src="E:\Mouli\kaggle\T M MANASWINI - Python.png" alt="Certificate 1">
        </div>
        <div class="certificate">
            <img src="E:\Mouli\kaggle\T M MANASWINI - Pandas.png" alt="Certificate 2">
        </div>
        <div class="certificate">
            <img src="E:\Mouli\kaggle\T M MANASWINI - Intro to Programming.png" alt="Certificate 2">
        </div>
        <div class="certificate">
            <img src="E:\Mouli\Coursera python.jpg" alt="Certificate 2">
        </div>
        <div class="certificate">
            <img src="E:\Mouli\Coursera Financial markets.jpg" alt="Certificate 2">
        </div>
        <div class="certificate">
            <img src="E:\Mouli\manaswini.jpg" alt="Certificate 2">
        </div>
        <div class="certificate">
            <img src="E:\Mouli\Aicte\aicte.jpg" alt="Certificate 2">
        </div>
        <div class="certificate">
            <img src="E:\Mouli\cisco certificate.jpg" alt="Certificate 2">
        </div>
        <!-- Add more certificates as needed -->
    </div>
</body>
</html>

contact.html :

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Details</title>
    <style>
        body {
            background-image: url('https://png.pngtree.com/background/20210716/original/pngtree-galaxy-abstract-glitter-background-picture-image_1391042.jpg');
            font-family: 'Arial', sans-serif;
            margin: 20px;
            background-color: #f4f4f4;
            text-align: center;
        }
        h1 {
            color: #7D0552;
        }
        h2 {
            color: #7E354D;
        }
        b{
            color:#FF007F;
        }
        #contact-info {
            display: flex;
            justify-content: center;
            gap: 20px;
            flex-wrap: wrap;
        }
        .contact-card {
            background-color: #E3E4FA;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            border-radius: 8px;
            overflow: hidden;
            width: 250px;
            margin: 10px;
            padding: 20px;
        }
    </style>
</head>
<body>
    <h1>Contact Details</h1>

    <div id="contact-info">
        <div class="contact-card">
            <h2>TOPELLA MOULIKA MANASWINI</h2>
            <p><b>Email:</b></p>
            <p> 21pa1a5757@vishnu.edu.in</p>
            <p><b>Address:</b></p>
            <p> Vishnu Institute of Technology,Bhimavaram.</p>
        </div>

    </div>
</body>
</html>


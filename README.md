# basic-application-form
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="one.css"/>
</head>
<body>
    <form>
        <h1><strong><marquee>****Basic Application form****</marquee></strong></h1><hr>
        Enter your First name:<input type="text"><br><br>
        Enter your Last name:<input type="text"><br><br>
        Enter your Father's name:<input type="text"><br><br>
        Enter your mother's name:<input type="text"><br><br>
        Enter your Email:<input type="email"><br><br>
        Enter your mobile number:<input type="text" maxlength="10"><br><br>
        Choose your recent graduation:<br>
        <input type="radio" id="graduation" name="graduation" value="B.Tech">B.Tech<br>
        <input type="radio" id="graduation" name="graduation" value="M.Tech">M.Tech<br>
        <input type="radio" id="graduation" name="graduation" value="B.pharmacy">B.pharmacy<br>
        <input type="radio" id="graduation" name="graduation" value="M.pharmacy">M.pharmacy<br>
        <input type="radio" id="graduation" name="graduation" value="B.s.c">B.s.c<br>
        <input type="radio" id="graduation" name="graduation" value="B.B.A">B.B.A<br>
        <input type="radio" id="graduation" name="graduation" value="LLB">LLB<br>
        Choose your branch?:<br>
        <input type="radio" id="branch" name="branch" value="Civil">Civil<br>
        <input type="radio" id="branch" name="branch" value="EEE">EEE<br>
        <input type="radio" id="branch" name="branch" value="Mech">Mech<br>
        <input type="radio" id="branch" name="branch" value="ECE">ECE<br>
        <input type="radio" id="branch" name="branch" value="CSE">CSE<br>
        Enter your year of passed out:<input type="date"><br>
        Enter your graduation percentage:<input type="text" maxlength="4"><br>
        Have you done any programming courses mention below?:<br>
        <input type="checkbox" id="course" name="course" value="Python">Python<br>
        <input type="checkbox" id="course" name="course" value="Java">Java<br>
        <input type="checkbox" id="course" name="course" value="C">C<br>
        <input type="checkbox" id="course" name="course" value="C++">C++<br>
        <input type="checkbox" id="course" name="course" value="ASP.NET">ASP.NET<br>
        <input type="checkbox" id="course" name="course" value="ORACLE">ORACLE<br>
        <input type="checkbox" id="course" name="course" value="SQL">SQL<br>
        Mention your social media accounts:<br>
        <input type="checkbox" id="social media" name="social media" value="Youtube">YOUTUBE<br>
        <input type="checkbox" id="social media" name="social media" value="Instagram">INSTAGRAM<br>
        <input type="checkbox" id="social media" name="social media" value="Github">GITHUB<br>
        <input type="checkbox" id="social media" name="social media" value="Telegram">TELEGRAM<br>
        <center><a href="two.html">Submit</a></center>
    </form>
</body>
</html>


<!--Html 2nd page-->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="one.css"/>
</head>
<body>
    <form>
        <h1>Thanks for your response!!!! your response has been recorded</h1>
        <a href="one.html">Back</a>
    </form>
</body>
</html>


<!-- css code -->
h1{
    color: blue;
}
form{
    background-color: palegreen;
    margin: 200px 300px 200px;
    text-align: left;
    border:5px solid black;
}

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fitness Camp</title>
</head>
<link href="https://fonts.googleapis.com/css2?family=Satisfy&display=swap" rel="stylesheet">
<link rel="stylesheet" href="css/style.css">
<style>
    /* CSS Reset  */
    body {
        font-family: 'Satisfy', cursive;
        font-size: 12px;
        background-image: url("pics/c.jpg");
        background-size: 85%;
        margin: 0px;
        padding: 0px;
        color: white;


    }

    .left {
        color: white;
        /* border: 3px solid indianred; */
        display: inline-block;
        position: absolute;
        left: 45px;
        top: 20px;

    }

    .mid {
        color: white;
        /* border: 3px solid palegreen; */
        display: block;
        width: 43%;
        margin: 29px auto;

    }

    .right {

        position: absolute;
        right: 34px;
        top: 34px;

        /* border: 3px solid red; */
        display: inline-block;
    }

    .navbar {
        display: inline-block;
    }

    .navbar li {
        font-size: 18px;

        display: inline-block;

    }

    .navbar li a {
        color: white;
        text-decoration: none;
        padding: 24px;
    }

    .left div {
        text-align: center;
        font-size: 21px;
        text-align: center;
    }

    .navbar li a:hover,
    .navbar li a.active {
        text-decoration: underline;
        color: grey
    }

    .left img {
        width: 89px;
    }

    .btn {
        margin: 0px 8px;
        color: white;
        background-color: black;
        padding: 4px 14px;
        border: 2px solid gray;
        border-radius: 10px;
        font-size: 14px;
        cursor: pointer;
        font-family: 'Satisfy', cursive;
    }

    .btn:hover {
        background-color: rgb(158, 122, 122);
    }

    .container h1 {
        text-align: center;
    }

    .container button {
        display: block;
        width: 64%;
        margin: 15px auto;

    }

    .container {
        border: 4px solid white;
        margin: 106px 80px;
        padding: 75px;
        width: 33%;
        border-radius: 28px;


    }

    .form-group input {
        font-family: 'Satisfy', cursive;

        text-align: center;
        display: block;
        width: 405px;
        border: 2px solid black;
        margin: 3px auto;
        font-size: 24px;
        border-radius: 8px;
    }
</style>

<body>
    <header class="header">
        <!-- left box for logo -->
        <div class="left">
            <img src="pics/lo.jpg" alt="">
            <div>Fitness Camp</div>

        </div>

        <!-- mid for nav  -->
        <div class="mid">
            <ul class="navbar">
                <li><a href="#" class="active">Home</a></li>
                <li><a href="#">About Us</a></li>
                <li><a href="#">Fitness Calculator</a></li>
                <li><a href="#">Contact Us</a></li>
            </ul>

        </div>

        <!-- right for buttons -->
        <div class="right">
            <button class="btn">Call us Now</button>
            <button class="btn">Email Us</button>
        </div>
    </header>
    <div class="container">
        <h1>Join the GYM Now!</h1>
        <form action="noaction.php">
            <div class="form-group">
                <input type="text" name="" placeholder="Enter your Name">

            </div>
            <div class="form-group">
                <input type="text" name="" placeholder="Enter your Age">

            </div>
            <div class="form-group">
                <input type="text" name="" placeholder="Enter your Gender">

            </div>
            <div class="form-group">
                <input type="text" name="" placeholder="Enter your Locality">

            </div>
            <button class="btn">Submit</button>
        </form>
</body>

</html>

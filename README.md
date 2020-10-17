# HTML-Development
#A Website of Gym Fitness.
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fitness With Rajeev</title>
</head>
<link rel="CSS/stylesheet" href="">
<!-- imort font family -->
<style>
    /* CSS Reset */
    body {
        color: white;
        margin: 0px;
        padding: 0px;
        background: url('img/log1.jpg');
        width: auto;
        height: 100px;
    }

    .left {
        display: inline-block;
        /* border: 2px solid red; */
        position: absolute;
        left: 60px;
        top: 20px;
    }

    .mid {
        display: block;
        width: 45%;
        margin: 20px auto;
        /* border: 2px solid green; */
        top: 20px;

    }

    .right {
        position: absolute;
        right: 34px;
        top: 33px;
        display: inline-block;
        /* border: 2px solid yellow; */
    }

    .navbar {
        margin-top:35px;
        display: inline-block;

    }

    .navbar li {
        display: inline-block;
        font-size: 25px;

    }

    .navbar li a {
        color: white;
        text-decoration: none;
        /* margin: 12px; */
        padding: 34px 23px;
    }

    .navbar li a:hover,
    .navbar li a.active {
        text-decoration: underline;
        color: goldenrod;
    }

    .left img {
        /* remove the background of the logo  */
        width: 96px;

        filter: invert(100%);
    }

    .left div {
        text-align: center;
        line-height: 8px;
        font-size: 24px;
    }

    .btn {
        /* import font family */
        margin: 30px 9px;
        color: white;
        background-color: black;
        padding: 4px 14px;
        border: 2px solid green;
        border-radius: 10px;
        font-size: 20px;
        cursor: pointer;
    }

    .btn:hover {
        background-color: grey;
    }

    .container {
        border: 2px solid red;
        margin: 100px 101px;
        padding: 14px 75px;
        width: 33%;
        border-radius: 16px;
    }
    .form-group input{
        /* font-family: ; */

        text-align: center;
        display: block;
        width: 508px;
        padding:1px;
        border: 2px solid palevioletred;
        border-radius: 8px;
        font-size: 25px;
        margin:15px auto;
    }
    .container h1{
        text-align: center;
    }
    .container button{
        display: block;
        width: 196px;
    /* margin: auto; */
    margin: 33px
        /* margin: 20px; */
    }
    /* .container button #can{
        color: rgb(255, 0, 0);
        /* text-align-last: right; */
        /* display: block;
        margin: 35px;
        padding: 1px;
        height: 101px;
    } */ 
</style>

<body>
    <header class="header">
        <!-- left bos for logo -->
        <div class="left">
            <!-- insert round pictre -->
            <img src="img/logo.png" alt="">
            <div>Rajeev Fitness</div>

        </div>
        <!-- mid box for navbar -->
        <div class="mid">
            <ul class="navbar">
                <li><a href="#" Class="active">Home</a></li>
                <li><a href="#">About us</a></li>
                <li><a href="#">Fitness Calculator</a></li>
                <li><a href="#">Contact us</a></li>
            </ul>
        </div>
        <!-- right box for buttons -->
        <div class="right">
            <button class="btn">Call us </button>
            <button class="btn">Email us </button>
        </div>
    </header>
    <div class="container">
       <h1>Join the Best Gym of Bhagalpur now</h1>
       <form action="noaction.php">
           <div class="form-group">
               <input type="text" name="" id="" placeholder="Enter Your Name">
           </div>

           <div class="form-group">
            <input type="text" name="" id="" placeholder="Enter Your Age">
        </div>

        <div class="form-group">
            <input type="text" name="" id="" placeholder="Enter Your Gender">
        </div>

        <div class="form-group">
            <input type="text" name="" id="" placeholder="Enter Your Locality">
        </div>

        <div class="form-group">
            <input type="text" name="" id="" placeholder="Enter Your Email">
        </div>

        <div class="form-group">
            <input type="text" name="" id="" placeholder="Enter Your Phone">
        </div>
        <div>
            <button class="btn">Submit</button>
        </div>

        <div>
            <button class="btn" id="can">Cancel</button>
        </div>
       </form>
</body>

</html>

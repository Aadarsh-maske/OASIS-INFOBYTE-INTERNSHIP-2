# OASIS-INFOBYTE-INTERNSHIP-2
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Landing_page | Fashion</title>
    <style>
        body{
            background: linear-gradient(rgba(0,0,0,0.8),rgba(0,0,0,0.2)),url("pizza.jpg");
            background-repeat: no repeat;
            background-size: cover;
            /* background: linear-gradient(rgba(0,0,0,0.8),rgba(0,0,0,0.2)); */
        }
        header{
            width: 100%;
            height: 100vh;
            color: #fff;
            font-family: sans-serif;
            background-size: cover;
        }
        nav{
            width: 100%;
            height: 100px;
            background:transparent;
            color:white;
            display: flex;
            justify-content: space-around;
            align-items: center;
        }
        .logo{
            font-size: 2em;
            letter-spacing: 2px;
            color:#e45b07;
            font-weight: bold;
            font-size: 80px;

        }
        .menu a{
            text-decoration: none;
            color: #fff;
            padding: 10px 20px;
            font-size: 20px;


        }
        .register {
            text-decoration: none;
           
            padding: 10px 20px;
            font-size: 20px;
            background-color: orange;
            border: 1px solid red;
            border-radius: 50px;
        }
        .header-txt{
            max-width: 650px;
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%,-50%);
            text-align: center;

        }
        .header-txt span{
            letter-spacing: 5px;

        }
        .header-txt h1{
            font-size: 3.5em;
        }
        .header-txt a{
            text-decoration: none;
            background:red;
            border-radius: 25px;
            color:#fff;
            padding: 10px 20px;
            letter-spacing: 5px;
        }
        .menu a:hover{
            color: red;
        }
    </style>
</head>
<body>
    <header>
        <nav>
            <div class="logo">
                food X
            </div>
            <div class="menu">
                <a href="#">Menu</a>
                <a href="#">discounts</a>
                <a href="#">best offers</a>
                <a href="#">contact</a>
                <a href="#">FAQ</a>
                
            </div>
            <div class="register">
                    Order
            </div>
        </nav>
        <section class="header-txt">
            <span>Made with happines</span>
            <h1>What you want to order?</h1>
            <br>
            <a href="#">order food</a>
        </section>
    </header>


</body>
</html>

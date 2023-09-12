<!DOCTYPE html>

<html>

    <head>

        <title>travel</title>

             <style>

                body{

                    background-image: url(bus3.jpg);

                    width:100%;

                    height: 100%;

                    background-size: cover;

                    background-position: center;

                    background-repeat: no-repeat;



                }

                .nav-bar{

                    width: 85%;

                    margin: auto;

                    padding: 35px 0;

                    display: flex;

                    align-items: center;

                    justify-content: space-between;

                }

                .nav-bar ul li{

                    list-style: none;

                    display: inline-block;

                    margin: 0 35px;

                    position: relative;

                }

                .heading{

                    color: white;

                    text-align: center;

                }

                .nav-bar ul li a{

                    text-decoration: none;

                    color: white;

                    text-transform: uppercase;

                }

                .nav-bar ul li::after{

                    content: "";

                    height: 3px;

                    width: 0;

                    background: #009688;

                    position: absolute;

                    left: 0;

                    bottom: 0;

                    transform: 0.5s;

                }

                .nav-bar ul li:hover::after{

                    width: 100%;

                }

                .book{

                    text-align: center;

                    color: white;

                }

                .button1 {

                    position: absolute;

                    text-align: center;

                    padding: 15px 20px;

                    border: 1px solid #009688;

                    background: transparent;

                    color: white;

                    top: 80%;

                    left: 20%;

                    cursor: pointer;



                }

               

                

                .btn:hover{

                    background-color: #009688;

                    color: blueviolet;

                }

                .button2{

                    position: absolute;

                    text-align: center;

                    padding: 15px 20px;

                    border: 1px solid #009688;

                    background: transparent;

                    color: white;

                    left: 40%;

                    top: 80%;

                    cursor: pointer;

                   



                }

                

                .button3{

                    position: absolute;

                    text-align: center;

                    padding: 15px 20px;

                    border: 1px solid #009688;

                    background: transparent;

                    color: white;

                    top: 80%;

                    left: 60%;

                    cursor: pointer;

                }

                .button{

                    text-align: center;

                    margin-block: 90px; 

                }

             </style>

    </head>

    <body>

        <div class="heading"><h1>Online Bus Booking System</h1></div>

        <div class="nav-bar">

            <ul>

                <li><a href="home.html">HOME</a></li>

                <li><a href="about.html">ABOUT US</a></li>

                <li><a href="contact.html">CONTACT US</a></li>

                <li><a href="ticket.html">TICKET STATUS</a></li>

                <li><a href="travel.html">TRAVEL GUIDE</a></li>

                <li><a href="services.html">services</a></li>

            </ul>

            

        </div>

        <div class="book">

            <h1>BOOK YOUR TICKETS FROM THIS WEBSITE</h1>

            <h2>for safety and secure journey</h2>

        </div>

        <div class="button">

        <span><a href="login.html"><input type="button"  value="login" class="button1 btn"></a></span>

        <span><a href="signup.html"><input type="button" value="Sign up" class="button2 btn"></a></span>

        <span><a href="guest"><input type="button" value="Guest" class="button3 btn"></a></span>

        </div>

        <footer>

            

        </footer>

    </body>

</html>

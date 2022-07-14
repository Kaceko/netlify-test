<!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8"/>
        <meta name="viewport" content="width=device-width,initial-scale=1"/>
        <title>練習2</title>
        <style>
            *{
                margin: 0;
                padding: 0;
                box-sizing: border-box;
                outline: none;
            }
            body{
                font-family: 'Syne';
                font-size: 18px;
                color: #fff;
                overflow-x: hidden;
                background-color: blueviolet;
            }
            a{
                font-family: 'Syne';
                text-decoration: none;
                color: #fff;
            }
            h1 h3 h5{
                font-family: 'Krone one';
            }
            h1{
                font-size: 48px;
                font-weight: normal;
            }
            h3{
                font-size: 24px;
                font-weight: normal;
            }
            h5{
                font-size: 18px;
                font-weight: normal;
            }
            header{
                display: flex;
                justify-content: space-between;
                padding-right: 123px;
                position: fixed;
                width: 100%;
                z-index: 99;
            }
            .logo{
                width: 395px;
                padding-right: 30px 85px;
                background: linear-gradient(94deg,#0075ff 0%,#c92fff 100%);
                text-align: right;
                transform: skew(-15deg),translateX(-15px);
                border-radius: 0 0 40px 0;
                position: relative;
                padding:5px 20px 0 0;
            }
            .logo:before{
                position: absolute;
                content: '';
                top: 0;
                right: -20px;
                width: 100%;
                height: 100%;
                background: linear-gradient(94deg,#0075ff 0%,#c92fff 100%);
                border-radius: 0 0 40px 0;
                opacity: .3;
            }
            .menu ul li{
                list-style: none;
                display: inline-table;
                margin: 30px 25px;
            }
            .menu ul li a{
                color: #fff;
                transition: all ease 0.5s;
            }
            .menu ul li a:hover{
                opacity: 0.5;
            }
            .banner_img img{
                width: 400px;
                height: 400px;
                object-fit: cover;
            }
            .banner{
                display: flex;
                align-items: center;
                justify-content: space-between;
                flex-wrap: wrap;
                padding: 180px;
            }
            .banner_text{
                max-width: 570px;
                padding-right: 70px;
            }
            .banner_text p{
                margin: 20px 0 50px;
                line-height: 28px;
            }
            .buttons a{
                display: inline-table;
                padding: 14px;
                width: 190px;
                background: linear-gradient(94deg,#0075ff 0%,#c92fff 100%);
                text-align: center;
                font-size: 18px;
                font-weight: 700;
                transform: skew(-10deg);
                margin-right: 15px;
                transition: all ease 0.6s;
            }
            .buttons .second{
                background: transparent;
                border: 1px solid #fff;
            }
            .buttons .first{
                background: transparent;
                border: 1px solid #fff;
            }
            .buttons .second:hover{
                background: linear-gradient(94deg,#0075ff 0%,#c92fff 100%);
            }
            .buttons .first:hover{
                background: linear-gradient(94deg,#0075ff 0%,#c92fff 100%);
            }
            .banner_img{
                display: flex;
            }
            .banner_img .item{
                background-color: rgba(255, 255, 255, 0.1);
                padding: 22px;
                margin: 0 15px;
            }
            .item_text{
                margin-top: 20px;
            }
            h5{
                margin-top: 8px;
                font-weight: normal;
            }
            .banner_counter{
                width: 100%;
            }
            p{
                font-size: 10px;
            }
            .block_wrap{
                display: flex;
                justify-content: space-between;
                max-width: 550px;
            }
            .block_wrap .block{
                background-color: rgba(255, 255, 255, 0.1);
                padding: 20px 30px;
                text-align: center;
                width: 160px;
            }
        </style>
    </head>
    <body>
        <main>
            <header>
                <div class="logo">
                    <a href="#"><img src="file:///Users/webber/Desktop/%E7%B6%B2%E9%A0%81%E7%B7%B4%E7%BF%92/logo.svg" alt=""></a>
                </div>
                <div class="menu">
                    <ul>
                        <li><a href="#">About me</a></li>
                        <li><a href="#">Portfolios</a></li>
                        <li><a href="#">Instagram</a></li>
                        <li><a href="#">Contact</a></li>
                    </ul>
                </div>
            </header>
            <sectiom class="banner">
                <div class="banner_text">
                    <h1>Welcome to my web</h1>
                    <p>Hope you like my web and portfolios</p>
                    <div class="buttons">
                        <a href="#" class="first"><span>My portfolios</span></a>
                        <a href="#" class="second"><span>Contact me</span></a>
                    </div>
                </div>
                <div class="banner_img">
                    <div class="item">
                        <div class="img_group">
                            <img src="file:///Users/webber/Desktop/portfolio/1-10_%E5%B7%A5%E4%BD%9C%E5%8D%80%E5%9F%9F%201.png" alt="">
                            <img src="file:///Users/webber/Desktop/portfolio/2_%E5%B7%A5%E4%BD%9C%E5%8D%80%E5%9F%9F%201.png" alt="">
                        </div>
                        <div class="item_text">
                            <div class="item_text_left">
                                <p>Ripple Music</p>
                                <h5>Logo Design</h5>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="banner_counter">
                    <div class="block_wrap">
                        <div class="block">
                            <h3><span class="counter">50</span>+</h3>
                            <p>Poster design</p>
                        </div>
                        <div class="block">
                            <h3><span class="counter">30</span>+</h3>
                            <p>Logo design</p>
                        </div>
                        <div class="block">
                            <h3><span class="counter">25</span>+</h3>
                            <p>3D Motion design</p>
                        </div>
                    </div>
                </div>
            </sectiom>
        </main>

        <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.6.0/jquery.min.js"></script>
        <script src="https://cdnjs.cloudflare.com/ajax/libs/waypoints/4.0.1/noframework.waypoints.min.js"></script>
        <script src="https://cdnjs.cloudflare.com/ajax/libs/Counter-Up/1.0.0/jquery.counterup.min.js"></script>
        <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery.cycle/3.0.3/jquery.cycle.all.min.js"></script>
        <script>
            $(document).ready(function(){
                
                $('.img_group').cycle({ 
                    timeout:1000
                });

            });
        </script>
    </body>
</html># please
# please

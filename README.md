# Team-survival-login
<DOCTYPE html>	
    <!DOCTYPE html>
    <html>
    <head>
        <title>sample</title>
        <style type="text/css">
            #one{
                background-color: skyblue;
                width: 50%;
                height: 100%;
                float: left;
            }
            #two{
                background-color: whitesmoke;
                width: 50%;
                height: 100%;
                float: right;
            }
            #move{
                text-align: center;
                padding-top: 120px;
                font-size: 13px;
            }
            #name{
                font-size: 15px;
                box-shadow: 4px 7px lightgrey;
            }
            #password{
                font-size: 15px;
                box-shadow: 4px 7px lightgrey;
            }
            h1{
                color: red;
                font-size: 40px;
            }
            h5{
                color: grey;
                font-size: 20px;
            }
            .space{
                margin-left: 160px;
            }
            .botton{
                margin-left: 140px;
            }
            .submit{
                background-color: blue;
                color: white; 
                font-size: 20px;
                width: 18%;
                border-radius: 8px;
            }
            #dash{
                font-size: 20px;
                width: 18%;
                background-color: white;
                color: blue;
                border-radius: 8px;
            }
        </style>
    </head>
    <body>
    <div id="one">
    ​
    </div>
    <div id="two">
        <section id="move">
        <h1>HNGinternship</h1>
           <h5>Welcome back! Please login to your account</h5>
           <form action="action_page.php" method="post"> 
                <p> <input type="text" id="name" placeholder="Username" name="user_name" required minlength="20"></p>
               <input type="password" placeholder="Password" id="password" name="user_password" required>
               <p><input element, type="checkbox"> Remember Me <a href=""> <span class="space">Forget Password</span></a></p><br>
                <Button class="Submit">Login</Button><span class="botton"> <button id="dash"> Sign up </button></span>
                </form>
                </section>
    </div>
    </body>
    </html>

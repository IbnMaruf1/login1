<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Login page</title>
</head>
<style>
    #grad {background-image: linear-gradient(to right, red, blue);
    }
    .big {
        background-image: linear-gradient(to right,  navy, darkred);
        border: ;
         width: 70%;
         height: 500px;
         margin-top: 150px;
         margin-left: 15%;
    }
    .small {
        background-color: black;
        border: ;
        width: 70%;
        height: 480px;
        margin-top: 20px;
        margin-left: 15%;
        color: white;
        font-family: Arial, Helvetica, sans-serif;
        weight: 5px;
        font-size: 25px;
        text-align: center; 
    }
    .input3 {
        border: solid lightseagreen 3px;
         width: 40%;
         height: 40px;
         border-radius: 25px;
         background-color: black;
         font-size: 18px;
         text-align: center; 
         color: white;  
    }
    .input5 {border: solid lightseagreen 3px;
         width: 40%;
         height: 40px;
         border-radius: 25px;
         background-color: black;
         font-size: 18px;
         text-align: center;  
         color: white;

    }
    .f1 {
        margin-top: -70px ;
    }
    .f2 {margin-top: 15px ;

    }
    .f2 {margin-top: 15px ;
}
.input4 {border: solid green 3px;
         width: 20%;
         height: 40px;
         border-radius: 25px;
         background-color: black;
         font-size: 18px;
         text-align: center;
         color: grey;

}
a{color: grey;}
a:hover {color: green;}
a:active {color: white;}
button:hover {background-color: }


</style>
<body id="grad">
     <div class="big">
        
        <div class="small">
            <h1 style="font-weight: lighter; padding-top: 20px;" >LOGIN</h1>
            <p style="color: grey; font-size: 18px; padding-bottom: 100px;"> 
                Please enter your login and password!
            </p>
            <form action="" class="f1">
                <input type="Username" placeholder="Username"  class="input3">
                
            </form>
            <form action="" class="f2">
                <input type="Password" placeholder="Password" class="input5" >
                
            </form>
            <p style="color: grey; font-size: 18px;text-decoration: underline;" >
                 Forgot password?</p>
                 <form action="" class="f3">
                    <button class="input4"><a href="./successful.html">login</a></button>
                    
                </form>
        </div>
     </div>
</body>
</html>

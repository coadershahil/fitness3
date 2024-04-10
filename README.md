<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Shahil Fitness</title>
    <link  href="http://font.googleapis.com/css?family=Baloo+Bhai&display=swap" rel="stylesheet" >
    <link rel="stylesheet" href="fitness.css">
    <style>
    body{
        font-family: "Baloo Bhai",cursive;
        margin: 0px;
        padding: 0px;
        background:url(/HTML/images/gym2.avif);
        color: aliceblue;
        background-size: 100%;
           
    }
    .left{
        display: inline-block;
        
        color: aliceblue;
        position: absolute;
        left: 60px;
        top: 20px;
        }
    .mid{
        display: block;
        color: aliceblue;
        margin: 29px auto;
        width: 33%;
              
              
    }
    .right{
        
        color: aliceblue;
        display: inline-block;
        position: absolute;
        right: 34px;
        top: 43px;
    }
    .navbar{
        display: inline-block;
    }
    .navbar li{
        color: white;
        display: inline-block;
        padding: 10px;
        font-size: 25px;
        font-size: x-large;
        
       

            
    }
    .navbar li a{
            
            color: aliceblue;
            text-decoration: none;
            padding: 34px 24px;
            
    }
    .navbar li a:hover,.navbar li a:active{
            color: gray;
            text-decoration: none;
            padding: 34px 24px;
            text-decoration: underline;
        }
    .left img{
        width: 125px;
        filter:invert(100%)
    }

    .left div{
        text-align: center;
        line-height: 19px;
        font-size: 26px;
    }
    .btn{
          margin: 0px 9px;
          background-color: black;
          color: white;
          padding: 6px 14px;
          border-radius: 15px;
          font-size: 20px;
          cursor: pointer;
          font-family:"baloon bhai",cursive ;
          


    }
    .btn:hover{
        background-color: rgb(117, 117, 117);
    }

    .container{
        border: 2x solid rgb(250, 250, 250);
        margin: 106px 80px;
        padding:75px;
        width: 33%;
        border: 2px solid rgb(247, 246, 246);
        border-radius: 20px;
        
        
    }

    .form-group input{
        text-align: center;
          font-size:25px;
          display: block;
          width: 508px;
          padding: 1px;
          border: solid black;
          margin: 11px auto ;
          
          font-family: "baloon bhai",cursive;
          border: 2x solid white;
          border-radius: 20px;
          
          
    }
    .container h1{
        text-align: center;
       
    }
    .container button{
        display: block;
        width: 61%;
        margin: 20px auto;
    }
    </style>
</head>
<body>
    <header class="header">
    
        <!-- left box ka logo ke liye -->
        <div class="left">
           <img src="/HTML/images/3043888.png" alt="image" >  
           <div >
            Shahil Fitness
           </div>       

    
        </div>

    <!-- mid box ke logo ke liye -->
        <div class="mid">
            <ul class="navbar">
                <li><a href="#" class="active">Home</a></li>
                <li><a href="#">About Us</a></li>
                <li><a href="#">Fitness Calculator</a></li>
                <li><a href="#">Contact Us</a></li>
            </ul>

        </div>

    <!-- right class ke logo ke liye -->
        <div class="right">
            <button class="btn">Call Us Now</button>
            <button class="btn">Email us</button>

        </div>        
    </header>
    
    <div class="container" >
     <h1>Join the best Gym of Jamalpur Now</h1>
     <form action="noaction.php">
        <div class="form action">

        </div>
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
        
    <button class="btn">submit</button>
    
    
    
        
    
     </form>
    </div>

    
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <style>
    body{
        margin: 0;
    }
    .container{
        background-color:  #b72a67;
        height: 100vh;
        width: 100wh;
    }
    .miniContainer{
        background-color: #8d2050;
        height: 100vh;
        width:180px;
    }
    .cont{
        background-color: #8d2050;
        width: 180px;
        height: 170px;
    }
    .miniCont{
        background-color:blck ;
        width: 50px;
        height: 50px;
    
        /* transition: 2s, linear; */
        padding-top: 3px;
    }
    .text{
        color: white;
        font-size: small;
        position: absolute;
        left: 90px;
        top: 30px;
        /* visibility: hidden; */
        
    
    }
    .bar{
        height: 5px;
        width: 35px;
        background-color: white;
        margin: 10px auto;
        box-shadow: 0px 5px 50px 5px gray;
    }
    .miniCont:hover .top{
        transform: translateY(15px) rotateZ(45deg);
        transition: 0.8s linear;
    }
    .miniCont:hover .bottom{
        transform: translateY(-15px) rotateZ(-45deg);
        transition: 0.8s linear;
    }
    .miniCont:hover .middle{
        width: 0px;
        transition: 0.8s linear;
    }
    .text-one:hover{
        border-top: 1px solid white;
        border-bottom: 1px solid white;
        padding-top: 4px;
        padding-bottom: 4px;
        width: 80px;
    }
    .text-two:hover{
        border-top: 1px solid white;
        border-bottom: 1px solid white;
        padding-top: 4px;
        padding-bottom: 4px;
        width: 80px;
    }
    
    .text-three:hover{
        border-top: 1px solid white;
        border-bottom: 1px solid white;
        padding-top: 4px;
        padding-bottom: 4px;
        width: 80px;
    }
    .miniCont:hover+.text{
        /* visibility: visible; */
        animation: nigga 1.3s linear 1;
    }
    @keyframes nigga{
        from{
            left: 60px;
            top: 30px;
            opacity: 0.001;
    
        }
    
        to{
            left: 90px;
            top: 30px;
        }
    }
</style>
</head>
<body>
    <div class="container">
        <div class="miniContainer">
            <div class="cont">
                
                <div class="miniCont"> 
                    <div class="bar top"></div>
                    <div class="bar middle"></div>
                    <div class="bar bottom"></div>
                    
                </div>
                    <div class="text tbbo">
                       <p class="text-one">Namuun</p>
                       <p class="text-two">Dulguun</p>
                       <p class="text-three">Chuka</p>
                    </div>
                    
            </div>
        </div>
    </div>

</body>

</html>

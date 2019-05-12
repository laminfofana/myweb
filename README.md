# myweb<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>templete-9</title>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css">
    <link rel="stylesheet" href="templete-9.css">
    <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.8.1/css/all.css">
    <script src="jquery-3.3.1.min.js"></script>

</head>
<body>
    <header>
        <nav>
            <div class="nav-logo">
            <div class="logo">Logo</div>
            <div class="min-1"><i class="fa fa-align-justify" id="menu-icon"></i></div>
        </div>
            <div class="min">
                <ul>
                    <li><a href="#">Home</a></li>
                    <li><a href="#">About</a></li>
                    <li><a href="#">Contact</a></li>
                    <li><a href="#">Service</a></li>
                </ul>
            </div>
        </nav>
       <div class="header-div">
           <h1 class="header-h1"> Quas architecto non sapiente sunt iste quidem neque commodi, dicta similique ipsam.</h1>
           <div class="hh"><h2  class="header-h2">see more</h2></div>
        </div>
        </header>
        <section class="section-A">
            <div class="A-div">
                <div class="A-div-son-1">
                        <i class="fa fa-address-card" id="font"></i>
                    <h1 class="son-1-h1">Lorem ipsum dolor sit.</h1>
                   <p class="son-1-p">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Laboriosam repellendus ullam id numquam quos et eius provident in animi ea.</p>
               
                </div>
                <div class="A-div-son-2">
                        <i class="fa fa-code" id="font"></i>
                    <h1 class="son-1-h1">Lorem ipsum dolor sit.</h1>
                   <p class="son-1-p">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Laboriosam repellendus ullam id numquam quos et eius provident in animi ea.</p>
               
                </div>
                <div class="A-div-son-3">
                        <i class="fa fa-file-code" id="font"></i>
                    <h1 class="son-1-h1">Lorem ipsum dolor sit.</h1>
                   <p class="son-1-p">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Laboriosam repellendus ullam id numquam quos et eius provident in animi ea.</p>
               
                </div>
            </div>
        </section>
        <section id="section-B">
          <div class="section-B-son">
              <div class="B-son-1">
                  <img src="IMG2.jpg" alt="" id="img3">
                   </div>
              <div class="B-son-2">
                     <h2 id="son-2-h2">lamin fofana</h2>
                     <p id="son-2-h2">Lorem ipsum dolor Lorem ipsum, dolor sit amet consectetur adipisicing elit. Adipisci amet quam explicabo, doloremque debitis sed sunt sapiente quaerat quis optio dolorem reiciendis cupiditate beatae voluptas earum modi aliquam soluta minima dolore odio dicta! sit amet consectetur adipisicing elit. Explicabo omnis voluptates odio nisi quo velit molestias perspiciatis aut inventore iste cumque repellendus reprehenderit, ipsum vero illum iusto quis vel libero!</p>
              </div>
          </div>
        </section>
        <section id="section-C">
            <div class="section-C-son">
                <div class="C-son-1">
                    <img src="24.png" alt="" id="jpg">
                    <h1 id="C-son-h1"> new  dolor.</h1>
                    <p id="C-son-h1">Lorem Lorem ipsum dolor sit, amet consectetur adipisicing elit. Placeat, sed! ipsum dolor sit amet consectetur adipisicing elit. Dignissimos, qui.</p>
                
                </div>
                <div class="C-son-2">
                    <img src="25.png" alt="" id="jpg">
                    <h1 id="C-son-h1"> good prod .</h1>
                    <p id="C-son-h1">Lorem Lorem ipsum dolor sit, amet consectetur adipisicing elit. Placeat, sed! ipsum dolor sit amet consectetur adipisicing elit. Dignissimos, qui.</p>
                
                </div>
                <div class="C-son-3">
                    <img src="26.jpg" alt="" id="jpg">
                    <h1 id="C-son-h1"> ipsum dolor.</h1>
                    <p id="C-son-h1">Lorem Lorem ipsum dolor sit, amet consectetur adipisicing elit. Placeat, sed! ipsum dolor sit amet consectetur adipisicing elit. Dignissimos, qui.</p>
                
                </div>
            </div>
        </section>
         <section class="section-d">
             <div class="d-son">
                 <div class="d-son-child">
                     <img name="lamin" alt="" id="slide-img">
                     <div id="slide">
                         <h5>Lorem, ipsum dolor.</h5>
                         <p id="slide-p">Lorem, Lorem ipsu Molestias non quo reiciendis esse. ipsum dolor sit amet consectetur adipisicing elit. Pariatur veritatis aliquid dolor quisquam, quos vero cupiditate nam eum alias inventore!</p>
                     </div>
                 </div>
             </div>
         </section>
</body>
<script>
    $(document).ready(function(){
        $(".min-1").click(function(){
           $(".min").slideToggle(1000);
        });
    });
    var i = 0;
    var images = [];
    var time = 3000;
    images[0] = '11.jpg';
    images[1] = '14.jpg';
    images[2] = '15.jpg';
    images[3] = '18.jpg';
    images[4] = '17.jpg';
    images[5] = '12.jpg';
    function buba(){
        document.lamin.src = images[i];
        if(i < images.length - 1){
            i++;
        }else{
            i = 0;
        }
        setTimeout("buba()", time);
    }
    window.onload = buba;
</script>
</html>
body{
    margin: 0;
    padding: 0;
    background: #f5f5f5;
    font-family: Arial, Helvetica, sans-serif;
}
header{
   
    height: 100vh;
    width: 100%;
    background-image:url(IMG1.jpg);
    background-size: cover;
    background-position:center;  
}
nav{
    width: 100%;
    display: block;
    position: fixed;
    background: #44444477;
    float: left;
}
.nav-logo{
    width: 100%;
    font-size: 25px;
    padding: 20px 0px;
    display: flex;
     flex-direction: row;
}
.logo{
    
    width: 100%;
    font-size: 25px;
    padding: 1px  10px 0 0 ;
    margin-left: 30px;
    color: #40E0D0;
}
.min-1{
   
    width: 100%;
    font-size: 25px;
    padding: 1px 30px 0 0px ;
    color: #40E0D0;
    display: flex;
    flex-direction: row-reverse;
    
}
.min{
    margin-top: 0px;
    display: none;
}
ul{
    padding: 0px;
}
li{
    padding: 10px 10px;
    list-style: none;
    text-align: center;
}
a{
    text-decoration: none;
    font-size: 20px;
    color: #40E0D0;
    transition: .7s;
}
a:hover{
    color: #f5f5f593

}
.header-div{
    width: 100% ;
    float: left;
}
.hh{
    width: 170px;
    height: auto;
    margin: 0 auto;
}
.header-h1{
    padding: 0 30px;
    margin-top: 30vh;
    text-align: center;
    color: #f5f5f5;
}
.header-h2{
    color: #40E0D0;
    border: 1px solid #40E0D0;
    border-radius: 10px;
    text-align: center;
    padding:  5px 10px ;
    /* margin: 5vh 100px; */
}
                                      /* header */
.section-A{
     width: 100%;
     height: auto;
     background: #c7c7c7;
     float: left;
}
.A-div{
    margin: 50px auto;
    width: 90%;
    height: auto;
    display: grid;
    grid-template-columns: 1fr;
    grid-gap: 1em;
}
#font{
    font-size: 50px;
    color: #40E0D0;
}
.A-div-son-1, .A-div-son-2, .A-div-son-3{
    display: flex;
    flex-direction: column;
align-items: center;
padding: 20px 30px;
text-align: center;
background: #f5f5f5;
border-radius: 10px;
}
                       /* section-A end here */
#section-B{
   width: 100%;
   height: auto;
   float: left;

}
.section-B-son{
    margin: 50px auto;
    width: 90%;
    display: grid;
    grid-template-columns: 1fr;
   
}
.B-son-1{
    width: 100%;
    height: auto;
    border-radius: 10px ;
}
#img3{
    width: 100%;
    height: 100%;
    /* border-radius: 10px; */
    /* border: 3px solid #40E0D0; */
}
#son-2-h2{
    padding-top:0px ;
}
.B-son-2{
    display: flex;
    flex-direction: column;
    align-items:center;
    padding: 10px;
    text-align: center;
    /* border-radius: 10px ; */
    background: #c7c7c7;
    padding:   20px;
    /* border: 3px solid #40E0D0; */
}
                                 /* section-B end here */
#section-C{
    width: 100%;
    height: auto;
    float: left;
    background:#c7c7c7;
 
 }
 .section-C-son{
     margin: 50px auto;
     width: 90%;
     display: grid;
     grid-template-columns: 1fr;
     grid-gap: 1em;
 }
#jpg{
    width: 100%;
    height: 300px;
    border-top-right-radius: 10px ;
    border-top-left-radius: 10px ;
}
 .C-son-1, .C-son-2, .C-son-3{
     /* margin-top: 10px; */
     width: 100%;
    display: flex;
    flex-direction: column;
    align-items: center;
    text-align: center;
    border-radius: 10px ;
    background: #f5f5f5;
}
#C-son-h1{
    padding:  20px;
}
                                    /* section-C end here */
.section-d{
    width: 100%;
    height:auto ;
    float: left;
    background:#f5f5f5;
 
 }
 .d-son{
    margin: 50px auto;
    width: 90%;
    /* float: left; */
    
}
.d-son-child{
    margin: 0 auto;
    width: 100%;
    height: 300px;
    position: relative;
    top: 0;
}
#slide-img{
    border-radius:10px;
    width: 100%;
    height: 100%;
    /* object-fit: cover; */
}
#slide{
    width: 100%;
    height: 100%;
    background: #151616ca;
    border-radius: 10px;
    position: absolute;
    top: 0;
    display: flex;
    justify-content: center;
    flex-direction: column;
    align-items: center;
    
}
#slide-p{
    text-align: center;
    color: #f5f5f5;
    display: flex;
   
    margin-top: 100px;
    padding: 0px 40px;
}
h5{
    border: 3px solid #f5f5f5;
    padding: 10px 15px;
    margin: 10px 0px;
    position: absolute;
    top: 20px;
    color: #fff;
    font-size: 20px;
    font-weight: bold;
    font-family: Arial, Helvetica, sans-serif;
}
h5::before{
    margin-left:90px; 
    border-radius: 5px;
    position: absolute;
    top: -10px;
    content: '';
    width: 20px;
    height: 20px;
    background: #f5f5f5;
}
h5::after{
    content: '';
    border-radius: 5px;
    position: absolute;
    bottom: -10px;
    margin-left: -102px;
    width: 20px;
    height: 20px;
    background: #f5f5f5;
}

@media screen and (min-width: 615px) {
    .header-h2{
        color:#40E0D0;
        border: 2px solid #40E0D0;
        border-radius: 10px;
        text-align: center;
        padding:  5px 10px ;
    }
    .A-div{
        margin: 50px auto;
        width: 90%;
        height: auto;
        display: grid;
        grid-template-columns:  1fr 1fr;
        grid-gap: 1em;
    }
    #font{
        font-size: 50px;
        color: #40E0D0;
    }
    .A-div-son-1, .A-div-son-2, .A-div-son-3{
        display: flex;
        flex-direction: column;
    align-items: center;
    padding: 20px 30px;
    text-align: center;
    background: #f5f5f5;
    border-radius: 10px;
    }
    .section-B-son{
        margin:  50px auto;
        width: 90%;
        height: auto;
        display: grid;
        grid-template-columns:1fr 1fr;
    }
    #son-2-h2{
        padding-top:0px ;
    }
    .section-C-son{
        margin: 50px auto;
        width: 90%;
        display: grid;
        grid-template-columns:1fr  1fr;
        grid-gap: 1em;
    }
    .d-son-child{
        margin: 0 auto;
        width: 100%;
        height: 400px;
        position: relative;
        top: 0;
    }
    #slide-img{
        width: 100%;
        height: 100%;
        object-fit: cover;
    }
    h5{
        border: 3px solid #f5f5f5;
        padding: 10px 15px;
        margin: 100px 0px;
        position: absolute;
        top: 20px;
        color: #fff;
        font-size: 20px;
        font-weight: bold;
        font-family: Arial, Helvetica, sans-serif;
    }
    h5::before{
        margin-left:90px; 
        border-radius: 5px;
        position: absolute;
        top: -10px;
        content: '';
        width: 20px;
        height: 20px;
        background: #f5f5f5;
    }
    h5::after{
        content: '';
        border-radius: 5px;
        position: absolute;
        bottom: -10px;
        margin-left: -102px;
        width: 20px;
        height: 20px;
        background: #f5f5f5;
    }
    
    }
    @media screen and (min-width: 1000px) {
        .header-h2{
            color: #40E0D0;
            border: 2px solid #40E0D0;
            border-radius: 10px;
            text-align: center;
            padding:  5px 10px ;
            /* margin: 5vh 0px; */
        }
        .A-div{
            margin: 50px auto;
            width: 90%;
            height: auto;
            display: grid;
            grid-template-columns: 1fr 1fr 1fr;
            grid-gap: 1em;
        }
        #font{
            font-size: 50px;
            color: #40E0D0;
        }
        .A-div-son-1, .A-div-son-2, .A-div-son-3{
            display: flex;
            flex-direction: column;
        align-items: center;
        padding: 20px 30px;
        text-align: center;
        background: #f5f5f5;
        border-radius: 10px;
        }
        .section-B-son{
            margin:  50px auto;
            width: 90%;
            height: auto;
            display: grid;
            grid-template-columns:1fr 1fr;
        }
        #son-2-h2{
            padding-top:60px ;
        }
        #section-C{
           
            width: 100%;
            height: auto;
            float: right;
            background:#c7c7c7;
         
         }
        .section-C-son{
            margin: 50px auto;
            width: 90%;
            display: grid;
            grid-template-columns: 1fr 1fr 1fr;
            grid-gap: 1em;
        }
        .d-son-child{
            margin: 0 auto;
            width: 100%;
            height: 400px;
            position: relative;
            top: 0;
        }
        #slide-img{
            width: 100%;
            height: 100%;
            object-fit: cover;
        }
        h5{
            border: 3px solid #f5f5f5;
            padding: 10px 15px;
            margin: 100px 0px;
            position: absolute;
            top: 20px;
            color: #fff;
            font-size: 20px;
            font-weight: bold;
            font-family: Arial, Helvetica, sans-serif;
        }
        h5::before{
            margin-left:90px; 
            border-radius: 5px;
            position: absolute;
            top: -10px;
            content: '';
            width: 20px;
            height: 20px;
            background: #f5f5f5;
        }
        h5::after{
            content: '';
            border-radius: 5px;
            position: absolute;
            bottom: -10px;
            margin-left: -102px;
            width: 20px;
            height: 20px;
            background: #f5f5f5;
        }
        
        }
        var slideIndex = 0;
showSlides();

function showSlides() {
  var i;
  var slides = document.getElementsByClassName("mySlides");
  for (i = 0; i < slides.length; i++) {
    slides[i].style.display = "none"; 
  }
  slideIndex++;
  if (slideIndex > slides.length) {slideIndex = 1} 
  slides[slideIndex-1].style.display = "block"; 
  setTimeout(showSlides, 2000); // Change image every 2 seconds
}

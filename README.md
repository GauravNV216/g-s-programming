<!doctype html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="./styles.css">
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-BmbxuPwQa2lc/FVzBcNJ7UAyJxM6wuqIj61tLrc4wSX0szH/Ev+nYRRuWlolflfl" crossorigin="anonymous">
     <!--Google Fonts-->
     <link rel="preconnect" href="https://fonts.gstatic.com">
     <link href="https://fonts.googleapis.com/css2?family=Roboto+Mono&display=swap" rel="stylesheet">
     <link rel="preconnect" href="https://fonts.gstatic.com">
     <link href="https://fonts.googleapis.com/css2?family=Questrial&display=swap" rel="stylesheet">
     <!-- card slider -->
     <!-- <script src="https://code.jquery.com/jquery-3.5.1.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/OwlCarousel2/2.3.4/owl.carousel.min.js"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/OwlCarousel2/2.3.4/assets/owl.carousel.min.css"> -->
    <title>Hello, world!</title>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta2/dist/js/bootstrap.bundle.min.js" integrity="sha384-b5kHyXgcpbZJO/tY9Ul7kGkf1S0CWuKcCD38l8YkeH8z8QjE0GmW1gYU5S9FOnJ0" crossorigin="anonymous"></script>    
  </body>
    <style>
      /* cardslider2 */
.contac{
 display:flex;
 align-items: center;

}
.wrapper{
  width: 100%;

}
.wrapper .carous{
  min-width:1200px;
  margin:auto;
  padding:0 30px;
}
.carous .card{
  height:250px;
  text-align:center;
  color:#fff;
  margin:20px 0;
  box-shadow: 0 4px 15px rgba(0,0,0,0.2);
}
.alert{
  font-size:20px;
  margin:10px;
}
.colo{
    background-color: #4a47a3;
    clip-path:  polygon(0 0,0 100%,80% 100%,30% 0);
    height:35rem;z-index: 0;
    
}
.zin{
  position:relative;
  z-index: 1;
  top:-440px;
}
        .img-text{
width:100%;
height:300px;
display:block;
text-align:center;
padding:40% 5%;
background-color:rgb(255, 217, 0);
color:rgb(3, 3, 0);
border-radius:10px;
}
.img-text h2{
font-size: 25px;
text-transform:uppercase;
letter-spacing:2px;
}
.img-text p{
font-size:14px;
}
.single-box{
position: relative;
margin-bottom: 30px;
}
.img-area{
position: absolute;
width: 100px;
height: 100px;
border:5px solid #fff;
overflow: hidden;
top:15px;
left:150px;
border-radius:100%;
}
.carousel-indicators{
left:0;
top:auto;
bottom:-70px;
}
.carousel-indicators li{
background:#000;
border-radius:50%;
width: 15px;
height:15px;
}
.carousel-indicators .active{
background:#fff;
}
    </style>
  </head>
  <body>
    <!-- preloader -->
  <div class="loading">
   <img src="images/load.gif" >
  </div>
  
      <!-- navbar -->
    <div class="container container-fluid" style="font-family:'Roboto Mono', monospace;">
        <nav class="navbar navbar-expand-lg navbar-light">
            <div class="container-fluid">
              <a class="navbar-brand" href="#" style="font-family:'Roboto Mono', monospace;">G's Programming</a>
              <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
              </button>
              <div class="collapse navbar-collapse justify-content-end mar" id="navbarNav">
                <ul class="navbar-nav">
                  <li class="nav-item">
                    <a class="nav-link active" aria-current="page" href="#">Home</a>
                  </li>
                  <li class="nav-item">
                    <a class="nav-link" href="#">Guides</a>
                  </li>
                  <li class="nav-item">
                    <a class="nav-link" href="#">Reviews</a>
                  </li>
                  
                  <li class="nav-item dropdown">
                    <a class="nav-link dropdown-toggle" href="#" id="navbarDropdownMenuLink" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                      Dropdown link
                    </a>
                    <ul class="dropdown-menu" aria-labelledby="navbarDropdownMenuLink">
                      <li><a class="dropdown-item" href="#">Action</a></li>
                      <li><a class="dropdown-item" href="#">Another action</a></li>
                      <li><a class="dropdown-item" href="#">Something else here</a></li>
                    </ul>
                  </li>
                  <li>
                    <div class="form-check form-switch">
                        <input class="form-check-input" type="checkbox" name="theme" id="flexSwitchCheckChecked">
                        <label class="form-check-label" for="flexSwitchCheckChecked" id="c1">Dark Mode/</label>
                        <label class="form-check-label" for="flexSwitchCheckChecked" id="c2">light Mode</label>
                      </div>
                      
                  </li>
                </ul>
              </div>
            </div>
          </nav></div>
    <!-- topsection -->
   
    <!-- toast -->
    <div class="cont">
        <div class="col1">
            <h1 style="font-family: 'Questrial', sans-serif;">
              <div class="toph" style="color:#4a47a3;" id="demo"></div>
                <div class="toph" style="color:#4a47a3;">The best programing</div> 
                <div class="both" style="color:#4a47a3;margin-bottom: 10px;">guide for beginners</div>
                <button class="btn" style="background-color:rgb(255, 230, 0);padding:5px 20px;margin-bottom: 5px;">Discover</button>
                <br><br>
                <div class="d-flex">       
                <input type="text" class="form-control me-2" name="name" id="name" placeholder="Name...">
                <button class="btn btn-outline-success" onclick="myfun()" id="buth">Submit</button></div>
                <div class="alert alert-success" role="alert">
                  <h4 class="alert-heading">Well done!<button type="button" id="clo"  style="margin-left:200px;height:10px;width: 10px;" class="btn-close"></button></h4>
                  <p style="font-size:15px">Your Name Will Not be saved Any where else.</p>
                  
                </div> 
            </h1><br>
               
        </div>
        <div class="col2"><img src="./images/prg.png" alt="programmer"  style="height:400px;opacity: 0.8;"></div>
    </div><br><br><br>
 <!-- requirements -->
 <h1 style="font-family:'Roboto Mono', monospace;text-align:center;color:#4a47a3;">Required by the industry</h1><br>
 <div class="cont" style="background-color:rgb(255, 230, 0) ;">
     <!-- slide up card 1 -->
     <div class="f1">
            <div class="conta1">
              <div class="cart" id="cart">
                  <div class="cott face face1 ">
                    <h3>1.Web developement</h3>
                     <div class="content">
                         <img src=".." alt="">
                     </div>
                  </div>
                  <div class="face face2">
                     <div class="content">
                         <p>Lorem ipsum dolor sit,
                             amet consectetur adipisicing elit. 
                             Lorem ipsum dolor sit,
                             amet consectetur adipisicing elit. 
                             Lorem ipsum dolor sit,
                             amet consectetur adipisicing elit. 
                                 </p>
                         <a href="#">Read more</a>
                     </div>
                 </div>
              </div>
            </div>     
     </div>
     <!-- slide up card 2 -->
     <div class="f2">
        <div class="conta2">
            <div class="cart" id="cart">
                <div class="cott face face1 ">
                    <h3>2.Machine learning</h3>
                    <div class="content">
                       <img src=".." alt="">
                       
                   </div>
                </div>
                <div class="face face2">
                   <div class="content">
                       <p>Lorem ipsum dolor sit,
                           amet consectetur adipisicing elit. 
                           Lorem ipsum dolor sit,
                           amet consectetur adipisicing elit. 
                           Lorem ipsum dolor sit,
                           amet consectetur adipisicing elit. 
                               </p>
                       <a href="#">Read more</a>
                   </div>
               </div>
            </div>
          </div>     
    </div>
    <!-- slide up card 3 -->
    <div class="f3">
        <div class="conta3">
            <div class="cart" id="cart">
                <div class="cott face face1 ">
                    <h3>3.Data Sience</h3>
                   <div class="content">
                       <img src=".." alt="">
                       
                   </div>
                </div>
                <div class="face face2">
                   <div class="content">
                       <p>Lorem ipsum dolor sit,
                           amet consectetur adipisicing elit. 
                           Lorem ipsum dolor sit,
                           amet consectetur adipisicing elit. 
                           Lorem ipsum dolor sit,
                           amet consectetur adipisicing elit. 
                               </p>
                       <a href="#">Read more</a>
                   </div>
               </div>
            </div>
          </div>   
    </div>
 </div>
 <!-- reviews -->

<h1 style="font-family:'Roboto Mono', monospace;text-align:center;position: relative;top:20px;">Our reviews</h1>
<div class="container colo" id="Abs">

</div>
 <div class="container zin" >
       <div id="carouselExampleIndicators" class="carousel slide" data-bs-ride="carousel">
       <div class="carousel-indicators">
         <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
         <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="1" aria-label="Slide 2"></button>
         <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="2" aria-label="Slide 3"></button>
       </div>
       <div class="carousel-inner">
         <div class="carousel-item active">
           <div class="row">
             <div class="col-md-4">
               <div class="single-box">
                 <div class="img-area"><img src="images/ca-1.jpg" alt="al"></div>
                 <div class="img-text">
                   <h2>Person 1</h2>
                   <p>lorem ipsum dolor sit am lorem ipsum dolor sit am lorem ipsum dolor sit am</p>
                 </div>
               </div>
             </div>
             <div class="col-md-4">
               <div class="single-box">
                 <div class="img-area"><img src="images/ca-2.jpg" alt="al"></div>
                 <div class="img-text">
                   <h2>Person 1</h2>
                   <p>lorem ipsum dolor sit am lorem ipsum dolor sit am lorem ipsum dolor sit am</p>
                 </div>
               </div>
             </div>
             <div class="col-md-4">
               <div class="single-box">
                 <div class="img-area"><img src="images/c-3.jpg" alt="al"></div>
                 <div class="img-text">
                   <h2>Person 1</h2>
                   <p>lorem ipsum dolor sit am lorem ipsum dolor sit am lorem ipsum dolor sit am</p>
                 </div>
               </div>
             </div>
           </div>
         </div>
         <div class="carousel-item">
           <div class="row">
             <div class="col-md-4">
               <div class="single-box">
                 <div class="img-area"><img src="images/c-1.jpg" alt="al"></div>
                 <div class="img-text">
                   <h2>Person 1</h2>
                   <p>lorem ipsum dolor sit am lorem ipsum dolor sit am lorem ipsum dolor sit am</p>
                 </div>
               </div>
             </div>
             <div class="col-md-4">
               <div class="single-box">
                 <div class="img-area"><img src="images/c-2.jpg" alt="al"></div>
                 <div class="img-text">
                   <h2>Person 1</h2>
                   <p>lorem ipsum dolor sit am lorem ipsum dolor sit am lorem ipsum dolor sit am</p>
                 </div>
               </div>
             </div>
             <div class="col-md-4">
               <div class="single-box">
                 <div class="img-area"><img src="images/c-3.jpg" alt="al"></div>
                 <div class="img-text">
                   <h2>Person 1</h2>
                   <p>lorem ipsum dolor sit am lorem ipsum dolor sit am lorem ipsum dolor sit am</p>
                 </div>
               </div>
             </div>
           </div>
         </div>
         <div class="carousel-item">
           <div class="row">
             <div class="col-md-4">
               <div class="single-box">
                 <div class="img-area"><img src="images/c-1.jpg" alt="al"></div>
                 <div class="img-text">
                   <h2>Person 1</h2>
                   <p>lorem ipsum dolor sit am lorem ipsum dolor sit am lorem ipsum dolor sit am</p>
                 </div>
               </div>
             </div>
             <div class="col-md-4">
               <div class="single-box">
                 <div class="img-area"><img src="images/c-2.jpg" alt="al"></div>
                 <div class="img-text">
                   <h2>Person 1</h2>
                   <p>lorem ipsum dolor sit am lorem ipsum dolor sit am lorem ipsum dolor sit am</p>
                 </div>
               </div>
             </div>
             <div class="col-md-4">
               <div class="single-box">
                 <div class="img-area"><img src="images/c-3.jpg" alt="al"></div>
                 <div class="img-text">
                   <h2>Person 1</h2>
                   <p>lorem ipsum dolor sit am lorem ipsum dolor sit am lorem ipsum dolor sit am</p>
                 </div>
               </div>
             </div>
           </div>
         </div>
       </div>   
       <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleIndicators"  data-bs-slide="prev">
         <span class="carousel-control-prev-icon" aria-hidden="true"></span>
         <span class="visually-hidden">Previous</span>
       </button>
       <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleIndicators"  data-bs-slide="next">
         <span class="carousel-control-next-icon" aria-hidden="true"></span>
         <span class="visually-hidden">Next</span>
       </button>
     </div>  
  </div>
<!-- footer -->
<footer style="background-color: #4a47a3;color:White;text-align:center;height:100px;padding:50px;width:100%;"><span>&#169;</span> 2021 Developed by Gaurav N.v</footer>
<script src="./jquery.js"></script>
<script>
var pre = document.querySelector('.loading');
window.addEventListener("load", vanish);
 function vanish(){
   pre.classList.add('disappear');
 }
</script>
  <script>
    function myfun(){
      var a = document.getElementById("name").value;
      document.getElementById("demo").innerHTML = "Welcome  " + a+ " !"; 
      $("div.alert").show();     
    }

  </script>	
 <!-- scripting -->
 <script type="text/javascript" src="./add.js"></script>
    <script>
        $("div.alert").hide();    
        var x = document.querySelector('input[name="theme"]');
        x.addEventListener('change',function(){
            if(this.checked){
                $('body').css('background-color','black');
                $("nav").removeClass(".navbar-light");
                $('')
                $('nav').addClass("navbar-dark");
                $('nav').css('color','white');
                $("#c2").hide();
                $("#c1").show();  
                $("buth").addClass("btn-outline-success");
                $("buth").addClass("btn-outline-light");
                         
            }
            else{
                $('body').css('background-color','white');
                $("nav").addClass(".navbar-light");
                $('nav').removeClass("navbar-dark");
                $('nav').css('color','black');
                $("#c2").show();
                $("#c1").hide(); 
                $("div.alert").hide();         
           }
        })
        $("#clo").click(() =>{
             $("div.alert").hide();
         });
    </script>
 
</html>

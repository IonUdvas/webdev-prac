#webdev prac
<!DOCTYPE html>
<html>
  <head>
    <meta name = "viewport" content="width=device-width, initial-scale=1.0">
          <title>University Website Design - Easy Tutorials</title>   
              <link rel="stylesheet" href="stylesheet.css">  
    <link rel="preconnect" href= "<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@100;200;300;400;600;700&display=swap" rel="stylesheet">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@fortawesome/fontawesome-free@6.1.1/css/fontawesome.min.css ">
</head>
<body>
  <section class="sub-header">
    <nav>
      <a href="index.html"><img src="C:/Users/saumy/OneDrive/pictures/logo.png"></a>
        <div class="nav-links" id="navLinks">
                              <!----i class="fa fa-times" onclick="hideMenu()"----></i>
          <ul>
            <li><a href="">HOME</a></li>
            <li><a href="">ABOUT</a></li>
            <li><a href="">COURSE</a></li>
            <li><a href="">BLOG</a></li>
            <li><a href="">CONTACT </a></li>
            
          </ul>
        </div>
                          <!---i class="fa fa-bars" onclick="showMenu()"---></i>

    </nav>
    <h1>About Us</h1>
                   
                            
  </section>
                                                       <!---------JavaScript for Toggle Menu----->
  <script>
                                                       var navLinks = document.getElementbyId("navLinks");
                                                        function showMenu(){
                                                                           navLinks.style.right = "0";
                                                                                                     }
                                                                                                     function hideMenu(){ 
                                                                          navLinks.style.right = "-200px";
                                                                                                        }
                                                       </script>   
    
    <!---The image and the text were side by side in the original web page but here image is below the text-->
     </section>   
     <section class="about-us">
         <div class="row">
            <div class="about-col">
                <h1>We are World's biggest University</h1> 
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Pellentesque aliquet turpis nulla, elifend faucibus est 
                     sollicitudin ut. Maecenas ut venanatis ex, et dapibus purus.</p>
                     <a href="" class="hero-btn red-btn">Explore Now</a>
             </div>
             <div class="about-col">
                 <img src="C:/Users/saumy/OneDrive/pictures/about.jpg">
             </div>
         </div>
         
     </section>    
      <!---footer----->
      <section class="footer">
        <h4>About Us</h4>
        <p>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Pellentesque aliquet turpis nulla, elifend faucibus est 
            <br> sollicitudin ut. Maecenas ut venanatis ex, et dapibus purus.

        </p>
        <section class="icons">
            
            <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.0.7/css/all.css">
            <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
           <i class="fa fa-facebook"></i>
           <i class="fa fa-instagram"></i>
           <i class="fa fa-twitter"></i>
           <i class="fa fa-instagram"></i>
           
           <p>
               Made with <i class="fa fa-heart-o"></i> Easy Tutorial

           </p>
        </section>                                         
  </body>
  </html>
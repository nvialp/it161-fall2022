# it161-fall2022
IT 161 class work for fall 2022 Seattle Central

<!DOCTYPE html>
<html lang="en">
 <head>
  <title>Nicholas Vialpando's IT161 Portal Website</title>
  <meta name="robots" content="noindex,nofollow" />
  <meta name="viewport" content="width=device-width" />
  <meta charset="utf-8" />
  <link rel="stylesheet" href="css/portal.css" />
  <link rel="stylesheet" href="css/nav.css" />
  <link rel="stylesheet" href="css/forms.css" />
 </head>
 <body>
     <header>
     <h1>Nicholas Vialpando: IT161 Website</h1>
     <nav class="topnav" id="myTopnav">
       <a href="index.html" class="active">Welcome</a>
       <a href="elements.html">HTML Elements</a>
       <a href="aia.html">AIA</a>
       <a href="big/index.html">BIG</a>
       <a href="http://w3schools.com" target="_blank">W3 Schools</a>
       <a href="https://www.linkedin.com/learning/" target="_blank">LinkedIn Learning</a>
       <a href="flowchart.html">Flowchart</a>
       <a href="fp/index.html">Final Project</a>
       <a href="contact.php">Contact Nick</a>
       <a href="javascript:void(0);" class="icon" onclick="myFunction()">&#9776;</a>
     </nav>
     </header>
     
   <div class="wrapper">

     <img class="desktop" src="images/desktop.png" alt="Photo of Nicholas Vialpando" />
       
     <img class="tablet" src="images/tablet.png" alt="Photo of Nicholas Vialpando" />
       
     <img class="phone" src="images/phone.png" alt="Photo of an Nicholas Vialpando" />
       
       <h2 class="subheader">A little about me!</h2>
       
       <p>Army veteran originally from New Mexico but was stationed at Fort Lewis.</p>
       <p>Currently studying software development at Seattle Central, as well as finishing a bachelors in computer egineering</p>
       <p>I have taken classes in 3 other languages so far, those being c, c++, and python.</p>
       
     <footer>
      <p><small>&copy; 2022 by 
          <a href="contact.php">Nicholas Vialpando</a>, All Rights Reserved ~ 
          <a id="html-checker" href="#">Check HTML</a> ~ 
          <a id="css-checker" href="#">Check CSS</a></small>
     </p>
    </footer>
  </div>
     
  <!-- Toggle between adding and removing the "responsive" class to topnav when the user clicks on the icon -->
     
  <script>
    //https://tinyurl.com/dynamic-html-checker
    document.getElementById("html-checker").setAttribute("href","https://validator.w3.org/nu/?doc=" + location.href);
      
    document.getElementById("css-checker").setAttribute("href","https://jigsaw.w3.org/css-validator/validator?uri=" + location.href);  
    
    //manages mobile nav 
    function myFunction() {
        var x = document.getElementById("myTopnav");
        if (x.className === "topnav") {
            x.className += " responsive";
        } else {
            x.className = "topnav";
        }
    }   
 </script>
     
 </body>
</html>

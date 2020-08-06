# My-Portfolio
# Style

body,html{
    height: 100%;
    margin-top: 0px;
    
} 
.hello{
    width:100%;
    height:100%;
    background-color: aqua;
     background: url('surya.jpg');
    background-repeat: no-repeat;
    background-position: center;
    background-size:cover;
    background-attachment: fixed; 
}


html,body{
    font-family: 'Source Sans Pro', sans-serif;
    margin: 0;
    padding: 0;
  }
  .graph-cont{
    width: calc(100% - 40px);
    width: 100%;
    max-width: 800px;
    margin: 0 auto;
  }
  h1,h2,h3{
    text-align: center;
    color: #34495e;
  }
  .bar{
    height: 30px;
    max-width: 800px;
    margin: 0 auto 10px auto;
    line-height: 30px;
    font-size: 16px;
    color: white;
    padding: 0 0 0 10px;
    position: relative;
  }
  .bar::before{
    content: '';
    width: 100%;
    position: absolute;
    left: 0;
    height: 30px;
    top: 0;
    z-index: -2;
    background: #ecf0f1;
  }
  .bar::after{
    content: '';
    background: #2ecc71;
    height: 30px;
    transition: 0.7s;
    display: block;
    width: 100%;
    -webkit-animation: bar-before 1 1.8s;
    position: absolute;
    top: 0;
    left: 0;
    z-index: -1;
  }
  .bar1::after{
    max-width: 80%;
  }
  .bar2::after{
    max-width: 85%;
  }
  .bar3::after{
    max-width: 75%;
  }
  .bar4::after{
    max-width: 45%;
  }
  @-webkit-keyframes bar-before{
    0%{
      width: 0px;
    }
    100%{
      width: 100%;
    }
  }
  
  .how-cont{
    width: calc(100% - 40px);
    width: 100%;
    max-width: 800px;
    margin: 0 auto;
  }
  code {
    padding: 5px;
    background: #ecf0f1;
    display: block;

#navbar.php
</head>
<body>
<nav class="navbar navbar-expand-lg navbar-dark bg-primary">
<i class="fas fa-graduation-cap" style="font-size:48px;color:red;"></i> 
  <a class="navbar-brand" href="#">Suryansh Pratap Singh</a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>

  <div class="collapse navbar-collapse" id="navbarSupportedContent">
    <ul class="navbar-nav mr-auto">
      <li class="nav-item active">
        <a class="nav-link" href="index.php">Home <span class="sr-only">(current)</span></a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="myresume.php">My resume</a>
      </li>
      <li class="nav-item dropdown">
        <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
          Dropdown
        </a>
        <div class="dropdown-menu" aria-labelledby="navbarDropdown">
          <a class="dropdown-item" href="project/project.php">My project</a>
          <a class="dropdown-item" href="education/education.php">My education</a>
          <a class="dropdown-item" href="hobbies/hobbies.php"> My hobbies</a>
          <a class="dropdown-item" href="to do/mytodo.php">MY to-do list</a>
          
        </div>
      </li>
      <li class="nav-item">
        <a class="nav-link disabled" href="#" tabindex="-1" aria-disabled="true">Disabled</a>
      </li>
    </ul>
   
  </div>
</nav>


# worhspace.php
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <!-- CSS only -->
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/css/bootstrap.min.css" integrity="sha384-9aIt2nRpC12Uk9gS9baDl411NQApFmC26EwAOH8WgZl5MYYxFfc+NcPb1dKGj7Sk" crossorigin="anonymous">

<!-- JS, Popper.js, and jQuery -->
<script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js" integrity="sha384-Q6E9RHvbIyZFJoft+2mJbHaEWldlvI9IOYy5n3zV9zzTtmI3UksdQRVvoxMfooAo" crossorigin="anonymous"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/js/bootstrap.min.js" integrity="sha384-OgVRvuATP1z7JjHLkuOU7Xw704+h835Lr+6QL9UvYjZE3Ipu6Tp75j7Bh/kR0JKI" crossorigin="anonymous"></script>
    
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="https://fonts.googleapis.com/css2?family=Dancing+Script:wght@700&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Merriweather:ital,wght@0,700;1,700&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Libre+Caslon+Text&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Merriweather:wght@700&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Merriweather:wght@700&display=swap" rel="stylesheet">

    <!--font aweswom link-->
<script src="https://kit.fontawesome.com/657cfbfe0e.js" crossorigin="anonymous"></script>

    <title>My Portfolio</title>


#body.css
body,html{
    height: 100%;
    margin-top: 0px;
    
} 

 .hello{ 
    width:100%;
    height:500px;
    background-color: aqua;
    /* background: url('surya.jpg');
    background-repeat: no-repeat;
    background-position: center;
    background-size:cover;
    background-attachment: fixed; */
} 
.word{
    font-family: 'Merriweather', serif;
}
.intro{
    font-family: 'Merriweather', serif;
}

    
/*background: url(image/ankur.jpg);
height: 80%;
background-position: center;
background-repeat: no-repeat;
background-size: cover;
}*/
    
     
 

#footer.php

<br><br>
<!-- Footer -->
<footer class="page-footer font-small blue bg-primary" style="color: white;">

  <!-- Copyright -->
  <div style="float: left;"><h3 style="color:dark;">Contact:-9336156564</h3></div><br><br>

  <div style="float: left;"><h3 style="color:dark;">E-Mail:-<a href="https://mail.google.com" style="color:white;">suryanshpratapsingh340@gmail.com</a></h3></div><br><br>
  <div style="float: left;"><h3 style="color:dark">Address:-120 Indira Nagar ,Behind Doodh Dairy Building ,Raibareli,
  Uttar Pradesh,INDIA</h3></div><br><br>
  <div class="footer-copyright text-center py-3 "><h5>© 2020 Copyright: Suryansh Pratap Singh</h5>
    
  </div>
  <!-- Copyrit -->

</footer>

</body>
</html>
<!-- Footer -->


#index.php
<?php require 'workspace.php'?>
<link rel="stylesheet" href="style.css">
   

<?php require 'navbar.php'?>

    <!-- <div class="hello">
        
    <h1 class="jumborton"style="color:black;float:center;font-family: 'Dancing Script', cursive;">
            Hello!This is Suryansh
     </h1>
    </div> -->


    <!-- flip carsd
    <div class="flip-card">
  <div class="flip-card-inner">
    <div class="flip-card-front">
    

<img src="1.jpg" alt="hi" class="col-md-7 align-self-center img-thumbnail">

     <div class="row justify-content-center">

<img src="1.jpg" alt="hi" class="col-md-7 img-thumbnail">
</div> -->
 <!-- <img src="1.jpg" alt="Avatar" style="width:300px;height:300px;"> --> 
    <!-- </div>
    <div class="flip-card-back">
      <h1>John Doe</h1>
      <p>Architect & Engineer</p>
      <p>We love that guy</p>
    </div>
  </div>
</div> -->


<!-- Rotating card -->
<div class="card-wrapper">
  <div id="card-1" class="card card-rotating text-center">

    <!-- Front Side -->
    <div class="face front">

      <!-- Image-->
      <div class="card-up">
        <img class="card-img-top" src="https://mdbootstrap.com/img/Photos/Others/photo7.jpg" height="500px" alt="Image with a photo of clouds.">
      </div>

      <!-- Avatar -->
      <div class="avatar mx-auto white"><img src="surya.jpg" class="rounded-circle" height="200px"
          alt="Sample avatar image.">
      </div>

      <!-- Content -->
      <div class="card-body">
        <h4 class="font-weight-bold mb-3">Suryansh Pratap Singh</h4>
        <p class="font-weight-bold blue-text">Software Developer
            <br>
            -Enthusiast
        </p>
        <!-- Triggering button -->
        <!-- <a class="rotate-btn" data-card="card-1"><i class="fas fa-redo-alt"></i> Click here to rotate</a> -->
      </div>
    </div>
    <!-- Front Side -->

    <!-- Back Side -->
    <div class="face back">
      <div class="card-body">

        <!-- Content -->
        <h4 class="font-weight-bold mb-0">About me</h4>
        <hr>
        <p>
        <!-- I'm a full stack web developer who can develope both front and back ends of a website or application
       -meaning I can tackel projects that involve databases,building user-facing website or 
       even work with client during the planning phase of projects 
       .In addition to mastering C++,Data Structure and Algorithms I can solve problems efficiently.
        So,please check my resume and feel free to contact me.I am always avilable for you. -->
        Keen to learn and apply new and advance technologies in order to make the life of people around me easier.
        In addition to mastering <b>C++,JAVA,Data stuctures and Algorithms</b> I can solve problems efficiently.
        I am also a team player with good leadership &team management skill.
          
          <!-- Social Icons -->
          <!-- <ul class="list-inline py-2">
            <li class="list-inline-item"><a class="p-2 fa-lg fb-ic"><i class="fab fa-facebook-f"></i></a></li>
            <li class="list-inline-item"><a class="p-2 fa-lg tw-ic"><i class="fab fa-twitter"></i></a></li>
            <li class="list-inline-item"><a class="p-2 fa-lg gplus-ic"><i class="fab fa-google-plus-g"></i></a></li>
            <li class="list-inline-item"><a class="p-2 fa-lg li-ic"><i class="fab fa-linkedin-in"></i></a></li>
          </ul>
        Triggering button -->
          <!-- <a class="rotate-btn" data-card="card-1"><i class="fas fa-undo"></i> Click here to rotate back</a> --> 

      </div>
    </div>
    <!-- Back Side -->

  </div>
</div>
<!-- Rotating card -->



<!-- Skill Meter -->
<link href='https://fonts.googleapis.com/css?family=Source+Sans+Pro:300,400' rel='stylesheet' type='text/css'>

<div class="graph-cont">
  <h1>MY SKILLS </h1>
  <h3> C++</h3>
  <div class="bar bar2">85%</div>
  
  <h3> JAVA</h3>
  <div class="bar bar1">80%</div>
  <h3> Data Structures</h3>
  <div class="bar bar3">75%</div>
  <h3> Algorithms</h3>
  <div class="bar bar4">45%</div>
  
</div>
<div class="how-cont">
  
 
</div>
<div class="card-deck">
  <div class="card">
    <img class="card-img-top" src="blogs.jpg" alt="Card image cap">
    <div class="card-body">
      <h5 class="card-title">MY BLOGS</h5>
      <p class="card-text">This is a longer card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
      <a href="project/project.php" class="btn btn-info ">My blogs</a>
      <p class="card-text"><small class="text-muted">Last updated 3 mins ago</small></p>
    </div>
  </div>
  <div class="card">
    <img class="card-img-top" src="achivements.jpg" alt="Card image cap">
    <div class="card-body">
      <h5 class="card-title">MY ACHIVEMENTS</h5>
      <p class="card-text">This card has supporting text below as a natural lead-in to additional content.</p>
      <a href="project/project.php" class="btn btn-danger">My Achivements</a>
      <p class="card-text"><small class="text-muted">Last updated 3 mins ago</small></p>
    </div>
  </div>
  <div class="card">
    <img class="card-img-top" src="resume.jpg" alt="Card image cap">
    <div class="card-body">
      <h5 class="card-title">MY RESUME</h5>
      
      <p class="card-text">This is a wider card with supporting text below as a natural lead-in to additional content. This card has even longer content than the first to show that equal height action.</p>
      <a href="project/project.php" class="btn btn-warning">My Resume</a>
      <p class="card-text"><small class="text-muted">Last updated 3 mins ago</small></p>
    </div>
  </div>
</div>
   <?php require 'footer.php'?>

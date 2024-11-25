<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
    <link rel="stylesheet" href="https://www.w3schools.com/lib/w3-colors-flat.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <link rel="stylesheet" href="style.css">
  <style>
    {font-family: "Montserrat", sans-serif}
  body {
  background-color: LavenderBlush;
  } 

  .container {
  position: relative;
  width: 50%;
}

.image {
  opacity: 1;
  display: block;
  width: 100%;
  height: auto;
  transition: .5s ease;
  backface-visibility: hidden;
}

.middle {
  transition: .5s ease;
  opacity: 0;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  -ms-transform: translate(-50%, -50%);
  text-align: center;
}

.container:hover .image {
  opacity: 0.3;
}

.container:hover .middle {
  opacity: 1;
}

.text {
  background-color: #800000;
  color: white;
  font-size: 16px;
  padding: 16px 32px;
}

.container2 {
  position: relative;
  width: 50%;
}

.container2 .image {
  opacity: 1;
  display: block;
  width: 100%;
  height: auto;
  transition: .5s ease;
  backface-visibility: hidden;
}

.container2 .middle {
  transition: .5s ease;
  opacity: 0;
  position: absolute;
  top: 60%;
  left: 150%;
  transform: translateY(-50%); 
  width: 80%;
  height: 15vh;
  text-align: center;
}

.container2:hover .image {
  opacity: 0.3;
}

.container2:hover .middle {
  opacity: 1;
  transform: translate(-50%, -50%) scale(1); 
}

.container2 .text {
  background-color: #800000;
  color: white;
  font-size: 16px;
  padding: 16px 32px;
}

.container3 {
  position: relative;
  width: 50%;
}

.container3 .image {
  opacity: 1;
  display: block;
  width: 100%;
  height: auto;
  transition: .5s ease;
  backface-visibility: hidden;
}

.container3 .middle {
  transition: .5s ease;
  opacity: 0;
  position: absolute;
  top: 60%;
  left: 50%;
  transform: translateY(-50%); 
  width: 80%;
  height: 15vh;
  text-align: center;
}

.container3:hover .image {
  opacity: 0.3;
}

.container3:hover .middle {
  opacity: 1;
  transform: translate(-50%, -50%) scale(1); 
}

.container3 .text {
  background-color: #800000;
  color: white;
  font-size: 16px;
  padding: 16px 32px;
}

.container4 {
  position: relative;
  width: 50%;
}

.container4 .image {
  opacity: 1;
  display: block;
  width: 100%;
  height: auto;
  transition: .5s ease;
  backface-visibility: hidden;
}

.container4 .middle {
  transition: .5s ease;
  opacity: 0;
  position: absolute;
  top: 60%;
  left: 150%;
  transform: translateY(-50%); 
  width: 80%;
  height: 15vh;
  text-align: center;
}

.container4:hover .image {
  opacity: 0.3;
}

.container4:hover .middle {
  opacity: 1;
  transform: translate(-50%, -50%) scale(1); 
}

.container4 .text {
  background-color: #800000;
  color: white;
  font-size: 16px;
  padding: 16px 32px;
}


  </style>
    <title>Lyra Ashley</title>
</head>
<body>
    <header class="header" id="top">
        <div class="w3-top">
            <div class="w3-bar w3-flat-midnight-blue w3-card header">
              <a class="w3-bar-item w3-button w3-padding-large w3-hide-medium w3-hide-large w3-right" href="javascript:void(0)" onclick="myFunction()" title="Toggle Navigation Menu"><i class="fa fa-bars"></i></a>
              <a href="#top" class="w3-bar-item w3-button w3-padding-large " >Lyra Ashley Embalsado</a>
              <span class="w3-right">

             
              <a href="#about" class="w3-bar-item w3-button w3-padding-large w3-hide-small">About Me</a>
              <a href="#hai" class="w3-bar-item w3-button w3-padding-large w3-hide-small">Hobbies and Interests</a>
              <a href="#skills" class="w3-bar-item w3-button w3-padding-large w3-hide-small">Skills</a>
              <a href="#paa" class="w3-bar-item w3-button w3-padding-large w3-hide-small">Projects and Activities</a>
              <a href="#achievements" class="w3-bar-item w3-button w3-padding-large w3-hide-small">Achievements</a>
              <a href="#contact" class="w3-bar-item w3-button w3-padding-large w3-hide-small">Contact Information</a>
            </span>
            </div>
          </div>
  
          <!-- Navbar on small screens (remove the onclick attribute if you want the navbar to always show on top of the content when clicking on the links) -->
          <div id="navDemo" class="w3-bar-block w3-black w3-hide w3-hide-large w3-hide-medium w3-top" style="margin-top:46px">
            <a href="#about" class="w3-bar-item w3-button w3-padding-large" onclick="myFunction()">About Me</a>
            <a href="#hai" class="w3-bar-item w3-button w3-padding-large" onclick="myFunction()">Hobbies and Interests</a>
            <a href="#skills" class="w3-bar-item w3-button w3-padding-large" onclick="myFunction()">Skills</a>
            <a href="#paa" class="w3-bar-item w3-button w3-padding-large" onclick="myFunction()">Projects and Activities</a>
            <a href="#achievements" class="w3-bar-item w3-button w3-padding-large" onclick="myFunction()">Achievements</a>
            <a href="#contact" class="w3-bar-item w3-button w3-padding-large" onclick="myFunction()">Contact Information</a>
          </div>
    </header>

<main>

  <div class="container">
  <img src="https://scontent.fmnl33-3.fna.fbcdn.net/v/t39.30808-6/399339756_2151448165187334_6825057760884249484_n.jpg?_nc_cat=104&ccb=1-7&_nc_sid=cc71e4&_nc_eui2=AeFgbCW71QEDbBm-zoW1Iu5x04twUUXboQTTi3BRRduhBM-ncSdp9qWJhcGKASFBVzMB6l4_9zZKe8wZD--UnMA0&_nc_ohc=Jkecm29SshgQ7kNvgF5rkB8&_nc_zt=23&_nc_ht=scontent.fmnl33-3.fna&_nc_gid=AbYzG3s0d7vNaVDUtWHh3c7&oh=00_AYAbKpKsVYXhg-8XqG78zsc7zwJnKmN-yA4_pT1qXEFm0A&oe=6748EEC4" alt="image" class="image" style="width:200%">
  <div class="middle">
    <div class="text">LEAD BY EXAMPLE
      "True advocacy begins with leading by example—let your actions speak louder than words, and inspire others to follow through the values you live by." — LAUE
    </div>
  </div>
</div>
  </main>

  <section>
  <div class="w3-container w3-padding-large" style="margin-bottom:20px" >
   <div class="w3-container" id="about">
  <div class="w3-content" style="max-width:1300px">
    <h2 class="w3-center w3-large">MAGANDANG BUHAY! I'm Lyra Ashley U. Embalsado, a 19-year-old student from Caloocan City, currently pursuing a Bachelor of Science in Information Technology at the University of the East Caloocan, While my studies equip me with the technical skills to navigate the digital world, my passion lies in using those skills, along with my voice, to advocate for children's rights and well-being. I believe in leading by example-whether It's through actively participating in child-centered projects, representing young people in initiatives focused on education and empowerment, or simply being a role model for others to follow. For me, it's not just about earning a degree; it's about demonstrating that each of us has the power to create change. By combining my knowledge and my dedication to service, I aim to inspire others to step up and make a lasting, positive Impact on the lives of children and future generations. 
  </section>

  <!-- Hobbies and Interests-->
<div class="w3-midnight-blue" id="hai">
  <div class="w3-container ">
    <h2 class="section-text-header" style="margin-top: 0px !important; font-weight: 800">Hobbies and Interests</h2>
  </div>

<div class="container2">
  <img src="https://i.pinimg.com/736x/90/b7/c9/90b7c9795b82dc53d1b946443a6473f0.jpg" alt="Image" class="image" style="width:200%">
  <div class="middle">
    <div class="text">The Promised Neverland is a Japanese manga series written by Kaiu Shirai and illustrated by Posuka Demizu. It was serialized in Shueisha's Weekly Shōnen Jump from August 2016 to June 2020, with its chapters collected in 20 tankōbon volumes. The series follows three gifted kids at an isolated idyllic orphanage who discover the secret and sinister purpose they were raised for, and look for a way to escape from their evil caretaker and lead the other children in a risky escape plan</div>
  </div>
</div> 

<div class="container3">
  <img src="https://i.pinimg.com/736x/a6/5c/c7/a65cc7ccf913b6d87731d92e778d6cee.jpg" alt="Image" class="image" style="width:200%">
  <div class="middle">
    <div class="text">Fifteen-year-old Ichigo Kurosaki is a typical teen with fighting skills, two caring sisters and a special trait: he can see ghosts. However, when Ichigo and his family find themselves under attack by a huge beast, Ichigo discovers that there’s more to the supernatural world than the everyday specter. Ichigo must now adjust to his new life of both vanquishing and saving souls for the sake of Soul Society. </div>
  </div>
</div> 

<div class="container4">
  <img src="https://i.pinimg.com/736x/e8/df/93/e8df9377ac24800e8023625bde1ad44d.jpg" alt="Image" class="image" style="width:200%">
  <div class="middle">
    <div class="text">The Untamed (Chinese: 陈情令; pinyin: Chén Qíng Lìng) is a 2019 Chinese television series adapted from the danmei novel Mo Dao Zu Shi by Mo Xiang Tong Xiu, starring Xiao Zhan and Wang Yibo. It follows the adventures of two soulmate cultivators who travel to solve a series of mysteries that link to a tragic event in the past. </div>
  </div>
</div> 

   <!-- Skills-->
<div class="w3-midnight-blue" id="skills">
  <div class="w3-container ">
    <h2 class="section-text-header" style="margin-top: 0px; margin-bottom: 20px; font-weight: 800">Skills</h2>
  </div>

<p style="margin: 0 30px; margin-bottom: 10px;">ADAPTABILITY</p>
  <div style="width: calc(100% - 40px); margin: 0 30px; background-color: LavenderBlush;">
    <div style="text-align: right; padding-top: 10px; padding-bottom: 10px; color: white; width: 95%; background-color: maroon; margin-bottom: 20px">95%</div>
  </div>

<p style="margin: 0 30px; margin-bottom: 10px;">PROBLEM SOLVING</p>
  <div style="width: calc(100% - 40px); margin: 0 30px; background-color: LavenderBlush;">
    <div style="text-align: right; padding-top: 10px; padding-bottom: 10px; color: white; width: 90%; background-color: SlateGrey; margin-bottom: 20px">90%</div>
  </div>

<p style="margin: 0 30px; margin-bottom: 10px;">DIGITAL ILLUSTRATION</p>
  <div style="width: calc(100% - 40px); margin: 0 30px; background-color: LavenderBlush;">
    <div style="text-align: right; padding-top: 10px; padding-bottom: 10px; color: white; width: 90%; background-color: Maroon; margin-bottom: 20px">90%</div>
  </div>

<p style="margin: 0 30px; margin-bottom: 10px;">CONTENT CREATION</p>
  <div style="width: calc(100% - 40px); margin: 0 30px; background-color: LavenderBlush;">
    <div style="text-align: right; padding-top: 10px; padding-bottom: 10px; color: white; width: 85%; background-color: SlateGrey; margin-bottom: 20px">85%</div>
  </div>

<p style="margin: 0 30px; margin-bottom: 10px;">COMMUNICATION</p>
  <div style="width: calc(100% - 40px); margin: 0 30px; background-color: LavenderBlush;">
    <div style="text-align: right; padding-top: 10px; padding-bottom: 10px; color: white; width: 80%; background-color: Maroon; margin-bottom: 20px">80%</div>
  </div>

   <!-- Projects and Activities-->
<div class="w3-midnight-blue" id="paa">
  <div class="w3-container ">
    <h2 class="section-text-header" style="margin-top: 0px; margin-bottom: 20px; font-weight: 800">PROJECTS AND ACTIVITIES</h2>
  </div>

  <!-- Achievements-->
<div class="w3-midnight-blue" id="achievements">
  <div class="w3-container ">
    <h2 class="section-text-header" style="margin-top: 0px; margin-bottom: 20px; font-weight: 800">ACHIEVEMENTS</h2>
  </div>

  <!-- Contact Information-->
<div class="w3-midnight-blue" id="contact">
  <div class="w3-container ">
    <h2 class="section-text-header" style="margin-top: 0px; font-weight: 800">CONTACT INFORMATION</h2>
  </div>

  <div class="w3-center contact" id="contact">
    <div class="w3-left-align w3-margin-top contact-info">
      <h3 style="font-weight: 800;" class="contact-head">GET IN TOUCH</h3>
      <p>Feel free to reach out for collaborations, opportunities, or just to connect!</p>

      <h4 style="font-weight: 600;">Follow Me</h4>
      <i class="fa fa-facebook-official w3-hover-opacity icons"></i>
      <i class="fa fa-github w3-hover-opacity icons"></i>
    </div>

    <div class="w3-left-align w3-margin-top contact-info">
      <h3 style="font-weight: 600;">CONTACT INFO</h3>
      <p><i class="fa fa-phone" style="margin-right: 8px; font-size: 20px;"></i> +63 9369474474</p>
      <p><i class="fa fa-envelope" style="margin-right: 5px; font-size: 20px;"></i> embalsado.lyraashley@ue.edu.ph</p>
    </div>
  </div>
</div>




  <div class="w3-flat-midnight-blue w3-padding w3 w3-center w3-margin-top">
    <p>Powered by W3.css</p>
  </div>
    <script>
        function myFunction() {
          var x = document.getElementById("navDemo");
          if (x.className.indexOf("w3-show") == -1) {
            x.className += " w3-show";
          } else { 
            x.className = x.className.replace(" w3-show", "");
          }
        }
    </script>
</body>
</html>

# IEEEVITBHOPAL_BLH26_Synchronousbyte
<!DOCTYPE html>

<html lang="en">

<head>

<meta charset="UTF-8">

<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Mental Health Support</title>

<link rel="stylesheet" href="style.css">

</head>

<body>

<div class="container">

<div class="form-box">

<h1 class="title">REGISTER</h1>

<h1 class="title">To</h1>

<h1 class="title">TruHeal</h1>

<form>

<!-- <div class="input-group">

<div class="input-field" id="nameField">

<i class="fa-solid fa-user"></i>

<input type="text" placeholder="Name">


</div>

<div class="input-field">

<i class="fa-solid fa-envelope"></i>

<input type="email" placeholder="Email">


</div>

<div class="input-field">

<i class="fa-solid fa-lock"></i>

<input type="password" placeholder="Password">


</div>-->

</div>

<div class="btn-field">

<a href="second.html">

<button type="button" id="signupBtn">Sign Up</button>

</a>

<button type="button" id="signinBtn"class="disable">Sign In</button>



</div>

</form>

</div>

</div>

<script>

let signupBtn=document.getElementById("signupBtn");

let signinBtn=document.getElementById("signinBtn");

let nameField=document.getElementById("nameField");

let title=document.getElementById("title");

signinBtn.onclick=function(){

nameField.style.maxHeight="0";

title.innerHTML="Sign In";

signupBtn.classList.add("disable");

signinBtn.classList.remove("disable");

}

signupBtn.onclick=function(){

nameField.style.maxHeight="60px";

title.innerHTML="Sign Up";

signupBtn.classList.remove("disable");

signinBtn.classList.add("disable");

}


</script>

</body>

</html>

<!DOCTYPE html>

<html lang="en">

<head>

<meta charset="UTF-8">

<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Sign_up</title>

<link rel="stylesheet" href="style.css">

</head>

<style>

.con{

width: 100vw;

height:100vh;

background-image:linear-gradient(rgba(0,0,50,0.8),rgba(0,0,50,0.8)),url('https://i0.wp.com/takeitpersonelly.com/wp-content/uploads/2021/02/five-practical-ways-to-support-your-mental-health-as-a-busy-professional.jpg?ssl=1');

background-size: cover;

background-position: center;

position: relative;

}


.sign{

height:70% ;

width:30% ;

background-color: white;

margin-left: 35%;

margin-top: 7%;

position: absolute;

}


h1{
margin-top: 50px;

margin-left: 15px;

font-size: 30px;

}


.det{

 border: 0px;

 height: 50px;

 width: 300px;

 background-color: rgb(222, 217, 217);

 padding: 18px 15px;

 font-size: 15px;

 margin-left: 55px;

}


#sign_up{

border: 0px;

margin-left: 188px;

font-size: 20px;

/* border-radius: 45%; */

background-color: skyblue;

}



</style>

<body>

<div class="con">

<div class="sign">

<h1>Sign Up</h1>

<br>


<div class="number">

<input class="det" type="number" placeholder="Mobile Number">

</div>

<br>

<div class="name">

<input class="det" type="text" placeholder="Full Name">

</div>

<br>


<div class="passcode">

<input class="det" type="text" placeholder=" Set-Password">

</div>

<br>

<br>

<br>

<div class="sig">

<a href="third.html">


<button id="sign_up">Sign Up</button>

</a>

</div>

</div>

</div>

</body>

</html>

<!DOCTYPE html>

<html lang="en">

<head>

<meta charset="UTF-8">

<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>sign_in</title>

<link rel="stylesheet" href="style.css">

</head>

<style>

*{

margin: 0px;

padding: 0px;

}




.contain{

width: 100vw;

height:100vh;

background-image: linear-gradient(rgba(0,0,50,0.8),rgba(0,0,50,0.8)),url('https://i0.wp.com/takeitpersonelly.com/wp-content/uploads/2021/02/five-practical-ways-to-support-your-mental-health-as-a-busy-professional.jpg?ssl=1');

background-size: cover;

background-position: center;

position: relative;

}


.sign_in{

height: 60%;

width: 30%;

background-color: white;

margin-left: 35%;

margin-top: 10%;

position: absolute;

}


h1{

margin-left: 15px;

font-size: 30px;

margin-bottom: 60px;

margin-top: 30px;

position: relative;

}


.details{

border: 0px;

height: 50px;

width: 300px;

background-color: rgb(222, 217, 217);

padding: 18px 15px;

font-size: 15px;

margin-left: 55px;

} 

#sign_in{

border: 0px;

margin-left: 188px;

font-size: 20px;

/* border-radius: 45%; */

background-color: skyblue;

}

</style>

<body>

<div class="contain">

<div class="sign_in">

<h1>Sign In</h1>


<div class="num">

<input class="details" type="number" placeholder="Mobile Number:">

</div>

<br>

<div class="pass">

<input class="details" type="text" placeholder="Password:">

</div>

<br>

<br>

<br>

<div class="in">

<a href="fourth.html">


<button id="sign_in">Sign In</button>

</a>

</div>

</div>




</div>

</body>

</html>
<!DOCTYPE html>

<html lang="en">

<head>

<meta charset="UTF-8">

<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Question Form</title>

</head>

<style>

body {

font-family: Arial, sans-serif;

display: flex;

justify-content: center;

align-items: center;

height: 140vh;

margin: 0;

background-color: #f4f4f4;

background-size: cover;

position:relative;

background-image:url('https://www.acpcpsychology.com.au/cmsAdmin/uploads/shutterstock_1112857520.jpg');

}


.container {

background: white;

padding: 20px;

border-radius: 8px;

box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);

width: 300px;

}


h1 {

margin-bottom: 20px;

font-size: 24px;

text-align: center;

}


form {

display: flex;

flex-direction: column;

}


label {

margin-top: 10px;

}


input[type="text"], input[type="number"] {

padding: 8px;

margin-top: 5px;

border: 1px solid #ccc;

border-radius: 4px;

}


button {
height:30px;
margin-top: 20px;

border: none;

border-radius: 4px;

background-color: #28a745;

color: white;

cursor: pointer;
width: 300px;

}


button:hover {

background-color: #218838;

}


#result {

margin-top: 20px;

font-size: 18px;

color: #333;

}

</style>





<body>

<div class="container">

<h1>QUESTIONNAIRE</h1>

<br>

<form id="questionForm">

<label for="question1">How are you feeling right now?</label>

<input type="text" id="question1" name="name" required>

<br>

<label for="question2">Could you describe the event that has traumatized you?</label>

<input type="text" id="question2" name="age" required>

<br>

<label for="question3">Do you ever have nightmares about the event?</label>

<input type="text" id="question3" name="color" required>

<br>

<label for="question4">Do you ever get flashbacks? If yes,what actions do you perform to control them?</label>

<input type="text" id="question3" name="color" required>

<br>

<label for="question5">Do you feel alone around your friends and family? If yes, try to explain your feelings.</label>

<input type="text" id="question3" name="color" required>

<br>

<label for="question6">Has the trauma affected your interest in activites? If yes, How?</label>

<input type="text" id="question3" name="color" required>

<br>

<label for="question7">Tell us the difference between before and after that event in yourself.</label>

<input type="text" id="question3" name="color" required>
<div class="submit"></div>
</form>
<a href="fifth.html">
    <button id="container">Submit</button>
</a>

</div>



</body>

</html>

<!DOCTYPE html>
<html>
<head>
<title>Trauma and PTSD Resources</title>
<style>
body {
  font-family: sans-serif;
  display: flex;
  justify-content: center;
  align-items: center;
  min-height: 100vh;
  background-color: #f4f4f4;
}

.container {
  display: flex;
  gap: 20px;
  background-color: #ffffff;
  padding: 20px;
  border-radius: 10px;
  box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
}

.card {
  display: flex;
  flex-direction: column;
  gap: 10px;
  text-align: center;
  width: 250px;
}

.card img {
  width: 100%;
  height: 150px;
  object-fit: cover;
  border-radius: 10px;
}

.card h3 {
  font-size: 1.2rem;
  font-weight: bold;
  color: #333;
}

.card p {
  font-size: 1rem;
  color: #666;
}

.button {
  background-color: #4CAF50;
  color: white;
  padding: 12px 20px;
  border: none;
  border-radius: 5px;
  cursor: pointer;
  transition: background-color 0.3s;
}

.button:hover {
  background-color: #45a049;
}
</style>
</head>
<body>
  <div class="container">
    <div class="card">
      <img src="https://akm-img-a-in.tosshub.com/indiatoday/images/story/202204/in-service_doctors_to_go_on_an_1200x768.jpeg?VersionId=WHCT7hJkIi4fZHXHVQKAWtyzaGhonMOE&size=690:388" alt="Professional help">
      <h3>Professional help</h3>
      <a href="sixth.html" class="button">click to view </a>
    </div>
    <div class="card">
      <img src="https://lsb.edu.in/wp-content/uploads/2021/07/WhatsApp-Image-2021-07-29-at-2.31.26-PM.jpeg" alt="Articles and resources">
      <h3>Articles and resources</h3>
      <a href="eigth.html" class="button">click to view</a>
    </div>
    <div class="card">
      <img src="https://www.tpoftampa.com/wp-content/uploads/2022/08/meditation-meaning-turning-point-tampa.jpg" alt="yoga and meditation">
      <h3>yoga and meditation</h3>
      <a href="seventh.html" class="button">click to view</a>
    </div>
  </div>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Professional Help</title>
    <style>
        * {
            background-color: rgb(170, 210, 226);
        }
        h1 {
            text-align: center;
            text-decoration: underline solid;
        }
        .container {
            display: flex;
            flex-direction: column;
            align-items: center;
            gap: 30px;
            margin: 30px 0;
        }
        .profile {
            display: flex;
            gap: 20px;
            border: 2px solid black;
            padding: 10px;
            background-color: white;
        }
        .profile img {
            height: 300px;
            width: 275px;
            border: 2px solid black;
        }
        .profile p {
            margin: 0;
            font-size: 1.1em;
        }

        p{
            background-color: white;
        }

        button{
            height: 30px;
            width: 70px;
            background-color: navy;
            color: white;
            border-radius: 75%;
        }
    </style>
</head>
<body>
    <h1>Professional Help</h1>
    <div class="container">
        <div class="profile">
            <img src="https://d35oenyzp35321.cloudfront.net/Dr_S_K_S_Marya_3_6a12969844.jpg" alt="Dr. S.K.S. Marya">
            <p>Dr. S.K.S. Marya<br>
            Chairman & Chief Surgeon - Orthopaedics & Joint Replacement<br>
            Orthopaedics & Joint Replacement, Arthroscopy & Sports Injury, Robotic Surgery<br>
            Experience: 38+ Years<br>
            Mobile Number:9912571065
        </p>
        </div>
        <div class="profile">
            <img src="https://d35oenyzp35321.cloudfront.net/Dr_Anil_Arora_6c5c5c7ce6.JPG" alt="Dr. (Prof.) Anil Arora">
            <p>Dr. (Prof.) Anil Arora (Ortho)<br>
            Vice Chairman & Head of Department - Orthopaedics & Joint Replacement Surgery<br>
            Orthopaedics & Joint Replacement<br>
            Experience: 35+ Years<br>
            Mobile Number:9685596450
        </p>
        </div>
        <div class="profile">
            <img src="https://d35oenyzp35321.cloudfront.net/medium_Dr_Ramneek_Mahajan_f8682aed23.JPG" alt="Dr. Ramneek Mahajan">
            <p>Dr. Ramneek Mahajan<br>
            Senior Director (Orthopaedics) & Head Joint Reconstruction (Hip & Knee) Unit<br>
            Orthopaedics & Joint Replacement, Arthroscopy & Sports Injury, Robotic Surgery<br>
            Experience: 24+ Years<br>
            Mobile Number:8446257912
        </p>
        </div>
        <a href="sixth.html">
            <button id="Next">Next</button>
        </a>
    </div>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Yoga and Meditation</title>
    <style>
        body {
            background-image: url("https://www.tpoftampa.com/wp-content/uploads/2022/08/yoga-and-meditation-turning-point-tampa.jpg");
            background-size: cover;
            background-position: center;
            font-family: Arial, sans-serif;
        }
        .container {
            max-width: 800px;
            margin: 40px auto;
            padding: 20px;
            background-color: #f9f9f9;
            border: 1px solid #ddd;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h1{
            margin-left: 200px;
        }
        .article {
            margin-bottom: 20px;
        }
        .article h2 {
            color: #333;
            margin-top: 0;
        }
        .article p {
            color: #666;
        }
        .pose {
            display: inline-block;
            margin: 10px;
            text-align: center;
        }
        .pose img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            margin-bottom: 10px;
        }
        .pose h3 {
            color: #333;
            margin-top: 0;
        }
        .importance {
            background-color: #f7f7f7;
            padding: 20px;
            border: 1px solid #ddd;
        }
        .importance h2 {
            color: #333;
            margin-top: 0;
        }
        .importance p {
            color: #666;
        }
        button{
            height: 30px;
            width: 70px;
            background-color: navy;
            color: white;
            border-radius: 75%;
            margin-left: 1450px;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Yoga and Meditation</h1>
        <section class="article">
            <h2>The Benefits of Yoga and Meditation</h2>
            <p>Yoga and meditation are ancient practices that originated in northern India over 5000 years ago. Today, they are practiced by over 500 million people worldwide.</p>
        </section>
        <section class="article">
            <h2>Mindfulness Meditation Meaning</h2>
            <p>Mindfulness meditation is a practice that involves focusing your attention on the present moment. It can help reduce stress and anxiety, and improve your overall well-being.</p>
        </section>
        <section class="poses">
            <h2>Yoga Poses</h2>
            <div class="pose">
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRWJuCyoEhsjpss45UFmDbNnx1FW9paZh-ZMQ&s" alt="Yoga Pose 1">
                <h3>Downward Dog</h3>
            </div>
            <div class="pose">
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQeHtvaSk994Vl6XjmRadUsoFykZ6ftvtT92g&s" alt="Yoga Pose 2">
                <h3>Warrior Pose</h3>
            </div>
            <div class="pose">
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTpHZgEqNYw40ijE4r3-EsMXhD3fcpWh67znw&s" alt="Yoga Pose 3">
                <h3>Tree Pose</h3>
            </div>
        </section>
        <section class="importance">
            <h2>The Importance of Meditation in Stress Relief</h2>
            <p>Meditation is a powerful tool for reducing stress and anxiety. It can help calm the mind and body, and improve your overall well-being.</p>
        </section>
    </div>
    <a href="seventh.html">
        <button >Next</button>
    </a>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mindfulness & Relaxation</title>
    <style>
        body{
            height: 100vh;
            width: 100vw;
            font-family: 'Arial', sans-serif;
            background-image: url("anxiety2.avif");
            background-size: cover;
            position: relative;
            color: #333;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: rgba(255, 255, 255, 0.8);
            padding: 20px;
            text-align: center;
        }

        h1 {
            font-size: 2.5em;
            margin-bottom: 10px;
        }

        main {
            padding: 20px;
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
        }

        article {
            width: 300px;
            margin: 10px;
            padding: 15px;
            background-color: rgba(255, 255, 255, 0.8);
            border-radius: 10px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            text-align: center;
        }

        img {
            width: 100%;
            border-radius: 5px;
        }

        h2 {
            font-size: 1.5em;
            margin-bottom: 5px;
        }
        a{
            margin-top: 40px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Articles on Trauma and PTSD</h1>
    </header>
    <main>
            <article>
                <h2>Trauma and PTSD</h2>
                <a href="https://www.medicalnewstoday.com/articles/156285" target="_blank" style="background-color: #634caf; color: white; padding: 5px 8px; border: none; border-radius:3px; cursor: pointer; text-decoration: none;">click to view</a>
            </article>
            <article>
                <h2> Empathy in the Treatments of Trauma and PTSD</h2>
                <a href="https://www.taylorfrancis.com/books/mono/10.4324/9780203020999/empathy-treatment-trauma-ptsd-john-wilson-ph-rhiannon-brywnn-thomas-ph" target="_blank" style="background-color: #634caf; color: white; padding: 5px 8px; border: none; border-radius:3px; cursor: pointer; text-decoration: none;">click to view</a>
            </article>
            <article>
                <h2>Hidden trauma victims</h2>
                <a href="https://www.tandfonline.com/doi/abs/10.1080/15332985.2016.1220442" target="_blank" style="background-color: #634caf; color: white; padding: 5px 8px; border: none; border-radius:3px; cursor: pointer; text-decoration: none;">click to view</a>
            </article>
            <article>
                <h2>Everything You Need To Know About Trauma and PTSD</h2>
                <a href="https://www.mcleanhospital.org/essential/trauma-ptsd" target="_blank" style="background-color: #634caf; color: white; padding: 5px 8px; border: none; border-radius:3px; cursor: pointer; text-decoration: none;">click to view</a>
            </article>
            <article>
                <h2>PTSD(Post Traumatic Stress Disorder)</h2>
                <a href="https://www.helpguide.org/articles/ptsd-trauma/ptsd-symptoms-self-help-treatment.htm" target="_blank" style="background-color: #634caf; color: white; padding: 5px 8px; border: none; border-radius:3px; cursor: pointer; text-decoration: none;">click to view</a>
            </article>
            <article>
                <h2>Treatments for PTSD</h2>
                <a href="https://www.apa.org/ptsd-guideline/treatments" target="_blank" style="background-color: #634caf; color: white; padding: 5px 8px; border: none; border-radius:3px; cursor: pointer; text-decoration: none;">click to view</a>
            </article>
            <article>
                <h2>Various types of Trauma</h2>
                <a href="https://www.nctsn.org/what-is-child-trauma/trauma-types" target="_blank" style="background-color: #634caf; color: white; padding: 5px 8px; border: none; border-radius:3px; cursor: pointer; text-decoration: none;">click to view</a>
            </article>
            <article>
                <h2>How to heal Trauma? </h2>
                <a href="https://www.verywellmind.com/10-ways-to-heal-from-trauma-5206940" target="_blank" style="background-color: #634caf; color: white; padding: 5px 8px; border: none; border-radius:3px; cursor: pointer; text-decoration: none;">click to view</a>
            </article>
            <article>
                <h2>Advances in the Treatments</h2>
                <a href="https://link.springer.com/article/10.1007/s40501-020-00215-x" target="_blank" style="background-color: #634caf; color: white; padding: 5px 8px; border: none; border-radius:3px; cursor: pointer; text-decoration: none;">click to view</a>
            </article>
            <article>
                <h2>Dealing with Trauma </h2>
                <a href="https://newsinhealth.nih.gov/2018/06/dealing-trauma" target="_blank" style="background-color: #634caf; color: white; padding: 5px 8px; border: none; border-radius:3px; cursor: pointer; text-decoration: none;">click to view</a>
            </article>

        
    </main>
</body>
</html>





# Ex.07 Software Product Company Website
## Date:

## AIM:
To develop a static company website to display the softwares and services provided by the company.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
```
home.html

<html>
 <head>
 <meta name="viewport" content="width=device-width, initial-scale=1.0">
 <title> Software Development Company </title>
 <style type="text/css">
 * {
 margin: 0;
 padding: 0;
 font-family: Arial, Helvetica, sans-serif;
 }
 .banner {
 width: 100%;
 height: 100vh;
 
background-image:lineargradient(rgba(253,114,0,0.848),rgba(0,0,0,0.75)),url(background.jpg);
 background-size: cover;
 background-position: center;
 }
 .navbar {
 width: 85%;
 margin: auto;
 padding: 35px 0;
 display: flex;
 align-items: center;
 justify-content: space-between;
 }
 .logo {
 color: #5500ff;
 font-size: 40px;
 font-weight: 700;
 letter-spacing: 3px;
 }
 span {
 color: rgb(54, 249, 11);
 }
 form {
 width: 300px;
 height: 40px;
 display: flex;
 background: rgba(255, 255, 255, 0.2);
 padding: 1px 1px;
 font-size: 15px;
 border-radius: 10px;
 backdrop-filter: blur(4px) saturate(180%);
 }
 form input {
 background: transparent;
 flex: 1;
 border: 0;
 outline: none;
 padding: 12px 20px;
 font-size: 15px;
 color: white;
 } 
 ::placeholder {
 color: white;
 }
 form button {
 border: 0;
 outline: none;
 padding: 5px 20px;
 color: white;
 border-radius: 10px;
 background: #1004f5;
 cursor: pointer;
 }
 .navbar li {
 list-style: none;
 display: inline-block;
 margin: 0 20px;
 position: relative;
 }
 .navbar li a {
 text-decoration: none;
 color: white;
 text-transform: uppercase;
 }
 .navbar li:hover {
 border: 1px;
 padding: 10px;
 color: white;
 background-color: #0814fc;
 transition: 0.5s; 
 cursor: pointer;
 border-radius: 30px;
 }
 .content {
 position: absolute;
 top: 50%;
 left: 50%;
 transform: translate(-50%,-50%);
 text-align: center;
 }
 .text h2 {
 color: white;
 font-weight: 800;
 font-size: 50px;
 letter-spacing: 3px;
 }
 .text p {
 color: white;
 text-transform: capitalize;
 font-size: 15px;
 margin-bottom: 30px;
 word-spacing: 2px;
 letter-spacing: 1px;
 }
 .login {
 margin: 0px 10px;
 border: 2px solid #0828f8;
 padding: 13px 35px;
 letter-spacing: 1px;
 color: white;
 border-radius: 30px;
 background-color: #0e12f5;
 text-decoration: none;
 }
 .login:hover {
 border: 2px solid #0e12f5;
 color: #6fa1f8;
 background-color: white;
 transition: 0.5s;
 cursor: pointer;
 } 
 .signup {
 margin: 0px 10px;
 border: 2px solid #0e12f5;
 padding: 13px 35px;
 letter-spacing: 1px;
 color: white;
 border-radius: 30px;
 background-color: #0e12f5;
 text-decoration: none;
 }
 .signup:hover {
 border: 2px solid #0e12f5;
 color: #6fa1f8;
 background-color: white;
 transition: 0.5s;
 cursor: pointer;
 }
 footer {
 background-color: #0e25f5;
 margin-top: auto;
 }
 </style>
 </head>
<body>
 <div class="banner">
 <br>
 <div class="navbar">
 <h1 class="logo">C<span>ode</span>A<span>cadmey</span></h1>
 <ul>
 <li><a href="home.html"> Home </a></li>
 <li><a href="product.html"> Products </a></li>
 <li><a href="people.html"> People </a></li>
 <li><a href="contact.html"> Contact </a></li>
 </ul>
 <form action="" method="get">
 <input type="text" placeholder="Enter to Search">
 <button type="submit"> Search </button>
 </form>
 </div>
 <div class="content">
 <div class="text">
 <h2> Web Development </h2>
 <br>
 <p> If you're just getting started learning to code, Codecademy is a great way to 
get a sense for what coding is and how it works! </p>
 <br>
 <div>
 <a href="#" class="login"> Log In </a>
 <a href="#" class="signup"> Sign Up </a>
 </div>
 </div>
 </div> 
 </div>
 <footer>
 <center> Designed and Developed by Bharath </center>
 </footer>
</body>
</html>

people.html

<html>
 <head>
 <meta name="viewport" content="width=device-width, initial-scale=1.0">
 <title> people page </title>
 <style type="text/css">
 * {
 margin: 0;
 padding: 0;
 font-family: Arial, Helvetica, sans-serif;
 }
 .banner {
 width: 100%;
 height: 100vh;
 background-image: linear-gradient(rgba(255, 132, 16, 0.837),rgba(0,0,0,0.75)),url(background.jpg);
 background-size: cover;
 background-position: center;
 }
 .navbar {
 width: 85%;
 margin: auto;
 padding: 35px 0;
 display: flex;
 align-items: center;
 justify-content: space-between;
 }
 .bg-people {
 border: 1px;
 padding: 10px;
 color: white;
 background-color: #1c05f3;
 border-radius: 30px;
 }
 .logo {
 color: #0b13f6;
 font-size: 40px;
 font-weight: 700;
 letter-spacing: 3px;
 }
 span {
 color: rgb(71, 250, 5);
 }
 form {
 width: 300px;
 height: 40px;
 display: flex;
 background: rgba(255, 255, 255, 0.2);
 padding: 1px 1px;
 font-size: 15px;
 border-radius: 10px;
 backdrop-filter: blur(4px) saturate(180%);
 }
 form input {
 background: transparent;
 flex: 1;
 border: 0;
 outline: none;
 padding: 12px 20px;
 font-size: 15px;
 color: white;
 } 
 ::placeholder {
 color: white;
 }
 form button {
 border: 0;
 outline: none;
 padding: 5px 20px;
 color: white;
 border-radius: 10px;
 background: #060af9;
 cursor: pointer;
 }
 .navbar li {
 list-style: none;
 display: inline-block;
 margin: 0 20px;
 position: relative;
 }
 .navbar li a {
 text-decoration: none;
 color: white;
 text-transform: uppercase;
 }
 .navbar li:hover {
 border: 1px;
 padding: 10px;
 color: white;
 background-color: #050dfe;
 transition: 0.5s; 
 cursor: pointer;
 border-radius: 30px;
 }
 .image {
 position: relative;
 border: 0;
 top: 70px;
 background: transparent;
 }
 .image table {
 border: 0;
 color: white;
 position: relative;
 left: 150px;
 }
 .image table img {
 height: 140px;
 width: 140px;
 border: 2px solid white;
 padding: 5px;
 border-radius: 50%;
 }
 .image table td {
 color: #0813f4;
 }
 footer {
 background-color: #080cf7;
 margin-top: auto;
 }
 </style>
 </head>
<body>
 <div class="banner">
 <br>
 <div class="navbar">
 <h1 class="logo">C<span>ode</span>A<span>cademy</span></h1>
 <ul>
 <li><a href="home.html"> Home </a></li>
 <li><a href="product.html"> Products </a></li>
 <li><a href="people.html" class="bg-people"> People </a></li>
 <li><a href="contact.html"> Contact </a></li>
 </ul>
 <form action="" method="get">
 <input type="text" placeholder="Enter to Search">
 <button type="submit"> Search </button>
 </form>
 </div>
 <div class="image">
 <table cellspacing="20"> 
 <tr align="center">
 <td> <img src="bharath.png"> </td>
 <td> <img src="kishore.jpg"> </td>
 <td> <img src="mithun.jpg"> </td>
 <td> <img src="hero.jpg"> </td>
 <td> <img src="hero1.jpg"> </td>
 <td> <img src="images.jpg"> </td>
 </tr>
 <tr align="center">
 <th> Bharath</th>
 <th> Kishore</th>
 <th> Mithun</th>
 <th> Jadeja </th>
 <th> Pandya </th>
 <th> Rahul </th>
 </tr>
 <tr align="center">
 <td> CEO </td>
 <td> CEO, Co-Founder </td>
 <td> CTO, Co-Founder </td>
 <td> Director </td>
 <td> Asst. Director </td>
 <td> Dy. Director </td>
 </tr>
 </table>
 </div>
 </div>
 <footer>
 <center> Designed and Developed by Bharath </center>
 </footer>
</body>
</html>

product.html

<html>
 <head>
 <meta name="viewport" content="width=device-width, initial-scale=1.0">
 <title> Product Page </title>
 <style type="text/css">
 * {
 margin: 0;
 padding: 0;
 font-family: Arial, Helvetica, sans-serif;
 }
 .banner {
 width: 100%;
 height: 100vh;
 background-image: linear-gradient(rgba(254, 138, 14, 0.859),rgba(0,0,0,0.75)),url(background.jpg);
 background-size: cover;
 background-position: center;
 }
 .navbar {
 width: 85%;
 margin: auto;
 padding: 35px 0;
 display: flex;
 align-items: center;
 justify-content: space-between;
 }
 .bg-product {
 border: 1px;
 padding: 10px;
 color: white;
 background-color: #0004fd;
 border-radius: 30px;
 }
 .logo {
 color: #0213fa;
 font-size: 40px;
 font-weight: 700;
 letter-spacing: 3px;
 }
 span {
 color: rgb(29, 250, 8);
 }
 form {
 width: 300px;
 height: 40px;
 display: flex;
 background: rgba(255, 255, 255, 0.2);
 padding: 1px 1px;
 font-size: 15px;
 border-radius: 10px;
 backdrop-filter: blur(4px) saturate(180%);
 }
 form input {
 background: transparent;
 flex: 1;
 border: 0;
 outline: none;
 padding: 12px 20px;
 font-size: 15px;
 color: white;
 } 
 ::placeholder {
 color: white;
 }
 form button {
 border: 0;
 outline: none;
 padding: 5px 20px;
 color: white;
 border-radius: 10px;
 background: #3606e4;
 cursor: pointer;
 }
 .navbar li {
 list-style: none;
 display: inline-block;
 margin: 0 20px;
 position: relative;
 }
 .navbar li a {
 text-decoration: none;
 color: white;
 text-transform: uppercase;
 }
 .navbar li:hover {
 border: 1px;
 padding: 10px;
 color: white;
 background-color: #2f0bfa;
 transition: 0.5s; 
 cursor: pointer;
 border-radius: 30px;
 }
 .container {
 background: transparent;
 padding: 10px 5%;
 padding-bottom: 100px;
 }
 .container .box-container {
 display: grid;
 grid-template-columns: repeat(auto-fit, minmax(170px, 1fr));
 gap: 20px;
 }
 .container .box-container .box {
 color: white;
 box-shadow: 0 5px 10px rgba(0,0,0,.2);
 border-radius: 20px;
 background: transparent;
 border: 1px solid white;
 padding: 30px 20px;
 }
 .container .box-container .box img {
 height: 70px;
 border-radius: 20px;
 }
 .container .box-container .box h3 {
 color: #300eef;
 font-size: large;
 padding: 10px 0;
 }
 .container .box-container .box p {
 color: white;
 font-size: small;
 line-height: 1.5;
 }
 footer {
 background-color: #2e0cf3;
 margin-top: auto;
 }
 </style>
 </head>
<body>
 <div class="banner">
 <br>
 <div class="navbar">
 <h1 class="logo">C<span>ode</span>A<span>cademy</span></h1>
 <ul>
 <li><a href="home.html"> Home </a></li>
 <li><a href="product.html" class="bg-product"> Products </a></li>
 <li><a href="people.html"> People </a></li>
 <li><a href="contact.html"> Contact </a></li>
 </ul>
 <form action="" method="get">
 <input type="text" placeholder="Enter to Search">
 <button type="submit"> Search </button>
 </form>
 </div>
 <div class="container">
 <div class="box-container">
 <div class="box">
 <img src="gogle.png" alt="">
 <h3> gogle </h3>
 <p> Top tech company, famous for search and online services. </p>
 </div>
 <div class="box">
 <img src="chrome.png" alt="">
 <h3> Chrome </h3>
 <p> Tech used to browse in various fields </p>
 </div>
 <div class="box">
 <img src="photolab.png" alt="">
 <h3> photolab </h3>
 <p>used to edit photos </p>
 </div>
 <div class="box">
 <img src="photomake.png" alt="">
 <h3> Meta </h3>
 <p> used in world wide to edit photo</p>
 </div>
 <div class="box">
 <img src="photoshop.png" alt="">
 <h3> photoshop </h3>
 <p> Used edit photos</p>
 </div>
 <div class="box">
 <img src="ppt.png" alt="">
 <h3> Powerpoint </h3>
 <p> Tech giant, known for windows office, and cloud services. </p>
 </div>
 <div class="box">
 <img src="word.png" alt="">
 <h3>Word </h3>
 <p> Diverse social platform for content sharing and discussion. </p>
 </div>
 <div class="box">
 <img src="share.png" alt="">
 <h3> Share </h3>
 <p> used to share something </p>
 </div>
 <div class="box">
 <img src="visual.png" alt="">
 <h3>Visual </h3>
 <p> Global video-sharing giant for diverse content and engagement. </p>
 </div>
 <div class="box">
 <img src="vls.png" alt="">
 <h3>vls</h3>
 <p> Used to play videos,movies </p>
 </div>
 <div class="box">
 <img src="react.png" alt="">
 <h3> React </h3>
 <p> A realtime coding platform</p>
 </div>
 <div class="box">
 <img src="shell.png" alt="">
 <h3> Shell</h3>
 <p> A best database app to store datas </p>
 </div>
 </div>
 </div>
 </div>
 <footer>
 <center> Designed and Developed by Bharath</center>
 </footer>
</body>
</html>

contact.html

<html>
 <head>
 <meta name="viewport" content="width=device-width, initial-scale=1.0">
 <title> Contact Us Page </title>
 <style type="text/css">
 * {
 margin: 0;
 padding: 0;
 font-family: Arial, Helvetica, sans-serif;
 }
 .banner {
 width: 100%;
 height: 100vh;
 background-image: linear-gradient(rgba(255, 135, 6, 
0.886),rgba(0,0,0,0.75)),url(background.jpg);
 background-size: cover;
 background-position: center;
 }
 .navbar {
 width: 85%;
 margin: auto;
 padding: 35px 0;
 display: flex;
 align-items: center;
 justify-content: space-between;
 }
 .bg-contact {
 border: 1px;
 padding: 10px;
 color: white;
 background-color: #0824fd;
 border-radius: 30px;
 }
 .logo {
 color: #091dfa;
 font-size: 40px;
 font-weight: 700;
 letter-spacing: 3px;
 }
 span {
 color: rgb(81, 246, 10);
 }
 .navbar form {
 width: 300px;
 height: 40px;
 display: flex;
 background: rgba(255, 255, 255, 0.2);
 padding: 1px 1px;
 font-size: 15px;
 border-radius: 10px;
 backdrop-filter: blur(4px) saturate(180%);
 }
 .navbar form input {
 background: transparent;
 flex: 1;
 border: 0;
 outline: none;
 padding: 12px 20px;
 font-size: 15px;
 color: white;
 } 
 ::placeholder {
 color: white;
 }
 .navbar form button {
 border: 0;
 outline: none;
 padding: 5px 20px;
 color: white;
 border-radius: 10px;
 background: #0521f8;
 cursor: pointer;
 }
 .navbar li {
 list-style: none;
 display: inline-block;
 margin: 0 20px;
 position: relative;
 }
 .navbar li a {
 text-decoration: none;
 color: white;
 text-transform: uppercase;
 }
 .navbar li:hover {
 border: 1px;
 padding: 10px;
 color: white;
 background-color: #0630fe;
 transition: 0.5s; 
 cursor: pointer;
 border-radius: 30px;
 }
 .box {
 display: flex;
 column-gap: 40px;
 background: transparent;
 position: relative;
 top: 50px;
 }
 .box-1 {
 height: 400px;
 width: 400px;
 border: 3px solid white;
 border-radius: 20px;
 background: transparent;
 position: relative;
 left: 250px;
 }
 .box-2 {
 height: 400px;
 width: 400px;
 border: 3px solid #0909fb;
 border-radius: 20px;
 background: transparent;
 position: relative;
 left: 300px;
 }
 .box-1 form {
 display: flex;
 color: white;
 background: transparent;
 padding: 10px;
 font-size: 15px;
 position: relative;
 top: 15px;
 }
 .box-1 form input {
 background: transparent;
 display: flex;
 border: 1px solid white;
 border-radius: 10px;
 padding: 15px 30px;
 font-size: 15px;
 color: white;
 position: relative;
 top: 30px;
 }
 .box-1 form textarea {
 background: transparent;
 color: white;
 padding: 15px 10px;
 position: relative;
 top: 30px;
 left: 30px;
 border: 1px solid white;
 border-radius: 10px;
 }
 .box-1 form button {
 border: 0;
 outline: none;
 padding: 10px 20px;
 color: white;
 border-radius: 30px;
 background: #0804ed;
 cursor: pointer;
 position: relative;
 top: 50px;
 }
 .box-2 h2 {
 color: white;
 position: relative;
 top: 25px;
 left: 50px;
 font-size: 30px;
 }
 .box-2 p {
 color: white;
 position: relative;
 top: 50px;
 padding: 10px 80px;
 }
 .box-2 span {
 color: #0d09f8;
 font-size: 20px;
 }
 footer {
 background-color: #250af6;
 margin-top: auto;
 }
 </style>
 </head>
<body>
 <div class="banner">
 <br>
 <div class="navbar">
 <h1 class="logo">C<span>ode</span>A<span>cademy</span></h1>
 <ul>
 <li><a href="home.html"> Home </a></li>
 <li><a href="product.html"> Products </a></li>
 <li><a href="people.html"> People </a></li>
 <li><a href="contact.html" class="bg-contact"> Contact </a></li>
 </ul>
 <form action="" method="get">
 <input type="text" placeholder="Enter to Search">
 <button type="submit"> Search </button>
 </form>
 </div>
 <div class="box">
 <div class="box-1">
 <form>
 <center>
 <h1> Contact Us </h1>
 <input type="text" placeholder="Your Name">
 <br>
 <input type="email" placeholder="Your Email">
 <br>
 <textarea rows="4" cols="40" placeholder="Your Message"> </textarea>
 <br>
 <button type="submit"> Submit </button>
 </center>
 </form>
 </div>
 <div class="box-2"> 
 <h2> Contact Information </h2>
 <p> <span>Address</span> : no 5,balajistreet kattangulathur</p>
 <p> <span>Email</span> : Bharath@gmail.com </p>
 <p> <span>Phone</span> : 8597462315 </p>
 </div>
 </div>
 </div>
 <footer>
 <center> Designed and Developed by Bharath </center>
 </footer>
</body>
</html>

```
## output:

![Alt text](image.png)
![Alt text](image-1.png)
![Alt text](image-2.png)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.

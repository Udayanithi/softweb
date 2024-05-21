# Ex.07 Software Product Company Website
## Date:21.05.2024

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
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>SAAMAAN TECH</title>
    <style type="text/css">
      * {
        margin: 0;
        padding: 0;
        font-family: Arial, Helvetica, sans-serif;
      }
      .banner {
        width: 100%;
        height: 95vh;
        background: rgb(245, 172, 28);
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
        color: #d3e52a;
        font-size: 40px;
        font-weight: 700;
        letter-spacing: 3px;
      }
      span {
        color: rgb(24, 150, 196);
      }
      form {
        width: 300px;
        height: 40px;
        display: flex;
        background: rgba(231, 244, 244, 0.942);
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
        color: rgb(11, 109, 154);
      }
      ::placeholder {
        color: white;
      }
      form button {
        border: 0;
        outline: none;
        padding: 5px 20px;
        color: black;
        border-radius: 10px;
        background: rgb(115, 238, 217);;
        cursor: pointer;
      }
      #search.hover {
        border: 1px;
        padding: 10px;

        transition: 0.5s;
        cursor: pointer;
        border-radius: 30px;
        background: #0ef;
        color: #081b29;
        box-shadow: 0 0 20px #0ef;
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

        transition: 0.5s;
        cursor: pointer;
        border-radius: 30px;
        background: rgb(115, 238, 217);
        color: black;
        box-shadow: 0 0 20px rgb(115, 238, 217);
      }
      .content {
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
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
        border: 2px solid rgb(115, 238, 217);
        padding: 13px 35px;
        letter-spacing: 1px;
        color: black;
        border-radius: 30px;
        background-color: rgb(115, 238, 217);
        text-decoration: none;
      }
      .login:hover {
        border: 2px solid rgb(115, 238, 217);
        color: black;
        background-color: white;
        transition: 0.5s;
        cursor: pointer;
      }
      .signup {
        margin: 0px 10px;
        border: 2px solid yellow;
        padding: 13px 35px;
        letter-spacing: 1px;
        color: black;
        border-radius: 30px;
        background-color:yellow;
        text-decoration: none;
      }
      .signup:hover {
        border: 2px solid rgb(115, 238, 217);;
        color: black;
        background-color: white;
        transition: 0.5s;
        cursor: pointer;
      }
      footer {
        border: 1px;
        padding: 10px;

        transition: 0.5s;
        cursor: pointer;
        border-radius: 30px;
        background: rgb(115, 238, 217);
        color:black;
        box-shadow: 0 0 20px rgb(115, 238, 217);
      }
    </style>
  </head>
  <body>
    <div class="banner">
      <br />
      <div class="navbar">
        <h1 class="logo"><span>SAAMAAN </span>SIR</h1>
        <ul>
          <li><a href="soft.html"> Home </a></li>
          <li><a href="products.html"> Products </a></li>
          <li><a href="council.html"> People </a></li>
          <li><a href="contact.html"> Info </a></li>
        </ul>
        <form action="" method="get">
          <input type="text" placeholder="Enter to Search" />
          <button id="search" type="submit">Find</button>
        </form>
      </div>
      <div class="content">
        <div class="text">
          <h2>
            "SAAMAAN is a SEEMAN of tech where it seems to be occured in every corner of our day-to-day life" 
          </h2>
          <br />

          <br />
          <div>
            <a href="#" class="login"> Log In </a>
            <a href="#" class="signup"> Sign Up </a>
          </div>
        </div>
      </div>
    </div>
    <footer>
      <center>DESIGNED BY UDAYANITHI (212221220056)</center>
    </footer>
  </body>
</html>

products.html

<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Product Page</title>
    <style type="text/css">
      * {
        margin: 0;
        padding: 0;
        font-family: Arial, Helvetica, sans-serif;
      }
      .banner {
        width: 100%;
        height: 95vh;
        background: rgb(18, 198, 57);
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
        color: rgb(171, 56, 56);
        background-color: rgb(115, 238, 217);;
        border-radius: 30px;
      }
      .logo {
        color: rgb(115, 238, 217);
        font-size: 40px;
        font-weight: 700;
        letter-spacing: 3px;
      }
      span {
        color: white;
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
        color: black;
        border-radius: 10px;
        background: rgb(115, 238, 217);;
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

        transition: 0.5s;
        cursor: pointer;
        border-radius: 30px;
        background: rgb(115, 238, 217);
        color: black;
        box-shadow: 0 0 20px rgb(115, 238, 217);
      }
      .container {
        background: transparent;
        padding: 10px 5%;
        padding-bottom: 100px;
      }
      .container .box-container {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(170px, 1fr));
        gap: 100px;
      }
      .container .box-container .box {
        color: white;
        box-shadow: 0 5px 10px rgba(0, 0, 0, 0.2);
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
        color:yellow;
        font-size: large;
        padding: 20px 0;
      }
      .container .box-container .box p {
        color: white;
        font-size: small;
        line-height: 1.5;
      }
      footer {
        border: 1px;
        padding: 10px;

        transition: 0.5s;
        cursor: pointer;
        border-radius: 30px;
        background: rgb(115, 238, 217);
        color: black;
        box-shadow: 0 0 20px rgb(115, 238, 217);
      }
    </style>
  </head>
  <body>
    <div class="banner">
      <br />
      <div class="navbar">
        <h1 class="logo"><span>Z O </span>H O</h1>
        <ul>
          <li><a href="home.html"> Home </a></li>
          <li><a href="products.html" class="bg-product"> Products </a></li>
          <li><a href="council.html"> People </a></li>
          <li><a href="contact_us.html"> Info </a></li>
        </ul>
        <form action="" method="get">
          <input type="text" placeholder="Enter to Search" />
          <button type="submit">Find</button>
        </form>
      </div>
      <div class="container">
        <div class="box-container">
          <div class="box">
            <h3>C++</h3>
            <p>
              Efficiency Redefined: Harnessing the Power of C++ for Next-Level Development
            </p>
          </div>
          <div class="box">
            <h3>C</h3>
            <p>
              Crafting Performance: Where Precision Meets C Programming.
            </p>
          </div>
          <div class="box">
            <h3>JAVASCRIPT</h3>
            <p>
              Scripting Success: Unleashing the Power of JavaScript.
            </p>
          </div>
          <div class="box">
            <h3>PHP</h3>
            <p>
              PHP is a server side scripting language that is embedded in HTML.
            </p>
          </div>
          <div class="box">
            <h3>PYTHON</h3>
            <p>
              Unlocking Innovation: Python Paving the Way to Progress.
            </p>
          </div>
          <div class="box">
            <h3>SQL</h3>
            <p>
              SQL is a standard language for accessing and manipulating
              databases.
            </p>
          </div>
          <div class="box">
            <h3>SHELL</h3>
            <p>
              Shell can be accessed by users using a command line interface.
            </p>
          </div>
          <div class="box">
            <h3>RUBY</h3>
            <p>
              Ruby: Where Simplicity Meets Power in Programming
            </p>
          </div>
          <div class="box">
            <h3>TYPESCRIPT</h3>
            <p>
              Empower Your Code: Embrace the Future with TypeScript
            </p>
          </div>
          <div class="box">
            <h3>F#</h3>
            <p>
              F# is an Open-source programming language with a lot of features.
            </p>
          </div>
        </div>
      </div>
    </div>
    <footer>
        <center>DESIGNED BY UDAYANITHI (212221220056)</center>
    </footer>
  </body>
</html>


people.html

<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>thambigal</title>
    <style type="text/css">
      * {
        margin: 0;
        padding: 0;
        font-family: Arial, Helvetica, sans-serif;
      }
      .banner {
        width: 100%;
        height: 95vh;
        background: rgb(255, 1, 10);
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
        background-color: rgb(115, 238, 217);
        border-radius: 30px;
      }
      .logo {
        color: rgb(115, 238, 217);
        font-size: 40px;
        font-weight: 700;
        letter-spacing: 3px;
      }
      span {
        color: white;
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
        color: black;
        border-radius: 10px;
        background: rgb(115, 238, 217);;
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

        transition: 0.5s;
        cursor: pointer;
        border-radius: 30px;
        background: rgb(115, 238, 217);
        color: #081b29;
        box-shadow: 0 0 20px rgb(115, 238, 217);
      }
      .image {
        position: relative;
        border: 0;
        top: 150px;

        background: transparent;
      }
      .image table {
        border: 0;
        color: white;
        position: relative;
        left: 200px;
        border: 10PX;
        padding-left: 10px;
      
      }
      .image table img {
        height: 140px;
        width: 140px;
        border: 2px solid white;
        padding: 5px;
        border-radius: 50%;
      }
      .image table td {
        color:yellow;
      }
      footer {
        border: 1px;
        padding: 10px;

        transition: 0.5s;
        cursor: pointer;
        border-radius: 30px;
        background: rgb(115, 238, 217);
        color: black;
        box-shadow: 0 0 20px rgb(115, 238, 217);
      }
      .space{
        padding-left: 30px;
        color:rgb(115, 238, 217);
      }
      .spk{
        color:yellow;
      }

    </style>
  </head>
  <body>
    <div class="banner">
      <br />
      <div class="navbar">
        <h1 class="logo"><span>S A </span>M A</h1>
        <ul>
          <li><a href="soft.html"> Home </a></li>
          <li><a href="products.html"> Products </a></li>
          <li><a href="council.html" class="bg-people"> People </a></li>
          <li><a href="contact_us.html"> Info </a></li>
        </ul>
        <form action="" method="get">
          <input type="text" placeholder="Enter to Search" />
          <button type="submit">Find</button>
        </form>
      </div>
      <div class="image">
        <table cellspacing="65" >
          <tr align="center">
            <td><img src="my image.png" /></td>
            <td><img src="SAMAAN.jpg"></td>
            <td><img src="HAROLD.jpg" /></td>
            <td><img src="VIKRAM.jpg" /></td>
            <td><img src="MUTHUPANDI.jpg" /></td>
            <td><img src="LEO DAS.jpg" /></td>
          </tr>
          <tr align="center" class="space">
            <th>UDAYANITHI</th>
            <th>SAMAAN</th>
            <th>HAROLD DAS</th>
            <th>AGENT VIKRAM</th>
            <th>MUTHUPANDI</th>
            <th>LEO</th>
          </tr>
          <tr align="center" class="spk">
            <td>CEO</td>
            <td>CEO of Facebook</td>
            <td>CTO,Co-Founder</td>
            <td>DIRECTOR</td>
            <td>Asst.Director</td>
            <td>Dy.Director</td>
          </tr>
        </table>
      </div>
    </div>
    <footer>
        <center>DESIGNED BY UDAYANITHI (212221220056)</center>
    </footer>
  </body>
</html>

info.html

<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Contact Us Page</title>
    <style type="text/css">
      * {
        margin: 0;
        padding: 0;
        font-family: Arial, Helvetica, sans-serif;
      }
      .banner {
        width: 100%;
        height: 95vh;
        background: blueviolet;
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
        color: black;
        background-color:rgb(115, 238, 217);;
        border-radius: 30px;
      }
      .logo {
        color: rgb(115, 238, 217);
        font-size: 40px;
        font-weight: 700;
        letter-spacing: 3px;
      }
      span {
        color: white;
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
        color: black;
        border-radius: 10px;
        background: yellow;
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

        transition: 0.5s;
        cursor: pointer;
        border-radius: 30px;
        background: rgb(115, 238, 217);
        color: black;
        box-shadow: 0 0 20px rgb(115, 238, 217);
      }
      .box {
        display: flex;
        column-gap: 40px;
        background: transparent;
        position: relative;
        top: 50px;
        width: 220px;
      }
      .box-1 {
        height: 400px;
        width: 400px;
        border: 3px solid yellow;
        border-radius: 20px;
        background: transparent;
        position: relative;
        left: 250px;
      }
      .box-2 {
        height: 400px;
        width: 400px;
        border: 3px solid yellow;
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
        left: 20px;
        border: 1px solid white;
        border-radius: 10px;
        width: 300px;
      }
      .box-1 form button {
        border: 0;
        outline: none;
        padding: 10px 20px;
        color:black;
        border-radius: 30px;
        background: rgb(115, 238, 217);
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
        color: rgb(115, 238, 217);
        font-size: 20px;
      }
      footer {
        border: 1px;
        padding: 10px;

        transition: 0.5s;
        cursor: pointer;
        border-radius: 30px;
        background: rgb(115, 238, 217);
        color: black;
        box-shadow: 0 0 20px rgb(115, 238, 217);
      }
    </style>
  </head>
  <body>
    <div class="banner">
      <br />
      <div class="navbar">
        <h1 class="logo"><span>Z O </span>H O</h1>
        <ul>
          <li><a href="home.html"> Home </a></li>
          <li><a href="products.html"> Products </a></li>
          <li><a href="council.html"> People </a></li>
          <li><a href="contact_us.html" class="bg-contact"> Info </a></li>
        </ul>
        <form action="" method="get">
          <input type="text" placeholder="Enter to Search" />
          <button type="submit">Find</button>
        </form>
      </div>
      <div class="box">
        <div class="box-1">
          <form>
            <center>
              <h1>Contact</h1>
              <input type="text" placeholder="Your Name" />
              <br />
              <input type="email" placeholder="Your Email" />
              <br />
              
              <br />
              <button type="submit">Submit</button>
            </center>
          </form>
        </div>
        <div class="box-2">
          <h2>Contact Info</h2>
          <p>
            <span>Address</span> :saveetha engineering college, thandalam, chennai.
          </p>
          <p><span>Email</span> : UDAYANITHI@gmail.com</p>
          <p><span>Phone</span> : 1234567890</p>
        </div>
      </div>
    </div>
    <footer>
        <center>DESIGNED BY UDAYANITHI (212221220056)</center>
    </footer>
  </body>
</html>

```



## OUTPUT:
![alt text](<Screenshot (11).png>)
![alt text](<Screenshot (12).png>)
![alt text](<Screenshot (13).png>)
![alt text](<Screenshot (14).png>)
## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.

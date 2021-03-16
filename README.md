 <html>
<html lang="en">
<head>
<style>
body {
  background-color: pink;
}
</style>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>

 
body {
  font-family: Arial, Helvetica, sans-serif;
  margin: 0;
}


 .navbar {
  overflow: hidden;
  background-color:black ;
}






.navbar a {
  float: left;
  display: block;
  color: red;
  text-align: center;
  padding: 10px 50.6px;
  text-decoration:  none;
  background-color:black
}



.navbar a.right {
  float: left;
}


.navbar a:hover {
  background-color: yellow;
  color: none;

}


.row {  
  display: -ms-flexbox; 
  display: flex;
  -ms-flex-wrap: wrap; 
  flex-wrap: wrap;
}

.side {
  -ms-flex: 30%; 
  flex: 30%;
  background-color: none;
  padding: 20px;
}



.main {   
  -ms-flex: 70%; 
  flex: 70%;
  background-color: pink;
  padding: 20px;
}

.footer {
  padding: 20px;
  text-align: center;
  background: rgb(31, 58, 187);

}

</style>
</head>
<body>

<div class="navbar">
  <a href="https://sajjad172.github.io/homepage.networx/">Home</a>
  <a href="https://sajjad172.github.io/contact-us-page/">Contact Us</a>
  <a href="https://sajjad172.github.io/about.us.page/">About Us</a>
  <a href="https://sajjad172.github.io/artworx.page/">Artworx Page</a>
   <a href="https://sajjad172.github.io/sumbit.art/" class="right" class="center">Submit your Art!</a>
  </div>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
img {
  display: block;
  margin-left: auto;
  margin-right: auto;
}
</style>
<body>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
body {
  font-family: Arial, Helvetica, sans-serif;
}


* {
  box-sizing: border-box;
}


input[type=text], select, textarea {
  width: 100%;
  padding: 12px;
  border: 1px solid #ccc;
  margin-top: 6px;
  margin-bottom: 16px;
  resize: vertical;
}

input[type=submit] {
  background-color: red;
  color: white;
  padding: 12px 20px;
  border: none;
  cursor: pointer;
}

input[type=submit]:hover {
  background-color: gray;
}


.container {
  border-radius: 5px;
  background-color: pink;
  padding: 10px;
}


.column {
  float: left;
  width: 50%;
  margin-top: 6px;
  padding: 20px;
}


.row:after {
  content: "";
  display: table;
  clear: both;
}

@media screen and (max-width: 600px) {
  .column, input[type=submit] {
    width: 100%;
    margin-top: 0;
  }
}
</style>
</head>
<body>



<div class="container">
  <div style="text-align:center"><br>
    <h2 style="color:blue ;">Contact US</h2>
    <p><em><strong>Have a concern about the website or want to give feedback:</strong></em></p></div>
  <div class="row">
    <div class="column">
      <img src="https://raw.githubusercontent.com/sajjad172/aboutuspictures/main/mong%20us.jpg"  style="width:100%">
    </div>
    <div class="column">
       <form action="https://formspree.io/f/mdopqkdk" method="POST">
                <input type="hidden" name="_subject" value="Contact request from personal website" />
        <label for="fname"> Name</label>
        <input type="text" id="fname" name="Name" placeholder="Your name..." required>
       
        <label for="lsname">Email</label>
        <input type="text" id="lsname" name="Email"  placeholder="Your email..." required>
        <label for="country">Country</label>
        <select id="country" name="country">
          <option value="usa">USA</option>
          <option value="canada">Canada</option>
          <option value="australia">Australia</option>
          <option value="europe">Europe</option>
        </select>
        <label for="subject">Message</label>
    <textarea id="subject" name="subject" placeholder="Write us..." style="height:200px" required></textarea>
     <input type="submit" value="Submit">
      </form>
    </div>
  </div>






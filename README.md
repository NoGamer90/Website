<!DOCTYPE html>
<html>
  <head>
    <style>
         #a{
      margin: 0;
      padding: 0;
      height: 100vh;
      width: 100vw;
      background: url(homepage.jpg) no-repeat center center;
  }
#nav ul{
  list-style: none;
  overflow: scroll;
  white-space: nowrap;
}
#nav ul li{
  display: inline;
  margin: 2px;
}
#nav ul li a{
  text-decoration: none;
  border-style: double;
  color: blue;
  border: 2px
  border-color: blue;
  background-color: black;
}
#nav ul li #uc{
  text-decoration: none;
  border-style: double;
  color: green;
  border: 2px 
  border-color: green;
  background-color: black;
}
#nav ul li a:hover{
  text-decoration: none;
  border-style: double;
  color: red;
  border: 2px 
  border-color: red;
  background-color: yellow;
}
#nav ul li #uc:hover{
  text-decoration: none;
  border-style: double;
  color: red;
  border: 2px 
  border-color: red;
  background-color: yellow;
}
#h2{
  background-color: green;
  color: white;
  text-align: center;
  text-shadow: 3px 3px 8px;
}
#mar{
  background-color: yellow;
  color: red;
  font-family: cursive;
  text-shadow: 2px 2px 5px;
}
img {
  width: 100px;
  height: 100px;
  border-radius: 50%;
  object-fit: cover;
}
.g{
  text-decoration:none;
  font-style: italic;
  color: black;
  margin: 10px;
}
#con{
  display: flex;
}
footer {
          text-align: center;
          padding: 15px;
          background-color: #333;
          color: white;
          margin-top: 20px;
        }
    </style>
</head>
  <body id="a">
    <header>
    <h1>
      <nav id="nav">
        <ul>
          <li><a href="home.html" id="uc">Home</a></li>
          <li><a href="about.html">About Me</a></li>
          <li><a href="education.html">My Education</a></li>
          <li><a href="channel.html">Channel</a></li>
          <li><a href="#"></a></li>
          <li><a href="#"></a></li>
          <li><a href="#"></a></li>
        </ul>
      </nav>
      </h1>
    </header>
    <h2 id="h2"> Welcome to my website</h2>
    <h3>
      <marquee id="mar">Thanks for vesite my website &#128591  &#128591!!!</marquee>
    </h3>
     <h4>Akash Kumar Das</h4>
    <p>Secondary School Student | Passionate Learner</p>
   <footer>
    <p>&copy; 2025 Akash Kumar Das. All Rights Reserved.</p>
   </footer>
  </body>
</html>
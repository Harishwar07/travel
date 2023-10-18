<html>
<head>
  <title>House of travel</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-4bw+/aepP/YC94hEpVNVgiZdgIC5+VKNBQNGCHeKRQN+PtmoHDEXuppvnDJzQIu9" crossorigin="anonymous">
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.1/dist/js/bootstrap.bundle.min.js" integrity="sha384-HwwvtgBNo3bZJJLYd8oVXjrBZt8cqVSpeBNS5n7C8IVInixGAoxmnlMuBnhbgrkm" crossorigin="anonymous"></script>
  <script src="https://kit.fontawesome.com/fa3870dfe0.js" crossorigin="anonymous"></script>

<style>

body, h1, h2, h3, p, ul, li, form, input, textarea {
  margin: 0;
  padding: 0;
  font-family: Arial, sans-serif;
}
#background-video {
            width: 100vw;
            height: 100vh;
            object-fit: cover;
            position: fixed;
            left: 0;
            right: 0;
            top: 0;
            bottom: 0;
            z-index: -1;
        }

header {
  color: peru;
  padding: 20px;
  text-align: center;
  padding:50px;
  
}


h1 {
  font-size: 50px;
}

nav ul {
  list-style-type: none;
}

nav ul li {
  display: inline;
  margin-right: 10px;
}

nav ul li a {
  color: peru;
  text-decoration: none;
}

#home {
  background-size: cover;
  text-align: center;
  padding: 100px;
  color: peru;
}

h2 {
  font-size: 24px;
  margin-bottom: 20px;
}

p {
  font-size: 18px;
  margin-bottom: 30px;
}

.cta-button {
  display: inline-block;
  padding: 10px 20px;
  background-color: orangered;
  color: whitesmoke;
  text-decoration: none;
  border-radius: 5px;
}

#destinations {
  padding:30px;
  color:peru;
}

.destination-card {
  margin-bottom: 30px;
}

.destination-card img {
  width: 100%;
  max-height: 200px;
  object-fit: cover;
}

.destination-card h3 {
  font-size: 24px;
  margin: 10px 0;
}

.destination-card p {
  font-size: 16px;
  margin-bottom: 10px;
}

#contact {
  padding: 50px;
  color:peru;
}

form label {
  display: block;
  margin-bottom: 10px;
}

form input,
form textarea {
  width: 100%;
  padding: 10px;
  margin-bottom: 20px;
  border: 2px solid orangered;
  border-radius: 8px;
  padding: 5px;
  background-color: transparent;
}

form textarea {
  height: 100px;
  border: 2px solid orangered;
  border-radius: 8px;
  padding: 5px;
  background-color: transparent;
}

input[type="submit"] {
  background-color: orangered;
  color: white;
  border: none;
  padding: 10px 20px;
  cursor: pointer;
}

footer {
  color: peru;
  padding: 20px;
  text-align: center;
}

img{
  border-radius: 8px;
}
.dropdown{
    text-align:right;
    background-color: transparent; 
}
.dropdown-menu{
  background-color: transparent;
  text-align: center;
}
.fa-solid{
  font-size: 20px;
  padding-left: 12px;
}

  </style>
</head>
<body>
  <video id="background-video" autoplay loop muted >
    <source src="mount.mp4" type="video/mp4">
</video>
    <header>
      <h1 font-size:36px; >HOUSE OF TRAVEL </h1><br>
      <div class="dropdown">
        <button class="btn btn-primary dropdown-toggle" type="button" data-bs-toggle="dropdown" aria-expanded="false">
          Login
        </button>
        <ul class="dropdown-menu">
          <li><button class="dropdown-item" type="button" ><a href="jslogin.html" >Login</a></button></li>
          <li><button class="dropdown-item" type="button"><a href="jssignin.html" >Signup</a></button></li>
        </ul>
      </div>
      <nav>
        <ul>
          
          <li><i href="#home" class="fa-solid fa-house"></i><a href="#home">Home</a></li>
          
          <li><i class="fa-solid fa-map-location-dot"></i><a href="#destinations">Destinations</a></li>
          
          <li><i class="fa-solid fa-plane"></i><a href="#Flight">Flight</a></li>
          
          <li><i class="fa-solid fa-train-subway"></i><a href="#Train">Train</a></li>
          
          <li><i class="fa-solid fa-taxi"></i><a href="#Cab">Cab</a></li>
          
          <li><i class="fa-solid fa-bus"></i><a href="#Bus">Bus</a></li>
        </ul>
      </nav>
    </header>

    <section id="home">
      <h2>WELCOME TO THE HOUSE OF TRAVEL!!</h2>
      <p>Experience the adventure of a lifetime!</p>
      <a href="#destinations" class="cta-button">Explore Destinations</a>
    </section>
    
    <section id="destinations">
      <div class="destination-card">
        <h2>Popular Destinations</h2>
        <h3>Delhi</h3>
        <p>Experience the beauty of Delhi with its stunning landscapes and rich cultural heritage.</p>
      </div>
      <img src="/images/delhi.jpeg" width="700" alt="Destination 1">
      <div class="destination-card">
        <h3>Kerala</h3>
        <p>Discover the hidden treasures of Kerala and immerse yourself in its vibrant local traditions.</p>  
      </div>
      <img src="/images/kerala1-1024x536.jpg" width="700" alt="Destination 1">
    </section>
  
    <section id="contact">
      <h2>Contact Us</h2>
      <form>
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" required>
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required>
        <label for="message">Message:</label>
        <textarea id="message" name="message" required></textarea>
        <input type="submit" value="Send Message" class="cta-button">
      </form>
    </section>
  
    <footer>
      <p>&copy; 2023 Travel Agency. All rights reserved.</p>
    </footer>


  </body>
  </html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        marquee{color:red;background-color: aquamarine;}
    </style>
    
</head>
<body>
    <marquee behaviour="slide">Hello Nikita</marquee>
</body>

</style>
</head>

 <title>Login Page</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
  <style>
    body {
      background-color: #f8f9fa;
    }
    .login-container {
      max-width: 400px;
      margin: 100px auto;
      padding: 30px;
      background-color: #ffffff;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
  </style>
</head>
<body>

<div class="container">
  <div class="login-container">
    <h2 class="text-center mb-4">Login</h2>
    <form>
      <div class="mb-3">
        <label for="email" class="form-label">Email address</label>
        <input type="email" class="form-control" id="email" placeholder="Enter email">
      </div>
      <div class="mb-3">
        <label for="password" class="form-label">Password</label>
        <input type="password" class="form-control" id="password" placeholder="Password">
      </div>
      <div class="mb-3 form-check">
        <input type="checkbox" class="form-check-input" id="rememberMe">
        <label class="form-check-label" for="rememberMe">Remember Me</label>
      </div>
      <div class="d-grid mb-3">
        <button type="submit" class="btn btn-primary">Login</button>
      </div>
      <div class="text-center">
        <a href="#" class="d-block mb-2">Forgot Password?</a>
        <a href="#">Register</a>
      </div>
    </form>
  </div>
</div>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
	<header>
	  <div class="logo">
		<img src="C:\Users\NIKITA\Pictures\burger hut logo.jpg" class="bc" alt="Berger Hut Logo">
	  </div>
	  <nav>
		




        <button style="text-align:center"><a style="text-align:center" href="#Home"><i class="fa fa-home"style='font-size:24px'></i>Home </a></button>
        <button> <a href="#About"><i class="material-icons"style='font-size:24px'></i>About</a></button>
        <button> <a href="#Project"><i class="fa-project-diagram"style='font-size:24px'></i>Projects</a></button>
         <button><a href="#Contacts"><i class="fa fa-group"style='font-size:24px'></i>Contacts</a></button>
         
	  </nav>
	</header>

<section class="hero">
  <div class="hero-content">
    <h1 style="text-align:center">Welcome to Berger Hut</h1>
    <p style="text-align:center">Experience the Taste of Perfection</p>
    <a href="#menu" class="btn">Explore Our Menu</a>
  </div>
</section>

<section class="about dark-theme">
  <div class="about-content">
    <h2 style="text-align:center">About Berger Hut</h2>
    <p style="text-align:center">Experience the finest gourmet burgers in a cozy and rustic atmosphere. At Berger Hut, we are dedicated to delivering exceptional flavors that will tantalize your taste buds.</p>
    <p>Our chefs meticulously craft each burger using locally sourced ingredients and unique flavor combinations. From juicy beef patties to mouthwatering vegetarian options, there's something for everyone.</p>
    <a href="#menu" class="btn">Explore Our Menu</a>
  </div>
  <div class="about-image">
    <img src="C:\Users\NIKITA\Pictures\about burger hut logo image.jpg
    " alt="About Image">
  </div>
</section>


<section class="menu">
  <h2>Our Menu</h2>
  <div class="menu-items">
    <div class="menu-item">
      <img src="C:\Users\NIKITA\Pictures\burger 1.jpg" alt="Burger 1">
      <h3 style="text-align:center">Classic Cheeseburger</h3>
      <p >A juicy beef patty topped with melted cheese, fresh lettuce, tomato, and our special sauce. Served with a side of crispy fries.</p>
    </div>
    <div class="menu-item">
      <img style="text-align:center" src="file:///C:/Users/NIKITA/Downloads/burger2.jpg" alt="Burger 2">
      <h3 style="text-align:center">Veggie Delight</h3>
      <p style="text-align:center">A delicious veggie patty made from a blend of fresh vegetables and spices. Topped with avocado, sprouts, and tangy mayo. Served with a side of sweet potato fries.</p>
    </div>
    <div class="menu-item">
      <img src= "file:///C:/Users/NIKITA/Downloads/burger3.jpg"alt="Burger 3">
      <h3 style="text-align:center">Spicy BBQ Burger</h3>
      <p style="text-align:center">A fiery burger packed with flavor! Grilled chicken breast smothered in spicy BBQ sauce, topped with jalapenos, crispy onion rings, and chipotle mayo. Served with a side of coleslaw.</p>
    </div>
  </div>
</section>

<section class="reservations">
  <div class="reservation-form">
    <h2 style="text-align:center">Make a Reservation</h2>
    <form>
      <input type="text" name="name" placeholder="Your Name" required>
      <input type="email" name="email" placeholder="Your Email" required>
      <input type="tel" name="phone" placeholder="Phone Number" required>
      <input type="date" name="date" required>
      <input type="time" name="time" required>
      <textarea name="message" placeholder="Additional Message" rows="5"></textarea>
      <button type="submit">Submit</button>
    </form>
  </div>
</section>


<section class="testimonials">
  <h2style="text-align:center" >What Our Customers Say</h2>
  <div class="testimonial">
    <img src="file:///C:/Users/NIKITA/Desktop/HTML_project/customer1.jpg" alt="Customer 1">
    <p style="text-align:center">"The burgers at Berger Hut are simply amazing! The flavors are rich, and the ingredients are always fresh. It's my go-to place whenever I'm craving a delicious meal."</p>
    <h4>John Doe</h4>
  </div>
  <div class="testimonial">
    <img src="file:///C:/Users/NIKITA/Desktop/HTML_project/customer2.jpg" alt="Customer 2">
    <p style="text-align:center" >"Berger Hut never disappoints! The quality of their burgers and the friendly service make it a top-notch dining experience. I highly recommend it to all burger lovers!"</p>
    <h4>Jane Smith</h4>
  </div>
</section>


<section class="gallery">
  <h2 style="text-align:center" >Gallery</h2>
  <div class="image-grid">
    <div class="image-item">
      <img src="https://b.zmtcdn.com/data/pictures/6/18273566/076e2318d3f259d5e002115e1576de8e.jpg?fit=around|960:500&crop=960:500;*,*" alt="Image 1">
    </div>
    <div class="image-item">
      <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT0g_c0QRfq_9Ayn2WIp20NePQvuAgIYz4Yhg&s" alt="Image 2">
    </div>
    <div class="image-item">
      <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTk8_6M_nB44ZB2ajWRcFCqECMAd9nXx6ZlqA&s" alt="Image 3">
    </div>
    <div class="image-item">
      <img src="C:\Users\Nikita\Downloads\burger3.jpg" alt="Image 4">
    </div>
  </div>
</section>

<section class="contact">
  <div class="contact-container">
    <h2>Contact Us</h2>
    <div class="contact-info">
      <div class="info-item">
        <i class="fas fa-map-marker-alt"></i>
        <p>123 Main Street, City, Country</p>
      </div>
      <div class="info-item">
        <i class="fas fa-phone-alt"></i>
        <p>+1 234 567 890</p>
      </div>
      <div class="info-item">
        <i class="fas fa-envelope"></i>
        <p>info@bergerhut.com</p>
      </div>
    </div>
    <title>Contact Us</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
  <style>
    * {
      box-sizing: border-box;
      font-family: 'Roboto', sans-serif;
    }

    body {
      margin: 0;
      padding: 0;
      background: #f4f4f4;
    }

    .container {
      max-width: 800px;
      margin: 40px auto;
      background: white;
      padding: 40px;
      border-radius: 10px;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
    }

    h2 {
      text-align: center;
      margin-bottom: 30px;
      color: #333;
    }

    form {
      display: flex;
      flex-direction: column;
    }

    label {
      margin-top: 15px;
      font-weight: bold;
    }

    input[type="text"],
    input[type="email"],
    textarea {
      padding: 10px;
      margin-top: 5px;
      border: 1px solid #ccc;
      border-radius: 5px;
      resize: vertical;
    }

    textarea {
      height: 120px;
    }

    button {
      margin-top: 25px;
      padding: 12px;
      background-color: #28a745;
      color: white;
      font-size: 16px;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      transition: background 0.3s;
    }

    button:hover {
      background-color: #218838;
    }

    .info {
      text-align: center;
      margin-top: 40px;
      color: #555;
      font-size: 15px;
    }

    @media (max-width: 600px) {
      .container {
        padding: 20px;
      }
    }
  </style>
</head>
<body>

  <div class="container">
    <h2>Contact Us</h2>
    <form action="mailto:your-email@example.com" method="post" enctype="text/plain">
      <label for="name">Full Name</label>
      <input type="text" id="name" name="name" required>

      <label for="email">Email Address</label>
      <input type="email" id="email" name="email" required>

      <label for="subject">Subject</label>
      <input type="text" id="subject" name="subject" required>

      <label for="message">Your Message</label>
      <textarea id="message" name="message" required></textarea>

      <button type="submit">Send Message</button>
    </form>

    <div class="info">
      <p>Email: support@example.com</p>
      <p>Phone: +1 234 567 8901</p>
      <p>Address: 123 Main Street, Your City, Country</p>
    </div>
  </div>

</body>
</section>




<footer class="footer">
  <div class="footer-content">
    <div class="footer-logo">
      <img src="https://img.freepik.com/free-psd/food-template-design_23-2151068792.jpg?semt=ais_items_boosted&w=740" alt="Logo">
    </div>
    <nav class="footer-links">
      <a href="#">Home</a>
      <a href="#">About</a>
      <a href="#">Menu</a>
      <a href="#">Reservations</a>
      <a href="#">Testimonials</a>
      <a href="#">Gallery</a>
      <a href="#">Contact</a>
    </nav>
    <div class="footer-social">
      <a href="#"><i class="fab fa-facebook"></i></a>
      <a href="#"><i class="fab fa-twitter"></i></a>
      <a href="#"><i class="fab fa-instagram"></i></a>
    </div>
  </div>
  <p class="footer-text">&copy; 2023 Berger Hut. All rights reserved.</p>
</footer>


</body>
</html>

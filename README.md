# car-eduzone
it is a user friendy website about cars it will be very usefull thank you for using 
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Car EduZone</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #e9f5ff;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #004080;
      color: white;
      padding: 20px;
      text-align: center;
    }
    nav {
      background-color: #cce6ff;
      padding: 10px;
      text-align: center;
    }
    nav a {
      margin: 0 15px;
      color: #004080;
      text-decoration: none;
      font-weight: bold;
    }
    section {
      padding: 20px;
    }
    .car {
      background: white;
      margin: 10px auto;
      padding: 15px;
      border-radius: 10px;
      max-width: 600px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.2);
    }
    footer {
      background-color: #004080;
      color: white;
      text-align: center;
      padding: 10px;
      position: fixed;
      bottom: 0;
      width: 100%;
    }
  </style>
</head>
<body>
  <header>
    <h1>Car EduZone</h1>
    <p>Learn About Different Types of Cars</p>
  </header>

  <nav>
    <a href="#sports">Sports Cars</a>
    <a href="#suv">SUVs</a>
    <a href="#electric">Electric Cars</a>
  </nav>

  <section>
    <div class="car" id="sports">
      <h2>Sports Cars</h2>
      <p>Sports cars are built for speed and performance. Examples include the Ferrari 488, Lamborghini Huracan, and Porsche 911.</p>
    </div>

    <div class="car" id="suv">
      <h2>SUVs</h2>
      <p>Sport Utility Vehicles (SUVs) are great for families and rough roads. Examples include the Toyota Fortuner, Ford Endeavour, and Hyundai Creta.</p>
    </div>

    <div class="car" id="electric">
      <h2>Electric Cars</h2>
      <p>Electric cars are eco-friendly and powered by batteries. Examples include the Tesla Model 3, Tata Nexon EV, and MG ZS EV.</p>
    </div>
  </section>

  <footer>
    <p>&copy; 2025 Car EduZone | Learn More, Drive Smarter!</p>
  </footer>
</body>
</html>

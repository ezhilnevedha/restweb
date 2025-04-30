# Ex.07 Restaurant Website
## Date:30-04-2025
## Name: Ezhil Nevedha K-212223230055
## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

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
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Little Lemon Restaurant</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: url('pasta.png') no-repeat center center fixed;
      background-size: cover;
      color: #fff;
    }


    .navbar {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 15px 30px;
      background-color: rgba(114, 68, 68, 0.7);
    }

    .navbar .logo {
      font-size: 24px;
      font-weight: bold;
      color: #706742;
    }

    .hero {
      text-align: center;
      padding: 100px 20px;
    }

    .hero h1 {
      font-size: 48px;
      margin-bottom: 10px;
    }

    .hero p {
      font-size: 20px;
      margin-bottom: 20px;
    }

    .section {
      padding: 60px 20px;
      text-align: center;
    }

    .menu-container {
      display: flex;
      flex-direction: column;
      gap: 20px;
      max-width: 600px;
      margin: 0 auto;
    }

    .card {
      background-color: rgba(114, 68, 67, 0.7);
      padding: 15px;
      border-radius: 10px;
      backdrop-filter: blur(5px);
    }

    .card img {
      width: 100%;
      border-radius: 10px;
      margin-bottom: 10px;
    }

    .card h3 {
      color: #706742;
    }

    .price {
      font-weight: bold;
      color: #706742;
    }

    .footer {
      text-align: center;
      padding: 20px;
      background-color: rgba(0, 0, 0, 0.7);
      font-size: 14px;
    }

    @media (min-width: 700px) {
      .menu-container {
        flex-direction: row;
        flex-wrap: wrap;
        justify-content: center;
      }

      .card {
        width: 250px;
      }
    }
  </style>
</head>
<body>
  <div class="overlay">

    <nav class="navbar">
      <div class="logo">Little Lemon</div>
    </nav>

    <header class="hero">
      <h1>Welcome to Little Lemon</h1>
      <p>Delicious food, made with love.</p>
    </header>

    <section class="section">
      <h2>About Us</h2>
      <p>We serve fresh, flavorful dishes using authentic ingredients and traditional recipes.</p>
    </section>

    <section class="section">
      <h2>Our Menu</h2>
      <div class="menu-container">
        <div class="card">
          <img src="https://images.pexels.com/photos/5560763/pexels-photo-5560763.jpeg" alt="Dosa">
          <h3>Dosa</h3>
          <p>Crispy South Indian dosa with chutney.</p>
          <p class="price">Rs. 30</p>
        </div>
        <div class="card">
          <img src="https://images.pexels.com/photos/28674705/pexels-photo-28674705.jpeg" alt="Dal Rice">
          <h3>Dal Rice</h3>
          <p>Comforting dal with steamed rice.</p>
          <p class="price">Rs. 50</p>
        </div>
        <div class="card">
          <img src="https://images.pexels.com/photos/29333631/pexels-photo-29333631.jpeg" alt="Coffee">
          <h3>Coffee</h3>
          <p>Freshly brewed aromatic coffee.</p>
          <p class="price">Rs. 10</p>
        </div>
      </div>
    </section>

    <section class="section">
      <h2>Contact Us</h2>
      <p>Email: littlelemon@example.com</p>
      <p>Phone: +91 12345 67890</p>
      <p>Location: Main Street, Chennai, India</p>
    </section>

    <footer class="footer">
      &copy; 2025 Little Lemon Restaurant. All rights reserved.
    </footer>

  </div>
</body>
</html>
/html>
```

## OUTPUT:
![alt text](<Screenshot 2025-04-30 113401.png>)
![alt text](<Screenshot 2025-04-30 113414.png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.

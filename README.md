# shree-pawan-transport-<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Shree Pawan Transport</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #f9f9f9;
      color: #333;
    }
    header {
      background-color: #003366;
      color: white;
      padding: 1em 2em;
      text-align: center;
    }
    nav {
      background: #0055a5;
      padding: 0.5em;
      text-align: center;
    }
    nav a {
      color: white;
      margin: 0 1em;
      text-decoration: none;
      font-weight: bold;
    }
    section {
      padding: 2em;
      max-width: 1000px;
      margin: auto;
    }
    .booking-form {
      background: #fff;
      padding: 1em;
      border-radius: 5px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    .booking-form input,
    .booking-form textarea,
    .booking-form button {
      width: 100%;
      padding: 0.7em;
      margin: 0.5em 0;
      border: 1px solid #ccc;
      border-radius: 5px;
      box-sizing: border-box;
    }
    footer {
      background-color: #003366;
      color: white;
      text-align: center;
      padding: 1em;
      margin-top: 2em;
    }
    @media screen and (max-width: 768px) {
      nav a {
        display: block;
        margin: 0.5em 0;
      }
      section {
        padding: 1em;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>Shree Pawan Transport</h1>
    <p>Reliable Truck Transportation from Ahmedabad to All India</p>
  </header>
  <nav>
    <a href="#services">Services</a>
    <a href="#booking">Book Online</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="services">
    <h2>Our Services</h2>
    <p>We provide efficient and safe truck transportation services from Ahmedabad to any location in India. Whether it's commercial goods or bulk consignments, we ensure on-time delivery with proper care.</p>
  </section>

  <section id="booking">
    <h2>Online Booking</h2>
    <div class="booking-form">
      <form>
        <label for="name">Your Name</label>
        <input type="text" id="name" name="name" required>

        <label for="phone">Phone Number</label>
        <input type="tel" id="phone" name="phone" required>

        <label for="pickup">Pickup Location</label>
        <input type="text" id="pickup" name="pickup" required>

        <label for="drop">Drop Location</label>
        <input type="text" id="drop" name="drop" required>

        <label for="details">Additional Details</label>
        <textarea id="details" name="details" rows="4"></textarea>

        <button type="submit">Submit Booking</button>
      </form>
    </div>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <p><strong>Phone:</strong> 9512572475</p>
    <p><strong>Email:</strong> shreepawant@gmail.com</p>
    <p><strong>Address:</strong> FF-6 Takshila Gallariya Mall, Vastral, Ahmedabad</p>
    <p><strong>Hours:</strong> 9 AM to 7 PM</p>
  </section>

  <footer>
    <p>&copy; 2025 Shree Pawan Transport. All rights reserved.</p>
  </footer>
</body>
</html>


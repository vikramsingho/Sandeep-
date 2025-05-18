# Sandeep-
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Online Car Booking</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: url('https://example.com/car-background.jpg') no-repeat center center fixed;
      background-size: cover;
      color: #00ffff;
    }

    header {
      background-color: rgba(0, 0, 0, 0.8);
      text-align: center;
      padding: 1em;
      font-size: 1.2em;
      color: #ff00ff;
      border-bottom: 2px solid #00ffff;
    }

    .booking-form {
      background-color: rgba(0, 0, 0, 0.7);
      max-width: 500px;
      margin: 50px auto;
      padding: 30px;
      border-radius: 10px;
      box-shadow: 0 0 15px #00ffff;
    }

    .booking-form input, .booking-form select, .booking-form button {
      width: 100%;
      padding: 10px;
      margin: 10px 0;
      border: none;
      border-radius: 5px;
      font-size: 1em;
    }

    .booking-form input, .booking-form select {
      background: #222;
      color: #0ff;
    }

    .booking-form button {
      background: #ff00ff;
      color: white;
      cursor: pointer;
    }

    footer {
      text-align: center;
      padding: 1em;
      background-color: rgba(0, 0, 0, 0.8);
      color: #ff00ff;
      position: fixed;
      bottom: 0;
      width: 100%;
      border-top: 2px solid #00ffff;
    }

    .contact-info {
      text-align: center;
      margin: 20px 0;
      color: #0ff;
    }

    .contact-info a {
      color: #ff00ff;
      text-decoration: none;
    }
  </style>
</head>
<body>
  <header>
    Warning: Price of CNG is Rs.13/km
  </header>

  <div class="booking-form">
    <h2>Book Your Ride</h2>
    <form>
      <input type="text" name="name" placeholder="Your Name" required>
      <input type="tel" name="phone" placeholder="Phone Number" required>
      <input type="date" name="date" required>
      <select name="car_type" required>
        <option value="">Select Car Type</option>
        <option value="sedan">Sedan</option>
        <option value="suv">SUV</option>
        <option value="hatchback">Hatchback</option>
      </select>
      <button type="submit">Book Now</button>
    </form>
  </div>

  <div class="contact-info">
    WhatsApp: 9050017441<br>
    Instagram: <a href="https://www.instagram.com/sandeep4764kumar" target="_blank">@sandeep4764kumar</a>
  </div>

  <footer>
    Price of Petrol is Rs.15/km
  </footer>
</body>
</html>

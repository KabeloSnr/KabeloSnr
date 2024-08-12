<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Contact Us - WaterFlow</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f4f4f4;
      color: #333;
    }

    header {
      background-color: #007BFF;
      color: white;
      padding: 20px 0;
      text-align: center;
    }

    header h1 {
      margin: 0;
      font-size: 2.5em;
    }

    .container {
      width: 80%;
      margin: 20px auto;
    }

    .contact-form {
      background-color: #f8f9fa;
      padding: 20px;
      border-radius: 10px;
    }

    .contact-form input,
    .contact-form textarea {
      width: 100%;
      padding: 10px;
      margin: 10px 0;
      border-radius: 5px;
      border: 1px solid #ccc;
    }

    .contact-form button {
      background-color: #28a745;
      color: white;
      padding: 10px 20px;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      font-size: 1.2em;
    }

    .contact-form button:hover {
      background-color: #218838;
    }

    footer {
      background-color: #333;
      color: white;
      text-align: center;
      padding: 20px 0;
      margin-top: 40px;
    }

    .product-images {
      display: flex;
      justify-content: space-around;
      align-items: center;
      margin-bottom: 20px;
    }

    .product-images img {
      max-width: 100%;
      height: auto;
      border-radius: 10px;
    }
  </style>
</head>

<body>

  <header>
    <h1>WaterFlow</h1>
    <p>Contact Us for Pure Water Delivery</p>
  </header>

  <div class="container">
    <!-- Display Images Next to Each Other -->
    <div class="product-images">
      <img src="https://static4.depositphotos.com/1001069/357/i/450/depositphotos_3573185-stock-photo-soda-water-bottle-with-blank.jpg" alt="Water bottle Stock Photos, Royalty Free Water bottle Images" width="250" height="150">
      <img id="dimg_31" src="data:image/jpeg;base64,/9j/4AAQSk..." alt="Image 2" width="250" height="150">
    </div>

    <div class="contact-form">
      <h2>Get in Touch</h2>
      <form action="#" method="POST">
        <input type="text" name="name" placeholder="Your Name" required>
        <input type="email" name="email" placeholder="Your Email" required>
        <textarea name="message" rows="5" placeholder="Your Message" required></textarea>
        <button type="submit">Send Message</button>
      </form>
    </div>
  </div>

  <footer>
    <p>&copy; 2024 WaterFlow. All Rights Reserved.</p>
  </footer>

</body>

</html>

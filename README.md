<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Accessible Me</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@100;500&family=Stick+No+Bills:wght@300&display=swap" rel="stylesheet">
  <style>
    body {
  font-family: 'Roboto', Helvetica, sans-serif;
  background-color: rgb(156, 63, 63);
  margin: 0;
  padding: 0;
}

h1,
h2,
h3,
h4,
h5,
h6 {
  font-family: 'Stick No Bills', 'Roboto', Helvetica, sans-serif;
}

.container {
  max-width: 1080px;
  margin: 0 auto;
  padding: 0 1rem;
}

img {
  width: 100%;
}

.main-nav ul {
  list-style: none;
  display: flex;
  flex-wrap: wrap;
  margin: 0;
  padding: 0;
}

.main-nav ul li {
  flex: 1;
  text-align: center;
}

.main-nav ul li a {
  display: block;
  color: inherit;
  text-decoration: none;
  font-size: 1.25rem;
}

form input,
form textarea {
  display: block;
  width: 100%;
  margin-bottom: 1rem;
  padding: .5rem 1rem;
}

form textarea {
  min-height: 150px;
  max-height: 150px;
  height: 150px;
  resize: none;
}

form button {
  background: none;
  border: 2px solid black;
  padding: 1rem;
  text-transform: uppercase;
}

.site-footer {
  padding: 2rem 0;
}
  </style>
</head>

<body>
  <div class="container">
    <div class="site-header">
      <h1>Ankush playing game</h1>
      <div class="main-nav">
        <ul>
          <li><a href="#">Home</a></li>
          <li><a href="#">Products</a></li>
          <li><a href="#">Reservation</a></li>
          <li><a href="#">Studio</a></li>
        </ul>
      </div>
      <img src="images/untitled-2791.webp" class="banner">
    </div>
    <div class="main-content">
      <h1>Welcome to ankush game zone</h1>
      <p>this is a playing zone to spend the spare time</p>
      <div class="owner">
        <h1>Meet the owner</h1>
        <ul>
          <li>Name: Ankush bansal</li>
          <li>Title: CEO</li>
          <li>Email: ankus376@gmail.com</li>
          <li>Phone: 613-000-0000</li>
        </ul>
        <h1>Address</h1>
        <p>
          ankush playing game
         657 wantajd 
         scarborough
        </p>
      </div>
      <div class="contact-section">
        <h1>Contact Us</h1>
        <form action="thanks.html">
          <label>Full Name</label>
          <input type="text" placeholder="Full Name">
          <input type="text" placeholder="Email">
          <input type="text" placeholder="Subject">
          <b>Your Message</b>
          <textarea></textarea>
          <button type="submit">Send</button>
        </form>
      </div>
    </div>
    <div class="site-footer">
      &copy; 2023 ankush
    </div>
  </div>
</body>

</html>

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Jollibee - Home</title>
  <link rel="stylesheet" href="styles.css" />
</head>
<body>
  <header>
    <h1>Welcome to Jollibee</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="about.html">About</a>
      <a href="products.html">Menu</a>
      <a href="login.html">Login</a>
      <a href="contact.html">Contact</a>
    </nav>
  </header>
  <main>
    <section>
      <h2>Bee Happy, Eat Happy!</h2>
      <p>Experience the joy of eating with Jollibee – the home of your favorite Filipino comfort food.</p>
      <img src="images/homepage-preview.jpg" alt="Jollibee Storefront" class="responsive-img">
    </section>
  </main>
  <footer>
    <p>&copy; 2025 Jollibee Foods Corporation</p>
  </footer>
</body>
</html>

<!-- File: about.html -->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>About Jollibee</title>
  <link rel="stylesheet" href="styles.css" />
</head>
<body>
  <header>
    <h1>About Jollibee</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="about.html">About</a>
      <a href="products.html">Menu</a>
      <a href="login.html">Login</a>
      <a href="contact.html">Contact</a>
    </nav>
  </header>
  <main>
    <section>
      <h2>Our Story</h2>
      <p>Founded in 1978, Jollibee is the Philippines' number one fast-food chain. Known for its famous Chickenjoy, Jolly Spaghetti, and Yumburgers, Jollibee brings joy to Filipino families both locally and worldwide.</p>
      <p>With a strong presence in over 30 countries, Jollibee continues to share its delicious meals and joyful culture to millions of customers every day.</p>
    </section>
  </main>
  <footer>
    <p>&copy; 2025 Jollibee Foods Corporation</p>
  </footer>
</body>
</html>

<!-- File: products.html -->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Jollibee Menu</title>
  <link rel="stylesheet" href="styles.css" />
</head>
<body>
  <header>
    <h1>Jollibee Menu</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="about.html">About</a>
      <a href="products.html">Menu</a>
      <a href="login.html">Login</a>
      <a href="contact.html">Contact</a>
    </nav>
  </header>
  <main>
    <section>
      <h2>Customer Favorites</h2>
      <ul>
        <li><strong>Chickenjoy</strong> - Crispy on the outside, tender and juicy on the inside</li>
        <li><strong>Jolly Spaghetti</strong> - Sweet-style Filipino spaghetti with hotdog and cheese</li>
        <li><strong>Yumburger</strong> - Jollibee’s signature burger with special dressing</li>
        <li><strong>Burger Steak</strong> - Burger patties with savory mushroom gravy and rice</li>
      </ul>
      <img src="images/services-sample.jpg" alt="Jollibee Food Items" class="responsive-img">
    </section>
  </main>
  <footer>
    <p>&copy; 2025 Jollibee Foods Corporation</p>
  </footer>
</body>
</html>

<!-- File: login.html -->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Login to Jollibee</title>
  <link rel="stylesheet" href="styles.css" />
  <script>
    function login() {
      const username = document.getElementById("username").value;
      const password = document.getElementById("password").value;
      if (username === "admin" && password === "jollibee") {
        alert("Login successful!");
        window.location.href = "index.html";
      } else {
        alert("Invalid login credentials.");
      }
    }
  </script>
</head>
<body>
  <header>
    <h1>Login Page</h1>
  </header>
  <main>
    <section>
      <label>Username: <input type="text" id="username" /></label><br />
      <label>Password: <input type="password" id="password" /></label><br />
      <button onclick="login()">Login</button>
    </section>
  </main>
  <footer>
    <p>&copy; 2025 Jollibee Foods Corporation</p>
  </footer>
</body>
</html>

<!-- File: contact.html -->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Contact Jollibee</title>
  <link rel="stylesheet" href="styles.css" />
</head>
<body>
  <header>
    <h1>Contact Jollibee</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="about.html">About</a>
      <a href="products.html">Menu</a>
      <a href="login.html">Login</a>
      <a href="contact.html">Contact</a>
    </nav>
  </header>
  <main>
    <section>
      <form>
        <label>Name:<br /><input type="text" name="name" required></label><br />
        <label>Email:<br /><input type="email" name="email" required></label><br />
        <label>Message:<br /><textarea name="message" required></textarea></label><br />
        <button type="submit">Send</button>
      </form>
    </section>
  </main>
  <footer>
    <p>&copy; 2025 Jollibee Foods Corporation</p>
  </footer>
</body>
</html>

<!-- File: styles.css -->
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  background-color: #fff8f0;
  color: #333;
}
header {
  background-color: #d9232e;
  color: #fff;
  padding: 1rem;
  text-align: center;
}
nav a {
  margin: 0 15px;
  color: #fff;
  text-decoration: none;
}
nav a:hover {
  text-decoration: underline;
}
main {
  padding: 20px;
}
footer {
  background-color: #d9232e;
  color: #fff;
  text-align: center;
  padding: 10px;
  position: fixed;
  bottom: 0;
  width: 100%;
}
section {
  margin: 2rem 0;
}
.responsive-img {
  max-width: 100%;
  height: auto;
  border-radius: 8px;
}
form input, form textarea {
  width: 100%;
  padding: 8px;
  margin-top: 5px;
  margin-bottom: 10px;
  border: 1px solid #ccc;
  border-radius: 4px;
}
form button {
  background-color: #fbc02d;
  color: #000;
  padding: 10px 15px;
  border: none;
  border-radius: 4px;
  cursor: pointer;
}
form button:hover {
  background-color: #f9a825;
}
@media (max-width: 600px) {
  nav a {
    display: block;
    margin: 10px 0;
  }
}

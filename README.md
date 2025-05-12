# Ex.07 Restaurant Website
# Date:09/05/2025
# AIM:
To develop a static Restaurant website to display the food items and services provided by them.

# DESIGN STEPS:
## Step 1:
Requirement collection.

## Step 2:
Creating the layout using HTML and CSS.

## Step 3:
Updating the sample content.

## Step 4:
Choose the appropriate style and color scheme.

## Step 5:
Validate the layout in various browsers.

## Step 6:
Validate the HTML code.

## Step 7:
Publish the website in the given URL.

# PROGRAM:
index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Home - SPICY STORY</title>
  <link rel="stylesheet" href="index.css">
</head>
<body>
  <header>
    <h1>Welcome to SPICY STORY</h1>
  </header>
  <nav>
    <a href="index.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="admin.html">Administration</a>
    <a href="contact.html">Contact Us</a>
  </nav>
  <div class="banner"></div>
  <div class="container">
    <h2>About Us</h2>
    <p>Quality ingredients, friendly staff, good friends, memorable moments</p>
  </div>
  <footer>
    <p>Website designed by nakshu</p>
  </footer>
</body>
</html>
 
index.css
body {
    margin: 0;
    font-family: Arial, sans-serif;
    background-image: url('back.jpg');
    background-size: cover;
    background-repeat: no-repeat;
    background-attachment: fixed;
    background-position: center;
    color: #fff;
    min-height: 100vh;
    display: flex;
    flex-direction: column;
  }
  
  .container {
    width: 90%;
    max-width: 800px;
    margin: 30px auto;
    background-color: rgba(0, 0, 0, 0.6); /* semi-transparent bg */
    padding: 20px;
    border-radius: 10px;
  }
  
  header, nav, footer {
    text-align: center;
    padding: 20px;
  }
  
  nav {
    background-color: rgba(255, 255, 255, 0.2);
  }
  
  nav a {
    color: #fff;
    text-decoration: none;
    margin: 0 15px;
    font-weight: bold;
  }
  
  footer {
    background-color: rgba(0, 0, 0, 0.6);
  }

```
menu.html
```
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Menu</title>
<link rel="stylesheet" href="menu.css">
</head>
<body>
<header>
  <h1>Our Menu</h1>
</header>
<nav>
  <a href="index.html">Home</a>
  <a href="menu.html">Menu</a>
  <a href="admin.html">Administration</a>
  <a href="contact.html">Contact Us</a>
</nav>
<div class="container">
  <div class="menu-grid">
    <!-- Repeat for 12 items -->
    <div class="item">
      <img src="biryani.jpg" alt="Biryani">
      <h3>Biryani</h3>
      <p>Rs.399</p>
    </div>
    <div class="item">
      <img src="chicken lollipop.jpg" alt="Chicken lollipop">
      <h3>Chicken lollipop</h3>
      <p>Rs.210</p>
    </div>
    <div class="item">
      <img src="fr.jpg" alt="Prawn Fried Rice">
      <h3>Prawn Fried Rice</h3>
      <p>Rs.180</p>
    </div>
    <div class="item">
      <img src="m.jpg" alt="Mojito">
      <h3>Mojito</h3>
      <p>Rs.590</p>
    </div>
    <div class="item">
      <img src="f.jpg" alt="Falooda">
      <h3>Falooda</h3> 
      <p>Rs.185</p>
    </div>
    <div class="item">
      <img src="naan'.jpg" alt="Naan">
      <h3>Naan</h3>
      <p>Rs.150</p>
    </div>
    <div class="item">
      <img src="p.jpg" alt="pasta">
      <h3>Pasta</h3>
      <p>Rs.240</p>
    </div>
    <!-- Add 10 more -->
  </div>
</div>
<footer>
  <p>Website designed by nakshu</p>
</footer>
</body>
</html>
```
menu.css
```
body {
  font-family: sans-serif;
  background-color: #fdf6ec;
  margin: 0;
}

header {
  background-color: #8B0000;
  color: white;
  padding: 20px;
  text-align: center;
}

nav {
  background-color: #eee;
  text-align: center;
  padding: 10px;
}

nav a {
  margin: 0 15px;
  text-decoration: none;
  color: #8B0000;
}

.container {
  padding: 20px;
}

.menu-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 20px;
}

.item {
  background-color: white;
  padding: 10px;
  text-align: center;
  border: 1px solid #ccc;
}

.item img {
  width: 100%;
  height: 200px;
  object-fit: cover;
}

footer {
  background-color: #8B0000;
  color: white;
  text-align: center;
  padding: 10px;
}
```
admin.html
```
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Administration</title>
<link rel="stylesheet" href="admin.css">
</head>
<body>
<header>
  <h1>Our Team</h1>
</header>
<nav>
  <a href="index.html">Home</a>
  <a href="menu.html">Menu</a>
  <a href="admin.html">Administration</a>
  <a href="contact.html">Contact Us</a>
</nav>
<div class="container">
  <div class="team">
    <!-- Repeat for 6 members -->
    <div class="member">
      <img src="demi.jpg" alt="Chef">
      <h3>Demi david</h3>
      <p>Head Chef</p>
    </div>
    <div class="member">
      <img src="max.jpg" alt="Manager">
      <h3>Max jemima</h3>
      <p>Manager</p>
    <!-- 4 more -->
  </div>
</div>
<footer>
  <p>Website designed by nakshu</p>
</footer>
</body>
</html>
```
admin.css
```
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Administration</title>
<link rel="stylesheet" href="admin.css">
</head>
<body>
<header>
  <h1>Our Team</h1>
</header>
<nav>
  <a href="index.html">Home</a>
  <a href="menu.html">Menu</a>
  <a href="admin.html">Administration</a>
  <a href="contact.html">Contact Us</a>
</nav>
<div class="container">
  <div class="team">
    <!-- Repeat for 6 members -->
    <div class="member">
      <img src="demi.jpg" alt="Chef">
      <h3>Demi david</h3>
      <p>Head Chef</p>
    </div>
    <div class="member">
      <img src="max.jpg" alt="Manager">
      <h3>Max jemima</h3>
      <p>Manager</p>
    <!-- 4 more -->
  </div>
</div>
<footer>
  <p>Website designed by nakshu</p>
</footer>
</body>
</html>
```
contact.html
```
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Contact Us</title>
<link rel="stylesheet" href="contact.css">
</head>
<body>
<header>
  <h1>Contact Us</h1>
</header>
<nav>
  <a href="index.html">Home</a>
  <a href="menu.html">Menu</a>
  <a href="admin.html">Administration</a>
  <a href="contact.html">Contact Us</a>
</nav>
<div class="container">
  <h2>Reach Out to Us</h2>
  <p><strong>Address:</strong>murugesh nagar,pallipadai,vandigate,chidambaram </p>
  <p><strong>Phone:</strong>9015487872</p>
  <p><strong>Email:</strong> spicystory@gmail.com</p>
</div>
<footer>
  <p>Website designed by nakshu</p>
</footer>
</body>
</html>
```
contact.css
```
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Contact Us</title>
<link rel="stylesheet" href="contact.css">
</head>
<body>
<header>
  <h1>Contact Us</h1>
</header>
<nav>
  <a href="index.html">Home</a>
  <a href="menu.html">Menu</a>
  <a href="admin.html">Administration</a>
  <a href="contact.html">Contact Us</a>
</nav>
<div class="container">
    <h2>Reach Out to Us</h2>
    <p><strong>Address:</strong>murugesh nagar,pallipadai,vandigate,chidambaram </p>
    <p><strong>Phone:</strong>9015487872</p>
    <p><strong>Email:</strong> spicystory@gmail.com</p>
</div>
<footer>
  <p>Website designed by nakshu</p>
</footer>
</body>
</html>
```



# OUTPUT:

![alt text](<Screenshot 2025-05-13 005701.png>)

![alt text](<Screenshot 2025-05-09 201125.png>)

![alt text](<Screenshot 2025-05-09 201301.png>)

![alt text](<Screenshot 2025-05-13 005347.png>)
# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.

# Ex.07 Restuarant Website
## Date:01/11/2025

## AIM:
To develop a static Resturant website to display the menu and services provided by the resturant.

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
index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Fusion Feast - Home</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <img src="static/Fusion feast logo.png" alt="Fusion Feast Logo" class="logo">
    <nav>
      <a href="index.html" class="active">Home</a>
      <a href="menu.html">Menu</a>
      <a href="contact.html">Contact</a>
      <a href="admin.html">Admin</a>
    </nav>
  </header>

  <main>
    <section class="hero">
      <img src="static/homepage.jpeg" alt="Restaurant" class="hero-img">
      <div class="hero-text">
        <h1>Welcome to Fusion Feast</h1>
        <p>Where taste meets passion. Explore a variety of cuisines crafted with love!</p>
        <a href="menu.html" class="btn">Explore Menu</a>
      </div>
    </section>
  </main>

  <footer>
    <p>© 2025 Fusion Feast. All Rights Reserved.</p>
  </footer>
</body>
</html>
```
menu.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Menu - Fusion Feast</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <img src="static/Fusion feast logo.png" alt="Fusion Feast Logo" class="logo">
    <nav>
      <a href="index.html">Home</a>
      <a href="menu.html" class="active">Menu</a>
      <a href="contact.html">Contact</a>
      <a href="admin.html">Admin</a>
    </nav>
  </header>

  <main>
    <h1>Our Signature Dishes</h1>
    <div class="gallery">
      <img src="static/fish.jpeg" alt="Fish Dish">
      <img src="static/pasta.jpeg" alt="Pasta">
      <img src="static/juice.jpeg" alt="Juice">
      <img src="static/chef.jpeg" alt="Chef Special">
      <img src="static/table.jpeg" alt="Table Setup">
    </div>
  </main>

  <footer>
    <p>© 2025 Fusion Feast. Taste Beyond Borders.</p>
  </footer>
</body>
</html>
```
home.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Fusion Feast | Home</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <div class="logo">
      <img src="static/Fusion feast logo.png" alt="Logo">
      <h1>Fusion Feast</h1>
    </div>
    <nav>
      <a href="index.html" class="active">Home</a>
      <a href="menu.html">Menu</a>
      <a href="admin.html">Admin</a>
      <a href="contact.html">Contact Us</a>
    </nav>
  </header>

  <!-- Hero Section -->
  <section class="hero">
    <img src="static/about.jpeg" alt="Fusion Feast Background">
    <div class="hero-text">
      <h2>Welcome to Fusion Feast</h2>
      <p>Where global flavors meet local love 🍴</p>
      <a href="menu.html" class="btn">Explore Menu</a>
    </div>
  </section>

  <!-- About Section -->
  <section class="about">
    <img src="static/about.jpeg" alt="About Fusion Feast">
    <div>
      <h2>About Us</h2>
      <p>Fusion Feast is a cozy space where flavors from around the world unite. From classic recipes to modern creations, we blend cuisines to give you an unforgettable dining experience.</p>
    </div>
  </section>

  <footer>
    <p>© 2025 Fusion Feast | Designed by Reshika</p>
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
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Contact - Fusion Feast</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <img src="static/Fusion feast logo.png" alt="Fusion Feast Logo" class="logo">
    <nav>
      <a href="index.html">Home</a>
      <a href="menu.html">Menu</a>
      <a href="contact.html" class="active">Contact</a>
      <a href="admin.html">Admin</a>
    </nav>
  </header>

  <main>
    <h1>Contact Us</h1>
    <p>We’d love to hear from you! Reach out using the form below.</p>
    <form class="contact-form">
      <input type="text" placeholder="Your Name" required>
      <input type="email" placeholder="Email Address" required>
      <textarea placeholder="Your Message" rows="5"></textarea>
      <button type="submit" class="btn">Send Message</button>
    </form>
  </main>

  <footer>
    <p>📍 123 Flavor Street, Chennai | ☎ +91 98765 43210</p>
  </footer>
</body>
</html>
```
admin.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Admin - Fusion Feast</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <img src="static/Fusion feast logo.png" alt="Fusion Feast Logo" class="logo">
    <nav>
      <a href="index.html">Home</a>
      <a href="menu.html">Menu</a>
      <a href="contact.html">Contact</a>
      <a href="admin.html" class="active">Admin</a>
    </nav>
  </header>

  <main>
    <h1>Admin Login</h1>
    <form class="contact-form">
      <input type="text" placeholder="Username" required>
      <input type="password" placeholder="Password" required>
      <button type="submit" class="btn">Login</button>
    </form>
  </main>

  <footer>
    <p>© 2025 Fusion Feast Admin Panel</p>
  </footer>
</body>
</html>
```


## OUTPUT:
<img width="1919" height="1084" alt="Screenshot 2025-11-01 231756" src="https://github.com/user-attachments/assets/3f084a5a-448a-4be0-978a-943293b1faf1" />

<img width="1894" height="1088" alt="Screenshot 2025-11-01 232925" src="https://github.com/user-attachments/assets/3e3b46cb-31b5-4fc5-9368-654218abcc5c" />

<img width="1912" height="1092" alt="Screenshot 2025-11-01 231817" src="https://github.com/user-attachments/assets/69f4a9c7-0162-4dd3-84fc-4d7c7567c62f" />

<img width="1918" height="1092" alt="Screenshot 2025-11-01 231832" src="https://github.com/user-attachments/assets/cf400da6-b51c-48a8-b88e-c938b06bb9ee" />


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.

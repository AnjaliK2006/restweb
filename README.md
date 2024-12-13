# Ex.07 Restaurant Website
## Date: 13.12.2024

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
food.html

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>JAKK RESTAURANT</title>
    <style>
        body {
            font-family: 'Georgia', serif;
            margin: 0;
            padding: 0;
            background: url('Screenshot 2024-12-13 095914.png') no-repeat center center fixed;
            background-size: cover;
            color: #36032b;
        }

        header {
            background-color: rgba(180, 145, 172, 0.8); 
            color: rgb(67, 7, 7);
            padding: 20px;
            text-align: center;
        }

        header h1 {
            font-weight: 400;
        }

        header nav ul {
            list-style-type: none;
            padding: 0;
            margin: 0;
        }

        header nav ul li {
            display: inline;
            margin: 0 20px;
        }

        header nav ul li a {
            color: rgb(65, 6, 6);
            text-decoration: none;
        }

        header nav ul li a:hover {
            color: #16a085;
            font-weight: bold;
        }

        .container {
            width: 90%;
            max-width: 1200px;
            margin: 20px auto;
            text-align: center;
            background-color: rgba(255, 255, 255, 0.8); 
            padding: 20px;
            border-radius: 15px;
        }

        h2 {
            color: #2980b9;
        }

        footer {
            background-color: rgba(173, 131, 170, 0.9); 
            color: rgb(80, 10, 10);
            text-align: center;
            padding: 15px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }

        footer p {
            margin: 0;
        }

        ::-webkit-scrollbar {
            width: 5px;
        }

        ::-webkit-scrollbar-thumb {
            background-color: #16a085;
            border-radius: 10px;
        }
    </style>
</head>

<body>
    <header>
        <h1>JAKK RESTAURANT</h1>
        <nav>
            <ul>
                <li><a href="food.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <section class="container">
        <h2>Welcome to Our Restaurant</h2>
        <p>Experience the finest dining with us. Enjoy our delicious menu, excellent service, and a cozy atmosphere.</p>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2024 JAKK RESTAURANT | Designed by Anjali.K </p>
        </div>
    </footer>
</body>

</html>

menu.html

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MENU - JAKK RESTAURANT</title>
    <style>
        body {
            font-family: 'Verdana', sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(to bottom, #f0e5d8, #d9c9b5);
            color: #333;
        }

        header {
            background-color: #340202;
            color: white;
            padding: 20px;
            text-align: center;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }

        header h1 {
            font-weight: 700;
            letter-spacing: 2px;
        }

        header nav ul {
            list-style-type: none;
            padding: 0;
            margin: 0;
        }

        header nav ul li {
            display: inline;
            margin: 0 15px;
        }

        header nav ul li a {
            color: white;
            text-decoration: none;
            font-weight: bold;
            padding: 5px 10px;
            border-radius: 5px;
            transition: background-color 0.3s, color 0.3s;
        }

        header nav ul li a:hover {
            background-color: #360311;
            color: #f7f1e3;
        }

        .menu-container {
            width: 90%;
            max-width: 1200px;
            margin: 20px auto 100px auto;
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
            gap: 20px;
        }

        .menu-item {
            width: 28%;
            background: rgba(255, 255, 255, 0.8);
            padding: 15px;
            border-radius: 15px;
            display: flex;
            flex-direction: column;
            align-items: center;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.15);
            transition: transform 0.3s, box-shadow 0.3s;
        }

        .menu-item:hover {
            transform: translateY(-5px);
            box-shadow: 0 6px 15px rgba(0, 0, 0, 0.2);
        }

        .menu-item img {
            width: 100px;
            height: 100px;
            border-radius: 50%;
            margin-bottom: 10px;
        }

        .menu-item h3 {
            margin: 10px 0;
            font-size: 1.2em;
            color: #8e44ad;
        }

        .menu-item p {
            text-align: center;
            font-size: 0.9em;
            color: #555;
        }

        footer {
            background-color: #350304;
            color: white;
            text-align: center;
            padding: 15px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
            box-shadow: 0 -4px 8px rgba(0, 0, 0, 0.2);
        }

        footer p {
            margin: 0;
            font-size: 0.9em;
        }

        ::-webkit-scrollbar {
            width: 8px;
        }

        ::-webkit-scrollbar-thumb {
            background-color: #8e44ad;
            border-radius: 10px;
        }
    </style>
</head>

<body>
    <header>
        <h1>OUR MENU</h1>
        <nav>
            <ul>
                <li><a href="food.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <div class="menu-container">
        <div class="menu-item">
            <img src="Screenshot 2024-12-13 103410.png" alt="biryani">
            <h3>BIRYANI</h3>
            <p>A vibrant rice dish with mixed vegetables, chicken or mutton, and an egg.</p>
        </div>
        <div class="menu-item">
            <img src="Screenshot 2024-12-13 103557.png" alt="NON VEG MEALS">
            <h3>NON VEG MEALS</h3>
            <p>Rice with chicken, mutton, fish gravy with rotti and chicken starters.</p>
        </div>
        <div class="menu-item">
            <img src="burger.png" alt="Naan">
            <h3>BURGER</h3>
            <p>Soft and fluffy buns stuffed with chicken and cheese.</p>
        </div>
        <div class="menu-item">
            <img src="Screenshot 2024-12-13 104021.png" alt="chicken65">
            <h3>CHICKEN 65</h3>
            <p>Fresh chicken fried with Indian spices for a crispy delight.</p>
        </div>
        <div class="menu-item">
            <img src="grill.png" alt="chickenlollipop">
            <h3>GRILL CHICKEN</h3>
            <p>Juicy chicken with a tangy Korean-inspired sauce.</p>
        </div>
        <div class="menu-item">
            <img src="Screenshot 2024-12-13 104438.png" alt="butterchicken">
            <h3>BUTTER CHICKEN</h3>
            <p>Rich, creamy, and flavorful chicken curry in buttery sauce.</p>
        </div>
        <div class="menu-item">
            <img src="Screenshot 2024-12-13 104607.png" alt="mutton">
            <h3>MUTTON GRAVY</h3>
            <p>Mouth-watering mutton curry with aromatic Indian spices.</p>
        </div>
        <div class="menu-item">
            <img src="Screenshot 2024-12-13 104800.png" alt="prawnthokku">
            <h3>PRAWNTHOKKU</h3>
            <p>Succulent prawns cooked in a tangy, spicy Indian sauce.</p>
        </div>
        <div class="menu-item">
            <img src="soda.jpg" alt="crabsoup">
            <h3>SOFT DRINK</h3>
            <p>A refreshing and tasty soft drinks for digestion.</p>
        </div>
        <div class="menu-item">
            <img src="Screenshot 2024-12-13 105014.png" alt="attukalsoup">
            <h3>ATTUKAL SOUP</h3>
            <p>A hearty and flavorful bone soup for a warm beginning.</p>
        </div>
        <div class="menu-item">
            <img src="ice.png" alt="elaneerpayasam">
            <h3>ICECREAM</h3>
            <p>A cold dessert for fulfilling your delicious meal.</p>
        </div>
        <div class="menu-item">
            <img src="fries.png" alt="jigarthanda">
            <h3>FRENCH FRIES</h3>
            <p>A hot and salty snacks.</p>
        </div>
    </div>

    <footer>
        <p>&copy; 2024 Designed by ANJALI.K </p>
    </footer>
</body>

</html>

administration.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ADMINISTRATION - JAKK RESTAURANT</title>
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #7c9dcf;
            color: #333;
        }

        header {
            background-color: #38040e;
            color: white;
            padding: 15px;
            text-align: center;
        }

        header h1 {
            font-weight: 500;
            margin: 0;
        }

        header nav ul {
            list-style-type: none;
            padding: 0;
            margin: 0;
            display: flex;
            justify-content: center;
        }

        header nav ul li {
            margin: 0 15px;
        }

        header nav ul li a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }

        header nav ul li a:hover {
            color: #ffab40;
        }

        .admin-container {
            width: 90%;
            margin: 20px auto;
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
        }

        .admin-card {
            width: 240px;
            padding: 20px;
            background-color: #ffffff;
            border: 1px solid #e0e0e0;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            text-align: center;
            transition: transform 0.3s, box-shadow 0.3s;
        }

        .admin-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.2);
        }

        .admin-card img {
            width: 120px;
            height: 120px;
            border-radius: 50%;
            margin-bottom: 15px;
        }

        .admin-card h3 {
            margin: 10px 0 5px;
            font-size: 1.2em;
            color: #283593;
        }

        .admin-card p {
            font-size: 0.9em;
            color: #555;
        }

        footer {
            background-color: #2d0202;
            color: white;
            text-align: center;
            padding: 15px 0;
            margin-top: 20px;
        }

        footer p {
            margin: 0;
            font-size: 0.9em;
        }

        ::-webkit-scrollbar {
            width: 10px;
        }

        ::-webkit-scrollbar-thumb {
            background-color: #3f51b5;
            border-radius: 10px;
        }
    </style>
</head>
<body>
<header>
    <h1>ADMINISTRATION TEAM</h1>
    <nav>
        <ul>
            <li><a href="food.html">HOME</a></li>
            <li><a href="menu.html">MENU</a></li>
            <li><a href="administration.html">ADMINISTRATION</a></li>
            <li><a href="contact.html">CONTACT US</a></li>
        </ul>
    </nav>
</header>

<div class="admin-container">
    <div class="admin-card">
        <img src="anjali.png" alt="Owner">
        <h3>ANJALI</h3>
        <p>Owner</p>
        <p>Visionary leader ensuring the success of JAKK Restaurant.</p>
    </div>
    <div class="admin-card">
        <img src="Screenshot 2024-12-13 105905.png" alt="Executive Chef">
        <h3>JOSEPH VIJAY</h3>
        <p>Executive Chef</p>
        <p>Mastermind behind our exquisite menu and culinary excellence.</p>
    </div>
    <div class="admin-card">
        <img src="kabilan.png" alt="Operations Manager">
        <h3>KABILAN</h3>
        <p>Operations Manager</p>
        <p>Ensures smooth day-to-day operations and exceptional service.</p>
    </div>
    <div class="admin-card">
        <img src="jayanthi.png" alt="Customer Experience Manager">
        <h3>JAYANTHI</h3>
        <p>Customer Experience Manager</p>
        <p>Focuses on guest satisfaction and memorable dining experiences.</p>
    </div>
    <div class="admin-card">
        <img src="kumaran.png" alt="Beverage Specialist">
        <h3>KUMARAN</h3>
        <p>Beverage Specialist</p>
        <p>Crafts refreshing and unique drinks to complement every meal.</p>
    </div>
    <div class="admin-card">
        <img src="keerthy.png" alt="Front Desk Manager">
        <h3>KEERTHY SURESH</h3>
        <p>Front Desk Manager</p>
        <p>Welcomes guests and manages reservations with a smile.</p>
    </div>
</div>

<footer>
    <p>&copy; 2024 Designed by ANJALI.K</p>
</footer>
</body>
</html>

contact.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CONTACT US - JAKK RESTAURANT</title>
    <style>
        body {
            font-family: 'Verdana', sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(to bottom, #d5f3fe, #ffffff);
            color: #333;
        }

        header {
            background-color: #34020c;
            color: white;
            padding: 20px;
            text-align: center;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }

        header h1 {
            font-weight: 700;
            letter-spacing: 2px;
        }

        header nav ul {
            list-style-type: none;
            padding: 0;
            margin: 0;
        }

        header nav ul li {
            display: inline;
            margin: 0 15px;
        }

        header nav ul li a {
            color: rgb(172, 210, 116);
            text-decoration: none;
            font-weight: bold;
            padding: 5px 10px;
            border-radius: 5px;
            transition: background-color 0.3s, color 0.3s;
        }

        header nav ul li a:hover {
            background-color: #8151b7;
            color: #f7f1e3;
        }

        .contact-container {
            width: 70%;
            margin: 50px auto;
            padding: 30px;
            background: rgba(132, 107, 107, 0.9);
            border-radius: 15px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.15);
        }

        .contact-container h2 {
            text-align: center;
            margin-bottom: 20px;
            color: #6b3fa0;
            font-size: 1.8em;
        }

        .contact-item {
            margin-bottom: 20px;
            text-align: center;
        }

        .contact-item label {
            font-weight: bold;
            font-size: 1.2em;
        }

        .contact-item p {
            margin: 5px 0;
            font-size: 1.1em;
            color: #555;
        }

        .contact-item a {
            color: #6b3fa0;
            text-decoration: none;
            font-weight: bold;
            transition: color 0.3s;
        }

        .contact-item a:hover {
            color: #a569bd;
        }

        footer {
            background-color: #3c030c;
            color: white;
            text-align: center;
            padding: 15px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
            box-shadow: 0 -4px 8px rgba(0, 0, 0, 0.2);
        }

        footer p {
            margin: 0;
            font-size: 0.9em;
        }

        ::-webkit-scrollbar {
            width: 8px;
        }

        ::-webkit-scrollbar-thumb {
            background-color: #6b3fa0;
            border-radius: 10px;
        }
    </style>
</head>
<body>
<header>
    <h1>CONTACT US</h1>
    <nav>
        <ul>
            <li><a href="food.html">Home</a></li>
            <li><a href="menu.html">Menu</a></li>
            <li><a href="administration.html">Administration</a></li>
            <li><a href="contact.html">Contact Us</a></li>
        </ul>
    </nav>
</header>

<div class="contact-container">
    <h2>We Would Love to Hear from You</h2>
    <div class="contact-item">
        <label>Email:</label>
        <p><a href="mailto:info@jakkrestaurant.com">info@jakkrestaurant.com</a></p>
    </div>
    <div class="contact-item">
        <label>Phone:</label>
        <p><a href="tel:+919444079833">9444079833</a></p>
    </div>
    <div class="contact-item">
        <label>Address:</label>
        <p>Redhills, Chennai-52, Tamil Nadu</p>
    </div>
    <div class="contact-item">
        <label>Operating Hours:</label>
        <p>Monday - Sunday: 10:00 AM - 11:00 PM</p>
    </div>
    <div class="contact-item">
        <label>Follow Us:</label>
        <p>
            <a href="#" target="_blank">Facebook</a> | 
            <a href="#" target="_blank">Instagram</a> | 
            <a href="#" target="_blank">Twitter</a>
        </p>
    </div>
</div>

<footer>
    <p>&copy; 2024 Designed by ANJALI.K | All rights reserved</p>
</footer>
</body>
</html>

```


## OUTPUT:
![alt text](<Screenshot (26).png>)
![alt text](<Screenshot (27).png>)
![alt text](<Screenshot (28).png>)
![alt text](<Screenshot (29).png>)
![alt text](<Screenshot (30).png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.

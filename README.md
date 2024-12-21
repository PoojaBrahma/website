# Ex.07 Restaurant Website
# Date:02.12.2024
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
``` python
restaurant menu

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Restaurant menu</title>
</head>
<style>
    body{
        background-image: url("restaurant background.jpg");
        background-size: cover;
    }
    .ref{
        position: absolute;
        font-size: 400%;
        top: 55%;
        left: 5%;
    }
    .ref1 a{
        font-size: 142%;
        position: relative;
        top: 420px;
    }
    header{
        font-size: 568%;
    }
    nav {
            background-color:#333;
            padding: 10px;
            text-align: center;
        }
        nav a {
            color: white;
            text-decoration:none;
            margin: 7%;
            font-size:130%;
            font-family: cursive;
        }
        nav a:hover {
            text-decoration:underline;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
            margin-top: 500px;
        }

        footer p {
            font-size: 14px;
        }
</style>
<body>
    <center>
        <header>
            🅢🅟🅘🅒🅔 🅜🅨🅢🅣🅔🅡🅨
        </header>
        <nav>
            <img src="restaurannt logo.jpg" height="60" width="60">
            <a href="home.html">HOME</a>
            <a href="menu.html">MENU</a>
            <a href="about.html">ADMINISTRATION</a>
            <a href="contact.html">CONTACT</a>
        </nav>
    </center>
        <footer>
            Designed by POOJA BRAHMA
        </footer>
</body>
</html>

home

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Home</title>
</head>

<style>
    body{
        background-color: antiquewhite;
    }
    header{
        font-size: 620%;
        font-style: oblique;
        background-color: burlywood;
    }
    .content{
        font-size: larger;
        font-family: cursive;
    }
</style>
<body>
    <center>
        <header style="color:brown;">
            𝕊𝕡𝕚𝕔𝕖 𝕄𝕪𝕤𝕥𝕖𝕣𝕪
        </header>

        <img src="restaurant.jpeg" width="1500" height="700">
        <div class="content">
        <p>At The Spice Mystery, dining transcends the ordinary, transforming every meal into a celebration of the senses. The moment you step through the door, you are enveloped in an atmosphere of elegance and warmth, where every detail is thoughtfully crafted to captivate. The dishes are a harmonious symphony of flavors, each bite a delicate dance of texture, aroma, and taste that leaves an indelible mark on your soul. The chefs, true magicians of their craft, conjure culinary masterpieces that enchant the palate with unexpected twists and sublime richness. Every plate tells a story, inviting you to savor the artistry and passion woven into every ingredient. At The Spice Mystery, dining is not just a meal; it is an unforgettable experience that lingers long after the last bite.</p>
        </div>
        <a href="Restaurant menu.html" >BACK</a>
    </center>
    
</body>
</html> 

menu

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <center>
        
        </center>
        <div>
    <title>Menu</title>
        </div>

    <style>
        body{
            background-color:grey;
        }
     
    
        .menu-container {
            width: 80%;
            margin: 50px auto;
            background-color:cornsilk;
            padding: 20px;
            border-radius: 15px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            color: #ffffff;
        }

        header {
            text-align: center;
            padding: 20px 0;
            color:ivory;
            background-color:black;
            border-radius: 15px 15px 0 0;
        }

        header h1 {
            margin: 0;
            font-size: 78px;
        }

        h2 {
            text-align: center;
            color:grey;
            border-bottom: 2px solid #817c7c;
            font-size: 56px;
            margin-bottom: 20px;
        }

        .menu-item {
            display: flex;
            justify-content: space-between;
            margin-bottom: 20px;
            align-items: center;
        }

        .menu-item img {
            width: 200px;
            height: 150px;
            border-radius: 10px;
            object-fit: cover;
        }

        .menu-item-name {
            font-size: 34px;
            font-weight: bold;
            font-family: cursive;
            font-style: italic;
            color:rgb(26, 14, 14);
        }

        .menu-item-price {
            font-size: 28px;
            color: #e74c3c;
        }

    </style>
</head>
<body>
    <center>

<header>
    <h1>𝕾𝖕𝖎𝖈𝖊 𝕸𝖞𝖘𝖙𝖊𝖗𝖞</h1>    
</header>
<div class="menu-container">

    <div class="menu-section">
        <h2>STARTERS</h2>
        <div class="menu-item">
            <img src="chicken-tikka-kebab.jpg">
            <p class="menu-item-name">Chicken Tikka</p>
            <p class="menu-item-price">₹299</p>
        </div>

        <div class="menu-item">
            <img src="chicken tandoori.jpg">
            <p class="menu-item-name">Chicken Tandhoori</p>
            <p class="menu-item-price">₹399</p>
        </div>

        <div class="menu-item">
            <img src="chicken lollipop.jpg">
            <p class="menu-item-name">Chicken Lollipop</p>
            <p class="menu-item-price">₹199</p>
        </div>
        <div class="menu-item">
            <img src="chicken 65.jpg">
            <p class="menu-item-name">Chicken 65</p>
            <p class="menu-item-price">₹150</p>
        </div>
    </div>

    <div class="menu-section">
        <h2>MAIN COURSES</h2>
        <div class="menu-item">
            <img src="chicken biriyani.jpg">
            <p class="menu-item-name">Chicken Briyani</p>
            <p class="menu-item-price">₹199</p>
        </div>
        <div class="menu-item">
            <img src="Mutton-Biryani.jpg">
            <p class="menu-item-name">Mutton Biryani</p>
            <p class="menu-item-price">₹280</p>
        </div>
        <div class="menu-item">
            <img src="fried rice.jpg">
            <p class="menu-item-name">Fried Rice</p>
            <p class="menu-item-price">₹199</p>
        </div>
        <div class="menu-item">
            <img src="meals.jpg">
            <p class="menu-item-name">Meals</p>
            <p class="menu-item-price">₹100</p>
        </div>
        <div class="menu-item">
            <img src="naan and curry.jpg">
            <p class="menu-item-name">Butter Naan & Curry</p>
            <p class="menu-item-price">₹299</p>
        </div>
        <div class="menu-item">
            <img src="noodles.jpg">
            <p class="menu-item-name">Chicken Noodles</p>
            <p class="menu-item-price">₹199</p>
        </div>
    </div>

    <div class="menu-section">
        <h2>DESSERTS</h2>
        <div class="menu-item">
            <img src="brownie.jpg">
            <p class="menu-item-name">Brownie</p>
            <p class="menu-item-price">₹90</p>
        </div>
        <div class="menu-item">
            <img src="cakes.jpg">
            <p class="menu-item-name"> Ice Cakes</p>
            <p class="menu-item-price">₹70</p>
        </div>
        <div class="menu-item">
            <img src="ice cream.jpg">
            <p class="menu-item-name">Ice Cream</p>
            <p class="menu-item-price">₹199</p>
        </div>
        <div class="menu-item">
            <img src="buklava.jpeg">
            <p class="menu-item-name">Buklava</p>
            <p class="menu-item-price">₹299</p>
        </div>
    </div>
</div>
<a href="Restaurant menu.html" >BACK</a>
    </center>
</body>
</html>

about

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Us</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color:peru;
            color: #333;
        }
        header {
            background-color:#333;
            color: white;
            padding: 1rem 2rem;
            text-align: center;
        }
        .container {
            padding: 2rem;
            max-width: 800px;
            margin: auto;
            background:beige;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        h3 {
            color:brown;
            text-align: center;
            font-style:inherit;
            font-size: x-large;
        }
        h1{
            color: blanchedalmond;
            font-style: oblique;
        }
        p {
            line-height: 1.6;
            margin-bottom: 1rem;
            font-size: medium;
        }
        .mission {
            font-style: italic;
            text-align: center;
            margin-top: 2rem;
        }
        footer {
            text-align: center;
            padding: 1rem 0;
            background-color: #333;
            color: white;
            margin-top: 2rem;
        }
    </style>
</head>
<body>
    <header>
        <h1>
            ꜱᴘɪᴄᴇ ᴍʏꜱᴛᴇʀʏ
        </h1>
    </header>
    <div class="container">
        <h2>Welcome to Spice Mystery!</h2>
    <center>
    <img src="chef1.jpg" width="400" height="400">
    <h3>Chef Steave</h3>
    <p style="font-size:x-large;font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;">CHEIF CHEF</p>
    <P>Head of the kitchen. Responsible for menu creation, kitchen management, and overall operations.</P>

    <img src="chef2.png" width="400" height="400">
    <h3>Chef Millie</h3>
    <p style="font-size:x-large;font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;">EXECUTIVE CHEF</p>
    <P>Second-in-command. Assists the Cheif Chef in managing the kitchen and oversees day-to-day operations.</P>

    <img src="chef3.avif" width="400" height="400">
    <h3>Chef Hopper</h3>
    <p style="font-size:x-large;font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;">PASTRY CHEF</p>
    <P>Head of the bakery and pastery.Manages desserts and baked goods.</P>
    
    <img src="chef4.png" width="400" height="400">
    <h3>Chef Eddie</h3>
    <p style="font-size:x-large;font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;">JUNIOR CHEF</p>
    <P>Works under the Chef de Partie to learn and assist in different stations.</P>

    <img src="chef5.jpg" width="400" height="400">
    <h3>Chef Nancy</h3>
    <p style="font-size:x-large;font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;">STATION CHEF</p>
    <P>In charge of a specific section of the kitchen (e.g., grill, pastry, or sauté station).</P>
    
    <img src="chef6.avif" width="400" height="400">
    <h3>Chef Will</h3>
    <p style="font-size:x-large;font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;">SAUCE CHEF</p>
    <P>Specializes in making sauces, stews, and sautéed dishes.</P>
    </div>
    <center><a href="Restaurant menu.html" >BACK</a></center>
    </center>
    <footer>
        &copy; 2024 Spice Mystery. All rights reserved.
    </footer>
</body>
</html>

contact

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color:beige;
            color: #333;
        }
        header {
            background-color:skyblue;
            color: white;
            text-align: center;
            padding: 1rem 2rem;
        }
        .container {
            padding: 2rem;
            max-width: 800px;
            margin: auto;
            background: white;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        h1, h2 {
            color:white;
            text-align: center;
        }
        form {
            display: flex;
            flex-direction: column;
            gap: 1rem;
        }
        label {
            font-weight: bold;
        }
        input, textarea {
            padding: 0.8rem;
            border: 1px solid #ddd;
            border-radius: 4px;
            font-size: 1rem;
            width: 100%;
        }
        textarea {
            resize: vertical;
        }
        button {
            padding: 0.8rem;
            background-color:dodgerblue;
            color: white;
            border: none;
            border-radius: 4px;
            font-size: 1rem;
            cursor: pointer;
        }
        button:hover {
            background-color: palegreen;
        }
        .contact-info {
            margin-top: 2rem;
            text-align: center;
            line-height: 1.8;
        }
        footer {
            text-align: center;
            padding: 1rem 0;
            background-color: #333;
            color:fuchsia;
            margin-top: 2rem;
        }
    </style>
</head>
<body>
    <center>
    <header>
        <h1>SPICE MYSTERY
            GET IN TOUCH</h1>
        <h2>𝑊𝑒’𝑑 𝑙𝑜𝑣𝑒 𝑡𝑜 ℎ𝑒𝑎𝑟 𝑓𝑟𝑜𝑚 𝑦𝑜𝑢</h2>
    </header>
    <div class="container">
        <form action="/submit-contact" method="POST">
            <label for="name">Your Name</label>
            <input type="text" id="name" name="name" placeholder="Enter your name" required>
            
            <label for="email">Your Email</label>
            <input type="email" id="email" name="email" placeholder="Enter your email" required>
            
            <label for="message">Your Message</label>
            <textarea id="message" name="message" rows="5" placeholder="Write your message" required></textarea>
            
            <button type="submit">Submit</button>
        </form>
        <div class="contact-info">
            <p><strong>Address:</strong>Nungambakkam,Chennai</p>
            <p><strong>Phone:</strong>9512357456</p>
            <p><strong>Email:</strong> info@spicemystery.com</p>
            <p><strong>Office Hours:</strong> Monday to Sunday, 9:00 AM - 10:00 PM</p>
        </div>
    </div>
    <a href="Restaurant menu.html" >BACK</a>
    </center>
</body>
</html>
```
# OUTPUT:

![alt text](<Screenshot 2024-12-21 162302.png>)

![alt text](<Screenshot 2024-12-21 162347.png>)

![alt text](<Screenshot 2024-12-21 162401.png>)

![alt text](<Screenshot 2024-12-21 162448.png>)

![alt text](<Screenshot 2024-12-21 162501.png>)

![alt text](<Screenshot 2024-12-21 162515.png>)

![alt text](<Screenshot 2024-12-21 162537.png>)

![alt text](<Screenshot 2024-12-21 162555.png>)

![alt text](<Screenshot 2024-12-21 162702.png>)

![alt text](<Screenshot 2024-12-21 162716.png>)

![alt text](<Screenshot 2024-12-21 162745.png>)

![alt text](<Screenshot 2024-12-21 162757.png>)

![alt text](<Screenshot 2024-12-21 162811.png>)

![alt text](<Screenshot 2024-12-21 162956.png>)
# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.

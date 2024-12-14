# Ex.07 Restaurant Website
## Date:14/12/2024

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
home.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Engineer's Campaign - Home</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f9fa;
        }

        header {
            background-color: #ff8801;
            color: white;
            text-align: center;
            padding: 20px;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
        }

        nav a:hover {
            color: #ffc107;
        }

        .banner {
        background-image: url('back.jpg'); /* Path to your background image */
        background-size: cover; /* Ensures the image covers the entire section */
        background-position: center; /* Centers the image */
        color: white;
        text-align: center;
        padding: 100px 20px;
    }

        .banner h2 {
            font-size: 2.5rem;
        }

        .content {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            padding: 40px;
        }

        .card {
            background-color: white;
            border: 1px solid #ddd;
            border-radius: 8px;
            overflow: hidden;
            width: calc(33.333% - 20px);
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        .card img {
            width: 100%;
            height: auto;
        }

        .card h3 {
            margin: 0;
            padding: 15px;
            background-color: #333;
            color: white;
        }

        .card p {
            padding: 15px;
            font-size: 1rem;
            color: #555;
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 20px;
        }

        footer a {
            color: #ffc107;
            text-decoration: none;
        }
    </style>
</head>
<body>
    <header>
        <h1><img src="logo.jpg" alt="Campaign Logo" style="height: 50px;"> Engineer's Campaign</h1>
    </header>

    <nav>
        <a href="home.html">Home</a>
        <a href="menu.html">Menu</a>
        <a href="administration.html">Administration</a>
        <a href="contact.html">Contact Us</a>
    </nav>

    <div class="banner">
        <h2>30% Off for Engineering Graduates</h2>
        <p>Special for Today</p>
    </div>

    <div class="content">
        <div class="card">
            <img src="Chicken_tikka_masala.webp" alt="Chicken Masala">
            <h3>Chicken Masala</h3>
            <p>A flavorful Indian classic made with tender chicken cooked in a spiced tomato-based gravy.</p>
        </div>
        <div class="card">
            <img src="biriyani.webp" alt="Chicken Biriyani">
            <h3>Chicken Biriyani</h3>
            <p>The king of rice dishes – aromatic, flavorful, and perfect for any occasion.</p>
        </div>
        <div class="card">
            <img src="shawarma.webp" alt="Chicken Shawarma">
            <h3>Chicken Shawarma</h3>
            <p>Juicy, seasoned meat wrapped in pita bread, packed with flavor.</p>
        </div>
        <div class="card">
            <img src="Tandoori-Chicken-Pic-1.webp" alt="Tandoori">
            <h3>Tandoori</h3>
            <p>Cooked in a tandoor oven, bringing out authentic and rich flavors.</p>
        </div>
        <div class="card">
            <img src="65.webp" alt="Chicken Starter">
            <h3>Chicken Starters</h3>
            <p>Appetizers that ignite your taste buds with bold flavors and crispy textures.</p>
        </div>
        <div class="card">
            <img src="KFC-Hot-and-Spicy-Wings-FT-BLOG0923-bcbfe79e54554f249c4bf246d09b1d98.webp" alt="KFC">
            <h3>KFC Favorites</h3>
            <p>Crunchy, flavorful fried chicken that’s loved by people around the world.</p>
        </div>
    </div>

    <footer>
        Designed and Developed by <a href="#">S Harish</a>
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
    <title>Engineer's Campaign - Menu</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 20px;
        }

        nav {
            text-align: center;
            background-color: #444;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
        }

        nav a:hover {
            color: #ffc107;
        }

        .content {
            display: flex;
            flex-wrap: wrap;
            padding: 40px;
            justify-content: center;
        }

        .card {
            background-color: white;
            border: 1px solid #ddd;
            border-radius: 8px;
            margin: 10px;
            width: calc(33.333% - 20px);
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        .card img {
            width: 100%;
            height: auto;
        }

        .card h3 {
            margin: 0;
            padding: 15px;
            background-color: #333;
            color: white;
        }

        .card p {
            padding: 15px;
            font-size: 1rem;
            color: #555;
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 20px;
        }

        footer a {
            color: #ffc107;
            text-decoration: none;
        }
    </style>
</head>
<body>
    <header>
        <h1><img src="logo.jpg" alt="Campaign Logo"> Engineer's Campaign - Menu</h1>
    </header>

    <nav>
        <a href="home.html">Home</a>
        <a href="menu.html">Menu</a>
        <a href="administration.html">Administration</a>
        <a href="contact.html">Contact Us</a>
    </nav>

    <div class="content">
        <div class="card">
            <img src="dish1.jpg" alt="Chicken Masala">
            <h3>Chicken Masala</h3>
            <p>Chicken masala is a flavorful Indian dish made with tender chicken pieces cooked in a spiced tomato-based gravy, enriched with aromatic herbs and spices.</p>
        </div>
        <div class="card">
            <img src="dish2.jpg" alt="Butter Chicken">
            <h3>Butter Chicken</h3>
            <p>Butter chicken is a rich, creamy dish made with marinated chicken cooked in a spiced tomato-based sauce, finished with butter and cream.</p>
        </div>
        <div class="card">
            <img src="dish3.jpg" alt="Paneer Tikka">
            <h3>Paneer Tikka</h3>
            <p>Paneer Tikka is a popular Indian appetizer featuring marinated paneer (cottage cheese) cooked on skewers with a smoky flavor.</p>
        </div>
        <div class="card">
            <img src="dish4.jpg" alt="Biryani">
            <h3>Biryani</h3>
            <p>Biryani is a flavorful rice dish made with spiced rice, meat (like chicken, mutton, or beef), and aromatic spices.</p>
        </div>
        <div class="card">
            <img src="dish5.jpg" alt="Tandoori Chicken">
            <h3>Tandoori Chicken</h3>
            <p>Tandoori chicken is marinated in yogurt and spices and cooked in a tandoor (clay oven), resulting in a rich, smoky flavor.</p>
        </div>
        <div class="card">
            <img src="dish6.jpg" alt="Samosas">
            <h3>Samosas</h3>
            <p>Samosas are deep-fried or baked pastry pockets filled with spiced potatoes, peas, and sometimes meat or lentils.</p>
        </div>
        <div class="card">
            <img src="dish7.jpg" alt="Dal Makhani">
            <h3>Dal Makhani</h3>
            <p>Dal Makhani is a rich and creamy lentil dish made with black lentils, kidney beans, butter, and cream, flavored with spices.</p>
        </div>
        <div class="card">
            <img src="dish8.jpg" alt="Lamb Curry">
            <h3>Lamb Curry</h3>
            <p>Lamb curry is a spicy, slow-cooked meat dish with tender lamb chunks simmered in a flavorful curry sauce made from spices.</p>
        </div>
        <div class="card">
            <img src="dish9.jpg" alt="Chole Bhature">
            <h3>Chole Bhature</h3>
            <p>Chole Bhature is a popular North Indian dish consisting of spiced chickpea curry (chole) served with fluffy fried bread (bhature).</p>
        </div>
        <div class="card">
            <img src="dish10.jpg" alt="Naan Bread">
            <h3>Naan Bread</h3>
            <p>Naan is a soft, leavened Indian flatbread traditionally cooked in a tandoor (clay oven) and served warm.</p>
        </div>
        <div class="card">
            <img src="dish11.jpg" alt="Pani Puri">
            <h3>Pani Puri</h3>
            <p>Pani Puri is a popular street snack of crispy puris filled with spicy flavored water, tangy chutneys, and tangy stuffing.</p>
        </div>
        <div class="card">
            <img src="dish12.jpg" alt="Gulab Jamun">
            <h3>Gulab Jamun</h3>
            <p>Gulab Jamun is a popular Indian dessert made of deep-fried dough balls soaked in rose-scented sugar syrup.</p>
        </div>
    </div>

    <footer>
        Designed and Developed by <a href="#">S Harish</a>
    </footer>
</body>
</html>

```
administration.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Engineer's Campaign - Administration</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1><img src="logo.jpg" alt="Campaign Logo"> Engineer's Campaign</h1>
    </header>

    <nav>
        <a href="home.html">Home</a>
        <a href="menu.html">Menu</a>
        <a href="administration.html">Administration</a>
        <a href="contact.html">Contact Us</a>
    </nav>

    <div class="content">
        <h2>Administration Team</h2>
        <div class="card">
            <img src="mem1.jpg" alt="Elon Musk">
            <h3>Elon Musk</h3>
            <p>Chief Visionary Officer - Leads the innovation and strategic goals of the campaign.</p>
        </div>
        <div class="card">
            <img src="mem2.jpg" alt="Oprah Winfrey">
            <h3>Oprah Winfrey</h3>
            <p>Head of Public Relations - Oversees public engagement and media strategies.</p>
        </div>
        <div class="card">
            <img src="mem3.jpg" alt="Dwayne Johnson">
            <h3>Dwayne Johnson</h3>
            <p>Operations Manager - Ensures seamless execution of day-to-day activities.</p>
        </div>
        <div class="card">
            <img src="mem4.jpg" alt="Emma Watson">
            <h3>Emma Watson</h3>
            <p>Creative Director - Crafts compelling visuals and designs for the campaign.</p>
        </div>
        <div class="card">
            <img src="mem5.jpg" alt="LeBron James">
            <h3>LeBron James</h3>
            <p>Fitness and Wellness Consultant - Adds a healthy lifestyle perspective to the campaign.</p>
        </div>
        <div class="card">
            <img src="mem6.jpg" alt="Taylor Swift">
            <h3>Robert Downey Jr</h3>
            <p>Community Engagement Lead - Drives initiatives to connect with local communities.</p>
        </div>
    </div>

    <footer>
        Designed and Developed by <a href="#">S Harish</a>
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
    <title>Engineer's Campaign - Contact Us</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1><img src="logo.jpg" alt="Campaign Logo"> Engineer's Campaign</h1>
    </header>

    <nav>
        <a href="home.html">Home</a>
        <a href="menu.html">Menu</a>
        <a href="administration.html">Administration</a>
        <a href="contact.html">Contact Us</a>
    </nav>
    <div class="content">
        <h2>Contact Us</h2>
        <p>We would love to hear from you! Reach out to us through any of the following methods.</p>

        <div class="contact-section">
            <div class="contact-method">
                <h3>📍 Address</h3>
                <p>123 Engineer's Avenue<br>Innovation City, Techland<br>456789</p>
            </div>
            <div class="contact-method">
                <h3>📞 Phone</h3>
                <p>Customer Support: +1 234 567 890</p>
                <p>Corporate Office: +1 987 654 321</p>
            </div>
            <div class="contact-method">
                <h3>✉️ Email</h3>
                <p>General Inquiries: info@engineerscampaign.com</p>
                <p>Support: support@engineerscampaign.com</p>
            </div>
        </div>

        <div class="contact-form">
            <h3>Leave Us a Message</h3>
            <form action="#" method="post">
                <label for="name">Name</label>
                <input type="text" id="name" name="name" placeholder="Your Name" required>

                <label for="email">Email</label>
                <input type="email" id="email" name="email" placeholder="Your Email" required>

                <label for="message">Message</label>
                <textarea id="message" name="message" placeholder="Your Message" rows="6" required></textarea>

                <button type="submit">Send Message</button>
            </form>
        </div>

       

        <div class="map">
            <h3>Find Us</h3>
            <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3151.8354345093145!2d144.95373531532248!3d-37.816279379751664!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x6ad642af0f11fd81%3A0xf5776a2b665411d5!2sEngineering%20Innovation%20Hub!5e0!3m2!1sen!2sin!4v1612462167733!5m2!1sen!2sin" 
                width="100%" height="300" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
        </div>
    </div>

    <footer>
        Designed and Developed by <a href="#">S Harish </a>
    </footer>
</body>
</html>

```

## OUTPUT:
![image](https://github.com/user-attachments/assets/1d5e1f09-6ece-49ac-8137-e9f3b0d2d8b8)
![image](https://github.com/user-attachments/assets/751e3180-ae0a-490c-abce-cc53f81fb727)
![image](https://github.com/user-attachments/assets/568a1355-7e5d-4c5c-8153-3afe28997e3d)
![image](https://github.com/user-attachments/assets/2a78cde4-fb12-4d27-a3ca-2b416edb83cc)
![image](https://github.com/user-attachments/assets/a54738d3-f352-4f39-8372-f54e9ef64fb1)



## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.

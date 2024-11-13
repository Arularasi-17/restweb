# Ex.07 Restaurant Website
## Date:10.11.2024

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
## HTML
```
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Little Lemon</title>
        <link rel="stylesheet" href="style.css"> <!-- Link to your CSS file here -->
    </head>
    
<body>
    <header>
        <div class="logo">
            <img src="logo.jpg" alt="Little Lemon Logo">
            <h1>Little Lemon</h1>
        </div>
        <nav class="menu">
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">Menu</a></li>
                <li><a href="#">Book</a></li>
                <li><a href="#">About</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section class="banner" style="background-image: url('bg.jpg');">
            <h2 class="offer-txt">30% Off This Weekend</h2>
            <p class = 'offer-txt'>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse et congue massa, eu fringilla mauris. Fusce dapibus vehicula ex at ultrices. Duis at varius ligula. Integer pulvinar tempus quam, et consequat nulla viverra in. Nullam ut tortor magna. Nulla eget placerat leo. Nunc eu finibus magna, sed vulputate magna.</p>
        </section>
        <section class="features">
            <div class="feature">
                <h3>Our New Menu</h3>
                <img src="menu.jpg" alt="Cuisine">
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse et congue massa, eu fringilla mauris. Fusce dapibus vehicula ex at ultrices. Duis at varius ligula. Integer pulvinar tempus quam, et consequat nulla viverra in. Nullam ut tortor magna. Nulla eget placerat leo. Nunc eu finibus magna, sed vulputate magna.</p>
                <a href="www.google.com">See our new menu</a>
            </div>
            <div class="feature">
                <h3>Book a table</h3>
                <img src="table.jpg" alt="Book a table">
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse et congue massa, eu fringilla mauris. Fusce dapibus vehicula ex at ultrices. Duis at varius ligula. Integer pulvinar tempus quam, et consequat nulla viverra in. Nullam ut tortor magna. Nulla eget placerat leo. Nunc eu finibus magna, sed vulputate magna.</p>
                <a href="www.google.com">Book your table now</a>
            </div>
            <div class="feature">
                <h3>Opening Hours</h3>
                <img src="open.jpg" class="hours" alt="Opening Hours">
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse et congue massa, eu fringilla mauris. Fusce dapibus vehicula ex at ultrices.</p>
                <ul>
                    Monday - Friday: 11:00 AM - 10:00 PM <br>
                    Saturday: 10:00 AM - 11:00 PM <br>
                    Sunday: 10:00 AM - 9:00 PM <br>
                </ul>
            </div>
        </section>
        <footer>
            <div class="logo">
                <img src="logo.jpg" class="footer" alt="Little Lemon Logo">
                <p class="copy">&copy; Copyright Little Lemon</p>
            </div>
        </footer>
    </main>
</body>
</html>
```
## CSS
```
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f0f0f0;
}

/* Header Styling */
header {
    display: flex;
    justify-content: space-between;
    color: rgb(251, 245, 245);
    align-items: center;
    padding: 20px;
    background-color: #0a0a0a;
    border-bottom: 2px solid #8e44ad;
}

/* Logo and Menu */
.logo {
    display: flex;
    align-items: center;
}

.logo img {
    width: 50px;
    height: 50px;
    margin-right: 10px;
}

.menu ul {
    list-style: none;
    display: flex;
    margin: 0;
    padding: 0;
}

.menu ul li {
    margin-right: 20px;
}

.menu ul li a {
    text-decoration: none;
    color: rgb(11, 10, 10);
    font-weight: bold;
    padding: 10px 15px;
    background-color: rgb(245, 236, 236);
    border-radius: 15px;
}

.banner {
    position: relative;
    text-align: center;
    background: url('bg.jpg') no-repeat center center/cover;
    padding: 60px 20px;
    color: white;
    border-radius: 8px;
    margin: 20px;
}

.banner .offer-txt {
    background: rgba(0, 0, 0, 0.5);
    padding: 15px;
    border-radius: 8px;
    display: inline-block;
}

.features {
    display: flex;
    justify-content: space-around;
    padding: 20px;
    background-color: #fafafa;
}

.feature {
    background-color: #020202;
    color: rgb(251, 245, 245);
    text-align: center;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(21, 20, 20, 0.1);
    width: 30%;
    margin: 10px;
}

.feature img {
    width: 100%;
    height: auto;
    border-radius: 8px;
}

.feature h3 {
    font-size: 1.5em;
    color: #f2eaea;
}

.feature a {
    color: #8e44ad;
    text-decoration: underline;
}

footer {
    text-align: center;
    padding: 20px;
    background-color: #070707;
    border-top: 2px solid #b041df;
    color: #f6f3f7;
    font-size: 0.9em;
}
```
## OUTPUT:
![RESTAURANT EXP6](https://github.com/user-attachments/assets/9758aa25-2d13-4cfb-8acd-4f40b0b269c8)

![restaurant2](https://github.com/user-attachments/assets/cd2c83a4-2538-46ea-aec3-45e13eb8fc44)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meghavi Restaurant Menu</title>
    <style>
        /* Basic Reset */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f9;
            color: #333;
            line-height: 1.6;
        }

        /* Header and Navbar */
        header {
            background-color: #333;
            color: #fff;
            padding: 1em;
            text-align: center;
        }

        header h1 {
            margin: 0;
            font-size: 2em;
        }

        header img {
            width: 150px; /* Adjust width as needed */
            margin-bottom: 10px;
        }

        nav {
            margin-top: 1em;
        }

        nav .button {
            background-color: #28a745; /* Green background */
            color: white; /* White text */
            padding: 10px 20px;
            margin: 0 5px;
            border: none;
            border-radius: 25px; /* Fully rounded corners */
            cursor: pointer;
            text-decoration: none;
            font-weight: bold;
            transition: background-color 0.3s, transform 0.3s;
        }

        nav .button:hover {
            background-color: #218838; /* Darker green on hover */
            transform: scale(1.05); /* Slightly enlarge on hover */
        }

        /* Slideshow Container */
        .slideshow-container {
            display: flex; /* Display videos in a line */
            justify-content: center;
            margin: 20px auto;
            max-width: 800px; /* Set a maximum width for the video container */
            flex-wrap: wrap; /* Allow wrapping on smaller screens */
        }

        video {
            width: 30%; /* Set width to medium size for each video */
            margin: 0 5px; /* Add margin for spacing between videos */
            border-radius: 8px; /* Rounded corners for the video */
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
        }

        /* Section Styles */
        section {
            padding: 2em;
            text-align: center;
            background-color: #fff; /* White background for sections */
            border-radius: 8px;
            margin: 1em 0;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
        }

        h2 {
            color: #FFD700; /* Yellow color for food headings */
            margin-bottom: 0.5em;
            font-size: 1.8em; /* Smaller font size for food headings */
            font-weight: bold; /* Bold font weight */
            display: inline-block;
        }

        /* Menu Item Styles */
        .menu-category {
            margin: 2em 0;
            text-align: left;
        }

        .menu-category h3 {
            color: #444;
            font-size: 1.5em;
            margin-bottom: 0.5em;
            border-bottom: 2px solid #ddd;
            padding-bottom: 0.2em;
        }

        .menu-item {
            display: flex;
            justify-content: space-between;
            padding: 0.5em 0;
            border-bottom: 1px dotted #ddd;
            font-size: 1.1em;
            color: #555; /* Darker text for menu items */
        }

        .menu-item:last-child {
            border-bottom: none;
        }

        .food-name {
            font-family: 'Courier New', Courier, monospace; /* Different font style for food name */
            font-weight: bold; /* Bold font weight */
        }

        .price {
            font-family: Arial, sans-serif; /* Different font style for price */
            font-weight: normal; /* Normal font weight */
            color: black; /* Black color for prices */
        }

        /* Footer */
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 1em;
            margin-top: 2em;
        }

        /* Images at the Bottom */
        .bottom-images {
            display: flex;
            justify-content: center;
            margin: 2em 0;
            flex-wrap: wrap; /* Allow wrapping on smaller screens */
        }

        .bottom-images img {
            width: 200px; /* Adjust width as needed */
            margin: 0 10px; /* Add spacing between images */
            border-radius: 8px; /* Rounded corners for images */
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
        }

        /* Responsive Styles */
        @media (max-width: 600px) {
            nav .button {
                display: block;
                margin: 10px 0; /* Stack buttons vertically on small screens */
                width: 90%; /* Full width for buttons on small screens */
            }

            video {
                width: 90%; /* Increase video width on smaller screens */
                margin: 10px 0; /* Add margin for spacing */
            }

            .menu-item {
                flex-direction: column; /* Stack items vertically */
                align-items: flex-start; /* Align items to start */
            }

            .price {
                margin-top: 5px; /* Add spacing for price */
            }
        }
    </style>
</head>
<body>

    <!-- Header and Navigation -->
    <header>
        <img src="logo.jpg" alt="Meghavi Restaurant Logo">
        <h1>Meghavi Restaurant</h1>
        <nav>
            <a href="#papad" class="button">Papad</a>
            <a href="#pizza" class="button">Pizza</a>
            <a href="#fries" class="button">French Fries</a>
            <a href="#drinks" class="button">Drinks</a>
            <a href="#starters" class="button">Tandoori Starters</a>
            <a href="#noodles" class="button">Noodles & Rice</a>
            <a href="#vegetables" class="button">Vegetables</a>
            <a href="#lentils" class="button">Lentils</a>
        </nav>
    </header>

    <!-- Slideshow Container -->
    <div class="slideshow-container">
        <video controls autoplay muted>
            <source src="1.mp4" type="video/mp4">
            Your browser does not support the video tag.
        </video>
        <video controls autoplay muted>
            <source src="2.mp4" type="video/mp4">
            Your browser does not support the video tag.
        </video>
        <video controls autoplay muted>
            <source src="4.mp4" type="video/mp4">
            Your browser does not support the video tag.
        </video>
    </div>

    <!-- Menu Sections -->
    <section id="papad">
        <h2>Papad</h2>
        <div class="menu-category">
            <div class="menu-item"><span class="food-name">Roasted Papad / રોઝટ પાપડ</span> <span class="price">₹10.00</span></div>
            <div class="menu-item"><span class="food-name">Fried Papad / ફ્રાઈડ પાપડ</span> <span class="price">₹20.00</span></div>
            <div class="menu-item"><span class="food-name">Masala Papad / મસાલા પાપડ</span> <span class="price">₹40.00</span></div>
            <div class="menu-item"><span class="food-name">Cheese Masala Papad / ચીઝ મસાલા પાપડ</span> <span class="price">₹60.00</span></div>
            <div class="menu-item"><span class="food-name">Special Meghavi Papad / સ્પેશિયલ મેઘવી પાપડ</span> <span class="price">₹80.00</span></div>
        </div>
    </section>

    <section id="pizza">
        <h2>Pizza</h2>
        <div class="menu-category">
            <div class="menu-item"><span class="food-name">American Garden Pizza / અમેરિકન ગાર્ડન પિઝા</span> <span class="price">₹140.00</span></div>
            <div class="menu-item"><span class="food-name">Cheese Pizza / ચીઝ પિઝા</span> <span class="price">₹130.00</span></div>
            <div class="menu-item"><span class="food-name">Italian Pizza / ઇટાલિયન પિઝા</span> <span class="price">₹140.00</span></div>
            <div class="menu-item"><span class="food-name">Mexican Pizza / મેક્સિકન પિઝા</span> <span class="price">₹150.00</span></div>
            <div class="menu-item"><span class="food-name">Mushroom Pizza / મશરૂમ પિઝા</span> <span class="price">₹160.00</span></div>
        </div>
    </section>

    <section id="fries">
        <h2>French Fries</h2>
        <div class="menu-category">
            <div class="menu-item"><span class="food-name">French Fries / ફ્રેંચ ફ્રાઈઝ</span> <span class="price">₹80.00</span></div>
            <div class="menu-item"><span class="food-name">Cheesy Fries / ચીઝી ફ્રાઈઝ</span> <span class="price">₹90.00</span></div>
            <div class="menu-item"><span class="food-name">Special Fries / સ્પેશિયલ ફ્રાઈઝ</span> <span class="price">₹100.00</span></div>
        </div>
    </section>

    <section id="drinks">
        <h2>Drinks</h2>
        <div class="menu-category">
            <div class="menu-item"><span class="food-name">Cold Drink / કોલ્ડ ડ્રિંક</span> <span class="price">₹20.00</span></div>
            <div class="menu-item"><span class="food-name">Ice Tea / આઈસ ટિ</span> <span class="price">₹30.00</span></div>
            <div class="menu-item"><span class="food-name">Juice / જ્યૂસ</span> <span class="price">₹40.00</span></div>
            <div class="menu-item"><span class="food-name">Mocktail / મૉકટેલ</span> <span class="price">₹80.00</span></div>
        </div>
    </section>

    <section id="starters">
        <h2>Tandoori Starters</h2>
        <div class="menu-category">
            <div class="menu-item"><span class="food-name">Tandoori Chicken / તંદૂરી ચિકન</span> <span class="price">₹150.00</span></div>
            <div class="menu-item"><span class="food-name">Paneer Tikka / પનીર ટિક્કા</span> <span class="price">₹130.00</span></div>
            <div class="menu-item"><span class="food-name">Tandoori Fish / તંદૂરી ફિશ</span> <span class="price">₹170.00</span></div>
        </div>
    </section>

    <section id="noodles">
        <h2>Noodles & Rice</h2>
        <div class="menu-category">
            <div class="menu-item"><span class="food-name">Chowmein Noodles / ચાઉમિન નૂડલ્સ</span> <span class="price">₹100.00</span></div>
            <div class="menu-item"><span class="food-name">Fried Rice / ફ્રાઈડ રાઈસ</span> <span class="price">₹120.00</span></div>
        </div>
    </section>

    <section id="vegetables">
        <h2>Vegetables</h2>
        <div class="menu-category">
            <div class="menu-item"><span class="food-name">Paneer Butter Masala / પનીર બટર મસાલા</span> <span class="price">₹150.00</span></div>
            <div class="menu-item"><span class="food-name">Mix Veg / મિક્ષ વેગ</span> <span class="price">₹100.00</span></div>
        </div>
    </section>

    <section id="lentils">
        <h2>Lentils</h2>
        <div class="menu-category">
            <div class="menu-item"><span class="food-name">Dal Tadka / દાલ તડકા</span> <span class="price">₹90.00</span></div>
            <div class="menu-item"><span class="food-name">Dal Makhani / દાલ માખણિ</span> <span class="price">₹120.00</span></div>
        </div>
    </section>

    <!-- Footer with Bottom Images -->
    <footer>
        <div class="bottom-images">
            <img src="01.jpg" alt="Delicious Dish 1">
            <img src="02.jpg" alt="Delicious Dish 2">
        </div>
        <p>&copy; 2024 Meghavi Restaurant. All rights reserved.</p>
    </footer>

</body>
</html>

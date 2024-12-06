# VEGETABLES-
VEGETABLES BLOG 

#HTML CODE 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <!-- Link to the external CSS file -->
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <h1 class="main-heading">
        VEGETABLES
    </h1>
    
    <h2 class="main">Leafy Greens</h2>
    <p class="food-description">
        Includes vegetables like spinach, kale, and lettuce; high in vitamins A, C, and K, as well as fiber.
    </p>
    
    <h2 class="main">Root Vegetables</h2>
    <p class="food-description">
        Includes carrots, beets, and sweet potatoes; packed with antioxidants and fiber for digestive health.
    </p>
    
    <h2 class="main">Cruciferous Vegetables</h2>
    <p class="food-description">
        Includes broccoli, cauliflower, and Brussels sprouts; great sources of fiber, vitamins, and cancer-fighting compounds.
    </p>
    
    <h2 class="main">Allium Vegetables</h2>
    <p class="food-description">
        Includes onions, garlic, and leeks; beneficial for heart health and immune function.
    </p>
    
    <h2 class="main">Legumes & Beans</h2>
    <p class="food-description">
        Includes peas, lentils, and beans; high in protein, fiber, and essential minerals.
    </p>
    
    <h2 class="main">Nightshade Vegetables</h2>
    <p class="food-description">
        Includes tomatoes, potatoes, and eggplants; rich in antioxidants and vital nutrients.
    </p>
    
    <h2 class="main">Squash & Pumpkins</h2>
    <p class="food-description">
        Includes zucchini, butternut squash, and pumpkin; great sources of vitamin A and antioxidants.
    </p>
    
    
</body>
</html>

#css code

/* Body background */
body {
    background-image: url('px.jpg');  /* Correct path to the image */
    background-repeat: no-repeat;
    background-size: cover;  /* The image will cover the whole area */
    background-position: center center;
    background-attachment: fixed;
    min-height: 400px;  /* Set a minimum height for the body */
}

/* Logo Styling */
h3 {
    text-align: center;
    margin: 1rem 0;
}

.logo {
    font-family: 'Lato', sans-serif;
    font-size: 3rem; /* Adjust the size */
    transition: color 0.3s ease; /* Smooth transition for color change */
}


/* Main Heading */
.main-heading {
    text-align: center;
    font-size: 4rem;
    color: black;
    margin-top: 3rem;
}

/* Call to Action (CTA) Links */
.cta-links {
    text-align: center;
    font-family: 'Cinzel', serif;
    font-size: 1.5rem;
    margin-top: 2rem;
}

.cta-links a {
    text-decoration: none;
    margin: 0 1rem;
    color: black;
    padding: 0.5rem 1rem; /* Add some padding for the button effect */
    border: 2px solid transparent;
    border-radius: 5px; /* Rounded corners */
    transition: background-color 0.3s ease, color 0.3s ease; /* Smooth transition */
}

.cta-links a:hover {
    color: white; /* Change text color to white on hover */
    background-color: #47acff; /* Change background color to tomato on hover */
    border-color: #47ffff; /* Border color change */
}
/* General body styling */
body {
    font-family: 'Arial', sans-serif;  /* Set a base font */
    margin: 0;
    padding: 0;
    background-color: #f4f4f4; /* Optional background color */
    color: #333;  /* Text color */
}

/* Styling for the heading */
.main {
    font-size: 3rem;  /* Make the heading large */
    font-weight: bold;  /* Make the text bold */
    color: #333;  /* Dark text color */
    margin-left: 20px;  /* Add some space from the left */
    margin-top: 20px;  /* Add space at the top */
}

/* Styling for the paragraph */
.food-description {
    font-size: 1.25rem;  /* Set a readable font size */
    line-height: 1.6;  /* Improve line spacing for readability */
    color: #555;  /* Lighter text color for the paragraph */
    margin-left: 20px;  /* Align the paragraph with the heading */
    margin-top: 10px;  /* Add space between heading and paragraph */
    max-width: 800px;  /* Optional: Limit the width of the paragraph */
    position: relative;  /* To allow positioning the icon */
}

/* Adding the icon after the paragraph text */
.food-description::after {
    content: '';  /* Don't display any text */
    display: inline-block;  /* Ensures the icon appears inline with text */
    margin-left: 10px;  /* Space between the text and the icon */
    width: 50px;  /* Set the width of the icon */
    height: 50px;  /* Set the height of the icon */
    background-size: cover;  /* Ensure the image covers the area */
    background-repeat: no-repeat;  /* Don't repeat the image */
    vertical-align: middle;  /* Vertically align the icon with the text */
}

/* General styling */
.main-heading {
    text-align: center;
}

.main {
    font-size: 1.5em;
    display: flex;
    align-items: center;
    margin-top: 20px;
}

/* Adding image to the headings using CSS */
.main::before {
    content: "";
    display: inline-block;
    width: 50px;
    height: 50px;
    background-image: url('veg.jpg'); /* Path to the image */
    background-size: cover;
    margin-right: 20px;
}

/* Optional description styling */
.food-description {
    margin-left: 20px;
}

.leafy-greens::before {
    background-image: url('veg.jpg'); 
}

.root-vegetables::before {
    background-image: url('veg.jpg');
}

.cruciferous-vegetables::before {
    background-image: url('veg.jpg');
}

.allium-vegetables::before {
    background-image: url('veg.jpg');
}

.legumes-beans::before {
    background-image: url('veg.jpg');
}

.nightshade-vegetables::before {
    background-image: url('veg.jpg');
}

.squash-pumpkins::before {
    background-image: url('veg.jpg');
}


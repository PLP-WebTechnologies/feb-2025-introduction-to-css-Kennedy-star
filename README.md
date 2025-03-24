# Introduction to CSS

## Objectives
Link an external CSS file to an HTML document.
Apply basic styling using selectors.
Use colors, fonts, and spacing effectively.

## Instructions

Create a style.css file.
Apply CSS to a HTML page.
Style elements using:
Classes and IDs.
Color and typography.
Margins, paddings, and borders.

>[!NOTE]
>  - Include at least:
>  - Use of 3 selectors
>  - Style an image
>  - Margin, Padding & Borders
>  - Different font

# Tasks
 - Link an external CSS file.
 - Apply at least 3 different selectors.
 - Improve readability and aesthetics.
 - <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Styled Page</title>
    <link rel="stylesheet" href="style.css"> <!-- Linking external CSS -->
</head>
<body>
    <header id="main-header">
        <h1>Welcome to My Styled Page</h1>
    </header>

    <section class="content">
        <p class="text">This is a simple webpage with external CSS styling.</p>
        <img src="image.jpg" alt="A styled image" class="styled-image">
    </section>

    <footer>
        <p>&copy; 2025 My Website</p>
    </footer>
</body>
</html>
/* Styling the header using an ID */
#main-header {
    background-color: #4CAF50;
    color: white;
    text-align: center;
    padding: 20px;
    font-family: Arial, sans-serif;
}

/* Styling a paragraph using a class */
.text {
    font-size: 18px;
    color: #333;
    margin: 20px;
    padding: 10px;
}

/* Styling an image */
.styled-image {
    width: 300px;
    height: auto;
    border: 5px solid #000;
    margin: 20px;
    padding: 10px;
    display: block;
}

/* Adding a hover effect */
.styled-image:hover {
    border-color: red;
}


Happy Coding! 💻✨

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

Happy Coding! 💻✨   
/* General Styles */
body {
    font-family: "Arial", sans-serif;
    background-color: #f4f4f4;
    margin: 0;
    padding: 0;
}

/* Header Styling */
#main-header {
    background-color: #007bff;
    color: white;
    text-align: center;
    padding: 20px;
    border-bottom: 5px solid #0056b3;
}

/* Paragraph Styling */
.text-content {
    font-size: 18px;
    color: #333;
    margin: 20px;
    padding: 10px;
    border-left: 5px solid #007bff;
}

/* Image Styling */
.styled-image {
    display: block;
    width: 50%;
    margin: 20px auto;
    border: 5px solid #007bff;
    border-radius: 10px;
}

/* Button Styling */
.button {
    display: inline-block;
    background-color: #28a745;
    color: white;
    padding: 10px 20px;
    text-decoration: none;
    margin: 20px;
    border-radius: 5px;
    font-weight: bold;
}

.button:hover {
    background-color: #218838;
}


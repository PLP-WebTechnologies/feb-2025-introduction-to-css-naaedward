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









##index.html
html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Styled Webpage</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1 class="main-title">Welcome to My Webpage</h1>
  </header>

  <nav id="main-nav">
    <a href="#">Home</a> |
    <a href="#">About</a> |
    <a href="#">Contact</a>
  </nav>

  <main>
    <p>This is a simple webpage designed to demonstrate external CSS styling.</p>
    <img src="https://via.placeholder.com/200" alt="Sample Image" class="styled-img">
  </main>

  <footer>
    <p>Co…
/* Selector 3: Element selector */
footer {
  margin-top: 20px;
  padding: 10px;
  border-top: 2px solid #ccc;
  text-align: center;
}

/* Style the image */
.styled-img {
  display: block;
  margin: 20px auto;
  padding: 10px;
  border: 2px solid #444;
}

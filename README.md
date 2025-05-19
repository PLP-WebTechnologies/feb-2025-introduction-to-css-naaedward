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






## index.html
html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Styled Webpage</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <h1 class="main-title">Welcome to My Page</h1>
  </header>

  <nav id="main-nav">
    <ul>
      <li><a href="#">Home</a></li>
      <li><a href="#">About</a></li>
    </ul>
  </nav>

  <main>
    <p>This is a simple webpage styled using external CSS.</p>
    <img src="naed.jpg" alt="Sample Image" class="styled-img">
  </main>

  <footer>
    <p>Contact: sarah@edward.com</p>
  </footer>
</body>
</html>


---

## style.css
css
/* Selector 1: Class */
.main-title {
  color: darkblue;
  font-family: 'Arial', sans-serif;
  font-size: 2em;
  margin-bottom: 20px;
}

/* Selector 2: ID */
#main-nav {
  background-color: #f4f4f4;
  padding: 10px;
  border: 1px solid #ccc;
}

/* Selector 3: Element */
p {
  font-family: 'Georgia', serif;
  line-height: 1.6;
  margin: 20px 0;
}

/* Style an image */
.styled-img {
  width: 300px;
  border: 5px solid #444;
  padding: 10px;
  margin-top: 15px;
}

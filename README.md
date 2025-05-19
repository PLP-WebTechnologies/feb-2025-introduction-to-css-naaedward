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









html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Simple Styled Page</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <header id="main-header">
    <h1>Welcome to My Page</h1>
  </header>

  <nav>
    <ul class="navigation">
      <li><a href="#">Home</a></li>
      <li><a href="#">About</a></li>
      <li><a href="#">Contact</a></li>
    </ul>
  </nav>

  <main>
    <section>
      <h2 class="section-title">About Me</h2>
      <p>This is a simple webpage styled with external CSS using selectors, padding, margin, and borders.</p>
      <img src="https://via.placeholder.com/150" alt="Sample" class="profile-img">
    </section>
  </main>

  <footer>
    <p>Contact me at: yourname@email.com</p>
  </footer>

</body>
</html>


---

✅ style.css
```css
/* ID selector */
#main-header {
  background-color: #333;
  color: white;
  text-align: center;
  padding: 20px;
}

/* Class selector */
.navigation {
  list-style-type: none;
  padding: 0;
  text-align: center;
  background-color: #f4f4f4;
  margin: 0;
}

.navigation li {
  display: inline;
  margin: 0 15px;
}
/* Element selector */
body {
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  margin: 20px;
  line-height: 1.6;
}

/* Image styling */
.profile-img {
  border: 3px solid #444;
  padding: 5px;
  margin-top: 15px;
  display: block;
}
```

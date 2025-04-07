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


<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>CSS Introduction</title>
  <link rel="stylesheet" href="style.css"> <!-- Linking external CSS -->
</head>
<body>

  <h1 id="main-title">Welcome to My Page</h1>

  <p class="intro">This is a simple webpage to demonstrate basic CSS styling.</p>

  <img src="https://images.pexels.com/photos/1236701/pexels-photo-1236701.jpeg" alt="Sample Image" class="styled-img">

  <div class="box">
    <p>This box has margins, padding, and a border.</p>
  </div>

</body>
</html>
✅ File 2: style.css
css
Copy
Edit
/* ID selector */
#main-title {
  color: #2c3e50;
  font-family: 'Georgia', serif;
  text-align: center;
  margin-top: 20px;
}

/* Class selector */
.intro {
  color: #34495e;
  font-size: 18px;
  margin: 20px;
  line-height: 1.6;
  font-family: Arial, sans-serif;
}

/* Element selector */
img.styled-img {
  width: 300px;
  height: auto;
  display: block;
  margin: 20px auto;
  border: 5px solid #3498db;
  padding: 10px;
  border-radius: 10px;
}

/* Box with margin, padding, and border */
.box {
  margin: 30px auto;
  padding: 20px;
  border: 2px solid #e74c3c;
  width: 60%;
  font-family: 'Courier New', monospace;
  background-color: #f9f9f9;
}

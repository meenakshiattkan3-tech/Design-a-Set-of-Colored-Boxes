# Design-a-Set-of-Colored-Boxes
This project demonstrates the use of different CSS color formats by designing a simple grid of colorful boxes. Each box is styled with a different type of color value in CSS, making it a great beginner-friendly practice project for learning and showcasing CSS basics.
** start of index.html **

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Colored Boxes</title>
  <style>
    /* 1. Body background color */
    body {
      background-color: #f4f4f4;
      font-family: Arial, sans-serif;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
    }

    /* 2. Container for color boxes */
    .color-grid {
      display: flex;
      gap: 15px;
    }

    /* 5. Shared style for color boxes */
    .color-box {
      width: 100px;
      height: 100px;
      border-radius: 10px;
      box-shadow: 0 4px 6px rgba(0,0,0,0.2);
    }

    /* 6. Hexadecimal color */
    .color1 {
      background-color: #3498db; /* Blue */
    }

    /* 7. RGB color */
    .color2 {
      background-color: rgb(231, 76, 60); /* Red */
    }

    /* 8. Predefined color */
    .color3 {
      background-color: green; 
    }

    /* 9. HSL color */
    .color4 {
      background-color: hsl(45, 100%, 50%); /* Yellow */
    }

    /* 10. Any background color */
    .color5 {
      background-color: orange;
    }
  </style>
</head>
<body>
  <!-- 2. Color Grid -->
  <div class="color-grid">
    <!-- 3 & 4. Five divs with correct classes -->
    <div class="color-box color1"></div>
    <div class="color-box color2"></div>
    <div class="color-box color3"></div>
    <div class="color-box color4"></div>
    <div class="color-box color5"></div>
  </div>
</body>
</html>


** end of index.html **

** start of styles.css **



** end of styles.css **


[Link to deployed site](https://lauraevepatterson.github.io/Learn-Responsive-Web-Design-by-Building-a-Piano/)

## Project: Learn Responsive Web Design by Building a Piano

### Introduction
This project is a part of the FreeCodeCamp curriculum aimed at teaching responsive web design principles through practical implementation. In this project, you will build a simple piano interface using HTML and CSS. The piano layout should adjust seamlessly across different screen sizes, demonstrating the importance of responsive design in web development.

### Project Structure
- **index.html**: Contains the HTML structure of the piano interface.
- **styles.css**: Contains the CSS styling rules for the piano interface.

### HTML Structure
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>Piano</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="./styles.css">
  </head>
  <body>
    <div id="piano">
      <img class="logo" src="https://cdn.freecodecamp.org/platform/universal/fcc_primary.svg" alt="freeCodeCamp Logo" />
      <div class="keys">
        <!-- Piano keys are dynamically generated here -->
      </div>
    </div>
  </body>
</html>
```

### CSS Styling
```css
html {
    box-sizing: border-box;
}

*, *::before, *::after {
    box-sizing: inherit;
}

#piano {
    /* Styling for the piano container */
}

.keys {
    /* Styling for the piano keys */
}

.key {
    /* Styling for individual keys */
}

.key.black--key::after {
    /* Styling for black keys */
}

.logo {
    /* Styling for the freeCodeCamp logo */
}

/* Media Queries for Responsive Design */
@media (max-width: 768px) {
    /* Adjustments for smaller screens */
}

@media (max-width: 1199px) and (min-width: 769px) {
    /* Additional adjustments for medium-sized screens */
}
```

### How to Run
1. Download or clone the project repository to your local machine.
2. Open the `index.html` file in a web browser to view the piano interface.
3. Experiment with resizing the browser window to observe the responsive behavior of the piano layout.

### Credits
- This project is based on the FreeCodeCamp curriculum.
- FreeCodeCamp Logo sourced from [freeCodeCamp.org](https://www.freecodecamp.org/).

### License
This project is licensed under the MIT License. Feel free to modify and distribute the code as per the terms of the license.

### Acknowledgments
Special thanks to FreeCodeCamp for providing educational resources to learn web development.
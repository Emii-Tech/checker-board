# checker-board
A beautiful and responsive checkerboard pattern crafted purely with HTML and CSS. No JavaScript!

# Checkerboard Pattern with HTML & CSS Grid

## Overview
This project is a **classic checkerboard pattern** created purely with **HTML and CSS**, utilizing the power of **CSS Grid** for layout. It demonstrates how to build an 8x8 grid with alternating colored squares without any JavaScript.

## Features
- Responsive 50x57 checkerboard layout
- Built entirely with semantic HTML and CSS Grid
- Clean, minimal code with no JavaScript dependencies
- Easy to customize colors and sizes via CSS

## How It Works
The checkerboard is implemented using a container with `display: grid`, defining 8 columns and 8 rows of equal size using fractional units (`1fr`). Each square is styled with alternating background colors (e.g., black and white) to create the classic pattern.

Example CSS snippet:

.outerbox{
    width:400px;
    border: 2px solid black;
    display: grid;
    grid-template-columns: 1fr 1fr 1fr 1fr 1fr 1fr 1fr;
    grid-template-rows: 1fr 1fr 1fr 1fr 1fr 1fr 1fr;
    gap: 0;
    margin-left: 200px;
    margin-top: 200PX;
}

.white{
    height:50px;
    width:57px;
    background-color: white;
}

.black{
    height:50px;
    width:57px;  
    background-color:black; 
}

h1{
    font-size: 50PX;
    color: brown;
}

.one{
  background-color: bisque; 
  width: 800px;
  margin-left: 400px;
  align-items: center;
  align-content: center;
  text-align: center;
}


## Usage
1. Clone or download the repository.
2. Open `index.html` in your browser.
3. The checkerboard will render automatically.

## Customization
- Adjust the `.container` width and height to change the board size.
- Modify the background colors in the `.square` classes to use different colors.
- Change the number of rows and columns in the CSS grid properties to create different grid sizes.

## Learnings
This project helped me explore:
- CSS Grid layout fundamentals
- Using `nth-child` selectors for alternating styles
- Creating patterns purely with CSS without JavaScript

## License
This project is open source and free to use.

Feel free to reach out if you have any questions or suggestions!

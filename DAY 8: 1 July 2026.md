Day 8 – CSS Flexbox and Grid

Date: 1 July 2026
Topic: CSS Flexbox and Grid
Training: MERN Stack Development

1. Introduction

Today, I learned about CSS Flexbox and CSS Grid. Both are CSS layout techniques used to arrange elements on a webpage.

They help developers create responsive and well-organized website layouts.

2. What is CSS Flexbox?

Flexbox stands for Flexible Box Layout. It is used to arrange elements in a row or column.

It makes it easier to align and distribute space between elements.

Important Flexbox Properties

1. "display: flex" – Enables Flexbox.
2. "flex-direction" – Defines the direction of items.
3. "justify-content" – Aligns items horizontally along the main axis.
4. "align-items" – Aligns items along the cross axis.
5. "flex-wrap" – Allows items to move to the next line.
6. "gap" – Adds space between items.

Example of Flexbox

HTML Code:

<!DOCTYPE html>
<html>
<head>
    <title>Flexbox Example</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <div class="container">
        <div class="box">Box 1</div>
        <div class="box">Box 2</div>
        <div class="box">Box 3</div>
    </div>

</body>
</html>

CSS Code:

.container {
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 20px;
    background-color: lightgray;
    padding: 20px;
}

.box {
    background-color: skyblue;
    padding: 30px;
    border: 2px solid black;
}

Output:

Three boxes appear in a horizontal row with equal spacing.

3. Flex Direction

The "flex-direction" property defines how flex items are arranged.

Common values:

- "row" – Items are arranged horizontally.
- "column" – Items are arranged vertically.
- "row-reverse" – Items are arranged in reverse horizontal order.
- "column-reverse" – Items are arranged in reverse vertical order.

Example:

.container {
    display: flex;
    flex-direction: column;
}

4. What is CSS Grid?

CSS Grid is a layout system used to arrange elements in rows and columns.

It is useful for creating complex webpage layouts.

Important Grid Properties

1. "display: grid" – Enables Grid layout.
2. "grid-template-columns" – Defines the number and size of columns.
3. "grid-template-rows" – Defines the size of rows.
4. "gap" – Adds space between rows and columns.
5. "justify-items" – Aligns items horizontally inside their grid cells.
6. "align-items" – Aligns items vertically inside their grid cells.

Example of CSS Grid

HTML Code:

<!DOCTYPE html>
<html>
<head>
    <title>Grid Example</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <div class="container">
        <div class="box">Box 1</div>
        <div class="box">Box 2</div>
        <div class="box">Box 3</div>
        <div class="box">Box 4</div>
    </div>

</body>
</html>

CSS Code:

.container {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 15px;
    padding: 20px;
}

.box {
    background-color: lightgreen;
    padding: 30px;
    text-align: center;
    border: 2px solid black;
}

Output:

Four boxes appear in two rows and two columns.

5. Difference Between Flexbox and Grid

CSS Flexbox| CSS Grid
One-dimensional layout system.| Two-dimensional layout system.
Works with rows or columns.| Works with rows and columns together.
Useful for navigation bars and aligning items.| Useful for complete webpage layouts.
Arranges items mainly along one axis.| Controls both rows and columns.

6. Responsive Layout

A responsive layout adjusts automatically according to the screen size of a device.

CSS Grid can create flexible columns using "auto-fit" and "minmax()".

Example:

.container {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
    gap: 15px;
}

This helps the layout adjust to different screen sizes.

7. Practical Example: Simple Webpage Layout

<!DOCTYPE html>
<html>
<head>
    <title>My Webpage Layout</title>
    <style>
        .container {
            display: flex;
            justify-content: space-around;
            background-color: lightblue;
            padding: 20px;
        }

        .box {
            background-color: white;
            padding: 25px;
            border: 2px solid black;
        }
    </style>
</head>
<body>

    <h2>My Webpage</h2>

    <div class="container">
        <div class="box">Home</div>
        <div class="box">About</div>
        <div class="box">Contact</div>
    </div>

</body>
</html>

8. Learning Outcomes

Today, I learned:

- The meaning of CSS Flexbox.
- How to arrange elements using Flexbox.
- Important Flexbox properties.
- The meaning of CSS Grid.
- How to create rows and columns using Grid.
- The difference between Flexbox and Grid.
- The basics of responsive layouts.

9. Practical Task

Create a webpage containing four boxes.

Apply the following:

- Use Flexbox to arrange three boxes horizontally.
- Use Grid to arrange four boxes in two rows and two columns.
- Apply different background colors.
- Add spacing using the "gap" property.
- Add borders and padding to the boxes.

10. Conclusion

Today, I learned about CSS Flexbox and Grid, which are important layout techniques in web development. I practiced arranging webpage elements in rows and columns and understood how to create responsive layouts.

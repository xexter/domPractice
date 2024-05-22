# DOM Manipulation Project

This project demonstrates how to manipulate a `div` element using the DOM (Document Object Model). The specific task is to change the color, background color, margin, padding, font size, font weight, height, and width of a `div` element.

## Task Details

The task involves the following DOM manipulations:

1. Use the `getElementById` method to retrieve the target `div` element.
2. Store the fetched element in a variable for further manipulation.
3. Change the background color of the fetched `div` element to yellow using the `style.backgroundColor` property.
4. Add a margin of 20 pixels to the element using the `style.margin` property.
5. Apply a padding of 10 pixels using the `style.padding` property.
6. Change the font size to 18 pixels using the `style.fontSize` property.
7. Set the font weight to bold using the `style.fontWeight` property.
8. Change the height of the element to 200 pixels using the `style.height` property.
9. Modify the width of the element to 300 pixels using the `style.width` property.

## Live Version

To view the live version of the project, visit the following link:

[Live Project Link](https://xexter.github.io/domPractice/)


## Example Code

 <div id="domDiv">Hello, I'm a div!</div>

    <script>
        let Element = document.getElementById("domDiv");

        Element.style.color = "blue";            // Change text color to blue
        Element.style.backgroundColor = "yellow"; // Change background color to yellow
        Element.style.margin = "20px";           // Add a margin of 20px
        Element.style.padding = "10px";          // Add a padding of 10px
        Element.style.fontSize = "18px";         // Change font size to 18px
        Element.style.fontWeight = "bold";       // Set font weight to bold
        Element.style.height = "200px";          // Change height to 200px
        Element.style.width = "300px";           // Change width to 300px
    </script>

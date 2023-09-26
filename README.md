# Eye-movement

This HTML and CSS code creates a simple web page with a cartoon face that follows the mouse cursor with its eyes. explanation 

1. The HTML structure consists of a `div` element with the class "face" representing the face of the cartoon character.

2. Inside the "face" div, there is another div with the class "eyes" which contains two "eye" divs and a "nose" div.

3. Each "eye" div is a white circular background with a black "ball" inside, representing the character's eyes.

4. The "nose" div is a brown-colored triangular shape that appears below the eyes.

5. In the CSS section, various styles are applied to create the appearance of the cartoon face, including positioning, sizing, and colors.

6. JavaScript is used to track the mouse cursor's movement (`document.onmousemove`). It calculates the mouse's X and Y coordinates as percentages of the window's width and height, respectively.

7. Inside the mousemove event handler, it iterates through the "ball" elements and updates their positions and transformations based on the mouse coordinates, creating the effect of the eyes following the cursor.

In summary, this code creates a visually appealing and interactive cartoon face that responds to the user's mouse movements by making the eyes follow the cursor.

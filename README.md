# CSS_Drills

Objective

Practice using the fundamentals of CSS that were explored in lecture.

Setup

1. Create a new project folder and connect it to a github repository. Copy this README.md file into it.
2. Create an index.html file and a styles.css file
3. In the head element, link the two files together by using the link tag:

Build the HTML Structure

1. In the body element, create a div with an id of "container"
2. Add 4 div elements with a class name of "boxes" and a unique id (box1, box2, boxN) inside the container div. Each added div will be a child of the container div and a sibling to each other
3. Create a h2, p, and an anchor element inside of each of the 4 div's
    h2: A story title
    p: A story description
    a: Read Me
4. Add some text for the heading, paragraph, and anchor elements

Now, Lets style!

1. Assign a global font family
    Here is a list of some Web Safe Fonts: https://www.w3schools.com/cssref/css_websafe_fonts.asp

    You could also play around with Google Fonts: https://fonts.google.com/

        { font-family: "Palatino Linotype", "Book Antiqua", Palatino, serif; }
2. Change the background color for the body element: *the two forward slashes indicate a comment. The HEX value (#XXXXXX) is the HEX equilvalent to lightgray. *you can use either one in this drill.
3. Use a multiple selector rule set to center the text for all h2, p, and a elements
4. Use an element selector to remove the default underline styles for a anchor element and change the font color:
*When you refresh your browser you'll notice that the link is not centered like the h2 and p elements. This is because text-align will center the element based on the width assigned to it. If you apply a border to the link tag, you'll see that the link is centered inside the anchor element. The best way to center the link, relative to its parent element, is to enclose it inside of a div element.

5. Wrap the anchor element inside of the div and give the div a class name of "readme-wrapper":
6. Replace the a in the multiple selector rule with .readme-wrapper
7. Now refresh and you'll see the link is centered as we expected it
8. Use a class selector to target the .boxes class:
    Change the display to inline-block
    add margin
    add padding
    add a solid border
    add a border radius to round the edges of the border
9. Add a CSS :hover selector so that when the link is moused over the cursor changes to a pointer, the font is bold, and text color changes:
10. Wrap a single word in each paragraph element inside of a span element and assign it a new font color and font weight:
11. Change the display to block in the class selector named .boxes
12. When you refresh the page, you'll see each div now takes up the entire row
13. Add a width of 20% to each div with the class .boxes
14. Use an id selector to add an unique background color to each div
15. Change the position of the second div to be relative to its parent
16. Position the second div so that it is next to the first div
17. Change the position to absolute
18. Position the second div to the top right corner
19. Remove the position styles for the second div
20. The second div should now be returned to the normal flow
21. Add a new div element as a child inside each of the 4 div elements
    we'll use this div to represent an image
22. Give the new div a class name
23. Assign a width, height, and background color to the div
24. Position the div so its inline and to the left of the header

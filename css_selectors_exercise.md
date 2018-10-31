# CSS Selector Exercise

1. Add a link in the index.html to a css file.
completed

2. Assign a class to all header tags and make them all underlined and bold.
completed

3. Change the size of all img tags that have a src that starts with https.
I learned I can class images AFTER the alt

4. Give the h1 tag a unique id and make turn it to the color of your choice.
I can assign something with both a class & an ID
HTML will try to apply as much as possible - going left to right

5. All links that end in .com should be the color green after a visit to the link.
completed - must update default color THEN set a visited color.


6. Using a class name in the ul remove all of the li's bullet points in the list of .coms.
completed - Set class to list-style: none;  

7. In the ol change only the last child element to be bold. Look it up!
completed - ol li:last-child

8. Give the contact email a hover effect of turning red.
completed

9. Give all other links a hover effect of turning orange.
completed
we know that the links are apart of the UL group so we can specify the pseudo-class to the UL class

10. Inside of your languages ul, change the font to be in italics.
completed

11. Center all text inside the body.
completed text-align: center;

12. In the hardest bug so far, change only the first p tag using a selector on the div. Give it this: background-color: rgba(0,0,0,.5);

i want to use sibling (+)because sibling will give me the next item that fits:
 div / h3 / p

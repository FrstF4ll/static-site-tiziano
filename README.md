# Static website

## Content

- Pictures folder
- "Index" files for HTML
- "Style" files for CSS

## Built with : 

* HTML5
* CSS3 
    * Flexbox
    * Grid 
## What is it ?
 
This is my first website. It was built to display properly at a 1920x1080 resolution. It's based on a predefined Figma model. 


### Flexbox

Flexbox was used to group content, enabling me to move entire sections at once rather than adjusting each item separately.

Example of flexbox : 

    .white_box {
    display: flex; 
    flex-direction: column;
    align-items: center;
    border-radius: 50px;
    padding: 71px 165px; 
    gap: 60px;

### Grid

I utilized CSS Grid to structure and organize the layout of my items.

Example of grid :

    .comments {
    display: grid;
    grid-template-columns: 4fr 4fr 2fr 4fr 4fr;
    grid-template-rows: 1fr 10fr 1fr;

 I used ```column-gap``` and row-gap to add spacing, preventing the creation of unnecessary columns or rows.

SSome Flexbox elements have been inserted inside the grid to allow better organization and display. I positioned them using the common```grid-column``` or ```grid-row``` properties.


The HTML code has been validated with the W3C Validator.

### Conclusion

This website uses a lot of pixel values for dimensions, which makes it less adaptive, but it was a good experience for taking my first steps in basic web development.
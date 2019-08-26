Furthering CSS revision via FreeCodeCamp's CSS Flexbox resources and copying passed code to Git repo as I go through each task. Documenting below anything new I learn, or anything I am reminded of that I may have forgotten.

- Learned to use flex-shrink to shrink items on an individual basis:
    - Applied to individual elements within a flex container
    - Takes a number as a property, indicating the amount the element will shrink compared to the other items in the container example:
        .box-1 {
        background-color: dodgerblue;
        width: 100%;
        height: 200px;
        flex-shrink:1;
    }

        .box-2 {
        background-color: orangered;
        width: 100%;
        height: 200px;
        flex-shrink:2;
    }

    .box-2 will shrink twice as much as .box-1.

- Learned to use flex-grow. Works as above to expand items.

- Learned flex-basis. Works similar to shrink/grow but takes a size value (px, em, % etc.) to set the initial scale of an item prior to shrinking or growing.

-Learned flex shorthand. Establishes grow, shrink and basis all in one declaration.
    - Order is grow, shrink, basis. Not comma separated:
        .box-1{
            flex: 1 1 150px;
        }

- Learned order property. Tells elements in which order to display, rather than drawing order from HTML. Values must be numbers. Negative numbers accepted.
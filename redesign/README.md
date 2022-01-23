Exercises

EASY
- A
  - Justify content to give a positioning to all elements simultaneously
- A-A
  - Use margin to add spacing to an element by the sides
- B
  - Setting flex property to 1 for 1 element makes it fill as much space as possible, and the rest just fit their content
- C
  - Setting flex to all elements except for one, makes all fill equal portions of available space, but the one without flex will fit its content
- D
  - Align items in the cross axis direction with align-items
  - center items inside its container with justify-content and align-items
  - Align items one by one with align-self
- E
  - Use column as main axis direction
  - align-items now affects the horizontal direction
- F
  - If items are larger than the space available, with flex-wrap they can go to the next row
- G
  - Flex property is a shorthand of flex-grow, flex-shrink and flex-basis, it's set for each item inside the flex box
  - The default is `flex: 0 0 auto;`
- H
  - Set order of elements

MEDIUM
- I
  - A typical example of responsive list of items, for small screens there's no space to fit all items in the same line
  - We made fontsize very large to more easily visualize
  - Desktop: 4 items, item 3 fills as much space as is available
  - width < 880px: 2 rows, 2 items per row
  - width < 560px: one column, order is 1, 2, 4, 3
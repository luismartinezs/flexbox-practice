# Flexbox grind

## Levels:

- 1 = all line by line TODOs
- 10 = very general TODOs
- 11 = Empty
- 15 = Empty
- 20 = Emtpy

|Difficulty | TODO | From zero|
|---|---|---|
|1|2|4|
|2|4|8|
|3|6|12|
|4|8|16|
|5|10|20|

## Steps

- [x] Decide layouts
- [x] Recording once, without preparation
- [x] Watch and write steps
- [x] Take screenshot of end result
- [ ] Write README, and/or create a PDF with instructions and images
- [ ] Do video following steps
- [ ] Make repo with TODOs
- [ ] Publish video with link to repo
- [ ] Design merc (tees)


## Exercises

### Difficulty: 1

- A: position along main axis (1)
  - Justify content to give a positioning to all elements simultaneously
- A-A: position along main axis (2)
  - Use margin to add spacing to an element by the sides
- B: filling space with flex (1)
  - Setting flex property to 1 for 1 element makes it fill as much space as possible, and the rest just fit their content
- C: filling space with flex (2)
  - Setting flex to all elements except for one, makes all fill equal portions of available space, but the one without flex will fit its content
- D: align items
  - Align items in the cross axis direction with align-items
  - center items inside its container with justify-content and align-items
  - Align items one by one with align-self
- E: flex direction, aligning items in column layouts
  - Use column as main axis direction
  - align-items now affects the horizontal direction
- F: wrap items to next row
  - If items are larger than the space available, with flex-wrap they can go to the next row
- G: make elements grow and shrink differently
  - Flex property is a shorthand of flex-grow, flex-shrink and flex-basis, it's set for each item inside the flex box
  - The default is `flex: 0 0 auto;`
- H: Order items
  - Set order of elements

### Difficulty: 2

- I: responsive list of items
  - A typical example of responsive list of items, for small screens there's no space to fit all items in the same line
  - We made fontsize very large to more easily visualize
  - Desktop: 4 items, item 3 fills as much space as is available
  - width < 880px: 2 rows, 2 items per row
  - width < 560px: one column, order is 1, 2, 4, 3

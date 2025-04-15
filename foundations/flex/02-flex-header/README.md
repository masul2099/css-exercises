# A Basic Header

Use flexbox rules to create this very common webpage header style. The benefit to using flex here is that everything should be _flexible_. Check out the two screenshots below to get an idea of how it should scale with your screen. Besides flex rules, you'll also want to add some rules for margin and padding. (Hint: `ul`s have some default margin/padding that you will need to deal with.)

## Desired Outcome

narrow:
![narrow](./desired-outcome-narrow.png)

wide: 
![wide](./desired-outcome-wide.png)

### Self Check
- There is space between all items and the edge of the header (specific px amount doesn't matter here).
* Use space-between and padding of 8px
- Logo is centered vertically and horizontally.
* Space-between centers logo
- list-items are horizontal, and are centered vertically inside the header.
* List is flex container and children are layed horizontally
- left-links and right-links are pushed all the way to the left and right, and stay at the edge of the header when the page is resized.
* Both links remain at beginning and end of header when page is narrower
- Your solution does not use floats, inline-block, or absolute positioning.
* No, just flexbox

- Note: For this exercise, it's completely acceptable to not match the font-family.
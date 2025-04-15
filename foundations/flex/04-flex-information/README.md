# A very common website feature

The goal of this exercise is to recreate a section that is found on many informational websites.

For this one you will need to edit the HTML a little bit too. We can't be making things _too_ easy for you. You'll want to add containers around the various elements so that you can flex them. Good luck!

## Desired outcome

![desired outcome](./desired-outcome.png)

### Self Check

- All items are centered on the page (horizontally, not vertically).
* Only aligned items horizontally with d-flex
- The title is centered on the page.
* With d-flex
- There is 32px between the title and the 'items.'
* Added mb of 22px
- There is 52px between each item.
* No gap, only justified with space-around
- The items are arranged horizontally on the page.
* Yes
- The items are only 200px wide and the text wraps.
* No, added flex-basis of 200px, and added d-flex 
  and changed flex-direction to column, and aligned img
  with auto margins
- The item text is centered.
* Yes, with text-align

**Solution

- .title is aligned with text-align: center in body selector
- .plants has d-flex with content justified in center with gap of 52px
- .info has a max-width of 200px

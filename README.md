# Inspire-Page-using-Flexbox
I used flexbox to design the layout of the webpage
## Layout type
Flexbox
### Properties
| **Property**       | **Description**                                                                                                                                                                         | **Values**                                                                                                                                                                              |
|--------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `flex-direction`   | Specifies the display-direction of flex items in the flex container.                                                                                                                   | `row` (horizontal), `column` (vertical), `row-reverse` (right to left), `column-reverse` (bottom to top)                                                                               |
| `flex-wrap`        | Specifies whether the flex items should wrap or not, if there is not enough room for them on one flex line.                                                                            | `nowrap` (don’t wrap), `wrap` (wrap if necessary), `wrap-reverse` (wrap in reverse order)                                                                                               |
| `flex-flow`        | Shorthand property for setting both the `flex-direction` and `flex-wrap` properties.                                                                                                   | Set the `flex-direction` then the `flex-wrap`, e.g., `row wrap`                                                                                                                         |
| `justify-content`  | Used to align the flex items when they do not use all available space on the main axis (horizontally).                                                                                 | `flex-start`, `center`, `flex-end`, `space-around`, `space-between`, `space-evenly`                                                                                                     |
| `align-items`      | Used to align the flex items when they do not use all available space on the cross axis (vertically).                                                                                  | Same values as `justify-content`, plus `stretch` (default), `baseline`                                                                                                                  |
| `align-content`    | Similar to `align-items`, but instead of aligning flex items, it aligns the flex **lines** when there's extra space in the cross-axis.                                                | Same values as `align-items`                                                                                                                                                           |



Properties                                                           Description                                                                                                                                              Values
1. flex-direction                          specifies the display-direction of flex items in the flex container.                                                                            row(hor), column(ver), row-reverse(horizontal but from right to left), column-                                                                                                                                                                                                 reverse(vertical but from bottom to top)
  

2. flex-wrap                               specifies whether the flex items should wrap or not, if there is not enough room for them on one flex line.                                     nowrap(don't wrap), wrap(wrap if necessary), wrap-reverse(wrap in reverse order)




3. flex-flow                              shorthand property for setting both the flex-direction and flex-wrap properties.                                                                 set the flex-direction then the flex-wrap, ex: row wrap 




4. justify-content                        used to align the flex items when they do not use all available space on the main-axis (horizontally).                                            start, center, end, space-around(displays the flex items with space around them),                                                                                                                                                                                              space between( displays the flex items with space between them), space-                                                                                                                                                                                                        evenly(displays the flex items with equal space around them)




5. align-items                            used to align the flex items when they do not use all available space on the cross-axis (vertically).                                              Same values as justify-content but on the secondary axis, and some more values                                                                                                                                                                                                 like stretch(stretches the flex items to fill the container (this is equal to                                                                                                                                                                                                  "normal" which is default)), baseline(positions the flex items at the baseline of                                                                                                                                                                                               the container) 




6. align-content                          similar to align-items, but instead of aligning flex items, it aligns the flex lines.                                                              Same values as align-items

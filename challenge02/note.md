Notes:

Max-Widths
- Setting a fixed width on an element tends to be a bad idea
- Instead we can use percentages, which make our lives easier
- The issue with this is at large screens, things can get too big 
- We have max-width to help us out!

CSS Units: vh, vw, vmin, vmax
- 'vh' and 'vw' stand for viewport height/width
- It adapts to whatever your viewport height/width is
- This can be a problem on mobile, as the height of some content may exceed the vh

- This can be useful for padding. E.g 'padding: 10vh 0' adapts it's height to the viewport
- Setting font-size with 'vh' can be useful for increasing/decreasing size of titles 

- 'vmin' finds the smaller of vh or vw, and bases size of this (can use for font-size)
- 'vmax' finds the larger of vh or vw (not quite as useful as things never really shrink small enough)
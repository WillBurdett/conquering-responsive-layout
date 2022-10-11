Key learnings:

Big picture
- HTML is completely responsive, so it is your CSS that is breaking the responsiveness

Widths 
- Percentages are better than fixed widths e.g. 20% is better than 15px
- A percentage 'width:' takes up the given % of the parent container
- You won't always need to set widths on the child element

Heights
- "If you need to give something a height - don't..."
- If you want more background, set padding on it using 'em's

Ems 
- A font-size in 'em' relates to the font-size of the parent
- E.g. 2.5em would be 2.5 times the size of the parent elements font-size
- 1em defaults to 16px if no other font-size is set
- An issue with this is that the elements font-size compound
- E.g. Grandparent 1em = 16px, Parent 2em = 32px, Child 2em = 64px!

Rems
- 'rem' was designed to solve this compounding problem
- Rem always looks at the root font-size

- These rules change when looking at 'margin' and 'padding' (things other than font-size)
- 'margin-bottom: 1em' will use 1em of THAT elements font-size
- e.g. 'font-size: 2.5em' and 'margin-bottom: 1em' will make the margin-bottom 2.5em!
- This is the same for all margins/padding

- However Rems still ONLY look at the root font-size for this sizing

Why is this useful?
- E.g. a buttons padding is set by 'em'
- This means you only need to change the font-size of the button for padding to scale
- In a larger sense, you can rescale large components using 'em'
- Apparently this will later help with media queries
- However if you want consistent/exact margins or padding, 'rem' would make more sense






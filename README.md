### There are four classes used in advanced CSS.
- **.has-pb-0** (for titles with padding bottom 0px instead of the default 16px)
- **.has-pb-8** (for titles with padding bottom 8px instead of the default 16px)
- **.change-order** ( flexbox, reverses order of columns on tablet and mobile)
- **.has-buttons-side-by-side** (when two or more buttons are side by side)

#### .has-pb-0 & .has-pb-8
Vertical rhythm is set to 8px. Padding-bottom is set to 16px instead of the default 10px. Some titles need to be tighter so we can use one of both utility classes. That is seen on hero banner where we have a h2 and h4 title.

#### .change-order
Some sections have rows where an image is on the second column. On tablet and mobile devices reversed order makes the section more pleasant. Utilizes flex-box and order on first and last child. **Works on two column rows only**.

#### .has-buttons-side-by-side 
Makes buttons inline-blocks, text-aligned center and adds margin left so that they have some space
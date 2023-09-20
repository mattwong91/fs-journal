# Bootstrap
## Documentation
https://getbootstrap.com/docs/5.3/getting-started/introduction/

## Notes
Container is the main parent element
Rows and columns are used to break up a page

Rows have 12 units of space
Rows are flex by default. Can apply `justify-content`, etc.

col-1 is using 1 unit of space, col-4 uses 4 units of space

`link` bootstrap to your html document

`container` class has some padding and margin by default. `container-fluid` class is edge to edge.

Do ***NOT*** nest rows inside of rows, cols inside of cols.
Do ***NOT*** apply margin to the x axis of a col-12

padding classes `p-1` to `p-5`
margin classes `m-1` for overall margin, `mt-1` for margin top, `my` for margin y-axis etc.
font weight `fw` font size `fs`
button class: `btn`
`img-fluid` class tells the image to respect column boundary if it is too large *(images only)*
  set the width to something *(ex: 100%)* in your own class if image is too small and want to stretch
`rounded` class is a border radius *(all elements)*
display can be none `d-none` class accomplishes this.
`sticky-top` class means that it will stick to the immediate parent element
`order-1` `order-2` can determine column order. Breakpoints can be applied

### Breakpoints
Allow for different viewport layouts
EX:  `class="col 12 col-md-4 col-lg-3"` This means once you hit the *medium* viewport it will change to a col-4, *large* will be col-3

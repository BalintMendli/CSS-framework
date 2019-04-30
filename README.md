## A Custom CSS framework

A simple CSS framework with a 12 column grid.

### Grid

The framework uses CSS flexbox for its grid system. 
To use it you have to specify a row by adding the class `.row`. 
If you want to specify the width, you can add the class `.col` followed by a number from `1` to `12`. 

The grid can responsive as well. You can specify different widths for different breakpoints by adding `s`, `m`, `l` at the end of the class's name. For example:
`col3 col5m col12s`

### Responsive breakpoints
```css
// l: large ( 992px and down)
@media (max-width: 992px) { ... }

// m: medium (768px and down)
@media (max-width: 768px) { ... }

// s: small (576px and down)
@media (max-width: 576px) { ... }
```
It is important to note that the framework is, unlike bootstrap, desktop first, so the breakpoints apply up to a maximum width.
There are a `.container` and a `.container-fluid` class to define a container for the content. `.container` has a max-width, `.container-fluid` has 100% width.

### Spacing

The margin and padding utility classes are named using the format {property}{side}{size}. Where property is either `m` for margin or `p` for padding, side is either `t`, `l`, `b` or `r` for top, left, bottom and right respectively, and the size can be a value from `0` to `5`.
For example, `mt0` gives a margin-top of `0px`.

### Colors

The color classes available:
`.primary`, `.accent`, `.white`, `.light`, and `.primary-bg`, `.accent-bg`, `.white-bg`, `.light-bg` to set background colors.

### Buttons

Buttons can be specified with the `.button` class.

### Typography

The framework uses the font Open Sans.

### Utilities

There are several other utility classes available:
* `.text-center`, `.text-left`, `.text-right` to align text,
* `.shadow` to add box-shadow to the element,
* `.d-none`, `d-block`, `d-flex` to specify display properties. These classes are responsive as well,
* `.flex-column`, `.justify-center`, `.justify-between`, `.align-center` to set flexbox properties,
* `.img-resp` to make an image responsive

Example project built with the framework: https://github.com/zenott/Building-with-custom-CSS-framework

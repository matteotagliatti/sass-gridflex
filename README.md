# SASS GridFlex

A responsive 12 columns grid system based on the flex property, written in Sass. It's fully responsive and easy to implement, inspired by Bootstrap class names.

👉 [Demo](https://matteotagliatti.github.io/sass-gridflex/demo.html)
👉 [Test](https://matteotagliatti.github.io/sass-gridflex/demo.html) (for visualize styles)

## How to use

### Container, Rows and Columns

```html
<div class="container">
    <div class="row">
        <div class="col-6-md">
        <div class="col-6-md">
    </div>
</div>
```

Put all your content into a `.container` class. Everything must be in a `.row` div and then create the columns with `.col-(number of column)-(breakpoint)`. The total of the columns is 12. The breakpoints are: `xs`, `sm`, `md`, `lg` and `xl`.

### Utilities

#### Margin and Padding

`.m-2` is `margin: 20px`. You can use `m-0`, `m-1`, `m-2` and `m-3`. You can apply a specific direction to it. `.m-t-2` is `margin-top: 20px`. There are 4 direction: `t` for top, `l` for left, `b` for bottom and `r` for right. There are 5 distances: from `1` to `5`.

The same is for the padding property using `p` insted of `m`. Example: `.p-t-2` is `padding-top: 20px`.

#### Opacity 

`o-(number from '1' to '10')`. Example: `.o-10` is `opacity: 0.1`

#### Border Radius

`br-(default / none / xs / sm / lg / full)`.

#### Display

`d-('n' for none / 'b' for block / 'f' for flex / 'i' for inline / 'i-b' for inline-block)`

#### Font Size

`font-(sm / md / lg / xl)`

### Justify Content

Our elements are based around the `flex` property. So you can style the layout according to it using 4 layout values: `justify-flex-start`, `justify-flex-end`, `justify-center`, `justify-space-between` and `justify-space-around`.

### Colors

Some prebuilt color: `blue`, `green`, `red`, `yellow`, `orange`, `purple`, `grey`, `black` and `white`.

You can use with `.text-(color)` or `.bg-(color)`. There are event link and dark variations. Example. `bg-green-dark-7`. You can change the color on hover using `text-hover-(color)` or in combination with a variation. Example: `text-hover-green-dark-3`.

### Buttons

`.btn-(color)` or `.btn-outlined-(color)`.
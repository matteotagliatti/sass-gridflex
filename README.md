# SASS GridFlex

A responsive 12 columns grid system based on the flex property, written in Sass. It's fully responsive and easy to implement, inspired by Bootstrap class names.

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

### Margin and Padding
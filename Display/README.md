# Block, Inline, and Inline-Block
This is my notes for using block, inline, and inline-block

#### Display Project <a href="https://haithamthabt.github.io/css/Display">Demo</a> 

## _Display_
The `display` property specifies if/how an element is displayed.

## Block-level Elements
#### _Note_: Most things are blocks (Almost everything is a block)
An example of a block is `<p>`
#### Block level elements always stack on top of each other even if they have room to go next to each other
By default A Block-level element always starts on a new line and have %100 width
- They Always force a new line
- They accept Margin-top-bottom, Padding-top-bottom, and they work and it effects the layout
#### Examples of block-level elements:
- `<div>`
- `<h1> - <h6>`
- `<p>`
- `<form>`
- `<header>`
- `<footer>`
- `<section>`


## Inline Elements
An inline element does not start on a new line and only takes up as much width as necessary.
#### Examples of inline elements:
- `<span>`
- `<a>`
- `<img>`

Padding-top-bottom and margin-top-bottom on inline elements dont effect them at all.
Generaly speaking you cant effect the height of inline elements
- They Dont force new line
- They dont accept Padding-top-bottom and margin-top-bottom, therfore it does not effect the layout
- They have margin-left-right, padding-left-right that will effect the layout but not top-bottom


## Inline-Block Elements
- This is used for if you need an inline element that can also have padding and margin on it
An example of this is when we style links as buttons 

    `<a href="#" class="btn">I am a link/button</a>`

- We usually use inline-block to prevent inline elements from overlapping on each other
- They dont force a new line if they have room to be next to each other
- Now we have the ability to set margin and padding, or height similar to block elements, but also allow the element to not force a new line so they are inline in a sense they go next to one another. 

## Display: none;
`display: none;` is commonly used with JavaScript to hide and show elements without deleting and recreating them. 
The `<script>` element uses `display: none;` as default. 






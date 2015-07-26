# CSS Styleable Lists

Easy CSS styling for `ul` bullets and `ol` numbers.

#### Have you ever wanted to color the bullets or numbers of an HTML list independently from the body text?  

Unfortunately, the CSS is not as straight forward as you'd expect.

The CSS library styleable-lists makes it easy to style HTML list bullets and numbers without affecting the body text. Simply place your styles on the `li:before` selector and vola custom bullets. Observe the following example where we choose to style our ul bullets &amp; ol numbers red.

```css
li:before {
  color: red;
}
```
### Installation

#### Using Bower

First, install the bower package with the following command.

```
bower install styleable-lists --save
```

Next, include the CSS or SCSS file in your project.

If you wish to use the complete package use the `stylable-lists-all.css` file. This includes the stylable-lists base styles plus additional styling classes.

```html
<link href="/bower_components/stylable-lists/stylable-lists-all.css">
```

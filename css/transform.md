# transform

## Applied Visual Design: Use the CSS Transform scale Property to Change the Size of an ElementPassed

 [freecodecamp explanation](https://www.freecodecamp.org/learn/responsive-web-design/applied-visual-design/use-the-css-transform-scale-property-to-change-the-size-of-an-element)

 To change the scale of an element, CSS has the transform property, along with its scale() function. The following code example doubles the size of all the paragraph elements on the page:


 ```css
 p {
  transform: scale(2);
}
```

### Heartshape
```css
  .heart {
    position: absolute;
    margin: auto;
    top: 0;
    right: 0;
    bottom: 0;
    left: 0;
    background-color: pink;
    height: 50px;
    width: 50px;
    transform: rotate(-45deg) ;
  }
  .heart::after {
    background-color: pink;
    content: "";
    border-radius: 250%;
    position: absolute;
    width: 50px;
    height: 50px;
    top: 0px;
    left: 25px;
  }
  .heart::before {
    content: "";
    background-color: pink;
    border-radius: 50%;
    position: absolute;
    width: 50px;
    height: 50px;
    top: -25px;
    left: 0px;
  }
```
```html
<div class="heart"></div>
```
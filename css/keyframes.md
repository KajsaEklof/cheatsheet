# keyframes 

## How the CSS @keyframes and animation Properties Work

 [freecodecamp explanation](https://www.freecodecamp.org/learn/responsive-web-design/applied-visual-design/learn-how-the-css-keyframes-and-animation-properties-work)

 ### keyframes

 The animation properties control how the animation should behave and the @keyframes rule controls what happens during that animation. There are eight animation properties in total. 

 * animation-name sets the name of the animation, which is later used by @keyframes to tell CSS which rules go with which animations.
* animation-duration sets the length of time for the animation.
* @keyframes is how to specify exactly what happens within the animation over the duration. 

### animation-fill-mode 

Specifies the style applied to an element when the animation has finished.

Example:
```css 
animation-fill-mode: forwards;
```

### Movement
```css
animation-name: slide;
animation-duration: 2s;
@keyframes slide {
    0% {
      left: -100%;
    }
    100% {
      left: 0px;
    }
  }
```

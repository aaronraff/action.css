# Action.css
Animation library for CSS3.

### How to use this library

If you would like to use an animation on something you need to add a class of "action" to the tag.

You also need to add a length class to the tag (classes listed below):

```css
/*Duration Cases*/
.action-fast {
  -webkit-transition: 0.3s all;
  -moz-transition: 0.3s all;
  -o-transition: 0.3s all;
  transition: 0.3s all;
}

.action-normal {
  -webkit-transition: 0.5s all;
  -moz-transition: 0.5s all;
  -o-transition: 0.5s all;
  transition: 0.5s all;
}

.action-slow {
  -webkit-transition: 1.0s all;
  -moz-transition: 1.0s all;
  -o-transition: 1.0s all;
  transition: 1.0s all;
}

.action-lengthy {
  -webkit-transition: 1.5s all;
  -moz-transition: 1.5s all;
  -o-transition: 1.5s all;
  transition: 1.5s all;
}
```

Finally you need to add an animation type class.

See the action.css file for different types of animation.

Any animations that include a color change can be modified by changing the "background-color" property in the corresponding class.

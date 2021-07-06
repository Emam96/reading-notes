# CSS Transforms, Transitions, and Animations

## Transforms

The transform property applies a 2D or 3D transformation to an element.
Transforms are triggered when an element changes states, such as on mouse-hover or mouse-click. The examples in this post will demonstrate transforms on mouse-hover.

### Transform Syntax

1. **matrix:** Defines a 2D transformation, using a matrix of six values 
2. **matrix3d** Defines a 3D transformation, using a 4x4 matrix of 16 values 
3. **translate(x,y)** Defines a 2D translation 
4. **translate3d(x,y,z)** Defines a 3D translation 
5. **translateX(x)** Defines a translation, using only the value for the X-axis 
6. **translateY(y)** Defines a translation, using only the value for the Y-axis 
7. **translateZ(z)** Defines a 3D translation, using only the value for the Z-axis 
8. **scale(x,y)** Defines a 2D scale transformation 
9. **scale3d(x,y,z)** Defines a 3D scale transformation 
10. **scaleX(x)** Defines a scale transformation by giving a value for the X-axis 
11. **scaleY(y)** Defines a scale transformation by giving a value for the Y-axis 
12. **scaleZ(z)** Defines a 3D scale transformation by giving a value for the Z-axis 
13. **rotate(angle)** Defines a 2D rotation, the angle is specified in the parameter 
14. **rotate3d(x,y,z,angle)** Defines a 3D rotation 
15. **rotateX(angle)** Defines a 3D rotation along the X-axis 
16. **rotateY(angle)** Defines a 3D rotation along the Y-axis 
17. **rotateZ(angle)** Defines a 3D rotation along the Z-axis 
18. **skew(x-angle,y-angle)** Defines a 2D skew transformation along the X- and the Y-axis 
19. **skewX(angle)** Defines a 2D skew transformation along the X-axis 
20. **skewY(angle)** Defines a 2D skew transformation along the Y-axis 
21. **perspective(n)** Defines a perspective view for a 3D transformed element 
22. **initial** Sets this property to its default value. Read about initial 
23. **inherit** Inherits this property from its parent element. Read about inherit

<div class="stage">
  <figure class="ball"></figure>
</div>
<style>
@keyframes slide {
  0% {
    left: 0;
    top: 0;
  }
  50% {
    left: 244px;
    top: 100px;
  }
  100% {
    left: 488px;
    top: 0;
  }
}
.stage {
  background: #eaeaed;
  border-radius: 6px;
  height: 150px;
  position: relative;
  min-width: 538px;
}
.stage:hover .ball {
  animation: slide 2s ease-in-out .5s infinite alternate;
}
.stage:active .ball {
  animation-play-state: paused;
}
.ball {
  background: #2db34a;
  border-radius: 50%;
  height: 50px;
  position: absolute;
  width: 50px;
}
</style>

&nbsp;


By understanding the transform property, you’ll unlock ways to further build unique and engaging interfaces from scratch. So, in this post, I’ll show you everything you need to know to start using the CSS transform property, including the many ways you can manipulate elements in two and three dimensions, and even how to animate such effects.

&nbsp;
<hr>


## Transitions

CSS transitions allows you to change property values smoothly, over a given duration.

To create a transition effect, you must specify two things:

* the CSS property you want to add an effect to.
* the duration of the effect.


The **transition-timing-function** property specifies the speed curve of the transition effect.

The transition-timing-function property can have the following values:

* ease - specifies a transition effect with a slow start, then fast, then end slowly (this is default)
* linear - specifies a transition effect with the same speed from start to end
* ease-in - specifies a transition effect with a slow start
* ease-out - specifies a transition effect with a slow end
* ease-in-out - specifies a transition effect with a slow start and end

Transitions are the grease in the wheel of CSS transforms. Without a transition, an element being transformed would change abruptly from one state to another. By applying a transition you can control the change, making it smooth and gradual.



&nbsp;
<hr>


## Animations

>An animation lets an element gradually change from one style to another.

### **The @keyframes**
When you specify CSS styles inside the @keyframes, the animation will change from the current style to the new style at certain times.
To get an animation to work, you must bind the animation to an element.


![ME](https://www.imore.com/sites/imore.com/files/styles/xlarge/public/field/image/2014/11/understanding_css_animations_03.jpeg?itok=Qdn5mQQc)

The animation-direction property specifies whether an animation should be played forwards, backwards or in alternate cycles.

The animation-direction property can have the following values:

1. **normal** - The animation is played as normal (forwards). This is default.
2. **reverse** - The animation is played in reverse direction (backwards).
3. **alternate** - The animation is played forwards first, then backwards.
4. **alternate-reverse** - The animation is played backwards first, then forwards.

The animation-fill-mode property specifies a style for the target element when the animation is not playing (before it starts, after it ends, or both).

The animation-fill-mode property can have the following values:

1. **none** - Default value. Animation will not apply any styles to the element before or after it is executing
   
2. **forwards** - The element will retain the style values that is set by the last keyframe (depends on animation-direction and animation-iteration-count)
3. **backwards** - The element will get the style values that is set by the first keyframe (depends on animation-direction), and retain this during the animation-delay period
4. **both** - The animation will follow the rules for both forwards and backwards, extending the animation properties in both directions.


<hr>
&nbsp;
&nbsp;

Get back to [EMAM'S HOMEPAGE](https://emam96.github.io/reading-notes/)

 I have created this page as a part of my project using Github, Please visit my [profile](https://github.com/Emam96), I will be more than happy to hear from you all.      &nbsp;        &nbsp;       &nbsp;   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;      © Emam Shararah 2021
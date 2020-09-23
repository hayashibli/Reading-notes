# CSS Transforms
The transform property comes in two different settings, 2D and 3D each has own properties and values. 
- *2D transforms* work on the x (horizantal) and y (vertical) axes. 
- *3D transforms* work on both the x (horizantal) and y (vertical) axes, as well as the z axis (depth).

### 2D Transforms
**2D Rotate**
*rotate* property allows to rotate an element from 0-360 degrees, a positive value (+) will rotate an element clockwise, and a negative value (-) will rotate the element counterclockwise. The default point of rotation is the *center* of the element, x =50% , y=50%.
**2D Scale**
*scale* property allows to change the size of an element. The default scale value is 1. Also, you can use *scaleX* to control the width , *scaleY* to control height and *scale(,)* to control both height and width.
**2D Translate**
*translate* property allows to change the position of an element. You can use *translateX* to move it horizantaly and *translateY* to move it vertically.
**2D Skew**
*skew* property allows to distort elements on the horizontal axis, vertical axis, or both.

You can combine  transform properties in one line like writing rotat and skew properties in the same line with their values.

### 3D Transforms
**3D Rotate**
You can rotate an element around any axes including rotateX, rotateY, and rotateZ.
**3D Scale**
By using the scaleZ three-dimensional transform elements may be scaled on the z axis.
**3D Translate**
Elements translated on the z axis using the *translateZ* value. A negative value here will push an element further away on the z axis, resulting in a smaller element. Using a positive value will pull an element closer on the z axis, resulting in a larger element.
**3D Skew**
Skew is the one two-dimensional transform that cannot be transformed on a three-dimensional scale.

# CSS Transitions
There are 4 main properties used with the transition :
- transition-property
- transition-duration
- transition-timing-function : linear, ease-in, ease-out, and ease-in-out.
- transition-delay

You can use :hover, :target, :active, :focus psuedo classes to determine styles for different states.

# CSS Animations
**Animation keyframes**
To set multiple points at which an element should undergo a transition, use the (@keyframes) rule. This rule must be vendor prefixed, just like all of the other transition and animation properties by writing @-webkit- , @-moz- ,@-o- before it.
**Animation Name**
Animation-name property is used with the animation name, identified from the @keyframes rule, as the property value. And you should use with  it **Animation duration**, **Animation Duration, Timing Function, & Delay**.

**Animation Iteration**
To have an animation repeat itself numerous times use this property and its values are an integer number or the word *infinite*.
**Animation Direction**
To specify the direction an animation completes include normal, reverse, alternate, and alternate-reverse.
**Animation Play State**
Allows an animation to be played or paused using the running and paused keyword values respectively. 
**Animation Fill Mode**
Identifies how an element should be styled either before, after, or before and after an animation is run, its four keyword values, including none, forwards, backwards, and both.



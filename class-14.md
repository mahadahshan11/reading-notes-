# Transforms

* using CSS3 has new ways to alter and position elements using *trensform* property.

* *transform* property comes in two different sittings, two-dimensional and three-dimensional. each comes with thier own individual properties and values. 

* **Transform syntax**:

    div {
        -webkit-transform: scale(1,5);
        -moz-transform: scale(1,5);
        -o-transform: scale (1,5);
        transform: scale(1,5);
    }


* **2D Transrom:**

* Two dimensional transforms work on both the x and y axes, known as horizonal and vertical axes, Three-dimensional transforms work on both the x and the y axes as well as the z axes.they all help to define the width, the length, and the depth of the element.  

* **2D Rotate:** 

* the *transform* property accepts a handful of different values. however, this rotate property provides the ability to rotate an element from 0 to 360 degrees. using a positive value will make the element raotate clockwise and using a negative value will meke the element rotate counter-clock-wise. 

* **2D Scale:**

* using the *scale* value within the *transform* property allow you to change the appeared size of an element. the defualt scale value is 1, therefore any element between .99 and ,01 will make the element aooear smaller while any vauw greater than or equal to 1.01 will make the element appear larger. 

* **2D Translate:**

* using the *trnslateX* value will change the position of an element on the horizontal axis while using the *?translateY* value will change the position of an element on the vertical axis. it also declare the x axis value first, followed by a comma, and then the y axis value. 

* **2D Skew:**

* the *skew* value is used to distort elements on the horizontal axis, vertical axis, or both. using the *skewX* value distorts an element on ahorizontal axis while using *skewY* value distort an element on the vertical axis. to distort an element on both axis the *skew* value is used, declaring the x axis value first, followed by comma, and then the y axis value .%p.

* **combining transforms**

* this occure when multiple trnasforms are used at once like rotating and scaling and the size. to combine transforms, list the transform values within the *transform* property one after the other without the use of commas. 

* **TRansform origin:**

* the defualt *transform-origin* is in the dead center of the element 50% horizonal and 50% vertical. to change this defual we must use the *transform-origin* by using two values. if only one value specified, this value will be used both horizonally and vertically, if two values are specified, the first value is used for the horizonal axis and the second value will be used for the vertical axis. 

* **Prespective:**

* In order for the three-dimensional transforms to work the elementa need a prespective from which to transform. the prespective of each element is *vanishing point* and it can be set in two different ways. one way includes using the *prespective* value within the *transform* property on indiviual elements, while the other way includes using the *prespective* propertyon the parent element residing over child elements being transformed.  

# Transitions & Animations

* transition and animation gives the ability to design such interactions directry through the HTML and CSS elements without having to use the JavaScript. these functions have the ability to alter the aooearence and behavior of an element whenever a state change occurs. such as when it hovererd over, focused on, active, or target.  

* **Trasitions:**

* befor applying this function, the element must have change in state, and different styiles must be identified for each states. [`:hover, :focus, :active, and :target`] is the easist way to do the job. tjere are four transition related properties: 1) *transition-property*. 2) *transition-duration*. 3) *tarnsition-timing*. 4) *transition-delay*.   


* 1) *transition-property* it determones excatly what properties will be altered in conjunction with the other transitional properties. 

* 2) *transition-duration* the value of this property can be set using general timing values, including seconds(s) and milliseconds (ms). 

* 3) *transition-timing* it property is used to set the speed in which a transition will move. the *linear* keyword value identifies a transiton moving in constant speed from one state to another.

* 4) *transition-delay* the delay sets the a time value that determines how long a transition should be stalled befor executing.

# Transforms
    - The transform property comes in two different settings,two dimensional and three dimensions. Each of these come with their own properties and values. 

## Transform Syntax
- The syntax for transform property is simple which invludes the transform property follwed by the value. The value specfifies the transform type folled  by a speicifc amount in the parenthesis. 

    
    2d Transforms:
     - Two dimensonal work transforms on the x and y axes which is known as horizontal and vertical axes. These three dimensional transforms help you define the length,width, and the depth. 

     - The transform property accepts different values. The rotate value provides the ability to rotate an element from 0 to 360 degreeses, using a postive value rotates clockwise and a negtieve will rotate it counter clokcwise. 


    Combining Transforms:
        - It is normal for multiple transforms to be used at once, in this event the they can be combined together. 
        - But usuing multiple transform declrations will not workm because each declration will overwrite each one above it. 

    Transform Origin:
        - The transform origin property can accept one or two values. If two values are specifed the first is used as a horizontal axis and the second is used for the vertical. 

    Perspective: 
        - For three dimensonal tranforms to work the elements need a perspective to transform to work the lements needs to be in a perspective from which to transform. 
        - Each perspective element can be thought of as a vanishing point. 
        - Using the perspective value with transform property works great with one transform element. 

    3d Transforms:
        - With two dimensional transform we are able to alter elements on the horzontal and vertical axis. Using three dimensional transforms we can change elements on th z axis giving us control of depth.

    Transform Style:
        - Somtimes three dimgensional transforms will be appled on an element that is nested within a parent element. 
        - The transform-style property needs to be placed on the parent element.
        - The preserve 3d value allows the transfomed children elements to appear in their own three dimensional plane.


# Transitions & Animations

    - Animations withing CSS3 allow the appearance and behavior of an element to be changed to muliple keyframes. 

    Transitions:
        - A transition need to take place and an element mush change a change in state. 
        - There are four trainsition related properties
            1. Transition property
            2. Transition duration
            3. Transition timing function
            4. Tranisiton delay 

    Shorthand transitions:
        - Declaring every transition properly individually can become quite intensive with vendor prefixes. Using the tranision value alone you can set every transition value in the order of transition poroperty, transition duration, transition timing function adn transition delay. 

    Animations:
        - Transition do a great job for for building visual interactions but if more control is needed this is where animations come into play. 
        - To set multiple points at which an element should undergo a trainstion use the keyframes rule. 
        - The animation name property is used for declaring key frame animations. 
        - Once you declare an animation name propertu on an element behave similar to transtion. 
    
    Customizing Animations:
        - You can also further your customized on an elements behavooir, including the ability to declare the number of times an animations runs. 
        - The normal value play an animation from start to end.
        - The alternate value will play an animation forwards then backwards.
        - The alternate-reverse value combines with alernate and reverse values. 
        - The animation play state property allows an animation to be played or paused using the running and puased keyword values.
        - Animation fill mode property identies how an element should be styled . It also accepts four keyword values, including none,forwads,backwards and both.

    ShortHand Animations:
        - Animations can be written in shorthand format. You would use one animation property rahter than having many. 


# 8 Simple css3 transitions:
    1. Fade In:
        .fade
{
        opacity:0.5;
}
.fade:hover
{
        opacity:1;
}
2. Change color:
.color:hover
{
        background:#53a7ea;
}

3.Gorw and Shirnk:
.grow:hover
{
        -webkit-transform: scale(1.3);
        -ms-transform: scale(1.3);
        transform: scale(1.3);
}
4. Rotate Elementts:
.rotate:hover
{
        -webkit-transform: rotateZ(-30deg);
        -ms-transform: rotateZ(-30deg);
        transform: rotateZ(-30deg);
}
5.Square to circle:
.circle:hover
{
        border-radius:50%;
}
6.3d Shadow:
.threed:hover
{
        box-shadow:
                1px 1px #53a7ea,
                2px 2px #53a7ea,
                3px 3px #53a7ea;
        -webkit-transform: translateX(-3px);
        transform: translateX(-3px);
}
7. Swing
@-webkit-keyframes swing
{
    15%
    {
        -webkit-transform: translateX(5px);
        transform: translateX(5px);
    }
    30%
    {
        -webkit-transform: translateX(-5px);
       transform: translateX(-5px);
    } 
    50%
    {
        -webkit-transform: translateX(3px);
        transform: translateX(3px);
    }
    65%
    {
        -webkit-transform: translateX(-3px);
        transform: translateX(-3px);
    }
    80%
    {
        -webkit-transform: translateX(2px);
        transform: translateX(2px);
    }
    100%
    {
        -webkit-transform: translateX(0);
        transform: translateX(0);
    }
}
@keyframes swing
{
    15%
    {
        -webkit-transform: translateX(5px);
        transform: translateX(5px);
    }
    30%
    {
        -webkit-transform: translateX(-5px);
        transform: translateX(-5px);
    }
    50%
    {
        -webkit-transform: translateX(3px);
        transform: translateX(3px);
    }
    65%
    {
        -webkit-transform: translateX(-3px);
        transform: translateX(-3px);
    }
    80%
    {
        -webkit-transform: translateX(2px);
        transform: translateX(2px);
    }
    100%
    {
        -webkit-transform: translateX(0);
        transform: translateX(0);
    }
}
8.Insert border:
.border:hover
{
        box-shadow: inset 0 0 0 25px #53a7ea;
}




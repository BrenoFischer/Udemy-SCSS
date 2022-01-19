- To reset default web behaviour
    * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
    }


- clip-path can have a figure, like polygon() and needs the coords x, y clockwise. Ex:
clip-path: polygon(0 0, 100% 0, 100% 80%, 0 100%);


- to move an element you can use transform and translate. It'll be translated based on the element itself. Ex:
transform: translate(-50%, -50%)
-> It'll move the element half his size to the left and up.


- can create animations with @keyframes animation-name. Ex:
@keyframes moveFromLeft {
    0% {
        transform: translateX(-100px);
    }

    100% {
        transform: translate(0);
    }
}
And then specify where you want to use, with:
.class-name {
    animation: moveFromLeft 1s ease-out;
}


- You can use animations on events, not only when page starts. Ex on hover:
.class-name:hover {
    animation: moveFromLeft 1s;
}


- If you want to apply an style of an animation before it starts, can use animation-fill-mode: backwards. For example, you want a button to not appear when the page starts, only when the animation is done:
@keyframes moveInBottom {
    0% {
        opacity: 0;
        transform: translateY(30px);
    }

    100% {
        opacity: 1;
        transform: translate(0);
    }
}
.btn-animated {
    animation: moveInBottom .5s ease-out .75s;
    animation-fill-mode: backwards;
}
-> It'll apply the style of the 0%, before the animation starts, then the animation will happen.



- Example of round button with hover animation (going up) and box-shadow:
.btn:link,
.btn:visited {
    text-decoration: none;
    padding: 15px 40px;
    display: inline-block;
    border-radius: 300px;
    transition: all .2s;
}

.btn:hover {
    transform: translateY(-3px);
    box-shadow: 0 10px 20px rgba(0,0,0,.2);
}

.btn:active {
    transform: translateY(-1px);
    box-shadow: 0 5px 10px rgba(0,0,0,.2);
}



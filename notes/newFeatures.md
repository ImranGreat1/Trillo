// Using svg icon in the html
<svg>
    <use xlink:href="img/sprite.svg#icon-home"></use>
</svg>

// How to style an svg icon using the fill css property
.icon {
    fill: orangered;
}


// Using the input::-webkit-input-placeholder to style input placeholder


// currentColor CSS variable, its hold the value of the selected element
color property or of its parent color property


// Using different transition settings for different properties
transition: transform .2s,
                    width .4s cubic-bezier(1, 0, 0, 1) .2s,
                    background-color .1s;


// transform-origin property, specifies the part of the element that the tranform
should start. Default is center, there is also top and bottom


// The power of using margin auto in flex-box
.flex-item {
    margin-right: auto;
}


// Set color to an an svg icon when we use it as a background-image in CSS using the new CSS mask-image
and mask-image-size property

.item::before {
    content: '',
    width: 1.2rem;
    height: 1.2rem;
    -webkit-mask-image: url(../img/chevron-thin-right.svg);
    -webkit-mask-size: cover;
    mask-image: url(../img/chevron-thin-right.svg);
    mask-size: cover;
}



// Summary of what I learned by noticing:
When an element expand and grow it container to like let say 500px, even if the child element
translate or changes to another position that is not inside the parent element, the parent element
will still retain the size of that containing that is the parent element will still be 500px in our
case.


// Background-color or background-image doesn't transition



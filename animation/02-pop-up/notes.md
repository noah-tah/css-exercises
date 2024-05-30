the code contains two css properties for an element

- css properties
- css element

there are two css properties, which are affecting 
one css element

the transition property

the transition property defines the timing function and the interval of time it takes to complete the transition  

ease-in-out starts the transition slowly, then speeds up in the middle, and then slows down at the end

```
transition: transform 0.3s, opacity 0.4s ease;
```

the transform property

the transform property is gonna give us parameters
to describe the transformation type we'd like to use

it takes (x,y) parameters as a percent value, and 
then the percents are measured relative to the original positon of the element
the position's magnitudes are related to the width and height of the element itself



my question is:

what would happen if we didnt use the transtion
for the transform: translate that we are using 

would it just happen instantly? would we not see the change?


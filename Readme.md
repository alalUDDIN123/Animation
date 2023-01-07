## Animation Part I
---

Before we jump into animations, we are going to discuss
two important types of css properties that will help us understand how to use
animations better.

Those are : 

1. transform  
2. transition

## 1) transform 👍
   - The transform CSS property lets us rotate, scale,
      skew, or translate an element. It modifies the coordinate space of the CSS visual
      formatting model.

= Keyword values 

 - transform: none

= Function values
  - transform: rotate(0.5turn); 
  - transform: rotateX(10deg);
  - transform: rotateY(10deg); 
  - transform: translate(12px, 50%); 
  - transform:translateX(2em);
  - transform: translateY(3in);
  - transform: scale(2, 0.5); 
  - transform: scaleX(2);
  - transform: scaleY(0.5);

= Multiple function values
  - transform: translateX(10px) rotate(10deg) translateY(5px);

## 2) transition 
   - Transition CSS transitions provide a way to control animation speed when changing CSS
     properties.  

   - It let us decide which properties to animate (by listing them
    explicitly), when the animation will start (by setting a delay), how long the
    transition will last (by setting a duration), and how the transition will run (by
    defining a timing function, e.g. linearly or quick at the beginning, slow at the end)


   We can define it

   ``` 
    .box{
        transition: <property> <duraton> <timing-function> <delay>
    }
   ``` 
      
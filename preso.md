# Happiness in Utility

## Intro

intro content goes here

## wtf are design systems

## Traditional ways of building design systems

### ITCSS

Traditionally we would try to build this with something like a combination of ITCSS (Inverted Triangle CSS) and the BEM (Block Element Modifier) naming convention.
If we look at the diagram on the screen, the idea behind ITCSS is you organise your classes into these 7 categories, and the further down the triangle you get, the more specific the classes are.

### Problems with ITCSS

which makes sense, **BUT** it is extremely time consuming. You need to set up your variables/design tokens, your folder structure, then break it down granually and set up appropriate imports. Then the real challenge, maintiainging it. Preventing it from becoming Spaghetti code, writing the documentation and keeping it up to date.  

## Introducing Tailwind

What if we could just plug your design tokens into a config, and voila! ready to go?
Enter, Tailwind.
Tailwind is a utility-first CSS framework that does all the heavy lifting for you.  NEED MORE CONTENT HERE

### What is utility first

so what is utility first? To some people, it's the worst thing to happen to front end development since microsoft outlook. To others its using a set of classes based upon design tokens to build out designs quickly and remain inline with your design system. 
ADD EXAMPLES

### problems with tw

need to research content add picture of mob with pitchforks to slide

### benefits

This method makes it easier to maintain, as you will be writing far less css,
something about eliminating bloat, something about documentation written for you. 
constrained by design tokens etc

## How tailwind can solve the problems of ITCSS

How can we leverage tailwind for our design systems? Well Tailwind itself IS a design system. However it is highly configuarable. If we take a look at their full config file you can see that we have the ability to customise almost anything and align with our design tokens. From colours, to border radius, to font and everything in between. Chances are you Design system will have spacing based on 4, 8, 16px - add example of overides and how tw will only override what you tell it to and fill in the gaps. -

Thats it, thats all you need to do. You now have a full suite of styles ready to go and chuck into your markup, your documentation is 99.99% written (and maintained by the TW team) you just need to make sure people are aware of your design tokens and terminology.

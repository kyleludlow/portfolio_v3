# Portfolio Site

An updated portfolio site made with semantic HTML5, SASS, Photoshop, responsive design, and graceful degradation. Photos to be uploaded soon!

## SASS Mixins and Variables

Sass is my absolute favorite css development tool! It lets me nest selectors for more readable and DRY code. It also lets me create variables for global values like color, font-size, margins, etc to rapidly change a sites look with only 1 character change. With mixins, I'm able to make real functions like a full programming language, which greatly comes in handy for repetitious values such as media query breakpoints and uncollapsing a collapsed div.

variables
![variables]: https://farm2.staticflickr.com/1810/29631381348_0d91d9c7ce_b.jpg "variable screenshot"

## Responsive design

I use rem and percentage units for nearly all my values. This lets me quickly change the entire page just by increasing or decreasing the font size, as rem stems directly from default font-size.

I use resolution swapping, density switching and changes in art direction to decrease page load time and improve performance.

I also, make modifications to a page when hovering is not available (i.e. mobile, tablets).

## Graceful degradation

Although I use a css pre-fixer to allow support for most of the newer css techniques, some older versions of browser still won't run certain features. As you can see below, I altered my SASS code to have a more basic look unless the browser has support.




[Check out the live site here!](http://www.kyleludlow.io)

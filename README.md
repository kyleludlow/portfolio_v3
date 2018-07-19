# Portfolio Site

An updated portfolio site made with semantic HTML5, SASS, Photoshop, responsive design, and graceful degradation. More photos to be uploaded soon!

## SASS Mixins and Variables

Sass is my absolute favorite css development tool! It lets me nest selectors for more readable and DRY code. It also lets me create variables for global values like color, font-size, margins, etc to rapidly change a sites look with only 1 character change. With mixins, I'm able to make real functions like a full programming language, which greatly comes in handy for repetitious values such as media query breakpoints and uncollapsing a collapsed div.

### mixin for easy media queries
![mixins](https://farm2.staticflickr.com/1810/29631381348_0d91d9c7ce_b.jpg)

### variables for quickly altering site appearance and better code readability
![variables](https://farm2.staticflickr.com/1786/29631382378_5fe3ef8714_b.jpg)

## Responsive design

I use rem and percentage units for nearly all my values. This lets me quickly change the entire page just by increasing or decreasing the font size, as rem stems directly from default font-size.

I use resolution swapping, density switching and changes in art direction to decrease page load time and improve performance.

### resolution swapping using HTML so that the right file gets loaded instead of loading both
![resolution swapping](https://farm2.staticflickr.com/1804/43454848812_9f865008d9_b.jpg)

### density switching to decrease loadtime for low dpi devices
![density switching](https://farm2.staticflickr.com/1823/28616239357_d67f3d5528_b.jpg)



I also, make modifications to a page when hovering is not available (i.e. mobile, tablets).



## Graceful degradation

Although I use a css pre-fixer to allow support for most of the newer css techniques, some older versions of browser still won't run certain features. As you can see below, I altered my SASS code to have a more basic look unless the browser has support.

### graceful degradation of the awesome clip-path feature so that non-supported browsers see a squared header
![graceful degradation](https://farm2.staticflickr.com/1768/43454848902_4af59cd4eb_b.jpg)


[Check out the live site here!](http://www.kyleludlow.io)

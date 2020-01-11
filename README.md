# outdoors
applying advance  CSS

## main point :
  - the best way to perform a basic reset using the universal selector.
  - set the project-wide font defenitions.
  - clip parts of elements using clip-path.

  -----

  we add the font proprtyes in bady selector not in the universal selector because the font's proprtyes are inheritance for all childes 

  the line height means in the font style that property specifies the height of a line.

  adding layer in the background using background-image with two proprtyes first one is liner-gradient which tack three parameters the position and the first color and the second color, and the next one is url to select the background image location

  adding padding in the body tag style will make a border for all the page .

  The clip-path CSS property creates a clipping region that sets what part of an element should be shown. Parts that are inside the region are shown, while those outside are hidden.

  if we wnat to make any box absolute to move it we need to make the parent posititon relative 

  when resizing the image just change the height and then the width will be automatically edited 

  span element is perfect to style some text differently so we can just put two spans or more in h1 

  they are two types of animations in css  the first one is to use transtion property and then change the propreties that you want to animate on an event  like when we hover the element, 
  the second one is to use the fram, start with write a keyframes and give it a name then , you can specify what I want to happen in each moment of the animation start with 0% which is before the animation actually starts and the finish will be 100% ,
  and to apply it , it need two properties to specify which the animation name and the animation duration 

  thire is a lettle shake after the animation finished so to solve this problem we need to add backface-visibility proprety to hidden in the parent element 

   pseudo class it's used to  style the element under a special condition 
   ex: .btn:link .btn:visited 

## Three Pillars of Writing Good HTML and CSS (Never Forget Them!)
  1- Responsive Design :
    - Fluid layouts.
    - Media queries
    - Responsive images
    - Correct units
    - Desktop-first vs mobile-first

  2- Maintainable and scalable code :
    - Clean
    - Easy-to-understand
    - Growth
    - Reudsble 
    - How to organize files
    - How to name classes
    - How to structure HTML

  3- Web performance :
    - Less HTTP requests
    - Less code
    - Compress code 
    - Use a CSS preprocessor
    - Less images 
    - Compress images 

## CSSOM(CSS Object Model) :
when it's start to parse html file and find the css sheets includes in the html head and start loading them, and start to parse the css, but parsing css is bit more complex, there tow main steps first off, conflicting CSS declarations are resolved (cascade), and the second is to process final CSS values , and after all of this is done , the final CSS is also stored in a tree like structure called CSSOM, now DOM and CSSOM together form the Render Tree and it ready to render the page and to do that the browser used the Visual Formatting Model algorithm uses a bunch of stuff like the box modile, floats, and positioning , and finally after Visual Formating Modle has done it's work , the website it's finally renderd or painted to the screen 
![CSSOM](img/CSSOM.png)
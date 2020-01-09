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

  thire is a lettle shake after the animation finished so to soleve this problem we need to add backface-visibility proprety to hidden in the parent element 
Clarrisa Peterson

The web used to have 256 web-safe colours. 

Hue/Value/Saturation

H: red/green/purple/etc 
V: lightness/darkness
S: how much gray is added, the intensity

Colour Notation in CSS
* RGB
* These mix to create all other colours
* A pixel is made up of three separate sub pixels
* There are 256 different values for each subpixel
* Ergo, 256 * 3 = a lot of colours!

RGB
* put the value of each subpixel
* `color: rgb(200, 0, 200);`

HEX
* again, put the value of each subpixel
* #RRGGBB

RGB and HEX are hard to visualize.

HSL notation makes this a lot easier.
Hue, saturation, and lightness.
This is supported in most browsers (not old IE)

HSL. 
* be familiar with the color wheel
* `color: hsl(HH, SS, LL);`
* more intuitive than RGB and/or HEX

Opacity
* we can do this with RGBa, which includes a fourth number in parentheses
* HEX does not support this
* HSLa notication also allows opacity. 
* whereas RGBa and HSLa work on the background, the `opacity` element works on the entire element.

Colour Blindness
* 5/100 people see colour differently. I.e. these people have colour blindness.
* Colour blindness is more about not being able to differentiate different colors... everything might look green. 
* Ergo: avoid using colour to communicate meaning - some people won't receive this meaning message. 
* If colour is the website's content is colour, then include clear alternate text on hover, for instance. 
* Test your website in grayscale settings. 

Colour Interpretation
* some cultures might use a single word for what in the west are called red and orange.
* so, what if we ask a user to click on the red button?

Screen Colours
* RGB is a recipe for what the device monitor implements
* Different screens can display the same RGB very differently. 
* we can adjust the colour, if we want, for screens at different light levels. 
* for smaller screens, we might assume that the device is more likely to be outside: therefor

Use SAAS for colours. 

Use CSS blend. 
* `background-blend-mode:`
* no support for lots of browsers - it would be a progressive enhancement

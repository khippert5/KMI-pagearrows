The following is a description of options and usage for KMi Page Arrows:


Dependencies for default:
The folder "font-awesome-4-6-3" should be included in the package. This should include everything you need.


Put in the head of your page as followed:
<link rel="stylesheet" type="text/css" href="<your-directory>/font-awesome-4-6-3/css/font-awesome.min.css">


To change default settings:
create an empty div on your page with the class attribute "kmipagearrowsOptions". Best suited near the bottom. KMi Pages Arrows will pick up the data attributes set on this div and overwritte the default settings.


Alternate change:
You can also go into the kmi-pagearrows.js and change out the defaults in here.  Just make sure to connect kmi-pagearrow.js to your page instead of kmi-pagearrows.min.js

***NOTE: 
If you are also using KMi Text Resizer the default settings are set to match the text resizer based on a 16px font-base




Default Settings:

"data-data-position":"fixed" -> Set the position of the pagearrow container

"data-padding":"0px" -> Set the padding of the pagearrow container

"data-zindex":"50" -> Set the z index of the container. Set to 9999 to always be on top;

"data-border-radius":"3px" -> Set the border radius on the pagearrow container

"data-border":"none" -> Set the border on the pagearrow container

"data-background-color":"transparent" -> Set the backgound color of the pagearrow container (Should not be changed but available)

"data-position-vertical":"bottom" -> Set the vertical position of the textresize container

"data-position-verticalOffset":"2px" -> Set the vertical offset of the textresize container (IE: bottom:2px)

"data-position-horizontal":"right" -> Set the horizontal position of the textresize container 

"data-position-horizontalOffset":"2px" -> Set the horizontal offset of the textresize container (IE: left:2px)

"data-text-color":"#FFF" -> Intial font color of display text

"data-hover-color":"#333" -> Changes the color of the font on hover

"data-hover-background-color":"#FFF" -> Changes the background color on hover

"data-text-font-weight":"bold" -> Set the font weight of the display text

"data-arrow-font-size":".75em" -> This is the font size of the toggle button

"data-arrow-border":"1px solid #000" -> Set the border around each arrow button

"data-arrow-border-radius":"3px" -> Set the border radius around each arrow button. In almost every case this would match "data-border-radius"

"data-arrow-padding":"25px 15px" -> Set the padding around each arrow button

"data-arrow-padding-top":"15px" -> Set the top padding around each arrow icon

"data-arrow-padding-bottom":"15px" -> Set the bottom padding around each arrow icon

"data-arrow-margin":"0 0 0 5px" -> Set the margin around each arrow icon

"data-arrow-icon":"fa" -> fa targets the font awesome arrows. Change this to img to use image in the next two attributes

"data-arrow-icon-fa-attribute-up":"chevron-up" -> This is the icon to use for the toggle up element

"data-arrow-icon-fa-attribute-down":"chevron-down" -> This is the icon to use for the toggle down element

"data-tint-background-color":"#000" -> This is the color setting to set the color behind the entire elemnet

"data-tint-background-opacity":".85" -> This is the opacity level of the color behind entire element

"data-action-slide":"left" -> This is the direction of the slide. Left will start offscreen right and slide in left; vice versa

"data-action-fade":"0" -> This is the delay timer on the fade in

"data-allow-double-clic":"1" -> This if set to 1 this will allow a quick (1 second) double click up which will allow the user to click once
	then within 1 second a second click will send back to top. After that second it will scroll the window height.  Set to 0 to turn this off.
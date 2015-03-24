1. Use index.htm file including all other files that are defined,
> js/jquery-1.3.2-drag-slider.min.js

> js/jquery-ui-1.7-drag-slider.custom.min.js

> css/jquery-ui-1.7-drag-slider.custom.css

> js/excanvas.js

> js/pixastic.custom.js

> js/rotator.js

> js/img\_adjust.js

> css/general.css

> js/conf.js

> js/conf\_adjust.js

2. In the conf.js set appropriate values to the variables:
> a. img\_path, the name of the image.

> b. path, the path of the image in relation to the index.htm file.

> c. img\_act\_height AND img\_act\_weight in order to define the size of the frame that the image would be displayed.

> d. max\_width, min\_width AND step in order to define:
<blockquote>
<blockquote>max_width  -------->  // Max allowable scale for image zoom</blockquote></li></ul>

<blockquote>min\_width  -------->  // Min allowable scale for image zoom</blockquote>

<blockquote>step       -------->  // Scale step for zoom </blockquote></blockquote>
<blockquote>The original image is supposed to be of scale 1.</blockquote>


<blockquote>e. displayZ, displayR AND displayBC in order to include or exclude specific functionality:<br>
<blockquote>
> displayZ  -------->  //Set to 'true' if you wanted to display the zoom controls
> > //Set to 'false' if you wanted to hide the zoom controls


> displayR  -------->  //Set to 'true' if you wanted to display the rotate controls
> > //Set to 'false' if you wanted to hide the rotate controls


> displayBC  -------->  //Set to 'true' if you wanted to display the brightness/contrast controls
> > //Set to 'false' if you wanted to hide the brightness/contrast controls
</blockquote></blockquote></li></ul>

3. For the script js/pixastic.custom.js to work you should place the application inside a web server (apache)<br>
<br>
4. You have to comment the DOCTYPE in index.htm in order for the application to work properly in IE7.<br>
<br>
5. Brightness/Contrast transformations doesn't work in IE.
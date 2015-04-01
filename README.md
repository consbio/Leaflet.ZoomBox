# Leaflet.ZoomBox

A zoom box control for Leaflet.  

It allows you to draw an area on the map to zoom into.  See the [example](//consbio.github.io/Leaflet.ZoomBox).

*Tested with Leaflet 0.7.x*


## Install

From Bower:

```
bower install Leaflet.ZoomBox
```


From NPM:

```
npm install leaflet-zoombox
```


## Usage

Include the CSS: 

```
<link rel="stylesheet" href="L.Control.ZoomBox.css" />
```

This control uses [Font Awesome](http://fortawesome.github.io/Font-Awesome/) for the icon by default.  To use, include:

```
<link rel="stylesheet" href="//maxcdn.bootstrapcdn.com/font-awesome/4.2.0/css/font-awesome.min.css" />
```


Include the JavaScript:

```
<script src="L.Control.ZoomBox.min.js"></script>
```


Example usage:

```
var control = L.control.zoomBox({
    modal: true,  // If false (default), it deactivates after each use.  
                  // If true, zoomBox control stays active until you click on the control to deactivate.
    // position: "topleft",                  
    // className: "customClass"  // Class to use to provide icon instead of Font Awesome
});
map.addControl(control);
```


## Credits:
Developed with support from the [South Atlantic Landscape Conservation Cooperative](http://www.southatlanticlcc.org/)

Binding to the map's zoom box (shift-click) was inspired by [ScanEx](https://github.com/ScanEx/gmxControls/blob/master/examples/L.Control.boxZoom.html)
# Leaflet.ZoomBox

A zoom box control for Leaflet.  

It allows you to draw an area on the map to zoom into.  See the [example](http://consbio.github.io/Leaflet.ZoomBox).

*Tested with Leaflet 1.0.*


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

This control uses [Font Awesome](http://fontawesome.io/) for the icon by default.  To use, include:

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
    // title: "My custom title" // a custom title
});
map.addControl(control);
```


## Credits:
Developed with support from the [South Atlantic Landscape Conservation Cooperative](http://www.southatlanticlcc.org/), and maintained with support from [Peninsular Florida LCC](http://peninsularfloridalcc.org/) and the [U.S. Forest Service Northwest Regional Climate Hub](http://www.fs.fed.us/climatechange/nrch/)

Binding to the map's zoom box (shift-click) was inspired by [ScanEx](https://github.com/ScanEx/gmxControls/blob/master/examples/L.Control.boxZoom.html)


## Contributors:
* [Brendan Ward](https://github.com/brendan-ward)
* [Nik Stevenson-Molnar](https://github.com/nikmolnar)
* [Kaveh Karimi-Asli](https://github.com/ka7eh)
* [Andreas Adelsberger](https://github.com/punknroll)


## See Also:
[L.Control.BoxZoom](https://github.com/gregallensworth/L.Control.BoxZoom): an alternative implementation

# *THE PAST, PRESENT & FUTURE OF LOCAL STORAGE FOR WEB APPLICATIONS..*


*What we really want is?*....
-

* a lot of storage space
* on the client
* that persists beyond a page refresh
* and isn’t transmitted to the server


### HTML5 STORAGE

![](https://images-na.ssl-images-amazon.com/images/I/51q0QH0xQ2L._SX401_BO1,204,203,200_.jpg)



function supports_html5_storage() {

  try {

    return 'localStorage' in window && window['localStorage'] !== null;
  } catch (e) {
    return false;
  
}

}

Instead of writing this function yourself, you can use [Modernizr](http://diveinto.html5doctor.com/detect.html#modernizr) to detect support for HTML5 Storage.


*There are also methods for removing the value for a given named key, and clearing the entire storage area (that is, deleting all the keys and values at once).*

- TRACKING CHANGES
- LIMITATIONS IN CURRENT BROWSERS
* HTML5 STORAGE IN ACTION
* BEYOND NAMED KEY-VALUE PAIRS:       COMPETING VISIONS
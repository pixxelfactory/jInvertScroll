jInvertScroll
=============

A lightweight jQuery vertical scroll - horizontal move plugin with parallax effect.

What is it?
It's a lightweight plugin for jQuery that allows you to move in horizontal with a parallax effect while scrolling down.<br/>
It's extremely easy to setup and requires nearly no configuration.

Quickstart
----------

1.) Include the css file, jQuery and the Plugin
2.) Create the desired elements that you want to scroll (You can create normal divs, wich contain other elements, images, videos...)
3.) Assign them the class "scroll" if you want to like the styles from the css-file, otherwise give them the following attributes:
    position: fixed;	// All scrollable elements have to be position:fixed
    bottom: 0;	// Make it stick to the bottom (or top)
    width: xxxxpx;	// I recommend to assign the width in px, prevents preloading issues
4.) Order the layers via z-index (Note that it is recommended that the front layers are wider than the ones in the back)
5.) In your javascript, use this code (the selectors refer to the elements that you desire to be scrolled):
    $.jInvertScroll(['yourselector1', 'yourselector2'...]);


License
-------

The MIT License (MIT)

Copyright (c) 2013 pixxelfactory

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.


More information
----------------

For more information check out the [plugin website](http://www.pixxelfactory.net/jInvertScroll)
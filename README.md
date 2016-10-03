# Week polyfill

This is a polyfill for implementing the HTML5 `<input type="week">` element in browsers that do not currently support it.

## Usage

Using it is easy — simply include the `week-polyfill.min.js` file in the HEAD of the HTML page.  
You can then use `<input type="week">` elements normally.

If the script detects that the browser doesn't support `<input type="week">`, it will search for these elements and replace them with a jQuery UI datepicker to select the week. The week selection is stored in a hidden form field and submitted with the form in the standard format.

A default CSS file is provided. You may edit this file to style the input fields to make them look the way you want.

## Manual usage

The script can also be called manually as a jQuery plugin for elements dynamically generated through script. Simply call the `.inputWeek()` method on any jQuery object containing one or more `<input type="week">` elements.

## Dependencies

This script requires [jQuery](http://jquery.com/), [jQuery UI](http://jqueryui.com/), and [Modernizr](http://www.modernizr.com/).

## Demo

https://jefmari.github.io/week-polyfill/demo.html

## See also

[Compatibility chart for input datetime elements](http://caniuse.com/input-datetime)

* [datetime-local-polyfill](https://github.com/jonstipe/datetime-local-polyfill)
* [datetime-polyfill](https://github.com/jonstipe/datetime-polyfill)
* [date-polyfill](https://github.com/jonstipe/date-polyfill)
* [time-polyfill](https://github.com/jonstipe/time-polyfill)
* [month-polyfill](https://github.com/jonstipe/month-polyfill)

## License (MIT)


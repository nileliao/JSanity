# jSanity
A secure-by-default, performant, cross-browser client-side HTML sanitization library.

Reference:<br>
[OWASP AppSec EU 2013 Talk](https://www.youtube.com/watch?v=n18Hwaxycwc)<br>
[Slides](http://www.slideshare.net/404aspx/insane-in-the-iframe)<br>

## Status

jSanity was just recently revived from two years of cold storage.  Only very minimal changes have been made so far since the code was originally developed.


## Demo / Benchmark pages

[Demo](http://jsanity.azurewebsites.net/jsanity-demo-pretty.htm)<br>
[Benchmark](http://jsanity.azurewebsites.net/jsanity-benchmark-pretty.htm)

## Latest news
  - 2/18/2016: [@kh9n](https://twitter.com/kh9n) has completed a significant refactoring
    - jQuery and setImmediate dependencies were removed!
    - jSanity now supports both sync and async modes


## Todo
  - Support for more elements and attributes
  - Update / document the demo & benchmark pages
  - Unit tests
  - Better solution for STYLE elements
  - Integration with one or more javascript frameworks
  - Experimental override for default sanitization in various web platforms
  - Leverage newer features of the web platform (Shadow DOM, etc.)
  - Fix linkClickCallback support


## Special thanks for making jSanity a reality:

  - Ben Livshits
  - Gareth Heyes
  - Loris D'Antoni
  - Mario Heiderich
  - Matt Thomlinson
  - Michael Fanning

# CSS Performance

* [Writing efficient CSS selectors](http://csswizardry.com/2011/09/writing-efficient-css-selectors/) by [@csswizardry](https://twitter.com/csswizardry)
* [Writing efficient CSS](https://developer.mozilla.org/en-US/docs/CSS/Writing_Efficient_CSS) via MDN
* [CSS PERFORMANCE](http://dl.dropbox.com/u/39519/talks/cssperf/index.html) by Paul Irish | 2011
* [Efficiently Rendering CSS](http://css-tricks.com/efficiently-rendering-css/) by Chris Coyier
* [CSS Selector Performance has changed! (For the better)](http://calendar.perfplanet.com/2011/css-selector-performance-has-changed-for-the-better/) by [Nicole Sullivan](http://www.stubbornella.org/)


# CSS hacks

* [Conditional Stylesheets vs CSS Hacks? Answer: Neither!](http://paulirish.com/2008/conditional-stylesheets-vs-css-hacks-answer-neither/) by Paul Irish
* [safe CSS hacks](http://mathiasbynens.be/notes/safe-css-hacks) by Mathias
* [Quick Tip: How to Target IE6, IE7, and IE8 Uniquely with 4 Characters](http://net.tutsplus.com/tutorials/html-css-techniques/quick-tip-how-to-target-ie6-ie7-and-ie8-uniquely-with-4-characters/)

  ``` css
  body {
     color: red;     /* all browsers, of course */
     color: green\9; /* IE8 and below */
    *color: yellow;  /* IE7 and below */
    _color: orange;  /* IE6 */
  }
  ```

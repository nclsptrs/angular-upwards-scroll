Angular Upwards Scroll
======================

Usage
-----

Include the script tag after the jQuery and AngularJS script tag (upwardsScroll requires jQuery to work)

```html
<script type="text/javascript" src="jquery.min.js"></script>
<script type="text/javascript" src="angular.min.js"></script>
<script type="text/javascript" src="upwards-scroll.min.js"></script>
```

Make sure to add "upwards-scroll" as a dependency into your Angular app
```javascript
angular.module('myApp', ['upwards-scroll']);
```

Use the directive by specifying an 'upwards-scroll' attribute on an element
```html
<div upwards-scoll="myFunction()"></div>
```

Demo
----
[Simple demo](http://htmlpreview.github.io/?https://github.com/nclsptrs/AngularUpwardsScroll/blob/master/demo.html)
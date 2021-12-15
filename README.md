# bootstrap-carousel-standalone

Bootstrap Carousel is one of the few carousel widgets that is implemented without using element cloning. Element cloning can cause trouble when the elements being cloned have event listeners or Shadow DOM elements.

However, just because you want to use Bootstrap's Carousel doesn't mean you want to pull in all of the components or default styling. This project solves you problem.

## Documentation

This is based on Bootstrap 3.x, so make sure to look at [the right documentation](https://getbootstrap.com/docs/3.3/javascript/#carousel).


## Using it on a website

To use this, just include the following elements in your <head>:

```html  
<link rel="stylesheet" href="https://cdn.statically.io/gh/mdlavin/bootstrap-carousel-standalone/292657fcb31f3c21cc7147816ab66e2191466f67/css/bootstrap.css" crossorigin="anonymous">

<script src="https://code.jquery.com/jquery-1.9.1.min.js"  crossorigin="anonymous"></script>
<script src="https://cdn.statically.io/gh/mdlavin/bootstrap-carousel-standalone/292657fcb31f3c21cc7147816ab66e2191466f67/js/bootstrap.js" crossorigin="anonymous"></script>
```

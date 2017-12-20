# my-scroll-reveal

My Scroll Reveal is a very light plug-in that reveal your HTML elements on scroll.

## How to us ?

-   First add *assets* file in your project root, if you want to put it elsewhere, you will have to change the links bellow.

-   Next you need to add to your HTML *My Scroll Reveal* Css and Js files, Jquery is also required for the plug-in to work.

```
/*-- My Scroll Reveal css --*/
<link rel="stylesheet" href="assets/scroll-reveal.css">
...
/*-- jquery --*/
<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/2.2.4/jquery.min.js"></script>
/*-- My Scroll Reveal js --*/
<script src="assets/scroll-reveal.js"></script>
```

-   Next add *data-scroll-reveal="true"* to the attribute of your element, for example :

```
<div data-scroll-reveal="true"> Hello World </div>
```

Congratulations it's working !

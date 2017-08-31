# JavaScript Libraries

### 1. Dojo
A JavaScript toolkit that saves you time and scales with your development process. Provides everything you need to build a Web app. Language utilities, UI components, and more, all in one place, designed to work together perfectly. - [https://dojotoolkit.org/](https://dojotoolkit.org/)

![Dojo](https://dojotoolkit.org/documentation/tutorials/1.7/gfx/images/gfxlogo.png)

#### Sample Code
```<script>
        require([
            'dojo/dom',
            'dojo/dom-construct'
        ], function (dom, domConstruct) {
            var greetingNode = dom.byId('greeting');
            domConstruct.place('<em> Dojo!</em>', greetingNode);
        });
    </script>```
    
### 2. JQuery
jQuery is a fast, small, and feature-rich JavaScript library. It makes things like HTML document traversal and manipulation, event handling, animation, and Ajax much simpler with an easy-to-use API that works across a multitude of browsers. With a combination of versatility and extensibility, jQuery has changed the way that millions of people write JavaScript. - [https://jquery.com/](https://jquery.com/)

![Jquery](http://www.vikaskbh.com/wp-content/uploads/2014/01/jquery_logo.png)

#### Sample Code
```var hiddenBox = $( "#banner-message" );
$( "#button-container button" ).on( "click", function( event ) {
  hiddenBox.show();
});```

### 3. Datejs
Datejs is an open-source JavaScript Date Library. Comprehensive, yet simple, stealthy and fast. Datejs has passed all trials and is ready to strike. Datejs doesn’t just parse strings, it slices them cleanly in two. - [http://www.datejs.com/](http://www.datejs.com/)

![Datejs](https://camo.githubusercontent.com/5e54f09cc38ce9071403ca237b6121c3051b6529/687474703a2f2f646174656a732e636f6d2f696d616765732f676f6f676c65636f64652d6865616465722e6a7067)

#### Sample Code
```// Get the first Monday of the year
Date.january().first().monday()
 
// Get the last Friday of the year
Date.dec().final().fri()
 
// Set a date to the 15th of the current month at 4:30 PM,
// then add 90 days and make sure that date is a weekday,
// else move to the next weekday.
var d1 = Date.today()
    .set({ day: 15, hour: 16, minute: 30 })
    .add({ days: 90 })
if (!d1.isWeekday()) {
    d1.next().monday();
}```

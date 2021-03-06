#Eeze v0.1

[http://eeze.us](http://eeze.us)


##What  
Eeze is a clean slate for professional developers creating custom applications. eeze.min.css comes out of the box at under 6K (**before** G-Zipping & you can gain ~2k by swapping to the HTML5 Reset) and sets up a great LESS workflow.

##Why
Unlike [Twitter Bootstrap](http://twitter.github.com/bootstrap/), Eeze comes as a minimal starting point for your app. I’ve only included the most common building blocks and base file structure that you might need to create a custom application. There are no base preset styles to work around, delete, or overwrite. Just clone the app and start writing *your* code in seconds.

##Files:

* `images/`

* `stylesheets/`

  * `less/`

    * `app-modules/`
      * `application.less` - empty to start
      * `buttons.less` - empty to start
      * `media-queries.less` - sets up your media queries, pulls all the "responsive-" less files.
      * `responsive-full.less`, responsive-mobile.less, responsive-tablet.less - width-specific stylesheets
      * `typography` - empty to start, 
      * `variables` - empty to start,

    * `eeze-modules/`
      * `1140-grid.less`, `960-grid.less` - choose your popular grid or import your own. Defaults to [http://cssgrid.net](http://cssgrid.net)'s 1140-grid _(update `stylesheets/less/eeze.less` to change to your preference.)_
      * `copyright.less` - just a simple copyright stamper.
      * `css3.less` - the basic css3 less mixins, when used they automatically add the browser specific styles to your CSS
      * `html5_doctor.less`, `normalize.less` - use the html5 reset or normalize? Defaults to `normalize.css`
      * `reusables` - 20 base styles that seem indespensible

    * `app.less` - compiles the application less styles
    * `eeze.less` - compiles your custom eeze.css file

  * `app.css` - out of the box compiles CSS (doesn't look like much, it shouldn't until you write this part.)
  * `eeze.min.css` - the standard eeze file has normalize, 1140 grid, and some base files  

* `base.html` - base elements of a modern front end HTML5 template
    

Documentation is coming soon to [http://eeze.us](http://eeze.us)


###Project Info:

Eeze front-end application starter kit   
by Wil Everts (@cousinwil)  
[http://eeze.us](http://eeze.us)  
Version 0.1 - 4/5/2012  

_Copyright 2012, Wil Everts  
Dual licensed under the MIT or GPL Version 2 licenses._
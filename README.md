# LibGuides CMS Resources

Mastering LibGuides CMS without any previous experience in LibGuides can be a tricky business. Below are some resources I used to build the Gregg-Graniteville Library's website (https://library.usca.edu/home).

## Bootstrap

Bootstrap v3 3.7 https://getbootstrap.com/docs/3.3/getting-started/

LibGuides is built on Bootstrap. Not the current version of Bootrap but the framework makes it much easier to customize the your library's website.
    
    Customization options
      
    -Navbar
    -Buttons
    -Dropdowns
    -Alerts
    -Layout
    -Etc
      
 For more customizaiton options see the "Components" section on the Bootstrap website (https://getbootstrap.com/docs/3.3/components/).
 
 The Bootstrap Grid
 
 The grid is your best friend when buildng in LibGuides CMS and it's one of the many benefits to LibGuides built on Bootstrap. Once you truly understand how the grid works, you can build and adapt your website to mobile and tablet with no trouble as well as have a cohesive and dynmanic layout. However, it can be difficult to understand if you're not familiar with Bootstrap. 
 
 Bootstrap descibes their grid as "a responsive, mobile first fluid grid system that appropriately scales up to 12 columns as the device or viewport size increases. It includes predefined classes for easy layout options, as well as powerful mixins for generating more semantic layouts," which essentially means your webiste is built on 12 columns and you adjust the layout of the content on your website by the size of the rows spanning across the columns. 
 
 So, let's say we want 3 equal size boxes across the full 12 columns. We would add a class of .col-md-4 to those particular boxes. 12 columns/4 = 3 boxes
 
 That said, let's say we want 4 equal size boxes across the full 12 columns instead. We would add a class of .col-md-3 this time. 12 columns/3 = 4 boxes
 
 Basically, you rows of boxes need to be divisible by 12. 
 
 You could even mix it up with different size boxes. Like one .col-md-6 box and two .col-md-3 boxes. 6+3+3 = 12 (one large and two small)
 
 Or one .col-md-8 box and one .col-md-4 box. 8+4 = 12 (one larger box and one small box)
 
 As long as the total of your .col-md boxes = 12 columns, you're golden.
 
 This is the simplest way to use the grid system. This particular method with only using .col-md boxes is called Stacked-to-horizontal. Bootstrap explains it as "Using a single set of .col-md-* grid classes, you can create a basic grid system that starts out stacked on mobile devices and tablet devices (the extra small to small range) before becoming horizontal on desktop (medium) devices. Place grid columns in any .row."

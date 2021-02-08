# LibGuides CMS Resources

Mastering LibGuides CMS is a tricky business. Every page reacts to certain elements differently. It takes plenty of patience and work arounds to ensure the website work and looks the way you want it to. Below are some resources I used to build the Gregg-Graniteville Library's website (https://library.usca.edu/home).

## Bootstrap

Bootstrap v3 3.7 https://getbootstrap.com/docs/3.3/getting-started/

LibGuides is built on Bootstrap, both the front-end and back-end. Because the back-end is also build on Bootstrap we must use the same version or things will become tricky on the back-end (the layout will change and etc - speaking from experience). 
    
    Customization options
      
    -Navbar
    -Buttons
    -Dropdowns
    -Alerts
    -Layout
    -Etc
      
 For more customizaiton options see the "Components" section on the Bootstrap website (https://getbootstrap.com/docs/3.3/components/).
 
 ### The Bootstrap Grid

The grid is your best friend when buildng in LibGuides CMS and it's one of the many benefits to LibGuides built on Bootstrap. Once you truly understand how the grid works, you can build and adapt your website to mobile and tablet with no trouble as well as have a cohesive and dynmanic layout. However, it can be difficult to understand if you're not familiar with Bootstrap.

Bootstrap descibes their grid as "a responsive, mobile first fluid grid system that appropriately scales up to 12 columns as the device or viewport size increases. It includes predefined classes for easy layout options, as well as powerful mixins for generating more semantic layouts," which essentially means your webiste is built on 12 columns and you adjust the layout of the content on your website by the size of the rows spanning across the columns.

So, let's say we want 3 equal size boxes across the full 12 columns. We would add a class of .col-md-4 to those particular boxes. 
    12 columns/4 = 3 boxes

That said, let's say we want 4 equal size boxes across the full 12 columns instead. We would add a class of .col-md-3 this time. 
    12 columns/3 = 4 boxes

Basically, you rows of boxes need to be divisible by 12.

You could even mix it up with different size boxes. Like one .col-md-6 box and two .col-md-3 boxes. 
    6+3+3 = 12 (one large and two small)

Or one .col-md-8 box and one .col-md-4 box. 
    8+4 = 12 (one larger box and one small box)

As long as the total of your .col-md boxes = 12 columns, you're golden.

This is the simplest way to use the grid system. This particular method with only using .col-md boxes is called Stacked-to-horizontal. Bootstrap explains it as "Using a single set of .col-md-* grid classes, you can create a basic grid system that starts out stacked on mobile devices and tablet devices (the extra small to small range) before becoming horizontal on desktop (medium) devices. Place grid columns in any .row."
 
 
 ## Font Awesome
 
 Font Awesome v4.7 https://fontawesome.com/v4.7.0/
 
 Font Awesome is a great way to add icons to your website. LibGuides uses Font Awesome icons on the back-end side so to make sure not to upset the apple cart, we must use the same version or the icons on the back-end will not work. 
 
 There are so many icons to choose from with Font Awesome. https://fontawesome.com/v4.7.0/icons/
 
 One of the best reasons to use Font Awesome is you don't have to worry about adding icons via an image tag. You add and make changes to the icons by adding classes to your code via the icon tag. It's all in the code! It makes things so much easier in the long run and makes edits to the icons easy, too!
 
 As Font Awesome explains in the Font Awesome Examples page (https://fontawesome.com/v4.7.0/examples/), "You can place Font Awesome icons just about anywhere using the CSS Prefix fa and the icon's name. Font Awesome is designed to be used with inline elements (we like the icon tag for brevity, but using a <span> is more semantically correct)."
    
    
        <i class="fa fa-camera-retro"></i> fa-camera-retro
        
All you do is add the above code (change the fa fa-camera-retro to the icon of your choosing) before or after the code where you want the icon. 

For example, the placement of the icon tag determines where the icon appears. 
    
    <div class="col-sm" id="ask-lib-btn"><a href="https://library.usca.edu/chat"><i class="fa fa-question fa-3x" aria-hidden="true"></i></br>Ask a Librarian</a></div>
    
Because the icon tag appears before the "Ask a Librarian" text of the anchor tag, the icon will appear before the text but will be linked as the text. If the icon tag appeared before the anchor tag, the icon wouldn't be linked but would still appear before the text. Also, if icon tag appeared after the text portion of the anchor tag, the icon would appear after the text "Ask a Librarian" but it would still be linked. 
    
You know how I mentioned earlier how easier it is to edit the icons because it's all in the code? Well, Font Awesome has code aka css classes we can add to our original icon code to change the size of the icons, set icons to fixed width (handy when you're using icons in a list or navigation), replace bullets in lists with your choice of icons, animate the icons and more! Pretty cool, huh? It's a piece of cake, too! We just add the appropriate css code Font Awesome gives us to make changes to the selected icons. The possibilites are endless! 

There's even a Bootstrap section because Font Awesome works seamlessly with the Bootstrap components! These two do all the work for us. 

Here's were you can find all the examples of the changes you can make to the Font Awesome icons : https://fontawesome.com/v4.7.0/examples/

Play around with them and see what works best for your website! I'm fan of the fixed-width and increasing the size of the icon. They're great for buttons, lists, directories, address areas, and etc. You can find Font Awesome icons all over the Gregg-Graniteville Library's website. 
 
 ## Color-Hex
 
 Color-Hex https://www.color-hex.com/
 
 This is one of my favorite resources to use to find color hex codes. Not only does color-hex show you the color you want but also include all the information about the code you could need for adding it to your code. Color-hex also shows you various tints and shades so you have access to similar colors. This will come in handy if you're trying to locate a lighter shade for your secondary colors. 
 
 ## Chrome DevTools
 
 Chrome DevTools https://developers.google.com/web/tools/chrome-devtools
 
 While using Chrome DevTools, you are able to see changes in real time. It's very useful while coding and updating elements in LibGuides CMS because you don't have to constantly go back into the back-end to make your changes. It's a lifesaver! 
 
 You can access the DevTools by right clicking on an element on your website and clicking Inspect. The code of your page will appear either on the bottom or side of the page. From here you can make changes to the CSS and HTML. This comes in handy when you want to test your CSS before making it live. 


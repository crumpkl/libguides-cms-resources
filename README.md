# LibGuides CMS Resources

Mastering LibGuides CMS without any previous experience in LibGuides can be a tricky business. Below are some resources I used to build the Gregg-Graniteville Library's website (https://library.usca.edu/home).

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
 


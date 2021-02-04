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
 
 Font Awesome is a great way to add icons to your website. LibGuides uses Font Awesome icons on the back-end side so to make sure not to upset the apple cart, we must use the same version or risk upsetting the apple cart (also speaking from experience, if you use the most recent version, the icons on the back-end will not load). 
 
 There are so many icons to choose from with Font Awesome. https://fontawesome.com/v4.7.0/icons/
 
 One of the best reasons to use Font Awesome is you don't have to worry about adding images or sizing them for your website. You add and make changes to the icons by adding classes to your code. It's all in the code! Yay! It makes things so much easier in the long run. Escpecially if you're creating this website by using the text editor and building the website in the tradtional code instead of using the provided widgets. 
 
 As Font Awesome explains in the Font Awesome Examples page (https://fontawesome.com/v4.7.0/examples/), "You can place Font Awesome icons just about anywhere using the CSS Prefix fa and the icon's name. Font Awesome is designed to be used with inline elements (we like the <i> tag for brevity, but using a <span> is more semantically correct)."
    
    
        <i class="fa fa-camera-retro"></i> fa-camera-retro
        
All you do is add the above code (change the fa fa-camera-retro to the icon of your choosing) before or after the code where you want the icon. 

For example, the placement of the <i> element determines where the icon appears. 
    
    <div class="col-sm" id="ask-lib-btn"><a href="https://library.usca.edu/chat"><i class="fa fa-question fa-3x" aria-hidden="true"></i></br>Ask a Librarian</a></div>
    
Because the <i> element appears before the "Ask a Librarian" text of the <a> element, the icon will appear before the text but will be linked as the text. If the <i> appeared before the <a> element, the icon wouldn't be linked but would still appear before the text. Also, if <i> element appeared after the text portion of the <a> element, the icon would appear after the text "Ask a Librarian" but it would still be linked. 
    
    
 


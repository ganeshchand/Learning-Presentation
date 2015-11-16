# Learning-Presentation
Repository for Learning Presentation


#HTML & JavaScript based Presentation Framework



##RevealJS

* [Github Source Code](https://github.com/hakimel/reveal.js)

###Instructions:
    *   Download the zip file or clone the repository
    
###Features

    *   Default styles and themes    
    *   Slide Transitions
    *   Slide Fragments
    *   Slide links
    *   Vertical/nested/basement slides
    *   Hiding Controls
    *   Slide Numbers
    *   Auto Advance
    *   Markdown support    
    *   You can use Saas
    *   Customize slides with global state
    *   Custom events
    *   plugins
    *   Export to PDF
    *   Server-side speaker notes
    
    
    

###Notes

*   **Dependencies**: reveal.js uses the HeadJS library to manage plugins and dependencies. You 
    can use only reveal.js if you want, but some useful resources (such as speaker notes
    and zoom) are only enabled using plugins. The plugins can be loaded through the 
    *initialize* method. 
*   **Overview and Blackout Modes**: 
    *   Press **ESC** key to switch to overview mode.
    *   Press **B** or **.** key to pause the presentation / hide your current slide
     
###Basics
     
*   **reveal.js slide property**: HTML must have one **div** with **reveal** as a class attribute. 
This **div** must contain another **div** with **slides** as a class attribute. The slides
**div** must contain or or more **section** element, each one representing a slide.


###Reveal.js initalization Options

*   controls: Navigation Control. *Default: true*
*   progress: Progression Bar. *Default: true*
*   history: History - enable back and forward buttons on the browser. *Default: true*
*   keyboard: Keyboard Navigation. *Default: true*
*   overview: Overview Mode. *Default: true*
*   center: Centers the presentation slides vertically. *Default: true*
*   loop: Enable/Disable presentation loop. *Default: false*
*   rtl (right-to-left): Navigation Control. *Default: false*
*   auto-Slide: Auto-presentation with a timer in millisecond. *Default: 0*
*   mouse-Wheel: Mouse wheel support. *Default: false*
*   rolling-Links: Sets a 3D roll effect to link elements. *Default: true*
*   transition: Transition effect between slids. *Default: 'default'*
    * other values are: cube, pagfe, concave, zoom, linear, none
    
    
###Adding Speaker notes
*   add the dependency
    ```javascript
    dependencies: [{
    src: 'plugin/notes/notes.js',
    async: true}]
    ```
*   use HTML5 tag *aside* and class="notes"
    ```html
    <section>
    <aside calss="notes">Speaker Notes</aside>
    </section>
    ```
*   To open presentation with notes, append **?notes** to the end of the presentation URL.

    *   Requires Pop-Up
    *   You need a web server or you may start chrome with *--allow-file-access-from-files* parameter
    
###Links
*   **#/2** links to the third slide"
*   **#/targetSlideID** links to the slide with id="targetSlideID"    
                                                            
                                                       

    




    


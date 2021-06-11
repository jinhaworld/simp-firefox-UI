# simp-firefox-UI 

![](https://github.com/jinhaworld/simp-firefox-UI/blob/master/assets/img/example.jpg)

Firefox allows users to style the browser through userChrome.css & userContent.css. 

# Installation 

1. Type about:config in the search bar and press accept to the risk button.

2. Search for `toolkit.legacyUserProfileCustomizations.stylesheets, layers.acceleration.force-enabled, gfx.webrender.all, 
and svg.context-properties.content.enabled.` Set it as True. 

3. Type about:profiles in the search bar and click `show in finder` for profile. 

4. Create a folder called chrome within it. git clone this repo into the folder. 

5. Go back to about:profiles and select restart (you will now be able to see the changes made) 

# Use 

> This code is for use with the default dark-mode in Firefox. 

The tab that the user is on will be highlighted with an unique color 
that distinguishes it from other tabs; the user can customize the background image of both 
the space behind the tabs and the homepage (upload images on assets/img). 

A common issue with browsers such as chrome is that it is easy for a single window to 
be overfilled by tabs. In order to prevent this and to store 
more tabs than is possible by default, with all of them visible, the max-width of each tab was set as 70px. 

The close button for tabs with small width typically disappears, but here, the user can simply
hover the mouse over the right side of the tab to magnify the close button. 


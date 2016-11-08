    ||||||||||||||||||||||||||||||||||||||||||||||||||||||||||
    |||██╗|||██╗███████╗|||███████╗|█████╗|███████╗███████╗|||
    |||██║|||██║██╔════╝|||██╔════╝██╔══██╗██╔════╝██╔════╝|||
    |||██║|||██║█████╗|||||███████╗███████║███████╗███████╗|||
    |||╚██╗|██╔╝██╔══╝|||||╚════██║██╔══██║╚════██║╚════██║|||
    ||||╚████╔╝|██║||||||||███████║██║||██║███████║███████║|||
    |||||╚═══╝||╚═╝||||||||╚══════╝╚═╝||╚═╝╚══════╝╚══════╝|||
    ||||||||||||||||||||||||||||||||||||||||||||||||||||||||||
---

##The no-conflict Bootstrap base built for VisualForce pages

+ Supports standard Salesforce stylesheets
+ Loads of veriables for fast site-wide adjustments
+ Ready to be zipped and used a static-resource


####Current Status:
+ It's probably broken for Visualforce with standard Salesforce stylesheets included.
+ Working on converting BS4 to a Visualforce friendly framework.
+ Working on jade templating for a style guide module


####Packages (managed by Bower):
+ Bootstrap Sass - v4.0.0-alpha.3
+ jQuery - 3.1.0
+ Fancyselect - latest


---

####Please note: Editing the the css files directly is a bad life choice if you plan on compiling ever again.
If you must do such a thing, create a separate file to prevent issues when the base stylesheets are compiled.
With the exception of some third-party plug-ins or frameworks, all of the CSS has been compiled from the .scss files located in `/scss` folder.






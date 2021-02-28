# Express + EJS: Styles and Partials

# Intro
* At this point we have covered the basics of Dynamic HTML content and Javascript. The missing ingredient at this point is CSS. So how do we style our EJS templates?

* We could of course add inline <style> tags to our EJS template files, but that would violate the separation of concerns principle.

# File Structure
* Therefore we will be creating external stylesheets and linking to them, just like we would with a static website. The first step is to create a new directory for our stylesheets titled public at the base of our application.

*public is an arbitrary name, it can be anything. However this is the standard convention.

# Direct Express to Styles Folder
* Previously we made a folder called views and Express knew automatically to look into that folder for our page templates. However that is the only location that Express has programmed by default. If we want Express to know where our stylesheets are located we need to direct it to them.
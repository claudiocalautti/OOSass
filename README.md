OOSass
===

A scaffold for sass/scss based projects.

See [this article](http://thesassway.com/beginner/how-to-structure-a-sass-project) and extend as you need.


**Modules**

The modules directory is reserved for Sass code that doesn't cause Sass to actually output CSS, things like mixin declarations, functions, variables, placeholder selectors.


**Partials**

The partials directory is where the meat of my CSS is constructed. Break stylesheets into (header, content, sidebar, and footer components and a few others), or break into much finer categories (typography, buttons, textboxes, selectboxes, etc…).


**Views**

The views directory is where page specific styles are constructed and partials combined or (if needed) modified and adapted to their container.


**Folder Structure**

```
styles/
|
|-- fonts/ # custom fonts source files.
|   ...
|
|-- modules/              # Modules
|   |-- _variables.scss   # Global Variables
|   |-- _functions.scss   # Global Functions
|   |-- _utility.scss     # Common mixins
|   |-- _responsive.scss  # Settings and mixin for responsive
|   ...
|
|-- partials/             # Partials
|   |-- _typography.scss  # Tipography settings and declarations
|   |-- _elements.scss    # Set of commons elements
|   |-- _layout.scss      # Global parts of the layout
|   ...
|
|-- views/                # Views
|   |-- _home.scss        # page/view specific stylesheet
|   ...
|
`-- style.scss            # primary Sass file
````

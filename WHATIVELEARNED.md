# What I've learned

###### 09.09.22
u can use .modules.css which are modules like this:
#example.modules.css
.red {
    color: red;
}

import classes from example.modules.css
element.classList = classes.red

typescript must be compiled seperately (no type checking out of the box) like running the command tsc somewhere (is already added in the package.json)

HMR (Hot Module Replacement) updating Modules automatically in the background when their version is changed in some config file

PostCss is js file that does something afterwards with your css

next: CSS preprocessors

> verschönern ist etwas das muss man sich vornehmen, aber erstmal mit Inhalt füllen!
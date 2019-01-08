# after
* after keyword adds a visual element to the front of the element

# three pillars of writing good html and css
* Responsive design
* Maintanable and scalable code
* Performance

# virtual formatting model
* last part of a the render family tree

# DOM (Document Object Model)
* th is is the decrypted html document

# CSSOM (CSS object model)

#  Render tree
/ combination of decrypted html and css

* rem is always relative to the root font-size

* em is relative to the font-size of the parent element

# BEM (Block Element Modifier)

# sass
* sass is a css preprocessor (it helps clean up css code)
* in sass $ is for variable & is for nesting @ is for function
* Sass and SCSS are the samething but has deferent syntaxes. SCSS uses curly braces Sass uses indentation

* use list-style: none to remove buttons form li

* sass comes with darken(colors, percent) and lighten as well

# mixin
* mixin is a reusable peave of code

# command line
* cp file.ext ./dir this is to copy file
* mv file.ext ./dir this is  to move file

* hit 'npm install' to download all packages on the package.json
* use 'npm uninstall' to uninstall a package

# float left
* when all the elements are floated the height of the parent element reduces to fix this clear-fix is used

# using px
* use pc if you don't want the size to be change if the font-siz of the root element is changed

# Desktop first
* this is designing fit the desktop and using media queries to shrink the design the media query here test for max-width

# Mobile first
* this is designing fit the desktop and using media queries to shrink the design the media query here test for min-width

# Media query
* Max-width(600px) check if the width of the screen is less than or equal to the specified width in the case <= 600px
* the last query of two contrasting queries most work   
* media queries don't add sepcificity to elements so you have to specify the width
* add ' only screen ' to media queries so if someone tries to prnt out the page the small screen wont get printed

# advantage of mobile first
* 100% optimised of the mobile experience
* reduces websites and apps to the absolute essentials
* results in smaller, faster and more efficient products
* priotizes content over fine design

# disadvantage of mobile first
* the desktop version might feel overly empty and simplistic
* more difficult to develop
* it reduces your creative freedom
* clients like to see dexktop version
* are your users from the web or mobile

* NOTE : whatever is being designed always keep mobile and desktop in mind

# breakpoints has 3 methods
* BAD : this is selecting breakpoint out of most popular used devices mostly apple products are used
* Good : this is selction based of most commonly used devices (that is different common width)
* PERFECT : this process entails scaling the website from small to large or vise-varse and finally getting    the adequate breakpoint
# statcounter 
* gives the stats of the most used phones it is free for use

# media query
* always add the the smaller lenght media below the larger lenght because the lower elemnt s get read last    on the css page
* use 'or' in supports for conditional statements

# responsive
* use sizzy.co to test out website on different devices

# responsive images
* the goal of responsive images is to serve the right image for the right device so the user will not download an unnesesary large file for a small device

- there are three use cases

* resolution switching - same image different resolution, this lets the browser choose the best image for the resolution
* density switching - the image is hown base on the density of the screen (it it will send 2 images one for   2 times density screen the other for 1x density screen)
* art direction - this entails serving a whole new image on smaller screens this forces the browser to use a particular image where as the resolution switching the browser chooses

# browser support
* Enter caniuse.com to check if a new css feature can be used for production yet
* Graceful degredation is providing a top notch experience for modern browsers and a fallback for older browsers

* chrome doesn't support backdrop-filter and background-blend-mode

* to concat files use npm install concat

# build process sass
* first compile to the main.scss to css (compilation),
* then join all the css files into one (concatenation),
* then prefix to work on all browsers (prefixing),
* then compress for web page (compression) ;
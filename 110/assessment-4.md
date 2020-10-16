
## 1
Building platform specific user interfaces can take tedious amounts of time because you have to create the site to be compatible with various screen dimensions on many different devices. Each item's width or height dimensions may not be able to be seen on a screen with smaller or it could be too small on larger dimensions. Everyone must be able to access your page so you may need to even have different fonts because some browsers do not support it.


## 2
  When using media queries for menus you would set the width for the menu to look different if it was on a phone or if someone resized the web page. You would use @media screen and then put max width of how many pixels you want to change how it looks on smaller screens and then below it put the class name for the menu like .nav if you named it that and put a because the menu is full of links. @media screen and (max-width: 400px) { .nav a {float: none; width: 50%;}}. Another one you could use is columns. it does the same thing as the menu but instead of changing how the menu would look it changes the columns. you would put the same thing in your css as you did with the menu but you would change .nav a with .column or whatever you put that class name to and get rid of the a because they are not links.


## 3
It's better to use breakpoints for specific content on your site because of the varying device screen sizes. When web developers were using standard device sizes they had to change it many times, we've gone from the computers to small phones, we have gotten bigger when we started using tablets, we have gone even smaller with wrist watches and eventually we will go even smaller and try to put it inside of a glass lens. If you use breakpoint for content then you won't have to keep changing the breakpoints for devices and the website will look the same for different devices but the content will be positioned differently on a smaller screen than it would on a bigger screen.

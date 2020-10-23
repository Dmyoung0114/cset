
## 1
Building platform specific user interfaces can take short amounts of time because you do not have to create the site to be compatible with various screen dimensions on many different devices. Each items dimensions may not be able to be seen on across different screens, content could be too small on larger dimensions, or to large on smaller dimensions. Everyone must be able to access your page so you need to accommodate for their screen sizes and browser capabilities. Some browsers also do not support new things added within a language so be sure to check compatibility across browsers and screen sizes. if it were platform specific you do not have to worry about all of the extra ins and outs you would have to be concerned about trying to get it to all platforms to be able to access your content.

## 2

body{
  display: flex;
  flex-direction: row;
  color: red;
}

@media screen(max-width: 500px){
  body{
    display: flex;
    flex-direction: column;
  }
  }  

 

  @media print {
    body {
      color: blue;
    }
  }

 this will change the body to be displayed differently on smaller screens and also changes the colors of the document when printed. the way the agent decides which rules to use or not is on their order so if i were to put @media print color black after the other media print  it will chose the one that was last applied so it would be black.

## 3
It's better to use breakpoints for specific content on your site because of the varying device screen sizes. Developers used to work on the same screen sizes so their was not a lot of variation. But  since then Developers have had to change screen sizes so many times, we have gone from the computers to small phones, we have gotten bigger when we started using tablets, we have gone even smaller with wrist watches and eventually we will go even smaller and try to put it inside of a glass lens. If you use breakpoint for content then you won't have to keep changing the content to fit devices and the website content will still be displayed properly it will look similar across different devices, but the content will be placed and aligned in different spots on a smaller screen than it would on a bigger screen.

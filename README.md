## Swipe JS Vertical

Warning. It is not the original release of Swipe JS by *Brad Birdsall*. This version handles **vertical swipe**.
About the API, config options, params, browser support,... please, [check out the original project](https://github.com/bradbirdsall/Swipe).


## Set Up

The only difference for using **Swipe JS Vertical** is that you must define a *height* for your container. You can do it in *CSS* files or in your *JavaScript* code.

 ``` css
 .swipe {
   overflow: hidden;
   visibility: hidden;
   position: relative;
   height: @myHeight px; /* <-- Mandatory */
 }
 .swipe-wrap {
   overflow: hidden;
   position: relative;
 }
 .swipe-wrap > div {
   float:left;
   width:100%;
   position: relative;
 }
 ```


Other settings (HTML, JS,...) are still the same.
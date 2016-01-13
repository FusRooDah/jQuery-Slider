jQuery-Plugin - Javascript
=========================

This jQuery plugin is created for one purpose and one only. To create a simpel and good looking image slider.


License
-------

This software is free software and carries a MIT license.

Install
-------
This plugin creates a slideshow with an click function that scrolls the images to the left. When the plugin reaches the last picture it starts over on the first image again. This is a very effective plugin that dosent require that much of the browser and it dosen't slow down the loading speed of the page.

## Why use this plugin over others?

This plugin is very easy to use it dosent take alot of knowledge to use it. Its designed to be user friendly and easy to configure by having saved the configuration in variables. Instead of having number all over the jQuery code.

To use it you simply include the javascript file:

                            <script src="js/slider.js"></script>

After that you create the div box where you want the slider to be:

                            <div id="slider">
                                <ul class="slides">
                                    <li class="slide"><img src="path"></li>
                                </ul>
                            </div>

In the **li** part you put the first image last again and the slider will start over on the first image and scroll through all images.

To configurate the slider you simply change these values:

                            var width = 720; // Width of the slider
                            var animationSpeed = 1700; //Speed of the slider
                            var pause = 3000; //Time between slides

Also don't forget in include the jQuery.js file which you can find [Here.](http://www.student.bth.se/~kepa14/JavaScript/kmom10/js/jquery.js)

##placephant

This is a very simple placeholder project featuring lovely elephpants.
It's built with Silex+Flint.

You can use this project as a base for your very own image placeholder. Just change the settings in the app/config/config.yml file and use your own image resources.

###Usage

You can point the src of your images direct to http://placephant.com with the desired width and height as path parameters, as shown below:

300x250 colored image:
``<img src="http://placephant.com/300/250"/>``

100x100 square colored image (just need to provide the width): 
``<img src="http://placephant.com/100"/>``

300x250 black and white image: 
``<img src="http://placephant.com/300/250?filter=bw"/>``

300x250 sepia image: 
``<img src="http://placephant.com/300/250?filter=sepia"/>``

###Requirements (dev)

Placephant requires php >= 5.4 and the php5-imagick extension.
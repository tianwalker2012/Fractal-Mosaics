Fractal-Mosaics
===============

Fractal Mosaics is a rotation, scale, and translation invariant photomosaic algorithm (i.e., the images can be placed at arbitrary locations, can be scaled to any size, and can be rotated by any angle).

![Alt text](https://raw.github.com/s-ben/Fractal-Mosaics/gh-pages/images/eye_mosaic_flickr_350pix.jpg?login=s-ben&token=08d50c08c1ba3bc2c568fccfa3b77361)

The code provided is free to use for non-commercial or commercial uses.  If you create something with the code, let me know!  If you wanna pay me, let me know!

# Prerequisites

Fractal Mosaics is implemented in Matlab.  You’ll need a copy of Matlab with the Signal Processing toolbox installed (any version should work, most should come with the Signal Processing toolbox).


# Getting Started

1.  Download the demo example.  This has all the code you need.  Simply modify the example to create your own mosaics.
2.	Download the example image set (706 MB database of images of San Francisco).
3.	Unpack zip file with images into the /library_images folder in the demo example.
4.	Navigate to the /m-files directory 
5.	Run ‘fractal_mosaic.m’ 

Your mosaic is now rendering.

Warning:  it takes a long time to render a mosaic (~6 to 8 hrs on my macbook pro).  If you want to optimize it, please do ;)

The demo example creates a black and white mosaic.  This is because color takes ~3X as long.  To create a color mosaic, download the color image set, and set Fractal Mosaics to color mode (see the Variables page for info on this).

# Documentation

Fractal Mosaic “paper”:  academic-style paper explaining how the algorithm works
How to create your own mosaic: step-by-step instructions
Variables:  how to use the 10 variables Fractal Mosaics uses to tweak mosaic output
Mosaics:  Flickr page containing finished mosaics


# Image_Reduction

The purpose of the project is to reduce the background and bias noise from CCD camera images, stack the images into 1 master image, then to adjust the RGB saturation levels of the final images to produce a single, noise-reduced, pretty picture. We will use our raw scientific images taken of a portion of the Pleiades constellation in the red, blue, and visible filters. We will use astrometry.net to align the sources across all images and then we will use DS9 software to adjust the saturation.

We will also look at a few characteristics of the images themselves such as histograms of the the average distribution of the amount of pixels that recorded a certain ''flux'' (or number of electrons that crossed the semi-conductor within the CCD) and also how to calibrate the source flux in the images to the known spectrum of Neon emission lines. 

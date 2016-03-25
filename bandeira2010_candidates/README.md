The filenames that contain tp are the true positive craters.  The filenames that contain tn are crater candidates created by Urbach's highlight/shadow method but are not craters.

Each file has the columns x,y,r where:

x center of crater measured from the left side of image
y center of crater measured from the top of image
r radius of crater

These will map to the images when they are 1700x1700 pixels.



# CraterDataset

Data Set Information:
This dataset was generated using HRSC nadir panchromatic image h0905_0000 taken by the Mars Express spacecraft. The images is located in the Xanthe Terra, centered on Nanedi Vallis and covers mostly Noachian terrain on Mars. The image had a resolution of 12.5 meters/pixel.

# Data Set Generation:

Using the technique described by L. Bandeira (Bandeira, Ding, Stepinski. 2010. Automatic Detection of Sub-km Craters Using Shape and Texture Information) we identify crater candidates in the image using the pipeline depicted in the figure below. Each crater candidate image block is normalized to a standard scale of 48 pixels. Each of the nine kinds of image masks probes the normalized image block in four different scales of 12 pixels, 24 pixels, 36 pixels, and 48 pixels, with a step of a third of the mask size (meaning 2/3 overlap). We totally extract 1,090 Haar-like attributes using nine types of masks as the attribute vectors to represent each crater candidate.






==Citations==

Bandeira, L., W. Ding, and T. F Stepinski. “Automatic Detection of Sub-Km Craters Using Shape and Texture Information.” In Proceedings of the 41st Lunar and Planetary Science Conference. The Woodlands, Texas, 2010.

Urbach, E. R, and T. F Stepinski. “Automatic Detection of Sub-Km Craters in High Resolution Planetary Images.” Planetary and Space Science 57, no. 7 (2009): 880–87.

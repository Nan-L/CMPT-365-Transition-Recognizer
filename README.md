# CMPT-365-Transition-Recognizer

credit by: Nan Liu, Joshil Patel

We are interested in finding and characterizing video transitions, specifically cuts and wipes.

One approach to this problem is to construct a “spatio-temporal” image [STI] = an image which contains video content for each frame along the ordinate axis, versus time along the abscissa. A simple version of such a construction consists of copying a column (or row), or weighted average of a few, directly into the STI.

One approach that is taken to characterize images is to use a histogram of colour, rather than just the raw pixel data. Histograms are fairly insensitive to troublesome problems such as movement and occlusion.

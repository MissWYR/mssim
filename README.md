MSSIM
=====
A simple implementation of the Mean Structural Similarity (MSSIM) algorithm as 
described in the paper: Zhou Wang et al. "Image quality assessment: From error
visibility to structural similarity". In: *Image Processing, IEEE Transactions
on* 13.4 (2004), pp. 600–612.

the environment is python==3.6 and scikit-image==0.16.2

Usage: `./mssim.py REFERENCE_IMAGE OTHER_IMAGES...`
example：python mssim.py breast_img1.png breast_img2.png


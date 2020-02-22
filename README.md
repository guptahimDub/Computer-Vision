# Computer-Vision
Histograms: 

a. Read a RGB colour image (e.g. png) and display it. 

b. Convert the RGB image into Lab colour system and display each component (L,a,b) as an grey level image (See section 2.7.4 in http://www.ee.columbia.edu/ln/dvmm/publications/PhD_theses/jrsmith-thesis.pdf). 

c. Compute the spatial derivatives of the luminance component L  in the horizontal and vertical direction using convolution by the derivatives of Gaussian filter. Display each these derivatives  as grey level images. 

d. Compute a 2D histogram with the chrominance component (a,b)  and display the histogram as a grey image (heat map) and/or as a 3D surface (bar plot) 

e. Using a part of the image to compute a 2D histogram model with the chrominance component (a,b), compute a back projection map with this model histogram in the target image (i.e. see BP1 section 5.3 in http://www.ee.columbia.edu/dvmm/publications/PhD_theses/jrsmith-thesis.pdf ). 

f. Perform histogram equalization using 1D histogram using the luminance L computed in 1.a. Display the resulting image with enhanced contrast (e.g. https://en.wikipedia.org/wiki/Histogram_equalization ) 

g. Evaluate the performance of these techniques with histograms (i.e. illustrate when it works, and when it does not work). 


PCA:

a. Compute the mean image and principal components for a set of images (e.g. use the training images of ‘5’ in the mnist dataset). Display the mean image and the first 2 principal components (associated with the highest eigenvalues). 

b. Compute and display the reconstructions of a test image using the mean image and with p principal components associated with the p highest eigenvalues (e.g. Fig 10.12) with p=10 and p=50. 

c. Read https://doi.org/10.1109/34.598227 ‘Probabilistic visual learning for object representation’ (PAMI1997). Compute and display a DFFS (distance-from feature-space) and SSD (sum-of-square-differences) heat maps for detection using your PCA 
   representation of a MNIST number. For the test image, use a composite image made of MNIST test images (see example below). 
   
d. Evaluate the performance of SSD and DFFS (i.e. illustrate when it works, and when it does not work). 

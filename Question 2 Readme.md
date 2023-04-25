
# Question 2
## How we have done
  
-----------
WWe have written Python function [cc] = Conncomp(I, connectivity, V ) to find all the connected components in an Image using Sequential algorithm. The parameter connectivity may be either 4 or 8, while the parameter V contains the set of intensity values to define connectivity. Compare your results with Python’s inbuilt function bwconncomp.

- Frist we have taken some test images from internet for counting number of connected components
   
- then we read the image
- convert the image to binary
- define the set of intensity values to define connectivity `v=[255]`
- then we find the connected components using our function `Conncomp(binary, 8, V)`
- then we find the connected components using bwconncomp `labels = label(binary, connectivity=2, background=0)`
- we have tested both the function for 3 different test images and results comes to equal for Each
- then we have printed all the connected components step by step


#### The code is written in Google Colabe Notebook so its easier to run 


# Question 1
## How we have done

Parameters:
-----------
- I : np.ndarray
    2D matrix representing the image.
- x1, y1 : int
    Coordinates of the starting point.
- x2, y2 : int
    Coordinates of the ending point.
- V : List[int]
    Set of allowable pixel values for the path.
- path_type : int
    Type of path to find. Can be 4, 8, or 10 for m-path.

Returns:
--------
A tuple (paths_info, shortest_path), where:
- paths_info is a list of structures containing all the paths of desired type, their lengths, and the shortest path.
  Each structure is a list of (x,y) tuples representing a path in the image.
- shortest_path is a dictionary with keys 'path' (a list of (x,y) tuples) and 'length' (an int).
  It represents the shortest path of the desired type between the two points.

#### The Input image is entered manually
#### We have generated and printed all the possible paths for 4,8 and m 
#### We have calculted disatance of all the path using Eculiedian Formula  
= √[(x2 – x1)2 + (y2 – y1)2].
and calculted the shortest_path among all paths 
#### Libraries we have used 
- numpy
- matplotlib.pyplot
### The code is in Google Colab notebook so its easy to run the code

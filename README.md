==============================================================================
Computer Vision and Image Processing functions and scripts 
==============================================================================


Create ply point cloud
--------------------------------------------------------------------------------

Converts 3D point cloud (x,y,z) to '.ply' format. The point cloud can have additional columns for the color information.

File: [mat2ply.m](https://github.com/giuliomarin/cvip/blob/master/mat2ply.m)

--------------------------------------------------------------------------------

Load ply point cloud
--------------------------------------------------------------------------------

Load a '.ply' file and store 3D point cloud in a N x 3 matrix (x,y,z). If the original point cloud has also color information, this will be saved as well.

File: [ply2mat.m](https://github.com/giuliomarin/cvip/blob/master/ply2mat.m)

--------------------------------------------------------------------------------

Otsu's segmentation method with 3 gray levels
--------------------------------------------------------------------------------
Example that shows the Otsu's algorithm for segmenting an image whose color distribution presents 3 peaks. The algorithm find the thresholds such that the within-class variance is minimized. This is an extension of the original algorithm for two peaks distribution.

Directory: [otsu3](https://github.com/giuliomarin/cvip/tree/master/otsu3)

--------------------------------------------------------------------------------
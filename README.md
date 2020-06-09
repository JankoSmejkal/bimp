# bimp
Make-life-easier Python functions for image processing. 

# Functions

show_image()
- Show image using matplotlib.
Parameters:
- 3D/2D image as uint8/16 array.
Output:
- No output

color2gray()
- Uses cv2.COLOR_BGR2GRAY, or cv2.COLOR_RGB2GRAY to convert rgb to gray.
Parameters:
- image -> 3D numpy array.
- bgr -> color channel order. Default -> bgr='True'. Specify bgr='False' if RGB order.
Output:
- Grayscale image 

normalize_image()
- Normalize pixel values to 0 - 1 range
Parameters:
- image -> 3D/2D numpy array of uint8 or uint16 data type.
Output:
- Normalized array of float64 data type

distance()
- Calculates Euclidian or Manhattan distance
Parameters:
- coords1 -> Expecting tuple with 2 values corresponding to x,y of point 1
- coords2 -> Expecting tuple with 2 values corresponding to x,y of point 2
- distance_type -> Expecting string: 'euclidian' or 'manhattan'
Output:
- Distance of chosen type  

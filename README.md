# bimp
Make-life-easier Python functions for image processing. 

# Includes

show_image()
- Show image using matplotlib

color2gray()
- Use cv2.COLOR_BGR2GRAY, or cv2.COLOR)RGB2GRAY to convert rgb to gray.
Parameters:
- image -> 3D numpy array
- bgr -> color channel order. Default -> bgr='True'. Specify bgr='False' if RGB order.

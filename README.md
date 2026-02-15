# Digital Image Processing 


1. Forward Rotation: Code to perform forward rotation on an image.
    
2. Reverse Rotation: Code to perform reverse rotation on the input image.
    
3. Rotation with interpolation: Code to rotate an the input image, using nearest neighbor and bilinear interpolation.

One images is provided for testing: cameraman.jpg
  
Notes: 

1. Files not to be changed: requirements.txt and Jenkinsfile 

2. the code has to run using one of the following commands

 - Usage: `./dip_hw1_rotate.py -i image-name -t theta -m method`
 
   Example: `./dip_hw1_rotate.py -i cameraman.jpg -t 0.5 -m nearest_neighbor`

 - Usage: `python dip_hw1_rotate.py -i image-name -t theta -m method`
 
   Example: `python dip_hw1_rotate.py -i cameraman.jpg -t 0.5 -m bilinear`
  
3. Any output file or image should be written to output/ folder

4. The code has to run on jenkins CI/CD
5. **Do not use** any in-built functions from opencv and numpy (E.g: np.mean). In general, you can use functions from the math (sin, cos, etc) library.
6. The only allowed functions for this part are: np.array(), np.matrix(), np.zeros(), np.ones(), cv2.imread(), cv2.namedWindow(), cv2.waitKey().




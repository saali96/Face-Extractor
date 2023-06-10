# Face Extractor
This repository contains code for extracting faces from images using OpenCV and Haar cascades. The script detects faces in an image and extracts them by drawing rectangles around the detected faces. The extracted faces are then displayed using the matplotlib library.

## Usage
1. Install the required libraries by running the following command: 
  pip install opencv-python pillow matplotlib  
2. Load the image and call the faceExtract function with the file path of the image:
  extracted_face = faceExtract('filePath.jpg')
3. The function will detect faces in the image, draw rectangles around them, and display the original image with rectangles and the extracted face.  
4.The execution time of the face detection process will be printed.




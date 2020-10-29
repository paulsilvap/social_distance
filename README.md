# social_distance
Social distance implementation using python and OpenCV. Original code belongs to https://www.pyimagesearch.com/2020/06/01/opencv-social-distancing-detector/. To run the code just write 

python .\social_distance_detector.py -i testvideo -o output.avi -d 0

OneDrive link with yolov3 and yolov4 weights: https://1drv.ms/u/s!AlhPZsy3RyaxgrYCUO-1cSMidPbA9w?e=52zc5V

Once you download the weights, put them in the yolo-coco folder on your local repository. Additionaly, if you want to run yolov4 you need to install OpenCV 4.4.0. Older versions of OpenCV are only compatible with yolov3.

# Additional packages required:

-numpy
-scipy
-imutils

This can be installed using pip.

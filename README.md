# Object Detection using OpenCV Computer Vision
 
## [1. Reading, writing and displaying images OpenCV](https://github.com/Ashish-Gore/Object-Detection-using-OpenCV-Computer-Vision/tree/main/1.%20Reading%2C%20writing%20and%20displaying%20images%20OpenCV)

Objectives:
-  Reading, writing and displaying the images using OpenCV Library.

Code:
- [1. Reading, writing and displaying images OpenCV.ipynb](https://github.com/Ashish-Gore/Object-Detection-using-OpenCV-Computer-Vision/blob/main/1.%20Reading%2C%20writing%20and%20displaying%20images%20OpenCV/1.%20Reading%2C%20writing%20and%20displaying%20images%20OpenCV.ipynb)

Input Image:
![picture alt](https://github.com/Ashish-Gore/Object-Detection-using-OpenCV-Computer-Vision/blob/main/image_examples/input1_Ashish(1).jpg)

Output Image:
![picture alt](https://github.com/Ashish-Gore/Object-Detection-using-OpenCV-Computer-Vision/blob/main/image_examples/input1_Ashish(1).jpg)


## [2. Face & Eye Detection](https://github.com/Ashish-Gore/Object-Detection-using-OpenCV-Computer-Vision/tree/main/2.%20Face%20%26%20Eye%20Detection)

Objectives:
-  Face & Eye Detection in the input images using OpenCV Library.

Working of Haar Cascade:
-A Haar Cascade feature considers adjacent rectangular regions at a specific location in a detection window, sums up the pixel intensities in each region and calculates the difference between these sums. This difference is then used to categorize subsections of an image.

Code:
- [2. Face & Eye Detection.ipynb](https://github.com/Ashish-Gore/Object-Detection-using-OpenCV-Computer-Vision/blob/main/2.%20Face%20%26%20Eye%20Detection/2.%20Face%20%26%20Eye%20Detection.ipynb)

- Tuning Cascade Classifiers
ourClassifier.detectMultiScale(input image, Scale Factor , Min Neighbors)

**Scale Factor** Specifies how much we reduce the image size each time we scale. E.g. in face detection we typically use 1.3. This means we reduce the image by 30% each time it’s scaled. Smaller values, like 1.05 will take longer to compute, but will increase the rate of detection.
**Min Neighbors** Specifies the number of neighbors each potential window should have in order to consider it a positive detection. Typically set between 3-6. It acts as sensitivity setting, low values will sometimes detect multiples faces over a single face. High values will ensure less false positives, but you may miss some faces.

Face Detection Input Image:
![picture alt](https://github.com/Ashish-Gore/Object-Detection-using-OpenCV-Computer-Vision/blob/main/image_examples/input1_Ashish(1).jpg)

Face Detection Output Image:
![picture alt](https://github.com/Ashish-Gore/Object-Detection-using-OpenCV-Computer-Vision/blob/main/2.%20Face%20%26%20Eye%20Detection/Ashish_face_output.jpg)

Face & Eye Detection Input Image:
![picture alt](https://github.com/Ashish-Gore/Object-Detection-using-OpenCV-Computer-Vision/blob/main/image_examples/input_Ashish.jpg)

Face & Eye Detection Output Image:
![picture alt](https://github.com/Ashish-Gore/Object-Detection-using-OpenCV-Computer-Vision/blob/main/2.%20Face%20%26%20Eye%20Detection/Ashish_face_and_eye_output.jpg)


## [3. Car & Pedestrian Detection](https://github.com/Ashish-Gore/Object-Detection-using-OpenCV-Computer-Vision/tree/main/3.%20Car%20%26%20Pedestrian%20Detection)

Objectives:
-  Car & Pedestrian Detection in the input images using OpenCV Library.

Code:
- [3. Car & Pedestrian Detection.ipynb](https://github.com/Ashish-Gore/Object-Detection-using-OpenCV-Computer-Vision/blob/main/3.%20Car%20%26%20Pedestrian%20Detection/3.%20Car%20%26%20Pedestrian%20Detection.ipynb)

Pedestrian Input Image:

![picture alt](https://github.com/Ashish-Gore/Object-Detection-using-OpenCV-Computer-Vision/blob/main/image_examples/walking.gif)

Pedestrian Detection Output Image 1:
![picture alt](https://github.com/Ashish-Gore/Object-Detection-using-OpenCV-Computer-Vision/blob/main/3.%20Car%20%26%20Pedestrian%20Detection/Pedestrian_Output.png)

Pedestrian Detection Output Image 2:
![picture alt](https://github.com/Ashish-Gore/Object-Detection-using-OpenCV-Computer-Vision/blob/main/3.%20Car%20%26%20Pedestrian%20Detection/Pedestrian_Output1.png)

Car Input Image:

![picture alt](https://github.com/Ashish-Gore/Object-Detection-using-OpenCV-Computer-Vision/blob/main/image_examples/cars.gif)

Car Detection Output Image 1:
![picture alt](https://github.com/Ashish-Gore/Object-Detection-using-OpenCV-Computer-Vision/blob/main/3.%20Car%20%26%20Pedestrian%20Detection/Car_output.png)

Car Detection Output Image 2:
![picture alt](https://github.com/Ashish-Gore/Object-Detection-using-OpenCV-Computer-Vision/blob/main/3.%20Car%20%26%20Pedestrian%20Detection/Car_output1.png)


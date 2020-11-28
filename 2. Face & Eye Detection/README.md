# Face & Eye Detection

Objectives:
-  Face & Eye Detection in the input images using OpenCV Library.

Working of Haar Cascade:
-A Haar Cascade feature considers adjacent rectangular regions at a specific location in a detection window, sums up the pixel intensities in each region and calculates the difference between these sums. This difference is then used to categorize subsections of an image.

Code: [2. Face & Eye Detection.ipynb](https://github.com/Ashish-Gore/Object-Detection-using-OpenCV-Computer-Vision/blob/main/2.%20Face%20%26%20Eye%20Detection/2.%20Face%20%26%20Eye%20Detection.ipynb)

**Tuning Cascade Classifiers
ourClassifier.detectMultiScale(input image, Scale Factor , Min Neighbors)**

**Scale Factor** Specifies how much we reduce the image size each time we scale. E.g. in face detection we typically use 1.3. This means we reduce the image by 30% each time it’s scaled. Smaller values, like 1.05 will take longer to compute, but will increase the rate of detection.
**Min Neighbors** Specifies the number of neighbors each potential window should have in order to consider it a positive detection. Typically set between 3-6. It acts as sensitivity setting, low values will sometimes detect multiples faces over a single face. High values will ensure less false positives, but you may miss some faces.

Face Detection Input Image:<br>
![picture alt](https://github.com/Ashish-Gore/Object-Detection-using-OpenCV-Computer-Vision/blob/main/image_examples/input1_Ashish(1).jpg)

Face Detection Output Image:<br>
![picture alt](https://github.com/Ashish-Gore/Object-Detection-using-OpenCV-Computer-Vision/blob/main/2.%20Face%20%26%20Eye%20Detection/Ashish_face_output.jpg)

<br>
<br>

Face & Eye Detection Input Image:<br>
![picture alt](https://github.com/Ashish-Gore/Object-Detection-using-OpenCV-Computer-Vision/blob/main/image_examples/input_Ashish.jpg)

Face & Eye Detection Output Image:<br>
![picture alt](https://github.com/Ashish-Gore/Object-Detection-using-OpenCV-Computer-Vision/blob/main/2.%20Face%20%26%20Eye%20Detection/Ashish_face_and_eye_output.jpg)


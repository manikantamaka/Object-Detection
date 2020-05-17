# Yolo v3 Object-Detection

Important Note:
You should know what is Object-Detection and Object-Recognition and their Algorithms, Archiechtures(VGG16, AlexNet, ResNet etc), and Pre-Trained Weigths models(COCO, CIFAR-10 etc) we are using those models in Transfer Learning.

### Please Download Yolo3.Weigths, I cannot upload the file here, coz its too large

Object Detection tells you which objects are present in the image, it also outputs bounding boxes (x, y, width, height) to indicate the location of the objects inside the image
Before Going to this, first of all you should know about what is Object Detection and Object recognition
The difference between object detection algorithms and classification algorithms is that in detection algorithms, we try to draw a bounding box around the object of interest to locate it within the image. Also, you might not necessarily draw just one bounding box in an object detection case, there could be many bounding boxes representing different objects of interest within the image and you would not know how many beforehand.
## Object Recognition:
An object recognition algorithm identifies which objects are present in an image. It takes the entire image as an input and outputs class labels and class probabilities of objects present in that image. For example, a class label could be “dog” and the associated class probability could be 97%.
## Object Recognition
Object Detection algorithm not only tells you which objects are present in the image, it also outputs bounding boxes (x, y, width, height) to indicate the location of the objects inside the image.
And most important you must know about, Sliding Window Algorithm, Region Proposal Algorithms, Selective Search for Object Recognition

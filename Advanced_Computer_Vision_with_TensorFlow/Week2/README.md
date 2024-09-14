# Object Detection

This week, you’ll get an overview of some popular object detection models, such as regional-CNN and ResNet-50. You’ll use object detection models that you’ll retrieve from TensorFlow Hub, download your own models and configure them for training, and also build your own models for object detection. By using transfer learning, you will train a model to detect and localize rubber duckies using just five training examples. You’ll also get to manually label your own rubber ducky images!

## Learning Objectives

- Get a conceptual overview of Regional CNN (R-CNN), Fast-RCNN, and Faster R-CNN.
- Retrieve the R-CNN model from TensorFlow hub and use it to perform object detection.
- Use TensorFlow’s object detection API to visualize the predicted bounding boxes from an object detection model
- Go beyond models in TensorFlow Hub: Load and configure a Resnet-50 model that isn’t on TensorFlow Hub, restore pre-trained - weights, and select the parts of the model to retrain.
- Use the object detection API to manually annotate images for object detection
- Implement a custom training loop to fine-tune a model using just 5 training examples.

## Object Detection

- [Video - Object Detection and Sliding Windows](https://www.coursera.org/learn/advanced-computer-vision-with-tensorflow/lecture/088bZ/object-detection-and-sliding-windows)

- [Reading - References: Amazon Rekognition, PowerAI & DIGITS](https://www.coursera.org/learn/advanced-computer-vision-with-tensorflow/supplement/3oVBO/references-amazon-rekognition-powerai-digits)

- [Video - R-CNN](https://www.coursera.org/learn/advanced-computer-vision-with-tensorflow/lecture/8NV2T/r-cnn)

- [Video - Fast R-CNN](https://www.coursera.org/learn/advanced-computer-vision-with-tensorflow/lecture/FjbUm/fast-r-cnn)

- [Video - Faster R-CNN](https://www.coursera.org/learn/advanced-computer-vision-with-tensorflow/lecture/VHfKu/faster-r-cnn)

- [Reading - Reference: R-CNN, Fast R-CNN](https://www.coursera.org/learn/advanced-computer-vision-with-tensorflow/supplement/tzRMX/reference-r-cnn-fast-r-cnn)

## Object Detection in TensorFlow

- [Video - Getting the Model from TensorFlow Hub](https://www.coursera.org/learn/advanced-computer-vision-with-tensorflow/lecture/tZDzl/getting-the-model-from-tensorflow-hub)

- [Reading - Reference: TensorFlow Hub](https://www.tensorflow.org/hub)

- [Video - Running the Model on an Image](https://www.coursera.org/learn/advanced-computer-vision-with-tensorflow/lecture/Et4Te/running-the-model-on-an-image)

- [Lab - Implement Simple Object Detection](./Labs/C3_W2_Lab_1_Simple_Object_Detection.ipynb)

- [Lab - Predicting Bounding Boxes for Object Detection](./Labs/C3_W2_Lab_2_Object_Detection.ipynb)

## Object Detection APIs

- [Video - Installation and overview of APIs](https://www.coursera.org/learn/advanced-computer-vision-with-tensorflow/lecture/vW2pY/installation-and-overview-of-apis)

- [Video - Visualization with APIs](https://www.coursera.org/learn/advanced-computer-vision-with-tensorflow/lecture/dqRWA/visualization-with-apis)

- [Reading - Read about the Object Detection API](https://www.coursera.org/learn/advanced-computer-vision-with-tensorflow/supplement/m2Z8o/read-about-the-object-detection-api)

- [Lab - Use the Object Detection API](./Labs/tf2_object_detection.ipynb)

## Retraining with the Object Detection API

- [Video - Loading a RetinaNet Model](https://www.coursera.org/learn/advanced-computer-vision-with-tensorflow/lecture/jKPMG/loading-a-retinanet-model)

- [Reading - Reference: RetinaNet, Model Garden](https://www.coursera.org/learn/advanced-computer-vision-with-tensorflow/supplement/RvSzb/reference-retinanet-model-garden)

- [Video - Loading Weights](https://www.coursera.org/learn/advanced-computer-vision-with-tensorflow/lecture/k3UjZ/loading-weights)

- [Video - Data Prep and Training Overview](https://www.coursera.org/learn/advanced-computer-vision-with-tensorflow/lecture/PVaTB/data-prep-and-training-overview)

- [Video - Custom Training Loop Code](https://www.coursera.org/learn/advanced-computer-vision-with-tensorflow/lecture/Yj69C/custom-training-loop-code)

- [Lab - Eager Few Shot Object Detection](./Labs/interactive_eager_few_shot_od_training_colab.ipynb)

## Lecture Notes (Optional)

- [Reading - Lecture Notes Week 2](./Readings/C3_W2.pdf)

## Assignment: Zombie Detector

- [Lab - Zombie Detector](./Labs/C3W2_Assignment.ipynb)
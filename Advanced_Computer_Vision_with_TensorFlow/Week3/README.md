# Image Segmentation

This week is all about image segmentation using variations of the fully convolutional neural network. With these networks, you can assign class labels to each pixel, and perform much more detailed identification of objects compared to bounding boxes. You’ll build the fully convolutional neural network, U-Net, and Mask R-CNN this week to identify and detect numbers, pets, and even zombies!

## Learning Objectives

- Describe the conceptual design of fully convolutional neural networks and subsequent models based on it
- Describe the decoder section of the fully convolutional neural network
- Describe two methods of upsampling: simple scaling and transposed convolutions
- Build the encoder and decoder sections of a fully convolutional neural network
- Evaluate a segmentation model’s performance using intersection-over-union and Dice score
- Describe the conceptual design of the U-Net model
- Build a U-Net model for image segmentation
- Use the Mask R-CNN to perform instance segmentation

## Image Segmentation Overview

- [Video - Image Segmentation Overview](https://www.coursera.org/learn/advanced-computer-vision-with-tensorflow/lecture/m8zpr/image-segmentation-overview)

- [Video - Popular Image Segmentation Architectures](https://www.coursera.org/learn/advanced-computer-vision-with-tensorflow/lecture/panWo/popular-image-segmentation-architectures)

- [Reading - References: FCN](https://arxiv.org/pdf/1411.4038)

- [Video - FCN Architecture Details](https://www.coursera.org/learn/advanced-computer-vision-with-tensorflow/lecture/uwVDj/fcn-architecture-details)

- [Video - Upsampling Methods](https://www.coursera.org/learn/advanced-computer-vision-with-tensorflow/lecture/ku4yr/upsampling-methods)

- [Video - Encoder in Code](https://www.coursera.org/learn/advanced-computer-vision-with-tensorflow/lecture/0THBa/encoder-in-code)

- [Reading - Reference: CamVid](https://github.com/divamgupta)

- [Video - Decoder in Code](https://www.coursera.org/learn/advanced-computer-vision-with-tensorflow/lecture/MXq83/decoder-in-code)

- [Video - Evaluation with IoU and Dice Score](https://www.coursera.org/learn/advanced-computer-vision-with-tensorflow/lecture/zbusx/evaluation-with-iou-and-dice-score)

- [Lab - Implement a Fully Convolutional Neural Network](./Labs/C3_W3_Lab_1_VGG16_FCN8_CamVid.ipynb)

## U-Net

- [Video - U-Net Overview](https://www.coursera.org/learn/advanced-computer-vision-with-tensorflow/lecture/QB2dZ/u-net-overview)

- [Reading - Reference: U-Net](https://arxiv.org/pdf/1505.04597)

- [Video - U-Net Code: Encoder](https://www.coursera.org/learn/advanced-computer-vision-with-tensorflow/lecture/AvjPI/u-net-code-encoder)

- [Video - U-Net Code: Decoder](https://www.coursera.org/learn/advanced-computer-vision-with-tensorflow/lecture/U24Rr/u-net-code-decoder)

- [Lab - Implement a UNet](./Labs/C3_W3_Lab_2_OxfordPets_UNet.ipynb)

## Instance Segmentation

- [Video - Instance Segmentation](https://www.coursera.org/learn/advanced-computer-vision-with-tensorflow/lecture/rQMB2/instance-segmentation)

- [Lab - Instance Segmentation Demo](./Labs/C3_W3_Lab_3_Mask_RCNN_ImageSegmentation.ipynb)

## Lecture Notes (Optional)

- [Reading - Lecture Notes Week 3](./Readings/C3_W3.pdf)

## Assignment: Image Segmentation of Handwritten Digits

- [Lab - Image Segmentation of Handwritten Digits](./Labs/C3W3_Assignment.ipynb)
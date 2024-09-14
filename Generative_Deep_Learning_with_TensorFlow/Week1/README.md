# Week 1: Style Transfer

This week, you will learn how to extract the content of an image (such as a swan), and the style of a painting (such as cubist, or impressionist), and combine the content and style into a new image. This is called neural style transfer, and you'll learn how to extract these kinds of features using transfer learning.

## Learning Objectives

- Describe the ways total variation loss ensures spatial continuity and smoothness
- Explore the benefits of fast neural style transfer compared to traditional DCNN
- Define Style Transfer
- Gain intuition about the Gram Matrix
- Describe the steps required to calculate loss

## Style Transfer Intro

- [Video - Welcome to Course 4](https://www.coursera.org/learn/generative-deep-learning-with-tensorflow/lecture/iVy5I/welcome-to-course-4)

- [Video - Style Transfer Intro](https://www.coursera.org/learn/generative-deep-learning-with-tensorflow/lecture/TBxWP/style-transfer-intro)

- [Reading - Reference: A Neural Algorithm of Artistic Style](https://arxiv.org/pdf/1508.06576)

- [Video - Style Transfer Conceptual Overview](https://www.coursera.org/learn/generative-deep-learning-with-tensorflow/lecture/5ffVL/style-transfer-conceptual-overview)

- [Reading - Reference: Perceptual Losses for Real-Time Style Transfer and Super-Resolution](https://cs.stanford.edu/people/jcjohns/papers/eccv16/JohnsonECCV16.pdf)

- [Video - Pre-Processing Inputs](https://www.coursera.org/learn/generative-deep-learning-with-tensorflow/lecture/Z78Sq/pre-processing-inputs)

- [Video - Extracting Style and Content Features](https://www.coursera.org/learn/generative-deep-learning-with-tensorflow/lecture/5GUTE/extracting-style-and-content-features)

- [Reading - Reference: Visualizing and Understanding Convolutional Networks](https://arxiv.org/pdf/1311.2901.pdf)

- [Video - Total Loss and Content Loss](https://www.coursera.org/learn/generative-deep-learning-with-tensorflow/lecture/LjM89/total-loss-and-content-loss)

- [Video - Style Loss](https://www.coursera.org/learn/generative-deep-learning-with-tensorflow/lecture/l9bTa/style-loss)

- [Reading - Reference: numpy.einsum](https://numpy.org/doc/stable/reference/generated/numpy.einsum.html)

- [Video - Update the Generated Image](https://www.coursera.org/learn/generative-deep-learning-with-tensorflow/lecture/kkImO/update-the-generated-image)

- [Video - Optional - Gram Matrix](https://www.coursera.org/learn/generative-deep-learning-with-tensorflow/lecture/9aJH0/optional-gram-matrix)

- [Video - Optional - Einstein Notation](https://www.coursera.org/learn/generative-deep-learning-with-tensorflow/lecture/FzkRh/optional-einstein-notation)

- [Video - Optional - Einsum in Code](https://www.coursera.org/learn/generative-deep-learning-with-tensorflow/lecture/uSmqm/optional-einsum-in-code)

- [Lab - Neural Style Transfer](./Labs/C4_W1_Lab_1_Neural_Style_Transfer.ipynb)

## Total Variation Loss

- [Video - Total Variation Loss](https://www.coursera.org/learn/generative-deep-learning-with-tensorflow/lecture/yVXmc/total-variation-loss)

- [Lab - Neural Style Transfer Part 2](./Labs/C4_W1_Lab_1_Neural_Style_Transfer.ipynb)

## Fast Neural Style Transfer

- [Video - Fast Neural Style Transfer](https://www.coursera.org/learn/generative-deep-learning-with-tensorflow/lecture/PT9Ax/fast-neural-style-transfer)

- [Reading - Reference: Exploring the structure of a real-time, arbitrary neural artistic stylization network](https://arxiv.org/pdf/1705.06830.pdf)

- [Lab - Fast Neural Style Transfer](./Labs/C4_W1_Lab_2_Fast_NST.ipynb)

## Lecture Notes (Optional)

- [Reading - Lecture Notes Week 1](./Readings/C4_W1.pdf)

## Assignment: Style Transfer

- [Lab - Style Transfer Dog](./Labs/C4W1_Assignment.ipynb)
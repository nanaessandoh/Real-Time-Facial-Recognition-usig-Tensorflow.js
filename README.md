# Real Time Facial Recognition using Face-api

# Description
Implementation of a real-time face-detector on the client-side (In the Browser) using Face-api which is built on top of tensorflow.js core API.

# Reason For Faster Inference Time
MTCNN (Multi-task Cascaded Convolutional Neural Networks) is an algorithm consisting of 3 stages, which detects the bounding boxes of faces in an image along with their 5 Point Face Landmarks. Each stage gradually improves the detection results by passing it’s inputs through a CNN, which returns candidate bounding boxes with their scores, followed by non max suppression.

# Demos

**Live Demo:** 
https://nanaessandoh.github.io/index.html


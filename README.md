# VGG-16-CNN

![VGG16_VGG19](https://user-images.githubusercontent.com/59202700/207290642-11cf4b31-c8d4-4d65-a17f-1f03477e12ba.jpeg)

- The VGG type of CNN was designed by the `Visual Geometry Group` at Oxford.
- In 2014 contest it took the first place on the "Image Location" task, and the second place on "Image Classification" task.
- VGG is considered the `Father` of formalizing a design pattern based on groups of convolutions.

_______________________________________________________________________________________________________________________________________________
_______________________________________________________________________________________________________________________________________________

### The fundamental principles behind the VGG design pattern are as follows:
- Grouping multiple convolutions into blocks, with the same number of filters.
- Progressively doubling the number of filters across blocks.
- Delaying pooling to the end of a block.
_______________________________________________________________________________________________________________________________________________
_______________________________________________________________________________________________________________________________________________

The best-known versions are the `VGG16` and `VGG19`. As they have been frequently used in transfer learning, others have kept the convolutional frontend of an ImageNet pretrained VGG16 or VGG19, and corresponding weights, and attached a new DNN backend for retraining for new classes of images.

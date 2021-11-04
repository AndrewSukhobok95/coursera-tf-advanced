# coursera-tf-advanced

Code and solutions from [TensorFlow: Advanced Techniques](https://www.coursera.org/specializations/tensorflow-advanced-techniques) Coursera specialisation


## Content

* [Custom Models, Layers, and Loss Functions with TensorFlow](./course_1/)
  * [Week 1](./course_1/week_1/)
    - Review Sequential API and compare with Functional API
    - Describe new model types that you can build with Functional API
    - Functional API: define input, layers, and model
    - Use Functional API to build a model
    - Use Functional API to create a model that produces multiple outputs
    - Use Functional API to build a Siamese network
  * [Week 2](./course_1/week_2/)
    - Describe when you need to build a custom loss function
    - Implement Huber Loss with a custom loss function
    - Add an adjustable hyper parameter to custom loss using a wrapper function
    - Define a custom loss using an object oriented class
    - Implement contrastive loss function used in a Siamese network
  * [Week 3](./course_1/week_3/)
    - Define a custom layer to include the activation function
    - Define a custom layer class by inheriting from the Layer class
    - Describe the two components of a custom layer
    - Describe what a custom layer can do that a lambda layer cannot
    - Use a lambda layer to customize a network layer
  * [Week 4](./course_1/week_4/)
    - Explain some benefits to defining a custom model class instead of using the Functional or Sequential APIs
    - Define a model by creating a Python class that inherits from TensorFlow's Model class
    - Describe functions that can be inherited from the TensorFlow Model class
    - Build a residual network by defining a custom model class
  * [Week 5](./course_1/week_5/)
    - Describe tasks that callbacks can do while a model is training
    - Create a callback and assign it to a model's training
    - Use a ModelCheckpoint object to save model parameters during training
    - Use the EarlyStopping callback to keep a model from overfitting
    - Describe an example where you may want to create a custom callback
    - Implement a custom callback to detect overfitting
* [Custom and Distributed Training with TensorFlow](./course_2/)
  * [Week 1](./course_2/week_1/)
    - Use various TensorFlow functions to create tensor objects
    - Describe the difference between graph-based execution and eager execution in TensorFlow
    - Use TensorFlow’s GradientTape to calculate derivatives of loss functions
  * [Week 2](./course_2/week_2/)
    - Define the steps in a custom training loop
    - Implement custom training loops using GradientTape
    - Implement a custom training loop with data from TensorFlow Datasets
  * [Week 3](./course_2/week_3/)
    - Describe when graph mode code is preferred over eager mode code
    - Use decorators and tf.autograph to convert code into graph based code
  * [Week 4](./course_2/week_4/)
    - Explain how distributed training is different from regular model training
    - Use the Mirrored Strategy to train a model on multiple GPUs on the same device
    - Use the TPU Strategy to train on multiple cores of a TPU
* [Advanced Computer Vision with TensorFlow](./course_3/)
  * [Week 1](./course_3/week_1/)
    - Distinguish between object localization and object detection
    - Distinguish between object detection and image segmentation
    - Distinguish between semantic segmentation and instance segmentation
    - Explain what is transfer learning and why it's used
    - Describe design options when using transfer learning
    - Implement object localization with a CNN
    - Implement an image classifier with transfer learning
  * [Week 2](./course_3/week_2/)
    - Get a conceptual overview of Regional CNN (R-CNN), Fast-RCNN, and Faster R-CNN.
    - Retrieve the R-CNN model from TensorFlow hub and use it to perform object detection.
    - Use TensorFlow’s object detection API to visualize the predicted bounding boxes from an object detection model
    - Go beyond models in TensorFlow Hub: Load and configure a Resnet-50 model that isn’t on TensorFlow Hub, restore pre-trained weights, and select the parts of the model to retrain.
    - Use the object detection API to manually annotate images for object detection
    - Implement a custom training loop to fine-tune a model using just 5 training examples.
  * [Week 3](./course_3/week_3/)
    - Describe the conceptual design of fully convolutional neural networks and subsequent models based on it
    - Describe the decoder section of the fully convolutional neural network
    - Describe two methods of upsampling: simple scaling and transposed convolutions
    - Build the encoder and decoder sections of a fully convolutional neural network
    - Evaluate a segmentation model’s performance using intersection-over-union and Dice score
    - Describe the conceptual design of the U-Net model
    - Build a U-Net model for image segmentation
    - Use the Mask R-CNN to perform instance segmentation
  * [Week 4](./course_3/week_4/)
    - Explain why model interpretation is important
    - Calculate class activation maps to visualize the parts of the image that a model uses to make its predictions.
    - Calculate saliency maps to visualize the parts of the image that a model uses to make its predictions.
    - Implement Gradient-weighted Class Activation Mapping (GradCAM) to identify parts of the image that are important in a model’s predictions.
    - Describe how visualization can help to improve a model’s design

# Adversarial

The task was to add adversarial noise to trick the image classification model into misclassifying the altered image.

A pre trained image classification model resnet 50 from torchvision was used.

Fast Gradient Sign Method (FGSM) developed by Ian Goodfellow et al.(2014) was used to add the adversarial noise to the input image.

AdversarialNoiseToTargetClass: adds adversarial noise using a iterative FGSM technique to trick an image classification model into misclassifying it to a specified target class.

# object-identifier
Final course project of CS 480, achieved ~80% test accuracy for 22 image classes, each with 5 training samples.

## Mechanism

Used pretrained resnet.

- I tried both fine-tuning the entire model with a lower learn rate AND fix the parameters of the model and replace the last layer. The former achieved better results in this case.
- Lots of careful image augmentations due to severe lack of training samples.


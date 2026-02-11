# DeepLearningExamples
Examples codes for different architectures

The Variational Autoencoder Jupyter notebook is not ready yet. I am currently implementing it in TensorFlow.
The multi-input Jupyter notebook combines image data with tabular features.
The pretrained image recognition notebook compares Transformer-based models and CNN architectures. In addition, we use a weighted loss function to address class imbalance. The Transformer appears to be significantly more flexible when classifying the images without extensive transfer learning, compared to the CNN.
Scientifically, for this example:
As very preliminary results for the GRB environment analysis, the Transformer achieves 91% accuracy after just one epoch, which is unexpectedly high. In contrast, the CNN shows a more gradual improvement in classification performance over successive epochs.
I still need to carefully validate these results. As an initial step, I plan to change the input images, since the current ones from the Legacy Survey are not very homogeneous.
I intend to use 2MASS images instead. Although they are less deep, they are more homogeneous than combining the three Legacy Survey filters. 


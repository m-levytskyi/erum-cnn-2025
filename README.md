# Convolutional Neural Networks

Materials and exercises for the CNN lecture at the ErUM deep learning school "Basic Concepts" 2025.
The exercises were created by Cedric Ewen for the 2023 "Basic Concepts" school.

You can find materials from the previous courses on CNNs in the [ErUM DataHub wiki](https://wiki.erumdatahub.de/bin/view/Material%20collection/#|t=materials&p=1&l=25&s=date&d=desc&doc.location=convolutional+neural+networks).

## Exercises

You can solve the exercises either on your own laptop or in Google Colab. The first exercise only
uses a very small network, so it is fast to train even on a CPU. For the second exercise, using a
GPU is recommended.

Run exercises in Google Colab:
- Exercise 1: [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/theoheimel/erum-cnn-2025/blob/main/CNN_Exercise_1.ipynb)
- Exercise 2: [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/theoheimel/erum-cnn-2025/blob/main/CNN_Exercise_2.ipynb)

To solve the exercises in Google Colab, click the _Copy to drive_ button and remember to change
your runtime type to GPU under _Runtime > Change runtime type_.

Clone exercises and run locally:
```
git clone https://github.com/theoheimel/erum-cnn-2025.git
```
If you run the exercises locally, make sure you have all the dependencies installed:
```
pip install -r requirements.txt
```

## Extra materials

You can find the slides for the lecture in the file `slides.pdf`. Here are some links to some nice
visualizations of convolutions and CNNs:
- [Animated convolutions of functions](https://dspillustrations.com/pages/posts/misc/convolution-examples-and-the-convolution-integral.html)
- [Interactive discrete convolutions](https://ezyang.github.io/convolution-visualizer/)
- [Interactive CNN in 3d](https://adamharley.com/nn_vis/cnn/3d.html)

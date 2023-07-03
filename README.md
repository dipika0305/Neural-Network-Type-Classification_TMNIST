## Neural-Network-Type-Classification_TMNIST

### Abstract

This dataset is inspired by the MNIST database for handwritten digits of the following 94 alphabetic characters:

{'0', '1', '2', '3', '4', '5', '6', '7', '8', '9', 'a', 'b', 'c', 'd', 'e', 'f', 'g', 'h', 'i', 'j', 'k', 'l', 'm', 'n', 'o', 'p', 'q', 'r', 's', 't', 'u', 'v', 'w', 'x', 'y', 'z', 'A', 'B', 'C', 'D', 'E', 'F', 'G', 'H', 'I', 'J', 'K', 'L', 'M', 'N', 'O', 'P', 'Q', 'R', 'S', 'T', 'U', 'V', 'W', 'X', 'Y', 'Z', '!', '"', '#', '$', '%', '&', "'", '(', ')', '*', '+', ',', '-', '.', '/', ':', ';', '<', '=', '>', '?', '@', '[', '', ']', '^', '_', '`', '{', '|', '}', '~'}

The structure of the csv file is:

- The first row contains column headers ['names', 'labels','1','2',…..'784']
- The 'names' column contains font file names such as 'Acme-Regular' and 'ZillaSlab-Bold'
- The 'labels' column contains characters such as '@','E' or '+'
- The remaining 784 columns contain the grayscale pixel values for the image of the corresponding character in the 'name' font-style
- This dataset contains over 281,000 images and is part of the Warhol.ai Computational Creativity and Cognitive Type projects.

### Aim

The objective of this notebook is to classify the images from TMNIST dataset using a Convolutional Neural Network.

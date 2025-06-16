# Image Colorization with Deep Learning (colornet)

This project uses an autoencoder model to colorize grayscale images by predicting the color channels from the lightness channel in the Lab color space.

The model takes a grayscale image (L channel) as input and outputs the two color channels (a and b), which are combined to reconstruct a color image.

You can train the model, visualize results, and evaluate on real grayscale images using the provided scripts.
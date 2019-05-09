# HO-GAN

A vanilla GAN for images of a single in-class. The GAN runs with a data set consisting of 28x28 images of one of the following classes:

- solidcolor  : entirely solid black
- simpleshape : a black-bordered square with white background, rotated and translated randomly
- reflection  : a series of black-filled rectangles from left-to-right against a white background, where the image reflects over the middle horizontal
- matching    : two black-filled shapes against a white background, where the shapes are congruent up to translation and rotation.

My goal is to test both the GAN's performance at classifying and generating images of each of these classes.

_Note_: Due to my lack of time and compute-power, I only train this GAN with 1000 example images for each class with batches of32 and 1000 iterations.


# Neural Style Transfer : Generating art using Deep Learning
## Programatically painting an image following the style of another image using Neural Style Transfer algorithm
This is an implementation of Neural Style Transfer algorithm using Tensorflow. The NST algorithm was created by Leon A. Gatys, Alexander S. Ecker and Matthias Bethge, as described in the famous paper [A Neural Algorithm of Artistic Style](https://arxiv.org/abs/1508.06576).

The idea is to use the filter responses from different layers of a convolutional network to build the style. Filter responses from different layers (ranging from lower to higher) captures from low level details (strokes, points, corners) to high level details (patterns, objects, etc) which can be used to modify the content image, which gives the final "painted" image.

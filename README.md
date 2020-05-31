### Deep Learning & Art: Neural Style Transfer
* Implementing the neural style transfer algorithm and
* Generate novel artistic images

Neural Style Transfer (NST) is one of the most fun techniques in deep learning. It merges two images, namely: a "content" image (C) and a "style" image (S), to create a "generated" image (G).

The generated image G combines the "content" of the image C with the "style" of image S.

Using VGG-19, a 19-layer version of the VGG network. 

This model has already been trained on the very large ImageNet database, and thus has learned to recognize a variety of low level features (at the shallower layers) and high level features (at the deeper layers).

## Flow of Neural Style Transfer Algorithm:

<img src="NST.png" alt="Neural Style Transfer Algorithm" style="width:400px;height:400px;">

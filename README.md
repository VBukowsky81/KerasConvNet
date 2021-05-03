# KerasConvNet
Keras CNN - simple classifier

![alt text](https://github.com/VBukowsky81/KerasConvNet/blob/main/KerasCNNPic.jpg)

Convolutional Neural Networks or CNN's.

There is so much to say about CNN's, where does one start? First of all else - neural networks in general attempt to replicate biological brain activities and functionalities. And CNN's, in particular, attempt to emulate biological vision - like in animals, and humans.

In super super short format, the main idea is this - detecting patterns, on flat surfaces:

![alt text](https://github.com/VBukowsky81/KerasConvNet/blob/main/DigitalSmile.jpg)

This is very much what biological vision does, in humans and animals - we detect objects, detect edges, and shadows, classify those objects, and then process a response. All that at great speed in our brains, so quickly that we don't notice these steps happening. And it all seems seamless.

So let me quickly break down how CNN's work, for developers. CNN's start off with filtering images - feature filter is applied to images, it's usually sized like 3x3 or 2x2 dimensions. Once filters are done with it - what you really have is features, and feature maps, of the original image - and this is what goes into the linear layers afterwards - features. Not just pixels, but entire FEATURES. So linear ANN after the filters is learning off FEATURES, not pixels.

So anyway, once convolution/filtering layers are done processing image - feature maps then get passed into forward-feed NN. And this is where learning is taking place.

This example is laughably simple, and anecdotal - it's a dog/cat classifier. But it shows all the imporant parts of CNN's right there, in a super simple format. This is why I keep such foundation templates for myself.

Anyway, after we get feature maps, standard linear modeling continues, just like any other classification task.

So let's quickly go over this example code.








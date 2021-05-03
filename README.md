# KerasConvNet
Keras CNN - simple classifier

![alt text](https://github.com/VBukowsky81/KerasConvNet/blob/main/KerasCNNPic.jpg)

Convolutional Neural Networks or CNN's.

There is so much to say about CNN's, where does one start? First of all else - neural networks in general attempt to replicate biological brain activities and functionalities. And CNN's, in particular, attempt to emulate biological vision - like in animals, and humans.

In super super short format, the main idea is this - detecting patterns, on flat surfaces:

![alt text](https://github.com/VBukowsky81/KerasConvNet/blob/main/DigitalSmile.jpg)

This is very much what biological vision does, in humans and animals - we detect objects, detect edges, and shadows, classify those objects, and then process a response. All that at great speed in our brains, so quickly that we don't notice these steps happening. And it all seems seamless.

So let me quickly break down how CNN's work, for developers. CNN's start off with filtering images - feature filter is applied to images, it's usually sized like 3x3 or 2x2 dimensions. Once convolutions/filters are done with it - what you really have is features, and feature maps, of the original image - and this is what goes into the linear layers afterwards - features. Not just pixels, but entire FEATURES. So linear ANN after the filters is learning off FEATURES, not individual pixels.

So anyway, once convolution/filtering layers are done processing image - feature maps then get passed into forward-feed NN. And this is where learning is taking place.

This example is laughably simple, and anecdotal - it's a dog/cat classifier. But it shows all the imporant parts of CNN's right there, in a super simple format. This is why I keep such foundation templates for myself.

Anyway, after we get feature maps, standard linear modeling continues, just like any other classification task.

So let's quickly go over this example code.

First, standard data preprocessing, just getting image dataset, this time it's 8000 images(4k each of labeled cats and dogs). Breaking it down into training and test datasets, batch sizes, etc, all the usual data preprocessing for ANN consumption. I did not include the dataset - it's too big, and GitHub doesn't accept larger file uploads. You can find your own, any dataset would do, ya know.

Next, building the CNN itself, as you can see, Convolution layers and Filtering layers are present - and these do what I said above - get feature maps, out of images. As you can see, this example repeats Conv/Filter twice. This further brings forward imporant and main features - another filtering layer just condenses main features even more.

Then linear layers do actual classification, and build weights, according to appropriate visual patterns, fed to it through given dataset.

After all that - the model will be able to classify between 2 given categories(dog/cat this time). In short, it will be able to tell you if it's a cat or a dog, on any given picture.

This classification can be done on any number of categories, not just 2.

And this is in short, how CNN's learn off visual images, and then learn to classify things, and express intelligent behavior.

Very simple example, but tremendous implications. So, so much can be done with this technology/idea. Robots that actually see our physical world, and fully comprehend it - is one thing that comes to mind. Amazing technology, and incredible field in general.

Good day!

Victor







# Augmenting data of an npz file
This is a script to augment your dataset, contained in a npz file.

It performs some random transformations over the original and creates a new npz file that concatenates the original and the augmented dataset.

I applied two transformations randomly but you can try as many as you like and what would make sense for your data. And use it in your data loader.

I used the data from the [Kuzushiji-49](https://github.com/rois-codh/kmnist) dataset.

**IMPORTANT:** Be careful with the size of the end file, in my case, it was way bigger than expected.


## SqueezeNet

### Data Augmentation


### Transfer learning



* Applied average pooling for the logits

* The first advantage is the global average pooling is more **native** to the CNN structure, by obtaining logits via channels rather than converting the data to flattened vectors.

* global average pooling is just a pooling layer, it uses no parameters. This means there is no risk of overfitting at the global average pooling layers.

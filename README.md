# google-image-dataset.torch
Dataset of images provided by Google Image

# features
* All features of `torch.utils.data.Dataset`
* Local storage control, since we really don't want that bottleneck comes from the network traffic.
* Image preprocessing.

# Qucick start

All you have to do is provide a list of keywords and run `main.py`, the trainer will search these keywords on Google Image, download them and train the network.

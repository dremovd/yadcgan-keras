# yadcgan-keras
Yet Another DCGAN for keras

The aim of DCGAN model is to be able to produce images that would be similar to the train set.

Dataset consists of ~100000 RGB images of size 48x48 from old games. Mainly images are of characters and objects. Images are at original scale. Dataset was extracted from http://spritedatabase.net/ and published with explicit permit of Paul, Sprite Database owner

# Requirements:
- keras with theano
- opencv3, for saving files
- joblib, to load image dump of big size
- matplotlib, for debug output
- GPU card for reasonable training speed 

# Examples:
![After ~5 hours of training](/example-early.png?raw=true "After ~5 hours of training")
![After ~16 hours of training](/example-16h.png?raw=true "After ~16 hours of training")

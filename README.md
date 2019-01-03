# multi-resolution-texture-synthesis
Based on “Fast Texture Synthesis using Tree-structured Vector Quantization” and “Multiresolution Sampling Procedure for Analysis and Synthesis of Texture Images” papers

![](TextureSynthesis_6.gif)

Here are the libraries and their versions you will need:
* Python 3.7
* Jupyter Notebook (5.6.0)
* Numpy (is 1.15.1)
* Matplotlib (2.2.3)
* Scipy (1.1.0)
* Skimage (0.14.0)
* scikit-learn (0.19.2)
* imageio (2.4.1)
* PIL (5.2.0)
* json (2.6.0)

To start, open the Jupyter Notebook file "Multi-resolution Texture Synthesis", and follow the instructions :) 

### Interested in contributing?

Here are some potentially interesting alterations/experiments one could do :3
* with laplacian pyramid, there is an element of 'memorylessness' as the parent map doesn't have full information from its own parents. What if we query not just our parent, but a sum of _all_ previous parents?
* can be potentially used for "super-resolution", where you enlarge an image based on some other example's details

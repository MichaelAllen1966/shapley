# An introduction to Shapley Values for interpreting machine learning algorithms.

Shapley values give the contribution of each feature in an example of interest to the model prediction.

## Running the notebooks
It is recommended, if not running locally on a machine with a GPU, that you use the link to Google Colab below, select the notebook, and change runtime to GPU in Colab.

[![Open In Collab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/MichaelAllen1966/shapley)

The notebooks may also be from Binder, but start-up time may be slow, and the image analysis part of the notebook will be signficantly slower than Colab.

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/MichaelAllen1966/shapley/main)

Environment `yml` files are provided in the `binder` folder. Use `environment.yml` when no GPU is available, and `environment_gpu.yml` when a GPU is available. Instructions are given in the Binder folder.

## Other resources

I thoroughly recommend this YouTube video from 'Machine Learning Dojo with Tim Scarfe':
https://youtu.be/jhopjN08lTM

Christopher Molner has an excellent online book with details on Shapley values:
https://christophm.github.io/interpretable-ml-book/shapley.html

There is also a good interview with Chris Molner on YouTube in machine Learning Street Talk: https://youtu.be/0LIACHcxpHU

Documentation for the SHAP library: https://shap.readthedocs.io/en/latest/index.html

Talk on the SHAP library by Scott Lunberg, a key author of the SHAP library: https://youtu.be/B-c8tIgchu0

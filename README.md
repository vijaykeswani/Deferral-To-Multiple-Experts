## Joint learning framework for deferral to multiple experts

This folder contains code for the joint learning framework for simultaneously learning a classifier and a deferrer. The complete model and analysis are presented in the following paper:

**Towards Unbiased and Accurate Deferral to Multiple Experts**\n
*Vijay Keswani, Matthew Lease, Krishnaram Kenthapadi*

https://arxiv.org/abs/2102.13004

The files in this folder can be used for implementing the framework
and replicating the results in the paper. The file description are provided below:

- multiple_experts_abusive_speech: This is the main file with the primary
code for the joint learning framework and its variants. This notebook 
works with the abusive speech dataset and synthetic experts primarily,
with code for plotting and replication provided in the notebook itself.

- hatespeech_defer.ipynb: This is the notebook from the paper on
learning-to-defer in ICML 20 - https://github.com/clinicalml/learn-to-defer.
We use this code only to obtain the preprocessed abusive speech dataset
from Davidson et al (https://github.com/t-davidson/hate-speech-and-offensive-language/).

- all_results.npy: Dataset containing decisions from crowdannotators for
the hate-speech labelling task described in the paper.

- twitteraae_models: Add AAE prediction models from http://slanglab.cs.umass.edu/TwitterAAE/
See hatespeech_defer.ipynb for more details.

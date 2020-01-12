# Deep Learning Class Project

*Posted with permission from instructor.*

**Authors/Creators:** Matthew Liechty, Ali Obaidi Ali, and Soren Nelson

This project attempts a relatively new idea we refer to as "scene extension". It uses neural networks to make a shorter image wider by generating a plausible extension to the scene.

The write up for this project and its results can be viewed [here](project_paper.pdf).

The `.ipynb` notebooks used to create these models are included in the root directory. The models were trained on Google Colab GPUs. The notebook [GAN_loss_CNN.ipynb](GAN_loss_CNN.ipynb) shows the training and setup for a convolutional neural network using GAN and L1 loss. The notebook [L1_loss_CNN.ipynb](L1_loss_CNN.ipynb) shows the same network trained only using L1 loss. The notebook [results_generation.ipynb](results_generation.ipynb) was used to generate example outputs for the [project paper](project_paper.pdf)


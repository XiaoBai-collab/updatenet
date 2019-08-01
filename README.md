## Learning the Model Update for Siamese Trackers [[paper]](https://arxiv.org/pdf/1806.01013.pdf)

## Instructions
This project is to replace the handcrafted update function with a method which learns to update. We use a convolutional neural network, called UpdateNet, which given the initial template, the accumulated template and the template of the current frame aims to estimate the optimal template for the next frame. The UpdateNet is compact and can easily be integrated into existing Siamese trackers.


## Analysis for RGB and TIR
<br>
<p align="center">
  <img width="80%" height='80%'src="fig3_reb.png" />
</p>
<p align="center">
  <em>Visualization accumulated and ground-truth templates for SiamFC.</em>
</p>


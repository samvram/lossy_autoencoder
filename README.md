# Lossy image autoencoders

This implementation has been done for course completion of **AV494 - Deep Learning for Computational Data Sciences** at **Indian Institute
of Space Science and Technology**. Course instructor : **Dr. Deepak Mishra**.

Referrence from : https://www.bonaccorso.eu/2017/07/29/lossy-image-autoencoders-convolution-deconvolution-networks-tensorflow/<br/>

## Requirements
<ul>
<li>Python 2.7-3.5</li>
<li>Tensorflow</li>
<li>Keras</li>
<li>SciPy</li>
<li>Scikit-Image</li>
<li>Numba (optional)</li>
</ul>

## Example with CIFAR-10 dataset
(Trained with CIFAR-10 dataset (with 50000 samples) and a code length equal to 128)
<table width="100%" align="center">
<tr>
<td width="auto">
<p align="center">
<img src="https://s3-us-west-2.amazonaws.com/lossy-image-autoencoder/ae_cifar.jpg" align="center" width="900">
</p>
<p align="center">First row: original images, second row: lossy reconstructions</p>
</td>
</tr>
</table>

## Possible improvements
Possible improvements include:<br/>
<ul>
<li>Adding a flag (using a placeholder) to use the model for both training and prediction. In the former mode, the input is an image batch, while in the latter is a code batch</li>
<li>Using L1 (and/or L2) code regularization</li>
</ul>

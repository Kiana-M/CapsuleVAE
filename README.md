# disentanglement_lib
![Sample visualization](https://github.com/google-research/disentanglement_lib/blob/master/sample.gif?raw=true)

**disentanglement_lib** is an open-source library for research on learning disentangled representation.
It supports a variety of different models, metrics and data sets:

* *Models*: BetaVAE, FactorVAE, BetaTCVAE, DIP-VAE
* *Metrics*: BetaVAE score, FactorVAE score, Mutual Information Gap, SAP score, DCI, MCE, IRS, UDR
* *Data sets*: dSprites, Color/Noisy/Scream-dSprites, SmallNORB, Cars3D, and Shapes3D
* It also includes 10'800 pretrained disentanglement models (see below for details).

# CapsuleVAE

**CapsuleVAE** is an experimental architecture that aims to improve the disentanglement of latent variables in variational autoencoders with the help of ![capsule networks](https://proceedings.neurips.cc/paper_files/paper/2017/file/2cad8fa47bbef282badbb8de5374b894-Paper.pdf), proposed by Hinton et al.


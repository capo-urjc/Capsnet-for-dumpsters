# Capsule Network #
[![License](https://img.shields.io/github/license/mashape/apistatus.svg?maxAge=2592000)](LICENSE)

#### PyTorch implementation of the following paper:
* [_Dynamic Routing Between Capsules_](https://arxiv.org/abs/1710.09829) by Sara Sabour, Nicholas Frosst and Geoffrey Hinton

### Run the experiment
* For details, run `python main.py -e 100 -bs 32 --lr_decay 0.99 --data_path train7`

______

### Requirements:
* PyTorch (http://www.pytorch.org)
* NumPy (http://www.numpy.org/)
* GPU

______

### Abstract

Garbage management is an essential task in the everyday life of a city. In many countries, dumpsters are owned and deployed by the public administration. An updated what-and-where list is in the core of the decision making process when it comes to remove or renew them as well as it may give extra information to other analytics in a smart city context. In this paper we present a Capsule Network that attains a 95.35% of accuracy in recognition over the largest dataset of dumpsters available nowadays.

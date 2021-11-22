# Oscar: Object-Semantics Aligned Pre-training for Vision-and-Language Tasks    


## Introduction
This repository contains source code necessary to reproduce the results presented in the paper [Oscar: Object-Semantics Aligned Pre-training for Vision-Language Tasks](https://arxiv.org/abs/2004.06165).
We propose a new cross-modal pre-training method **Oscar** (Object-Semantics Aligned Pre-training). It leverages **object tags** detected in images as anchor points to significantly ease the learning of image-text alignments. We pre-train Oscar on the public corpus of 6.5 million text-image pairs, and fine-tune it on downstream tasks, creating new state-of-the-arts on six well-established vision-language understanding and generation tasks. For more on this project, see the [Microsoft Research Blog post](https://www.microsoft.com/en-us/research/blog/objects-are-the-secret-key-to-revealing-the-world-between-vision-and-language/).


<img src="docs/oscar.PNG" width="650"> 

## Download
We released pre-trained models, datasets, VinVL image features, and Oscar+ pretraining corpus for downstream tasks. 
Please check [VinVL_DOWNLOAD.md](VinVL_DOWNLOAD.md) for details. 

To download checkpoints for the Vanilla OSCAR, please check [DOWNLOAD.md](DOWNLOAD.md) for details. 

## Installation
Check [INSTALL.md](INSTALL.md) for installation instructions.

## Model Zoo
Check [MODEL_ZOO.md](MODEL_ZOO.md) for scripts to run oscar downstream finetuning.

Check [VinVL_MODEL_ZOO.md](VinVL_MODEL_ZOO.md) for scripts to run oscar+ pretraining and downstream finetuning.



## License
Oscar is released under the MIT license. See [LICENSE](LICENSE) for details. 


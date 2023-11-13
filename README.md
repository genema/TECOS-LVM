<img src="https://github.com/genema/Noisy-Spiking-Neuron-Nets/raw/master/proj_logo.jpg" width="200px" align="left">

# [NeurIPS 2023] TeCoS-LVM

![Python](https://img.shields.io/badge/Python-3.8.16-brightgreen)

![PyTorch](https://img.shields.io/badge/PyTorch-1.12.1-brightgreen)

![PROJASGARD](https://img.shields.io/badge/Project-ASGARD-orange)

**Te**mporal **Co**nditioning **S**piking **L**atent **V**ariable **M**odels of the Neural Response to Natural Visual Scenes
- **Update 23-9-22** 🎉: Accepted at [NeurIPS 2023](https://neurips.cc/virtual/2023/poster/71480).


## Summary
Developing computational models of neural response is crucial for understand- ing sensory processing and neural computations. Current state-of-the-art neural network methods use temporal filters to handle temporal dependencies, resulting in an unrealistic and inflexible processing paradigm. Meanwhile, these methods target trial-averaged firing rates and fail to capture important features in spike trains. This work presents the temporal conditioning spiking latent variable models (*TeCoS-LVM*) to simulate the neural response to natural visual stimuli. We use spiking neurons to produce spike outputs that directly match the recorded trains. This approach helps to avoid losing information embedded in the original spike trains. We exclude the temporal dimension from the model parameter space and in- troduce a temporal conditioning operation to allow the model to adaptively explore and exploit temporal dependencies in stimuli sequences in a natural paradigm. We show that *TeCoS-LVM* models can produce more realistic spike activities and accurately fit spike statistics than powerful alternatives. Additionally, learned *TeCoS-LVM* models can generalize well to longer time scales. Overall, while remaining computationally tractable, our model effectively captures key features of neural coding systems. It thus provides a useful tool for building accurate predictive computational accounts for various sensory perception circuits.

## Acknowledgement
Special thanks to *Prof. Arno Onken* (Univ. of Edinburgh) for generous help and *Dr. Tao Fang* (Zhejiang Univ.) for helpful discussions.

## Citation info
~A [*preprint version*](https://doi.org/10.48550/arXiv.2306.12045):~

Formal:
```bibtex
@inproceedings{ma2023temporal,
  title={Temporal Conditioning Spiking Latent Variable Models of the Neural Response to Natural Visual Scenes},
  author={Gehua Ma and Runhao Jiang and Rui Yan and Huajin Tang},
  booktitle={Thirty-seventh Conference on Neural Information Processing Systems},
  year={2023},
  url={https://openreview.net/forum?id=V4YeOvsQfu}
}
```

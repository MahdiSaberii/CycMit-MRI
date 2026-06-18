# [ICML'26] Training-Free Adversarial Mitigation for Computational MRI


<p>
  <a href="https://arxiv.org/abs/2501.01908">
    <img src="https://img.shields.io/badge/arXiv-2501.01908-b31b1b.svg">
  </a>
  <a href="https://icml.cc/virtual/2026/poster/64452">
    <img src="https://img.shields.io/badge/ICML-2026-00BFFF">
  </a>
</p>

This repository provides the official implementation of our proposed cyclic mitigation strategy for adversarially robust computational MRI. 

<img src="Results/combined.gif">

## Abstract

Training-free adversarial mitigation is an inference-time defense method for improving the robustness of deep learning MRI reconstruction models without retraining.

The method treats the attacked measurement as an input to be corrected at test time by minimizing a cyclic measurement-consistency objective within a small neighborhood of the corrupted input. This allows the reconstruction to move away from adversarial perturbations while preserving consistency with the acquired k-space data.

Large-scale experiments show that the proposed method substantially reduces adversarial artifacts across datasets, attack types, attack strengths, and reconstruction networks. This repository currently includes the image-domain attack demo, with additional code to be added later.

<p align="center">
  <img src="Results/Method_comparison_1.jpg" width="100%">
</p>

## 📝 BibTeX

```bibtex
@article{saberi2025training,
  title={Training-Free Defense Against Adversarial Attacks in Deep Learning MRI Reconstruction},
  author={Saberi, Mahdi and Zhang, Chi and Ak{\c{c}}akaya, Mehmet},
  journal={arXiv preprint arXiv:2501.01908},
  year={2025}
}
```

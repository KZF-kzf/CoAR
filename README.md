# CoAR
Concept Injection into Autoregressive Models for Personalized Text-to-Image Generation
[![arXiv]([https://img.shields.io/badge/arXiv-2508.07341-b31b1b.svg)](https://arxiv.org/abs/2508.07341](https://arxiv.org/abs/2508.07341))

## 📌 TODO List
- [ ] Subject-driven inference scripts  
- [ ] Subject–style compositional inference scripts  
- [ ] Training scripts  

---

## 🔍 Overview
CoAR is a simple yet effective framework for injecting subject or style concepts into multi-modal autoregressive (AR) models without modifying any pretrained parameters. By leveraging a small set of **layer-wise multi-modal learnable tokens**, CoAR achieves high-quality, efficient customization for both subject-driven personalization and **training-free** subject-style compositional generation.

<p align="center">
  <img src="assets/framework.png" alt="CoAR Framework" width="80%">
</p>

---

## 📊 Qualitative Demo

<p align="center">
  <img src="assets/teaser.png" alt="Qualitative Results" width="80%">
</p>

<p align="center">
  <img src="assets/subject_comp_large.png" alt="Qualitative Results" width="80%">
</p>

<p align="center">
  <img src="assets/style_sample.png" alt="Qualitative Results" width="80%">
</p>

## 📈 Performance Comparison on DreamBench
<p align="center">
  <img src="assets/compare.jpg" alt="Quantitative Results" width="80%">
</p>

---

## 📝 Citation
```bibtex
@misc{wu2025coarconceptinjectionautoregressive,
      title={CoAR: Concept Injection into Autoregressive Models for Personalized Text-to-Image Generation}, 
      author={Fangtai Wu and Mushui Liu and Weijie He and Wanggui He and Hao Jiang and Zhao Wang and Yunlong Yu},
      year={2025},
      eprint={2508.07341},
      archivePrefix={arXiv},
      primaryClass={cs.CV},
      url={https://arxiv.org/abs/2508.07341}, 
}

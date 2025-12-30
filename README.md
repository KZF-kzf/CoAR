# DCoAR
DConcept Injection into Autoregressive Models for Personalized Text-to-Image Generation

[![arXiv](https://img.shields.io/badge/arXiv-2508.07341-b31b1b.svg)](https://arxiv.org/abs/2508.07341 "View paper on arXiv")


## 📌 TODO List
- [ ] Subject-driven inference scripts  
- [ ] Subject–style compositional inference scripts  
- [ ] Training scripts  

---

## 🔍 Overview
DCoAR is a simple yet effective framework for injecting subject or style concepts into multi-modal autoregressive (AR) models without modifying any pretrained parameters. By leveraging a small set of **layer-wise multi-modal learnable tokens**, DCoAR achieves high-quality, efficient customization for both subject-driven personalization and **training-free** subject-style compositional generation.

<p align="center">
  <img src="assets/framework.png" alt="DCoAR Framework" width="80%">
</p>

---

## 📝 Citation
```bibtex
@misc{wu2025coarconceptinjectionautoregressive,
      title={DCoAR: Concept Injection into Autoregressive Models for Personalized Text-to-Image Generation}, 
      author={Fangtai Wu and Mushui Liu and Weijie He and Wanggui He and Hao Jiang and Zhao Wang and Yunlong Yu},
      year={2025},
      eprint={2508.07341},
      archivePrefix={arXiv},
      primaryClass={cs.CV},
      url={https://arxiv.org/abs/2508.07341}, 
}

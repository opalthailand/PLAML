# PLAML

Prompt-Based Label-Aware Framework for Few-Shot Multi-Label Text Classification

This repository contains the code for the paper “[Prompt-Based Label-Aware Framework for Few-Shot Multi-Label Text Classification](https://ieeexplore.ieee.org/document/10440286)”. It includes three Jupyter notebooks, each running experiments on one of the datasets used in the paper. All experiments were executed on Kaggle with an NVIDIA P1000 GPU.

## Notebooks

- `PLAML_english.ipynb`
- `PLAML_philippines.ipynb` 
- `PLAML_thai.ipynb`

## PLAML Process

![PLAML_process](https://github.com/user-attachments/assets/1d247725-7629-41f8-b606-a82e76643832)

> PLAML: a prompt-based learning framework for MLTC comprising three proposed techniques including TS-ILF, LAAV_ML, and dynamic threshold mechanism. Solid lines represent operations within either the training or the inference process, while dashed lines connect the corresponding components between the training and the inference processes.


## Citation

If you use this code, please cite:

```bibtex
@ARTICLE{Thaminkaew2024PLAML,
  author={Thaminkaew, Thanakorn and Lertvittayakumjorn, Piyawat and Vateekul, Peerapon},
  title={Prompt‐Based Label‐Aware Framework for Few‐Shot Multi‐Label Text Classification},
  journal={IEEE Access},
  year={2024},
  volume={12},
  pages={28310-28322},
  doi={10.1109/ACCESS.2024.3367994}
}

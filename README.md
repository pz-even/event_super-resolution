# Neuromorphic Imaging with Super-Resolution

[![doi](https://img.shields.io/badge/Journal-IEEE_TCSVT-blue)](https://doi.org/10.1109/TCSVT.2024.3482436)
[![arXiv](https://img.shields.io/badge/arXiv-PDF-b31b1b)](https://arxiv.org/abs/2407.05764)
[![HKU](https://img.shields.io/badge/HKU-PDF-b31b1b)](https://www.eee.hku.hk/optima/pub/journal/2502_TCSVT.pdf)
![Python](https://img.shields.io/badge/Python-3.11-3776AB)
![PyTorch](https://img.shields.io/badge/PyTorch-2.1-EE4C2C)
![License](https://img.shields.io/badge/License-MIT-green)

```
@article{zhang2025tcsvt,
  title    =  {Neuromorphic Imaging with Super-Resolution},
  author   =  {Pei Zhang and Shuo Zhu and Chutian Wang and Yaping Zhao and Edmund Y. Lam},
  journal  =  {IEEE Transactions on Circuits and Systems for Video Technology},
  volume   =  {35},
  number   =  {2},
  pages    =  {1715--1727},
  month    =  {February},
  year     =  {2025},
  doi      =  {10.1109/TCSVT.2024.3482436},
}
```
![DEMO](./imgs/workflow.png)

![DEMO](./imgs/ex.png)

## Implementation
This repo provides an unoptimized prototype allowing you to make modifications as needed. You can try other networks and learning settings for various scenarios.
1. Prepare your event sample (with `t, x, y, p` entries) in the `data` folder.
2. Run
   ```
   CUDA_VISIBLE_DEVICES=0 python run_task.py
   ```
3. Check the `result` folder for output files.

## Result
3D visualization (x, y, t) is intuitive to verify your result and its distribution:
![DEMO](./imgs/demo.png)

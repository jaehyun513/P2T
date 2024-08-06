# Tabular Transfer Learning via Prompting LLMs

Official implementation of ["Tabular Transfer Learning via Prompting LLMs"](https://openreview.net/forum?id=r77CeOBO0L#all) by [Jaehyun Nam](https://jaehyun513.github.io/), [Woomin Song](https://woominsong.github.io/), [Seong Hyeon Park](https://shpark.org/), [Jihoon Tack](https://jihoontack.github.io/), [Sukmin Yun](https://sites.google.com/view/sukmin-yun), [Jaehyung Kim](https://sites.google.com/view/jaehyungkim), [Kyu Hwan Oh](https://www.linkedin.com/in/oh-kyu-hwan-8a16b9282/), [Jinwoo Shin](https://alinlab.kaist.ac.kr/shin.html).

**TL;DR**: We propose a novel tabular transfer learning framework that leverages LLM's in-context learning capabilities.

<p align="center">
    <img src=figure/concept_figure.png width="700"> 
</p>

## 1. Dependencies
```
conda create -n p2t python=3.8 -y
conda activate p2t

pip install openai==0.28.1
```

## 2. P2T
See `main.ipynb` to run P2T stey by step. We have provided (i) instructions on downloading the dataset from the OpenML repository and (ii) some example indexes in the `/data` folder.

## Citation
```bibtex
@inproceedings{nam2024tabular,
  title={Tabular Transfer Learning via Prompting LLMs},
  author={Jaehyun Nam and and Woomin Song and Seong Hyeon Park and Jihoon Tack and Sukmin Yun and Jaehyung Kim and Kyu Hwan Oh and Jinwoo Shin},
  booktitle={Conference on Language Modeling},
  year={2024}
}
```

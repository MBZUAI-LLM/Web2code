# Web2Code

Official implementation of **[A Large-scale Webpage-to-Code Dataset and Evaluation Framework for Multimodal LLMs](https://arxiv.org/abs/2406.20098)**.

- **Institute**: Mohamed bin Zayed University of Artificial Intelligence
- **Resources**: [[Paper](https://arxiv.org/abs/2406.20098)] [[Project Page](https://mbzuai-llm.github.io/webpage2code/)] [[Web2Code Dataset](https://huggingface.co/datasets/MBZUAI/Web2Code)][[Croissant](https://huggingface.co/api/datasets/the-Lin/Web2Code/croissant)]


<p align="center">
  <img src="./assets/samples1.png" width = "1000" alt="sample1">
</p>

## News
**[2024/7/25]** The [training code](web2code/README.md) and checkpoints are released!
**[2024/6/27]** The [paper](https://arxiv.org/abs/2406.20098) and [project page](https://mbzuai-llm.github.io/webpage2code/) are released!

## Training Web2Code

For training Web2Code model, refer to the [web2code training](web2code/README.md).

## Evaluation Benchmark Suite

Explore our comprehensive benchmarks for evaluating webpage-related tasks.

### Webpage Code Generation Benchmark

Set up your environment, generate webpage screenshots, and run evaluations efficiently. Get started here: [Webpage Code Generation Benchmark](/code_generation/README.md)

### Webpage Understanding Benchmark

Find clear instructions for setting up your environment, generating outputs, and running evaluations. Begin here: [Webpage Understanding Benchmark](/webpage_understanding/README.md)


## Acknowledgments
- [LLaVA](https://github.com/haotian-liu/LLaVA): the codebase we built upon. Thanks for their wonderful work.
- [WebSRC](https://x-lance.github.io/WebSRC/), [WebSight](https://huggingface.co/blog/websight), [Pix2Code](https://github.com/tonybeltramelli/pix2code): some high-quality web page and HTML code related dataset！

## Citation
If you find our work helpful for your research, please consider giving a star ⭐ and citation 📝

```
@article{web2code2024,
  title={Web2Code: A Large-scale Webpage-to-Code Dataset and Evaluation Framework for Multimodal LLMs},
  author={Sukmin Yun and Haokun Lin and Rusiru Thushara and Mohammad Qazim Bhat and Yongxin Wang and Zutao Jiang and Mingkai Deng and Jinhong Wang and Tianhua Tao and Junbo Li and Haonan Li and Preslav Nakov and Timothy Baldwin and Zhengzhong Liu and Eric P. Xing and Xiaodan Liang and Zhiqiang Shen},
  journal={arXiv preprint arXiv:2406.20098},
  year={2024}
}
```

## License
![Data License](https://img.shields.io/badge/Data%20License-MIT-red.svg) **Usage and License Notices**: The data is intended and licensed for general use under the MIT License. The dataset is MIT licensed (permitting both commercial and non-commercial use) and models trained using the dataset can be used freely, provided proper attribution is given, and the license terms are followed.

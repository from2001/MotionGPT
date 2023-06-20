# Official repo for MotionGPT
### [MotionGPT: Human Motion as a Foreign Language](https://chenxin.tech/motiongpt)

### [Project Page](https://chenxin.tech/motiongpt) | [Arxiv](https://arxiv.org/abs/2212.04048)

MotionGPT is a unified and user-friendly motion-language model to learn the semantic coupling of two modalities and generate high-quality motions and text descriptions on multiple motion tasks.

## Abstract

Though the advancement of pre-trained large language models unfolds, the exploration of building a unified model for language and other multi-modal data, such as motion, remains challenging and untouched so far. Fortunately, human motion displays a semantic coupling akin to human language, often perceived as a form of body language. By fusing language data with large-scale motion models, motion-language pre-training that can enhance the performance of motion-related tasks becomes feasible. Driven by this insight, we propose MotionGPT, a unified, versatile, and user-friendly motion-langzuage model to handle multiple motion-relevant tasks. Specifically, we employ the discrete vector quantization for human motion and transfer 3D motion into motion tokens, similar to the generation process of word tokens. Building upon this “motion vocabulary”, we perform language modeling on both motion and text in a unified manner, treating human motion as a specific language. Moreover, inspired by prompt learning, we pre-train MotionGPT with a mixture of motion-language data and fine-tune it on prompt-based question-and-answer tasks. Extensive experiments demonstrate that MotionGPT achieves state-of-the-art performances on multiple motion tasks including text-driven motion generation, motion captioning, motion prediction, and motion in-between.

## 🚩 News

- [2023/6/20] upload paper and init project

## ⚡ Quick Start

## ▶️ Demo

## 💻 Train your own models

## 👀 Visualization

## ❓ FAQ

## Citation

If you find our code or paper helps, please consider citing:

```bibtex
@inproceedings{chen2023mld,
  title     = {MotionGPT: Human Motion as a Foreign Language},
  author    = {Jiang, Biao and Chen, Xin and Liu, Wen and Yu, Jingyi and Yu, Gang and Chen, Tao},
  booktitle = {arxiv},
  month     = {June},
  year      = {2023},
}
```

## Acknowledgments

Thanks to [Motion-latent-diffusion](https://github.com/ChenFengYe/motion-latent-diffusion), [TEMOS](https://github.com/Mathux/TEMOS), [ACTOR](https://github.com/Mathux/ACTOR), [HumanML3D](https://github.com/EricGuo5513/HumanML3D) and [joints2smpl](https://github.com/wangsen1312/joints2smpl), our code is partially borrowing from them.

## License

This code is distributed under an [MIT LICENSE](LICENSE).

Note that our code depends on other libraries, including SMPL, SMPL-X, PyTorch3D, and uses datasets which each have their own respective licenses that must also be followed.

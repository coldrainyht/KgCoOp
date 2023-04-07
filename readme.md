
# Visual-Language Prompt Tuning with Knowledge-guided Context Optimization  [CVPR 2023]

> [**Visual-Language Prompt Tuning with Knowledge-guided Context Optimization**](https://arxiv.org/abs/2210.03117)<br>
> Hantao Yao, Rui Zhang, Changsheng Xu

1. [Dassl.ProGrad.pytorch](Dassl.ProGrad.pytorch/) is the modified toolbox of [Dassl.pytorch](https://github.com/KaiyangZhou/Dassl.pytorch).
2. [KgCoOp](KgCoOp/). To get the results in our paper, follow the [README.md](KgCoOp/README.md) under [KgCoOp/](KgCoOp/) to set the environment.

## Highlights
We introduce a novel Knowledge-guided Context Optimization (KgCoOp) to enhance the generalization ability of the learnable prompt for unseen classes. The key insight of KgCoOp is that the forgetting about essential knowledge can be alleviated by reducing the discrepancy between the learnable prompt and the hand-crafted prompt. Especially, KgCoOp minimizes the discrepancy between the textual embeddings generated by learned prompt and the hand-crafted prompts. Extensive evaluation shows that KgCoOp is an efficient method, i.e., achieves better performance with less training time.
![main figure](fig_main.png)

| Methods | Prompts | Base | New | H | Training-time|
|---------|---------|------|------|---|-------------|
| CLIP | hand-crafted | 69.34 | 74.22 | 71.70 | -|    


## Citation
If you use our work, please consider citing:
```bibtex
@inproceedings{khattakMaPLe,
    title={Visual-Language Prompt Tuning with Knowledge-guided Context Optimization},
    author={Hantao Yao, Rui Zhang, Changsheng Xu},
    booktitle={The IEEE/CVF Conference on Computer Vision and Pattern Recognition},
    year={2023}
}
```


## Acknowledgements
Our code is based on [Co-CoOp and CoOp](https://github.com/KaiyangZhou/CoOp) and [ProGrad](https://github.com/BeierZhu/Prompt-align) repository. We thank the authors for releasing their code. If you use our model and code, please consider citing these works as well.

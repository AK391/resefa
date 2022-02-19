# Region-Based Semantic Factorization in GANs

![image](./docs/assets/teaser.jpg)

**Figure:** *Image editing results using ReSeFa on BigGAN (first two columns) and StyleGAN2 (last three columns).*


> **Region-Based Semantic Factorization in GANs** <br>
> Jiapeng Zhu, Yujun Shen, Yinghao Xu, Deli Zhao, Qifeng Chen <br>
> arXiv preprint arXiv:2202.09649 <br>

[[Paper](http://arxiv.org/abs/2202.09649)]

In the repository, we propose a simple algorithm termed *ReSeFa* to precisely control the local region of an image generated by GANs.
Namely, we re-examine the task of local editing with pre-trained GAN models and formulate region-based semantic discovery as a dual optimization problem. 
By an appropriately defined generalized Rayleigh quotient, we solve such a problem in a closed-form way, avoiding any annotations or training on the models. Extensive experiments demonstrate the effectiveness and robustness of our proposed method.


![image](./docs/assets/face.jpg)
Image editing results using ReSeFa on StyleGAN2 face model.


## Code coming soon


## BibTeX

```bibtex
@article{zhu2022resefa,
  title   = {Region-Based Semantic Factorization in GANs},
  author  = {Zhu, Jiapeng and Shen, Yujun and Xu, Yinghao and Zhao, Deli and Chen, Qifeng},
  journal = {arXiv preprint arXiv:2202.09649},
  year    = {2022}
}
```
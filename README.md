# Scaling Transformer Energy-Based Models for High Quality Image Synthesis

This repository contains the source code for the project page of **TEM (Transformer Energy-Based Model)**.

**Jungsoo Lee**<sup>1</sup>, **Alexi Gladstone**<sup>2</sup>, **Yilun Du**<sup>3</sup>
<sup>1</sup>MIT, <sup>2</sup>UIUC, <sup>3</sup>Harvard University

[Project Page](#) | [Paper](./2610.31889v1.pdf) | [arXiv](https://arxiv.org/abs/2610.31889) | [Code](#)

TEM is a scalable transformer energy function trained contrastively in latent space. It reaches an FID-50K of 3.82 on
class-conditional ImageNet 256×256 and 8.24 on ImageNet 512×512 without classifier-free guidance, and supports
compositional generation, zero-shot inpainting, and out-of-distribution detection.

## Citation

If you find TEM useful for your work, please cite:
```
@article{lee2026scaling,
  title         = {Scaling Transformer Energy-Based Models for High Quality Image Synthesis},
  author        = {Lee, Jungsoo and Gladstone, Alexi and Du, Yilun},
  journal       = {arXiv preprint arXiv:2610.31889},
  year          = {2026},
  eprint        = {2610.31889},
  archivePrefix = {arXiv},
  primaryClass  = {cs.LG},
  url           = {https://arxiv.org/abs/2610.31889}
}
```

## Website License
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.

## Acknowledgments

The website template is borrowed from [Nerfies](https://github.com/nerfies/nerfies.github.io). If you use this template, please also cite:
```
@article{park2021nerfies,
  author    = {Park, Keunhong and Sinha, Utkarsh and Barron, Jonathan T. and Bouaziz, Sofien and Goldman, Dan B and Seitz, Steven M. and Martin-Brualla, Ricardo},
  title     = {Nerfies: Deformable Neural Radiance Fields},
  journal   = {ICCV},
  year      = {2021},
}
```

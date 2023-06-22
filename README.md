<div align='center' ><font size='70'>ContraNeRF: Generalizable Neural Radiance Fields for Synthetic-to-real Novel View Synthesis via Contrastive Learning</font></div>

<div align='center' ><font size='4'>Hao Yang<sup>1</sup>, Lanqing Hong<sup>2</sup>, Aoxue Li<sup>2</sup>, Tianyang Hu<sup>2</sup>, Zhenguo Li<sup>2</sup>, Gim Hee Lee<sup>3</sup>, Liwei Wang<sup>1</sup> </font></div>

<div  align='center' class="is-size-5 publication-authors">
  <span class="author-block"><sup>1</sup>Peking University &nbsp;&nbsp;</span>
  <span class="author-block"><sup>2</sup>Huawei Noah’s Ark Lab &nbsp;&nbsp;</span>
  <span class="author-block"><sup>3</sup>National University of Singapore &nbsp;&nbsp;</span>
</div>

<h1 align='center' style="font-size:28px;font-weight:bold">CVPR 2023</h1>

<div align='center'><a href="https://arxiv.org/abs/2303.11052">[Paper]</a>    <a href="https://github.com/ContraNeRF/ContraNeRF">[Code]</a></div>

<center ><font size='7'>Abstract</font></center>

Although many recent works have investigated generalizable NeRF-based novel view synthesis for unseen scenes, they seldom consider the synthetic-to-real generalization, which is desired in many practical applications. In this work, we first investigate the effects of synthetic data in synthetic-to-real novel view synthesis and surprisingly observe that models trained with synthetic data tend to produce sharper but less accurate volume densities. For pixels where the volume densities are correct, fine-grained details will be obtained. Otherwise, severe artifacts will be produced. To maintain the advantages of using synthetic data while avoiding its negative effects, we propose to introduce geometry-aware contrastive learning to learn multi-view consistent features with geometric constraints. Meanwhile, we adopt cross-view attention to further enhance the geometry perception of features by querying features across input views. Experiments demonstrate that under the synthetic-to-real setting, our method can render images with higher quality and better fine-grained details, outperforming existing generalizable novel view synthesis methods in terms of PSNR, SSIM, and LPIPS. When trained on real data, our method also achieves state-of-the-art results.

![pipeline](figs/pipeline.jpg)



<center ><font size='7'>Bibtex</font></center>

```
@article{yang2023contranerf,
  title={ContraNeRF: Generalizable Neural Radiance Fields for Synthetic-to-real Novel View Synthesis via Contrastive Learning},
  author={Yang, Hao and Hong, Lanqing and Li, Aoxue and Hu, Tianyang and Li, Zhenguo and Lee, Gim Hee and Wang, Liwei},
  journal={arXiv preprint arXiv:2303.11052},
  year={2023}
}
```

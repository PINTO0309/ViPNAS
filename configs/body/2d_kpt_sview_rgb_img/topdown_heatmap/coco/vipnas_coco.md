<!-- [BACKBONE] -->

<details>
<summary align="right">ViPNAS (CVPR'2021)</summary>

```bibtex
@article{xu2021vipnas,
  title={ViPNAS: Efficient Video Pose Estimation via Neural Architecture Search},
  author={Xu, Lumin and Guan, Yingda and Jin, Sheng and Liu, Wentao and Qian, Chen and Luo, Ping and Ouyang, Wanli and Wang, Xiaogang},
  booktitle={Proceedings of the IEEE conference on computer vision and pattern recognition},
  year={2021}
}
```

</details>

<!-- [DATASET] -->

<details>
<summary align="right">COCO (ECCV'2014)</summary>

```bibtex
@inproceedings{lin2014microsoft,
  title={Microsoft coco: Common objects in context},
  author={Lin, Tsung-Yi and Maire, Michael and Belongie, Serge and Hays, James and Perona, Pietro and Ramanan, Deva and Doll{\'a}r, Piotr and Zitnick, C Lawrence},
  booktitle={European conference on computer vision},
  pages={740--755},
  year={2014},
  organization={Springer}
}
```

</details>

Results on COCO val2017 with detector having human AP of 56.4 on COCO val2017 dataset

| Arch  | Input Size | AP | AP<sup>50</sup> | AP<sup>75</sup> | AR | AR<sup>50</sup> | ckpt | log |
| :-------------- | :-----------: | :------: | :------: | :------: | :------: | :------: |:------: |:------: |
| [S-VipNAS-Res50](https://github.com/luminxu/ViPNAS/blob/main/configs/body/2d_kpt_sview_rgb_img/topdown_heatmap/coco/s_vipnas_res50_coco_256x192.py)  | 256x192 | 0.711 | 0.893 | 0.789 | 0.769 | 0.769 | [ckpt](https://drive.google.com/file/d/1maPJb8bTsUZOEljp-ceSvJFz3Jyn3VbO/view) | [log](https://drive.google.com/file/d/1VRmsvPKvpaPqHqVZYqmX1aatGzfmCWRS/view) |

# KNN Matting

This repo reimplement [knn-matting](https://dingzeyu.li/files/knn-matting-cvpr2012.pdf) based on GPU-based in [FAISS](https://github.com/facebookresearch/faiss) Library.

### Inference

* Open the gpu-knn-matting notebook in Google Colab (recommended)

* Follow each cells for environment installation and inference

### Results

![woman](.\src\woman.png)![woman_trimap](.\src\woman_trimap.png)![woman_alpha](.\src\woman_alpha.png)![woman_composite](.\src\woman_composite.png)

### Reference

```
@article{Chen:2012:KM,
   author={Qifeng Chen and Dingzeyu Li and Chi-Keung Tang},
   journal={Pattern Analysis and Machine Intelligence, IEEE Transactions on},
   title={KNN matting},
   year={2013},
   month={Sept},
   volume={35},
   number={9},
   pages={2175-2188},
   doi={10.1109/TPAMI.2013.18}
}
```

```
@article{JDH17,
  title={Billion-scale similarity search with GPUs},
  author={Johnson, Jeff and Douze, Matthijs and J{\'e}gou, Herv{\'e}},
  journal={arXiv preprint arXiv:1702.08734},
  year={2017}
}
```


# KNN Matting

* How to inference
  * Opening the ipynb file in jupyter notebook or google colab (recommended)
  * Install dependencies follow the notebook (only support linux)
  * If using google colab, then the first cell is meant to install conda for google colab.
  * Change the paths to image, trimap, and background to desired images.
  * The arguments of knn_matting() function can activate certain features implemented in the notebook
    * When all false, then corresponds to the basic method in the report
    * use_bicg: whether to use biconjugate gradient as solver
    * use_faiss: whether to use GPU-based KNN
    * use_weak_spatial: whether to use
    * use_vgg_feature: whehter to use vgg_feature
    * If use_weak_spatial is true, then use_bicg must be true
    * If use_vgg_feature is true, then use_weak_spatial, use_faiss, and use_bicg must be true
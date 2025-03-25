1. The jypyter notebook is created on kaggle and the dataset used is :https://www.kaggle.com/datasets/blackcanary/cocotest2014
2. The model is ispired by pix2pix conditional GAN: https://arxiv.org/pdf/1611.07004
3. This process includes : fencing of coco-test2014 dataset, storing them in pairs of fenced and de fenced images along with edges created by xanny filters.
4. The model is trained with 10 epochs considering the small size of dataset.
5. It has an average generator loss of 6.3481 (may very slightly).
6. Using canny filters is a motivation from the following paper: https://arxiv.org/pdf/1908.06837

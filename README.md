## transfer learning demo

图像风格迁移

### 准备数据

- [VGG19模型下载地址](http://www.vlfeat.org/matconvnet/models/beta16/imagenet-vgg-verydeep-19.mat)，将模型下载后放到`data`目录下
- 将风格图片`style.jpg`放到`data/image`文件夹下，将要处理的图片`content.jpg`放到`data/image`文件夹下，并且在`data`目录下新建`output`文件夹

### 训练
- 在终端执行`python train.py`
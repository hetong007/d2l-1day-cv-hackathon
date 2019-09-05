# 使用教程

## 标注图片
你可以使用 [网页标注工具](https://www.makesense.ai/) ([备用地址](http://34.223.106.104)) 将本地电脑上的图片标注。当完成标注后，可以通过`EXPORT LABELS`按钮导出xml标注（A zip package containing files in VOC XML Fomrat).

当你准备好训练数据后（训练数据是N张jpg图片和同名xml)，将数据上传到远程GPU电脑上的`train_data`文件夹。

## 数据下载

如果github下载速度太慢了，可以试用这个百度网盘链接：https://pan.baidu.com/s/1UpAM06U9E2WzePm2JGqZhQ

## 服务器配置

如果jupyter让你选择kernel，建议选择 `conda_mxnet_p36`

在jupyter notebook上下载这个repo，并解压数据，可以在一个代码cell里输入下面的命令：

```
!git clone https://github.com/hetong007/d2l-1day-cv-hackathon.git
!cd d2l-1day-cv-hackathon && unzip images.zip
```

在jupyter notebook里安装 gluoncv，可以在一个代码cell里输入下面的命令：

```
!pip install --pre gluoncv
```

读数据时碰到报错内容含有`Unspecified`或者是`int()`等字样的，请安装最新版 gluoncv:

```
!pip install --pre gluoncv
```

申请新机器，请发送邮件到

```
d2lzh-1day-hackathon@request-nb.mxnet.io
```


更多模型与进阶应用: https://gluon-cv.mxnet.io


## 训练目标检测器

打开`training_object_detector.ipynb`，学习和训练一个目标检测器

## 测试目标检测器

打开`test_object_detector.ipynb`，测试目标检测器


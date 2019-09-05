# 使用教程

## 标注图片
你可以使用 [网页标注工具](https://www.makesense.ai/) ([备用地址](http://34.223.106.104)) 将本地电脑上的图片标注。当完成标注后，可以通过`EXPORT LABELS`按钮导出xml标注（A zip package containing files in VOC XML Fomrat).

当你准备好训练数据后（训练数据是N张jpg图片和同名xml)，将数据上传到远程GPU电脑上的`train_data`文件夹。

## 数据下载

如果github下载速度太慢了，可以试用这个百度网盘链接：https://pan.baidu.com/s/1UpAM06U9E2WzePm2JGqZhQ

## 训练目标检测器

打开`training_object_detector.ipynb`，学习和训练一个目标检测器

## 测试目标检测器

打开`test_object_detector.ipynb`，测试目标检测器


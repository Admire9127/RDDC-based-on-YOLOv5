# 基于YOLOv5的路面病害识别
 基于YOLOv5的路面病害识别模型，转化为tensflow lite模型并部署到移动端

- 使用基于pytorch的框架yolov5进行模型训练，数据集使用了RDDC2020数据集
- 训练完毕后的pt文件移植为Tensflow Lite格式，以便于移植到移动端
- 将转化后的TFLite模型文件，通过Tensflow的app Demo说明，移植到自己的app内
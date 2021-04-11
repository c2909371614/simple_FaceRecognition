# FaceRecognition-tensorflow
基于TensorFlow训练的人脸识别神经网络

python 库：dlib、tensorflow、opencv、numpy

分为：

**get_my_faces.py**                                   打开摄像头读取10000张人脸头像，需要在摄像头前待几分钟

**set_other_faces.py**                              将input_img内的人脸图像提取出来至other_faces文件夹中

**train_faces.py**                                       进行人脸训练并生成模型文件

**is_my_face.py**                                        进行模型检测判断当前摄像头前是否为get_my_face中读取到的人脸头像


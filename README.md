# banana_crown_dataset
香蕉冠数据集：自制的香蕉果柄图像数据集（共计1304张包含原始图片），拍摄方向自然生长方向的顶部视角，添加了用于关键点检测的YOLO (You Only Look Once) .txt格式的标签，可直接用于机器学习训练，助力农业智能化发展。
（A self-made dataset of banana crown images (A total of 6,620 images, including original and enhanced ones), captured from a top-view perspective in alignment with the natural growth direction. It incorporates YOLO (You Only Look Once) .txt format labels for keypoint detection, enabling direct use in machine learning training and contributing to the advancement of intelligent agriculture.）

# 下载链接 （Download link）
链接（link）: https://pan.baidu.com/s/1hQTHcUbRuYGlwT_OWZCbag 
提取码(code): bana

# 使用方法（How to use）
1. 划分训练集、验证集、测试集，参考比例8：1：1，每个集合里面分别有图片文件夹images和标签文件夹labels。（Divide the training set, validation set and test set, with a reference ratio of 8:1:1. Each set contains an image folder named "images" and a label folder named "labels" respectively.）
2. 修改crown_kp.yaml文件里的路径。（Modify the path in the crown_kp.yaml file.）
3. YOLO训练中索引此crown_kp.yaml文件的位置路径。（Index the position path of this crown_kp.yaml file during YOLO training.）


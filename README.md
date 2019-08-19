# A-New-Convolutional-Neural-Network-Based-Data-Driven-Fault-Diagnosis-Method

In this paper, a new CNN based on LeNet-5 is proposed for fault diagnosis. Through a conversion method converting signals into two-dimensional (2-D) images, the proposed method can extract the features of the converted 2-D images and eliminate the effect of handcrafted features.
</br>
I feel it very interesting because it applies CNN to mechanical scenes.
</br>
The .py file is an implemention of CNN. But I do not provide how to preprocess the dataset.

Reference:
</br>
L. Wen, X. Li, L. Gao and Y. Zhang, "A New Convolutional Neural Network-Based Data-Driven Fault Diagnosis Method," in IEEE Transactions on Industrial Electronics, vol. 65, no. 7, pp. 5990-5998, July 2018.

输入64 64图像
输出2类
LeNet-5结构：4卷积池化层+1全连接层+1全连接输出层

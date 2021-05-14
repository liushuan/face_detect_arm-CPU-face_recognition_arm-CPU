# face_detect_arm-CPU-
Arm边缘设备 基于CPU 真正超实时的人脸检测算法 720P 图像 只要 15ms

目前基于 RK3399 边缘设备进行测试，纯CPU算法很方便移植。
对720P的图像进行人脸检测 可以做到 10-15ms 即可完成人脸检测。
CPU消耗在90%左右

其中红色框为人脸检测的时间，蓝色框为人脸检测+人脸特征提取的耗时，测试均在CPU环境下进行

![image](https://user-images.githubusercontent.com/15781088/118229982-80f19000-b4bf-11eb-90ef-4dad211c0461.png)
上图展示了 算法 在 A73 CPU 上面的运行时间， 人脸检测部分一般在 10ms-15ms 左右 ，人脸检测+人脸特征提取 一般在 130-135ms,整体识别速度非常快速。

需要改进人脸识别算法的欢迎联系。
![image](https://user-images.githubusercontent.com/15781088/118230080-a54d6c80-b4bf-11eb-841f-59f366a7050c.png)

547691062@qq.com

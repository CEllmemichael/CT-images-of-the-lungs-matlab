## 肺部CT图像处理[matlab]
输入图像获得肺部内部的图像，并在内部生成随机种子点
肺部CT图像处理

本文上传肺部的ct图像，使用matlab进行连通域计算获得肺部的二值化模板

>【可以通过生成的种子点使用生成算法生成肺部影像的二值化模板】

>需要深度学习的同学可以使用生成的模板做end2end训练。

本文最终生成的是在肺部内生成随机点

本文的思路是根据图像进行切割然后计算最大连通域

通过判断前两个最大的是否为空白区域然后进行微调最终形成结果
## Lung CT Image Processing [MATLAB]
Input images are obtained to obtain images of the inside of the lungs and random seed points are generated inside
Lung CT image processing

In this paper, CT images of lungs are uploaded and the binarized template of the lungs is obtained using MATLAB for connectivity domain calculation

> [A binary template of lung images can be generated using a generation algorithm using the generated seed points]

> students who need deep learning can use the generated template to do end2end training.

The final result of this paper is the generation of random points within the lungs

The idea of this article is to cut the image and then calculate the maximum connected domain

By judging whether the first two largest are blank areas, and then fine-tuning, the final result is formed


## 下面是实验结果：
## Here are the results of the experiment:



![image](https://user-images.githubusercontent.com/66575985/225838526-a518086f-75db-48ec-aeda-b71ac1b1e0a9.png)

![image](https://user-images.githubusercontent.com/66575985/225838575-0d948da3-88bb-436e-91c5-65a4b7a17fe4.png)

![image](https://user-images.githubusercontent.com/66575985/225838605-dfffc709-210a-4d6c-bd37-e583905bbc79.png)

![image](https://user-images.githubusercontent.com/66575985/225838652-dae5ebf8-a37a-43f3-9838-5a883b988303.png)

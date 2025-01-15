# SVD-KD
## 环境：
- 我的环境是Python:3.7.16,  cudatoolkit: 11.3.1,  PyTorch: 1.10.0,  Torchvision: 0.11.0,  opencv-python: 4.10.0.84, Other Libraries: NumPy 1.21.6, scipy 1.7.3等基本库，其余报错缺啥pip install啥。
- ubuntu和windows都能运行，我的显卡是RTX 4090 *2
## 运行：
- dataload_cf100.py里面改数据集路径
- 先运行train_teacher.py得到教师的PTH文件保存在pth文件夹中。
- 再运行SVDKD_cf100.py
## 补充：
能力有限，只整理了cifar-100数据集上的代码，后续更新

##  To Be continue...

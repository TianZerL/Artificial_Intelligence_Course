# Artificial_Intelligence_Course
西南交通大学人工智能课程仓库

基于pytorch复现Waifu2x与FSRCNN，并提出ACNet模型用于动漫风格图像超分辨率

文件用途:

- rawDataProcess.py: 预处理数据集，包括缩放与裁剪等
- copyData.py: 复制处理后的数据集到指定文件夹
- dataLoader.py: 实现数据集数据的加载
- module.py: 模型定义
- train.py: 训练模型(训练参数在此修改)
- test.py: 效果测试

# hw07胸部 X 光肺炎影像二分类实战
1、目录结构
hw07/
├── train.ipynb          # 完整训练代码（含输出）
├── requirements.txt     # 依赖包列表
├── README.md            # 本文件
├── report.md            # 实验报告
└── figures/             # 图表目录
    ├── train curve.png+3class curve.png
    ├── confusion matrix.png
    └── 3class confusion matrix.png
2、一键运行命令
上传 train.ipynb 到 Kaggle
Add Data → 搜索添加 chest-xray-pneumonia
设置 CPU → Run All
3、数据集获取说明
名称：Chest X-Ray Images (Pneumonia)
链接：https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia
使用：下载后解压，路径为 chest_xray/
4、最终测试集指标摘要
二分类准确率：0.7788，召回率：0.6590
三分类准确率：0.7063，召回率：0.67
所有图表保存在figures/目录
###
二分类表现良好但召回率偏低（漏诊率34%）；三分类中Viral与Bacterial易混淆，难度显著高于二分类。

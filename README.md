# Steel-Defect-CNN-Transformer-Detection
Lightweight CNN-Transformer hybrid detection for steel surface defects

这个项目基于NEU-DET数据集，完成热轧钢材表面缺陷检测。
一共识别6类钢材缺陷：
0. crazing（裂纹）
1. inclusion（夹杂）
2. patches（斑块）
3. pitted_surface（麻点）
4. rolled-in_scale（氧化皮）
5. scratches（划痕）

## 项目流程
1. 数据准备：把XML标注转换成YOLO格式的TXT标签
2. YOLO基线模型测试
3. 搭建轻量CNN-Transformer混合检测模型
4. 模型评估与结果可视化


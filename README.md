# 基于 SAM 优化的 UNetFormer 模型

本项目包含两个主要文件夹：

1. **GeoSeg**：该文件夹包含原始的 UNetFormer 模型，主要用于遥感图像的语义分割任务。
2. **SAM_RS**：该文件夹包含使用基于 SAM 原始输出的辅助信息优化的 UNetFormer 模型，以提升模型在复杂城市场景中的表现。

## 文件夹概述

### GeoSeg
- 该目录包含了 **UNetFormer** 模型的实现，它是一种结合了 UNet 结构和 Transformer 注意力机制的混合架构，适用于遥感图像的语义分割。
- 模型使用遥感图像进行训练和评估，主要用于城市场景的分割任务。
- 参考文献：UNetFormer: A UNet-like transformer for efficient semantic segmentation of remote sensing urban scene imagery


### SAM_RS
- 该目录包含优化后的 **UNetFormer** 模型，使用 SAM (Self-Attention Mechanism) 的原始输出作为辅助信息来增强模型的能力，尤其在复杂的城市场景分割中取得了更好的效果。
- 通过这种优化，模型在一些类别上得到了提升。
- 参考文献：SAM-Assisted Remote Sensing Imagery Semantic Segmentation With Object and Boundary Constraints

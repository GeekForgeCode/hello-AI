# Transformer 模型简介

Transformer 是一种基于 **Attention (注意力机制)** 的深度学习模型。

### 核心组件
1. **Encoder (编码器)**：负责理解输入。
2. **Decoder (解码器)**：负责生成输出。

### 代码示例 (Python)
```python
import torch
import torch.nn as nn

# 定义一个简单的多头注意力层
multihead_attn = nn.MultiheadAttention(embed_dim=512, num_heads=8)

# WWR Training Dataset — 300

用于建筑立面窗墙比（Window-to-Wall Ratio, WWR）语义分割的 300 张人工标注训练数据。

## 数据内容

- 300 张 PNG 图像
- 300 个 X-AnyLabeling JSON 标注
- 标注类别：`building`、`window`、`door`、`road`、`ground`
- 编号范围：`image001`–`image300`

相较 248 张版本，本版本增加了建筑像素占比较小、距离更远和背景范围更大的实际街景样本。

数据压缩包位于仓库的 **Releases** 页面；`MANIFEST.csv` 提供每个文件的相对路径、字节数和 SHA-256。

## 配对方式

```text
data/image001.png
data/image001.json
```

图像与同名 JSON 一一对应。仓库不包含训练密钥、云服务凭据或运行日志。


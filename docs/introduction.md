# Markley 四面体投影：数学思想与历史

## 1. 历史沿革

- **1965 年**：L.P. Lee 设计出**等角四面体投影**（Conformal Tetrahedral Projection）。
- **1982 年**：F. Landis Markley 在 Lee 的基础上提出一种**特殊排列方式**，即本文所述的 **Markley 四面体投影**（Markley's Tetrahedral Map）。

因此，Markley 投影可视作 Lee 投影的一种优化排列，也可视为 **Guyou 投影的改进方案**。

## 2. 投影类型与几何原理

- **类型**：等角（Conformal）世界地图投影。
- **原理**：将地球表面投影到一个**正四面体的四个面**上，再将该四面体展开成矩形图幅。
- **图幅长宽比**：约为 `sqrt(3) / 4`。

## 3. 核心设计理念：大陆优先

Markley 投影通过精妙的数学排列，将投影过程中产生的**极端变形“驱逐”到远离大陆的海洋区域**，从而在矩形图幅内尽可能保持大陆轮廓的自然形状。

## 4. 优缺点

**优点**

- 局部形状与角度保持较好（等角性质），大陆轮廓自然。
- 矩形图幅，便于排版与展示。

**缺点**

- 海洋区域被严重拉伸，不适合面积精确测量与航海导航。
- 极地地区会被分割。

## 5. 奇点位置

四个奇点均位于海洋中，以保护大陆形状：

| 半球 | 大致经度 |
| :-- | :-- |
| 北半球 | 25°W、155°E 附近 |
| 南半球 | 115°W、65°E 附近 |

## 6. 参考资料

- [map-projections.net — Markley Tetrahedral（Tissot 30）](https://map-projections.net/single-view/markley-tetrahedral:tissot-30-stf)

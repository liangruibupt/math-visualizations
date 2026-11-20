# 数学之美 · Math Visualizations

用可交互的图形直观展现数学的奥妙。每个样例是一个独立的网页，用浏览器直接打开即可，拖动滑块就能看到公式如何变成形状。

从总目录页 [index.html](index.html) 进入，按“贝壳”和“分形”两类导航到各个样例；每个样例页面左上角有“← 全部样例”返回目录。

## 样例

| 样例 | 数学主题 | 预览 |
|------|----------|------|
| [Raup 贝壳卷曲模型 · 3D](examples/raup-shell/README.md)（[打开页面](examples/raup-shell/index.html)） | 对数螺线、自相似、超椭圆；W/D/T 三个数字生成几乎所有螺旋贝壳，可调管口形状、壁厚、纹理、透明度并沿中轴剖切 | <img src="examples/raup-shell/images/cover.png" width="240"> |
| [Mandelbrot 集与 Julia 集 · 分形](examples/mandelbrot-julia/README.md)（[打开页面](examples/mandelbrot-julia/index.html)） | 复数迭代 z → z^d + c、逃逸时间、连通性定理、自相似；左右联动，单击 Mandelbrot 集上任一点即得对应 Julia 集，可显示迭代轨道 | <img src="examples/mandelbrot-julia/images/rabbit-orbit.png" width="240"> |
| [L-system 植物](examples/lsystem-plants/README.md)（[打开页面](examples/lsystem-plants/index.html)） | 并行字符串重写、海龟作图、栈与分枝、自相似、分形维数；可编辑规则，逐代或按画线顺序播放生长，含 Koch 雪花、龙曲线、Hilbert 曲线等预设 | <img src="examples/lsystem-plants/images/plant.png" width="240"> |
| [IFS 蕨叶 · 混沌游戏](examples/ifs-fern/README.md)（[打开页面](examples/ifs-fern/index.html)） | 仿射变换、压缩映射、Hutchinson 算子与不动点定理、随机迭代、自相似；可编辑变换表，按变换着色并画出包围盒的像，含 Barnsley 蕨叶、Sierpinski 三角、龙曲线等预设 | <img src="examples/ifs-fern/images/fern.png" width="240"> |

## 目录约定

```
examples/<样例名>/
  index.html   # 单文件页面，无需构建
  README.md    # 数学原理、参数说明、效果图
  images/      # README 用到的截图
```

新增样例时，在上表加一行，并链接到它的 README 和页面。

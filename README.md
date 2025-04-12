# dijkstra
# Dijkstra Algorithm Implementation

单源最短路径的Dijkstra算法C++实现，适用于稠密图（邻接矩阵）。

## 输入格式

- 第一行：节点数 `n` 和边数 `m`
- 接下来 `m` 行：每行三个整数 `x y z`，表示从节点 `x` 到 `y` 的有向边权值为 `z`

节点编号从 **1** 开始，最大支持节点数 **510**。

## 构建与运行

```bash
make build
./dijkstra < test/input1.txt

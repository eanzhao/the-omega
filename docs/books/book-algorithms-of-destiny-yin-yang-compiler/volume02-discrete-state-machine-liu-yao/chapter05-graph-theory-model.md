# 第五章：图论模型：世应与六亲网络

**Chapter 5: Graph Theory Model: Subject-Object and Six Relations Network**

## 5.1 世应图谱：观察者与客体的距离矩阵

六爻卦象不是线性列表，而是一个**双向图 (Bidirectional Graph)**。

### 5.1.1 相对论性原点
**世爻 (Subject Node)**: 观察者所在的参考系原点 $(0,0)$。
**应爻 (Object Node)**: 目标对象所在的坐标 $(x,y)$。
预测算法的核心，是计算从世节点到应节点的**测地线距离 (Geodesic Distance)** 和 **传输阻抗 (Transmission Impedance)**。

*   **生合**: 阻抗 $Z \to 0$。超导连接。信息/能量无损传输。
*   **刑冲**: 阻抗 $Z \to \infty$。断路或短路。能量耗散在冲突中。

## 5.2 动爻演算：状态转移路径

### 5.2.1 变卦作为微扰 (Perturbation)
动爻是系统哈密顿量中的**微扰项 (Perturbation Term)** $H'$.
$H = H_0 + H'$
$H_0$ 是本卦（现状），$H'$ 是动爻（变化趋势）。
变卦展示了系统在微扰作用下的**演化轨迹 (Trajectory)**。

### 5.2.2 回头生克：因果回路
*   **回头生**: 变爻生本爻。这是一个**正反馈回路 (Positive Feedback Loop)**。未来的状态加强了现在的状态。这在非线性动力学中会导致系统的**自增强 (Self-reinforcement)**。
*   **回头克**: 变爻克本爻。这是一个**负反馈回路 (Negative Feedback Loop)**。未来的演化趋势在抑制现在的状态。这通常预示着系统的**自我毁灭**或**强制转型**。

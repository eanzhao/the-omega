# 第六章：多维数据融合：六神与神煞

**Chapter 6: Multi-dimensional Data Fusion: Six Spirits and Shen-Sha**

## 6.1 六神：叠加在五行物理层之上的元数据标签层

在六爻系统中，五行生克（Physics Layer）决定了事件的**吉凶（能量增减）**，而六神（Metadata Layer）决定了事件的**性质（语义标签）**。
六神是根据日干（Day Stem）循环映射到六个爻位上的。这是一种**周期性的元数据注入 (Periodic Metadata Injection)**。

### 6.1.1 六神语义向量 (Semantic Vectors)
1.  **青龙 (Green Dragon)**:
    *   属性：木。
    *   语义：生长、喜庆、左侧、新开始。
    *   对应数据类型：`Status: Success`, `Event: Celebration`.
2.  **朱雀 (Vermilion Bird)**:
    *   属性：火。
    *   语义：言语、信息、文书、口舌。
    *   对应数据类型：`Type: Message`, `Warning: Conflict`.
3.  **勾陈 (Hook Entity)**:
    *   属性：土。
    *   语义：田土、稳重、跌打、牵连。
    *   对应数据类型：`Object: Property`, `State: Stuck`.
4.  **腾蛇 (Flying Snake)**:
    *   属性：土/火。
    *   语义：惊恐、怪异、虚假、梦境。
    *   对应数据类型：`Exception: Anomaly`, `Mental: Panic`.
5.  **白虎 (White Tiger)**:
    *   属性：金。
    *   语义：血光、威权、道路、右侧。
    *   对应数据类型：`Risk: Critical`, `Authority: Police`.
6.  **玄武 (Black Turtle)**:
    *   属性：水。
    *   语义：阴私、盗贼、暧昧、后台。
    *   对应数据类型：`Hidden: True`, `Security: Breach`.

## 6.2 神煞：特定组合触发的预设函数或异常处理程序

**神煞 (Shen-Sha)** 是一套基于特定干支组合的**预定义触发器 (Triggers)**。
当特定的 Input (如年干+流年支) 满足条件时，系统自动执行一段预设的脚本。

*   **天乙贵人 (Nobleman)**:
    *   逻辑：`if (DayStem in [甲, 戊]) and (Branch in [丑, 未]): trigger(HelpFunction)`。
    *   作用：引入外部高权重节点的辅助，抵消系统内部的熵增（解灾）。
*   **驿马 (Traveling Horse)**:
    *   逻辑：`if (DayBranch == 申/子/辰) and (Branch == 寅): trigger(MoveFunction)`。
    *   作用：强制系统状态发生位移（出差、变动）。
*   **空亡 (Null/Void)**:
    *   逻辑：`if (Branch) not in CurrentXun: state = NULL`。
    *   作用：该节点的连接暂时断开，能量无法传输。类似于电路中的**高阻态 (High-Z)**。

神煞系统是道家算法中的**快捷指令集 (Shortcuts)**，用于快速识别常见的命运模式。


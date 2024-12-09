---
title: UAS

---


## 1. Logika Matematika

| $No$ | $P$ | $Q$ | $R$ | $S$ |$(P \rightarrow Q)$ | $(R \rightarrow S)$ | $(P \rightarrow Q)\rightarrow(R \rightarrow S)$ |
| -------- | -------- | -------- | -------- | -------- |-------- | -------- |-------- |
| 1   | T     | F     |F     | T     | F   |   T   |   T   |
| 2  | T     | T     |T     | T     | T  |    T  |   T   |
| 3   | F     | F    |T     | F     | T  |    F  |   F   |
| 4   | T     | T     |T     | F     | T |    F  |   F   |
| 5   | F    | T     |F     | F     | T  |   T   |   T   |
| 6   | F     | T     |   F  | T     | T  | T     |   T   |
| 7   | F     | F     |T     | T     | T  |  T    |  T    |
| 8   | T     | T     |F     | T     | T  |  T    |   T   |

## 2. Centrality graph
![Centrality Graph](https://hackmd.io/_uploads/BylFPfVVyx.png)

* **Closeness Centrality**


| Node | A | B | C | D | E | F | G |
| -------- | -------- | -------- |-------- | -------- |-------- | -------- |-------- | 
| A     | 0    |   1  |   1  |   2  |  2   |  2   |  3   |
| B     |   1   |   0  |    1 |   2  |   2  |  1   |  3   |     |
| C     |   1  |   1   |  0   |   1  |   1  |  1   |  2   |     |
| D     |   2   |    2  |  1  |   0  |   2  |   2  |   1  |     |
| E     |   2   |  2  |  1  |   2  |   0  |  2   |  1   |     |
| F    |    2  |   1  |  1  |   2  |  2   |   0  |   1  |     |
| G     |   3   |   3  |  2  |  1   |  1   |  1   |   0  |     |

$C_C(G) = \frac{7 - 1}{3 + 3 + 2 + 1 + 1 + 1 } = \frac{6}{11} = 0.5,$

* **Betweenness Centrality**


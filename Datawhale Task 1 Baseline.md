### 任务目标
了解实验环境和跑模型的流程，熟悉官方的baseline

### 相关化学知识与数据
- 化学分子的SMILES表达式，即Simplified Molecular Input Line Entry System，是用ASCII字符表示一个具有空间立体结构的分子结构所使用的一种语言规范。
  - SMILES字符串一般是有原子符号，化学键，以及标记支链所需要的括号
  - 此次官方发布的数据的字段有 rxnid, Reactant1, Reactant2, Product, Additive, Solvent, Yield
- RDKit http://www.rdkit.org 开源化学信息工具箱，提供了大量对化学分子的2D或3D计算操作 


### 建模
- 模型：随机森林
  - 参数有决策树的个数、深度，根据属性划分节点的最少样本数，叶子节点最少样本数
- 库：sklearn
- 后续：学调参

### 往期优秀笔记参考
https://exn8g66dnwu.feishu.cn/sheets/M4LFsR8oAhnFKZtGdZHcDJn4ncg?from=from_copylink
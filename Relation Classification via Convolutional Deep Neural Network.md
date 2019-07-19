# 基于深度卷积网络的关系分类
中科院自动化所（2014）

## 引言
- 关系分类定义： 识别/正确分类两个实体e<sub>1和e<sub>2间的关系
### 过往研究
- 有监督的方法
  1. feature-based： 通过文本分析提取特征，根据类似词袋模型（bag-of-ords model）的pardigm将特征转为向量
  2. kernel-based: 需要将数据处理为语义树的形式（pre-process input data in the form of parse trees, such as dependency parse trees ）
  3. 有监督方法的问题： 有监督方法多依赖现有的NLP工具来处理数据，这些现有方法带来的误差可能会在之后的训练中传播，并影响模型的表现
  

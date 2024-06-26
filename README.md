## 飞机打单词小游戏（记忆单词工具）
###  技术
* 原生JavaWeb开发（无maven）
- 原生html5、css3，引入jQuery和vue3的js包
* MySQL数据库、druid数据连接池
### 算法
余弦相似度匹配算法(本项目针对形似单词的筛选)  

**简单介绍**：余弦相似度（Cosine Similarity）是一种常用的度量两个非零向量方向相似程度的方法，广泛应用于文本分析、推荐系统和其他机器学习领域中。这种算法通过计算两个向量间夹角的余弦值来评估它们的相似性。

**算法步骤**

1. **向量化**：首先，将待比较的对象（如文本或商品属性）转换成数值向量。

2. **计算余弦值**：余弦相似度的计算公式为：
   cos(x) = A*B / |A||B|
3. **解释结果**：计算得出的余弦值范围从 -1 到 1。值为 1 表示两个向量在同一方向，即完全相同；值为 0 表示两者正交，即完全不相关；值为 -1 表示两者完全相反。

# Linear Algebra and Its Application (Third Edition) 线性代数及其应用
- (美) 莱(Lay D.C.)
- 本书主要内容包括`线性方程组`、`矩阵代数`、`行列式`、`向量空间`、`特征值`与`特征向量`、
  `正交性`和`最小二乘法`、`对称矩阵`和`二次型`等. 此外, 本书包含大量的练习题、
  习题、例题等, 便于读者参考. 

## Table Of Contents
- 译者序
- 关于作者
- 前言
- 给学生的注释
- 第 1 章 线性代数中的线性方程组
    + 介绍性实例 经济学与工程中的线性模型
    + 1.1 线性方程组
    + 1.2 行化简与阶梯形矩阵
    + 1.3 向量方程
    + 1.4 矩阵方程
    + 1.5 线性方程组的解集
    + 1.6 线性方程组的应用
    + 1.7 线性无关
    + 1.8 线性变换介绍
    + 1.9 线性变换的矩阵
    + 1.10 经济学、科学和工程中的线性模型
    + 第 1 章 补充习题
- 2章 矩阵代数
    + 介绍性实例 飞机设计中的计算机模型
    + 2.1 矩阵运算
    + 2.2 矩阵的逆
    + 2.3 可逆矩阵的特征
    + 2.4 分块矩阵
    + 2.5 矩阵因式分解
    + 2.6 列昂惕夫投入产出模型
    + 2.7 计算机图形学中的应用
    + 2.8 Rn 的子空间
    + 2.9 维数与秩
    + 第 2 章 补充习题
- 第 3 章 行列式
    + 介绍性实例 解析几何中的行列式
    + 3.1 行列式介绍
    + 3.2 行列式的性质
    + 3.3 克拉默法则、体积和线性变换
    + 第 3 章 补充习题
- 第 4 章 向量空间
    + 介绍性实例 空间飞行与控制系统
    + 4.1 向量空间与子空间
    + 4.2 零空间、列空间和线性变换
    + 4.3 线性无关集和基
    + 4.4 坐标系
    + 4.5 向量空间的维数
    + 4.6 秩
    + 4.7 基的变换
    + 4.8 差分方程中的应用
    + 4.9 马尔可夫链中的应用
    + 第 4 章 补充习题
- 第 5 章 特征值与特征向量
    + 介绍性实例 动力系统与斑点猫头鹰
    + 5.1 特征向量与特征值
    + 5.2 特征方程
    + 5.3 对角化
    + 5.4 特征向量与线性变换
    + 5.5 复特征值
    + 5.6 离散动力系统
    + 5.7 微分方程中的应用
    + 5.8 特征值的迭代估计
    + 第 5 章 补充习题
- 第 6 章 正交性和最小二乘法
    + 介绍性实例 重新整理北美地质数据
    + 6.1 内积、长度和正交性
    + 6.2 正交集
    + 6.3 正交投影
    + 6.4 格拉姆-施密特方法
    + 6.5 最小二乘问题
    + 6.6 线性模型中的应用
    + 6.7 内积空间
    + 6.8 内积空间的应用
    + 第 6 章 补充习题
- 第 7 章 对称矩阵和二次型
    + 介绍性实例 多波段的图像处理
    + 7.1 对称矩阵的对角化
    + 7.2 二次型
    + 7.3 条件优化
    + 7.4 奇异值分解
    + 7.5 图像处理和统计学中的应用
    + 第 7 章 补充习题
- 附录A 简化形阶梯矩阵的惟一性
- 附录B 复数
- 术语表
- 奇数习题答案


## New Words



## Content
### 给学生的注释
这门课程是最有趣、最有价值的大学数学课程. 事实上, 一些学生在毕业以后告诉我他们在大公司的工作中或工程研究生院的学习中还使用本教材作为参考书. 下面的注释给出一些建议和信息、有助于你掌握课本内容并且从中得到乐趣

==在线性代数中, 概念和计算同样重要.== 每个习题集开始的简单数值练习仅仅帮助你检査对基本步骤的理解. 以后, 虽然计算机会进行数值计算, 但你必须选取计算方法, 知道如何解释结果, 并且向其他人解释结果. 由于这个原因, 课本中的许多习题要求你解释或验证计算. 书面解释经常是习题答案的一部分, 对奇数习题, 会有一个期望的解释或者好的提示. **在独立写出答案之前应尽量避免査阅这些答案, 否则, 你会认为你已理解实际上并不懂的问题.**

==为掌握线性代数的概念, 你必须仔细地反复阅读本书.== 新的术语用黑体标示, 有时写在定义框中. 书的最后给出一个术语表, 便于参考. **重要的命题以定理的形式给出或放在方框中.** 最好阅读一下前言中对本书结构的介绍, 以对课程的框架有初步的理解.

**实际上, 线性代数是一种语言, 必须用学习外语的方法每天学习这种语言.** 理解每一节的内容并不容易, 除非你已透彻地学习教材且全部做出该节前面的练习, 跟上课程的进度会帮助你节约很多时间和解决很多困惑!

#### 数值计算的注解
希望你阅读课本中的 "数值计算的注解"(即: 书中黑色字体标注的 **数值计算的注解**), 即使你现在没有在学习过程中使用计算机或图形计算器. 在实际生活中, 线性代数的大多数应用涉及一定数值误差限制下的数值计算, 即使误差相当小. *"数值计算的注解" 会指出你以后工作中使用线性代数的潜在困难*, 如果现在学习了这些注释, 你以后就会容易记起这些内容.

如果你对 "数值计算的注解" 有兴趣, 以后可以学习一门**线性代数的数值计算**课程. 由于对计算机处理能力的更高需求, 需要计算机科学家和数学家给出更快、更可靠的线性代数的数值算法, 需要电子工程师设计出更快和更小的计算机去运行这些算法. 这是一个令人激动的领域, 线性代数的第一堂课有助于你做好准备

#### 学习指导
为帮助你成功学习这门课程, 我写了一本配合本书的 "学习指导"($^*)$ . 它不仅有助于你学习线性代数, 而且说明了如何学习数学. 它包含每第三个奇数习题的详细解答, 以及课本答案仅有提示的奇数写作题的附加答案. "学习指导" 还给出常见错误的警告、重点习题的有用提示和潜在考试题, 且有一个单独的各章术语表(考试复习时很有用). 此外,  "学习指导" 还介绍了如何使用 `MATLAB`、`Maple`、`MatheMatica` 和 `T1`、`HP` 图形计算器, 使用这些技术可以节约完成作业的时间.
* "学习指导" 即: `Study Guide` Linear Algebra And Its Applications

需要注意的是, 之所以将 "学习指导" 与教材分开, 是因为你必须在没有太多的帮助下独立完成作业. 多年的经验使我知道太容易査到(如教材后面的)解答会妨碍学生数学能力的开发. 前几周的学习会培养出整个学期的学习习惯, 并影响到学习效果. 我将 "学习指导" 的第 1 章放在网上, 你可以在获得 "学习指导" (ISBN0-201-77013-X)之前就开始学习. 请先阅读 "如何学习线性代数" , 在学习 1.4 节和 1.7 节时, 再按照 "掌提缄性代数概念" 的指导去做. 我的学生认为这些建议很有帮助, 希望你也有同感. 献上最好的祝愿.
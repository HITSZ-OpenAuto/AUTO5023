# AUTO5023 - 凸优化与最优控制

![考查课](https://img.shields.io/badge/%E8%80%83%E6%9F%A5%E8%AF%BE-green)
![学分](https://img.shields.io/badge/%E5%AD%A6%E5%88%86-2-moccasin)
![本研共通](https://img.shields.io/badge/本研共通-lightskyblue)

![成绩构成](https://img.shields.io/badge/%E6%88%90%E7%BB%A9%E6%9E%84%E6%88%90-gold)
![随堂测验10%](https://img.shields.io/badge/随堂测验-10%25-wheat)
![作业20%](https://img.shields.io/badge/%E4%BD%9C%E4%B8%9A-20%25-wheat)
![期末考试70%](https://img.shields.io/badge/%E6%9C%9F%E6%9C%AB%E8%80%83%E8%AF%95-70%25-wheat)

2024 年秋情况：**无随堂测验**，作业（含凸优化习题以及最优控制大作业）占比为 30%，期末考试占比为 70%。

## 课程内容介绍

课程名称为“凸优化与最优控制”，其中用于讲解凸优化的课时占了约四分之三，尽管李衍杰老师每年都想要给“最优控制”多分配些课时。

### 教材与参考书

凸优化部分的参考教材是 *Convex Optimization*, [Stephen Boyd](http://www.stanford.edu/~boyd/) & [Lieven Vandenberghe](http://www.ee.ucla.edu/~vandenbe/)。课上所使用的课件截取自配套课件（可从教材[官网](https://web.stanford.edu/~boyd/cvxbook/)下载）。

最优控制部分的参考书有：

1. A. E. Bryson and Y. C. Ho, Applied Optimal Control, New York: Taylor & Francis, 1975.
2. D. E. Kirk, Optimal Control Theory an Introduction, New York, Dover Publication Inc., 2004.
3. D. P. Bertsekas, Dynamic Programming and Optimal Control, Athena Scientific, 2007.

### 主要内容

{{% details title="第一讲 绪论" closed="true" %}} 主要内容是：凸优化与最优控制简介，包括各种凸优化和最优控制应用的实例。 {{% /details %}}

{{% details title="第二讲 凸集" closed="true" %}} 主要内容是：凸集的定义和例子，**证明某集合是凸集的方法（重点）**，保持集合凸性的运算，广义不等式。 {{% /details %}}

{{% details title="第三讲 凸函数" closed="true" %}} 主要内容是：凸函数的定义和例子，**证明某函数是凸函数的方法（重点）**，保持函数凸性的运算，共轭函数，准凸函数，对数凹函数和对数凸函数，关于广义不等式的凸性。 {{% /details %}}

{{% details title="第四讲 凸优化问题" closed="true" %}} 主要内容是：凸优化问题及其特殊实例，如线性规划、二次规划、二阶锥规划和半定规划等；**各种优化问题之间的转化（重点）**，例如将非凸优化问题转化为凸优化问题，将非线性规划问题转化为线性规划问题等。 {{% /details %}}

{{% details title="第五讲 对偶理论" closed="true" %}} 主要内容是：拉格朗日对偶理论，对偶优化问题及其几何解释，KKT条件。**这一讲都挺重要的，需要掌握其中的概念及推导。** {{% /details %}}

{{% details title="第六讲 无约束和等式约束" closed="true" %}} 主要内容是：梯度方法、最速下降法和**牛顿法（重点）**，几乎不讨论收敛性分析。补充介绍了 Gauss-Newton 法。此外，还走马观花地讲了讲数值线性代数的知识，其中包括 Cholesky 分解、QR 分解、奇异值分解等常用的矩阵分解以及算法复杂度等。 {{% /details %}}

{{% details title="第七讲 内点法" closed="true" %}} 主要内容是：不等式约束优化问题的对数障碍函数方法（即“内点法”），关于内点法的收敛性只给出了多种解释而不讨论严格的收敛性分析。此外，简单提及了广义不等式约束优化问题和主对偶内点优化算法。 {{% /details %}}

{{% details title="第八、九讲 动态优化与最优控制（重点）" closed="true" %}} 主要内容是：动态优化问题（最优控制问题）的三大方法——变分法、庞德里亚金最大值原理和动态规划，以及最优控制的数值解法。 {{% /details %}}

> 文 / [Hye](https://github.com/Co-ding-Man), 2025.1

## 授课教师

- 李衍杰
  - 课堂轻松愉悦，时常插入一些有趣的题外话。讲课节奏不快（甚至略显拖沓），有时会在一些具体示例上花很长时间讲解。不太点名。
  - 听课建议：可以重点听听优化问题之间的转化。
  - ~~课内知识我跳帧听讲，课外唠嗑我逐字分享。~~

> 文 / [Hye](https://github.com/Co-ding-Man), 2025.1

<!-- ## 关于作业 -->

## 关于考试

允许携带一张A4纸。可以带计算器（但基本用不上）。

这门考试的考点其实是很明确的，因为所讲的内容确实不多。凸优化中的复杂证明在课上就不会讲到，而是被当作“对我们没有什么用处”的“纯粹的数学”一笔带过（笑）。而最优控制问题中的复杂计算又难以考查。考试中最难的也就是一些稍微需要技巧的证明（主要是优化问题之间的转化），如果之前没有了解具体方法未必能想出证法，不过好在这些在课上都会讲到。

> 文 / [Hye](https://github.com/Co-ding-Man), 2025.1

## 学习建议

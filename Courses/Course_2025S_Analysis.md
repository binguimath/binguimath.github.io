# 2025 春季, 分析 II (H)





- 助教: 刘晗  秦楷

- Office hour: 鉴于以往的固定office hour时间段没有同学来，因此本课程不设置固定的office hour时间。欢迎单独约时间。
  
- 办公室: 双清综合楼A座C648
  
- Grades: 10% 出勤 + 20% 作业 + 30% 期中 + 40% 期末
> 按照书院要求，必修课的出勤应设为总成绩的10%~20%。因此，将出勤算入最终成绩并非出于本人意愿。
  
- 作业格式: 中文和英文皆可。每次作业请把所有解答合并为一个**单独的pdf文件**之后上传到网络学堂-课程作业。为了便于助教批改作业，请不要上传多个文件，请字迹尽量清晰，我们鼓励用LaTeX写作业。网络上很容易找到把多个pdf文件合并为单个文件的网页，例如[这个](https://www.ilovepdf.com/merge_pdf)。

## 关于课程

本课程计划大致涵盖以下讲义的后半部分（第20-36章）.

- [Qiuzhen Lectures on Analysis](https://binguimath.github.io/Pages/2023_Analysis.html)

> 以上链接包含讲义的最新版本以及若干历史版本。最新版本在课程结束后仍会更新，因此可能会与下面的Schedule中提到的章节或定理号不一致。一致的版本请参见链接中的2025.06.04版本，这是本课程期间更新的最后一个版本。
  
在前一两次课，我们会大致介绍一些关于网和拓扑空间的基本概念，对应于讲义第5,7,8章的部分内容。 Folland的书*Real Analysis*第4章也是不错的参考资料。

## Schedule

> 日期旁边括号里的数字代表已教的课时数

- 2/17（3） 引论（Riesz-Fischer定理；课程前半部分的主线：逐点收敛、弱收敛/弱紧性、对偶空间与表示定理。）

  网的基本定义，Cauchy网，网收敛刻画Hausdorff空间，函数连续性，网收敛决定拓扑，“逼近的逼近是逼近”，乘积拓扑与逐点收敛，无序和

  讲义章节：5.2.1，5.2.2，5.2.5（请大家补充定理5.38（完备度量空间里的Cauchy net收敛）的证明细节），7.2.2，7.3.1，7.4.1，7.4.2，7.5（乘积拓扑部分），5.3（刚开了个头）
  
- 2/19（5） 无序和，子网，网的cluster point，紧性和网的cluster point的关系，度量空间的紧性和列紧性，可数性条件（可分、第二可数、Lindelöf）

  讲义章节：5.3，5.2.3，8.3，8.5。课堂上涉及网的cluster point的部分在7.9.1节内。也见3.5节开头关于序列的cluster point的部分。

  课后阅读：8.6.2节开头到Prop. 8.42（LCH空间的基本性质），15.4节开头到Def. 15.21（紧包含的概念）

- 2/24（8） 内积空间，完备性与正交级数收敛性的等价，Hilbert空间同构于l^2(X)

  讲义章节：20， 21.1，21.2（讲到Cor. 21.6）

- 2/26（10） 关于闭子空间的正交分解，算子范数，Riesz-Fréchet表示定理，有界算子与有界sesquilinear form的等价性，对偶空间，Banach-Alaoglu定理

  讲义章节：21.2，10.5，21.3

  注：Banach-Alaoglu定理见17.3.1节，算子范数完备性见17.6.1节的定理17.34. 对同构 l^2(X)*≃l^2(X) 的证明见17.4.2节的定理17.30.
  
  注：我们在课上提到了Banach-Alaoglu定理使得对函数空间的对偶空间的研究变得重要。相关的数学问题为moment problem，可见17.5节。

- 3/3（13） 内积空间中的弱收敛，Fatou引理，单位闭球的弱紧性

  Hilbert空间的历史：从Dirichlet problem到积分方程到l^2(Z)，全连续算子，Hilbert-Schmidt算子（即矩阵表示为l^2的算子）是全连续的

  讲义章节：21.4，22.1-22.4

- 3/5（15） Hilbert空间的历史：Hilbert-Schmidt定理（即全连续自伴算子的对角化定理），从全连续算子到紧算子

  Lebesgue用切割codomain来定义积分

  讲义章节：22.5，22.7，23.1

  注：我们课上提到了在历史上，全连续sesquilinear form的概念如何演变成全连续算子的概念，最后出于研究非自反空间的需要而变成了紧算子的概念。关于这三个概念在Hilbert空间上的等价性我们课上没有证明。感兴趣的同学可以阅读22.7节。

  课后阅读：15.4.2，15.4.3（Urysohn引理和单位分解）

- 3/10（18） 依测度收敛与Lebesgue有界收敛定理，可测空间，测度空间，外测度与内测度，正则性的定义

  讲义章节：23.1-23.3，23.5（开头）

  注：更多关于依测度收敛和有界/控制收敛定理的关系的讨论，可见24.4.2节。

- 3/12（20） 用正则性构造测度，简单函数的积分

  讲义章节：23.4，23.5，24.1.1

  注：一种常见的且普世的构造测度的方法为Caratheodory方法，可见Folland的Real Analysis或者于品的数学分析讲义。关于课上讲的正则性构造测度法和Caratheodory方法的联系，以及与Lebesgue原本用正则性构造测度的联系，感兴趣的同学可以阅读课程讲义23.6节。

  课后阅读：15.4.5（Tietz扩张定理）

- 3/17（23） 简单函数的积分扩张为可测函数的积分（单调收敛扩张法之例一），收敛定理，Radon测度

  讲义章节：24.1.2，24.1.3，24.1.4，24.2，24.3，25.1（介绍了outer regular，inner reguar，以及Radon measure的定义）

- 3/19（25） 紧支集连续函数上的正线性泛函扩张为下半连续函数上的正线性泛函（单调收敛扩张法之例二），Riesz-Markov表示定理

  讲义章节：25.1-25.3

- 3/24（28） Radon测度在有限（外）测度可测集上的正则性，Lusin定理，Radon测度的判定法则，Stieltjes积分，C[a,b]上正线性泛函的Riesz表示定理

  讲义章节：25.4-25.7

- 3/26（30）乘积测度与Fubini定理

  讲义章节：26.1，26.2

- 3/31（33）L^p空间，L^p-L^q对偶（作为引论与动机），L^p空间的Cauchy完备性

  讲义章节：27.1-27.4

- 4/2（35）自伴算子谱定理：算子值Stieltjes 积分，多项式函数演算的正性，多项式上的正线性泛函的扩张

  讲义章节：25.8，25.9.1，25.9.2

- 4/7（38）自伴算子谱定理：多项式函数演算扩张为半连续函数演算（单调收敛扩张法之例三），连续函数演算的Stieltjes积分表示

  R^n上的微分与Jacobian，链式法则，C^1推出可微

  讲义章节：25.9.3，19

- 4/9（40）反函数定理，隐函数定理的子流形解释

  讲义章节：28.1，28.2，28.3（介绍完R^n中的（嵌入）子流形的定义，即定义28.14）

- 4/14 期中考试

- 4/16（42） 隐函数定理的子流形解释，微分流形及其子流形

  讲义章节：28.3，28.4

- 4/21（45） 子流形的判定，流形的切向量和与切向量场，映射的微分，向量场和1-形式

  讲义章节：28.5，28.6，29.1-29.3，29.4（讲完df的定义，Rem. 29.17）

- 4/23（47） 函数的differential的计算，1-形式的拉回，流形映射的反函数与隐函数定理，光滑嵌入的判定法则

  讲义章节：29.4，29.5

  请大家自行阅读29.6节关于Lagrange multipliers的内容

- 4/28（50）带边流形的基本性质、切空间、映射的微分，不带边流形的带边子流形，隐函数定理作为带边子流形的判定法则

  讲义章节：30.1-30.3，30.4.1

- 5/7（52）带边流形嵌入的判定法则，重积分换元公式的证明思路

  讲义章节：30.4.3，30.5，31.1，31.2.1

  课后阅读：30.5节最后的Thm. 30.65和Cor. 30.66（关于子流形的子流形的讨论），30.6节（光滑Urysohn引理和光滑单位分解），30.7.1节（光滑函数在紧支集连续函数空间中以及L^p空间中的稠密性）

- 5/10（55）重积分换元公式的严格证明，张量积的引入

  讲义章节：31.2.2，31.3，31.4，32.1，32.2（刚介绍完张量积的存在性，即Exp. 32.7的叙述）

- 5/12（58）张量积的存在性、唯一性、判定方法，张量积的加括号原则，线性映射的张量积，对偶空间的张量积，对称张量积

  张量场，带边黎曼流形与黎曼度量，黎曼度量拉回的计算，任意带边流形上都存在黎曼度量

  讲义章节：32.2-32.5，33.1-33.2

- 5/14（60）带边黎曼流形上的体积测度，标量值函数的积分，反对称张量的基本概念，通过对维数的归纳法来构造反对称张量积

  讲义章节：33.3，34.1.1，34.1.2（几乎讲完）

  课后阅读：33.4节

- 5/19（63）Exterior power的基，线性映射的exterior power，反对称张量的外积，完美配对，Riesz同构，对偶与exterior power的交换性，线性空间的定向，Cauchy-Binet公式，内积、对偶、exterior power之间的相容性，体积张量

  讲义章节：31.4.2，31.4.3，34.2-34.5（几乎讲完，讲到体积张量的定义）

- 5/21（65）内积空间体积张量的计算，微分形式，流形的Riesz isomorphism，流形的定向，黎曼流形的体积形式，方向的粘连

  讲义章节：34.5.2，35.1，35.2，35.3.1

- 5/26（68）坐标卡orientation compatible的判定，边界和超曲面的定向，微分形式的积分，R^n中的曲线积分

  讲义章节：35.3.2，35.4，35.5

- 5/28（70）Hodge星算子，向量的叉乘，单位正法向量场，超曲面积分表达为函数的积分和微分形式的积分

  讲义章节：35.6，35.7.1，35.7.2

- 6/4（72）利用向量场判定超曲面的可定向性，Stokes定理，散度定理

  讲义章节：35.7.3，36.1-36.3
  
  
  


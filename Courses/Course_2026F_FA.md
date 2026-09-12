<script>
window.MathJax = {
  tex: {
    inlineMath: [['$', '$'], ['\\(', '\\)']],
    displayMath: [['$$', '$$'], ['\\[', '\\]']]
  }
};
</script> 
<script defer src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>


<style>
details.literature {
  margin: 0 0 1.25rem 0;
}
</style>


# 2026 秋季, 泛函分析


- 课程时间地点：周一13:30-15:05 周三15:20-16:55 四教4304


- 助教: 李家琪

- Office hour: 鉴于固定的office hour时间段通常没有同学来，因此本课程不设置固定的office hour。欢迎单独约时间。
  
- 办公室: 双清综合楼A座C648
  
- 给分方式: 40%作业 + 60%期末
  
- 作业格式: 中文和英文皆可。每次作业请把所有解答合并为一个**单独的pdf文件**之后上传到网络学堂-课程作业。为了便于助教批改作业，请不要上传多个文件，请字迹尽量清晰，我们鼓励用LaTeX写作业。网络上很容易找到把多个pdf文件合并为单个文件的网页，例如[这个](https://www.ilovepdf.com/merge_pdf)。



- 本课程假设大家了解基本的点集拓扑和测度论结论，这些结论会在课程讲义（见下）的第一章中回顾。这些结论的证明可以在常见的教材中（例如Munkres的拓扑书，Folland或者Rudin的实分析书中）找到。本课程讲义主要引用
[Qiuzhen Lectures on Analysis](https://binguimath.github.io/Pages/2023_Analysis.html)


- 可以通过讨论、网上查资料、AI等方式来帮助自己理解课程与作业内容。但作业请大家用自己的理解来独立完成写作。严禁抄袭和照搬他人的作业或者AI的解答。若有查出照搬现成解答或AI解答的作业，当次作业算作0分。




## Lecture notes (in English)


- [Qiuzhen Lectures on Functional Analysis](https://binguimath.github.io/Pages/2025_FA.html)

<!--注意：以下Schedule中提到的定义与定理编号皆参照2026.06.09版的讲义。之后的讲义版本可能有编号变动。  -->


<!-- ## 参考书

- Reed, Simon. Methods of Modern Mathematical Physics, I.

- Simon. Operator Theory, a Comprehensive Course in Analysis IV.

- Van Neerven. Functional Analysis.

- Lax. Functional Analysis

-->

## 历史文献（GPT英译）
<details class="literature" markdown="1">
<summary><strong>展开/折叠</strong></summary>


- 1906 Hilbert. Grundzüge einer allgemeinen Theorie der linearen Integralgleichungen, Vierte Mitteilung. (Fundamentals of a General Theory of Linear Integral Equations, Fourth Communication.) [tex](https://binguimath.github.io/Pages/Classical/1906%20Hilbert_Fundamentals%20of%20a%20General%20Theory%20of%20Linear%20Integral%20Equations%20IV_GPT.tex)
[pdf](https://binguimath.github.io/Pages/Classical/1906%20Hilbert_Fundamentals%20of%20a%20General%20Theory%20of%20Linear%20Integral%20Equations%20IV_GPT.pdf)

> 在这篇文章中，Hilbert引入了Hilbert空间 $l^2$，引入了有界双线性型和紧双线性型（对应到现在的有界算子和紧算子）。Hilbert对紧对称双线性型证明了（离散的）谱分解定理，即现在所说的Hilbert-Schmidt定理。Hilbert对有界对称双线性型证明了一般的谱定理。对应讲义章节：3，4，5，8


- 1913 F.Riesz. Les systèmes d'équations linéaires à une infinité d'inconnues. (Linear Systems of Equations
with Infinitely Many Unknowns.) [tex](https://binguimath.github.io/Pages/Classical/1913%20F.Riesz_Linear%20systems%20of%20equations%20with%20infinitely%20many%20unknowns_GPT.tex)
[pdf](https://binguimath.github.io/Pages/Classical/1913%20F.Riesz_Linear%20systems%20of%20equations%20with%20infinitely%20many%20unknowns_GPT.pdf)


> 在第4和5章中，Riesz 利用函数演算和正线性泛函扩张，对Hilbert关于有界对称双线性型的谱定理进行了重新诠释和大大加强。现代教科书中对谱理论的处理更加接近Riesz的方法。对应讲义章节：5


- 1929 von Neumann. Allgemeine Eigenwerttheorie Hermitescher Funktionaloperatoren. (General Eigenvalue Theory of Hermitian Functional Operators.) [tex](https://binguimath.github.io/Pages/Classical/1929%20von%20Neumann_General%20eigenvalue%20theory%20of%20Hermitian%20functional%20operators_GPT.zip)
[pdf](https://binguimath.github.io/Pages/Classical/1929%20von%20Neumann_General%20eigenvalue%20theory%20of%20Hermitian%20functional%20operators_GPT.pdf)

> Von Neumann在这篇文章中建立了无界对称算子的谱理论。对应讲义章节：6

- 1932 von Neumann. Über adjungierte Funktionaloperatoren. (On adjoint functional operators.) 
[tex](https://binguimath.github.io/Pages/Classical/1932%20von%20Neumann_On%20adjoint%20functional%20operators_GPT.tex)
[pdf](https://binguimath.github.io/Pages/Classical/1932%20von%20Neumann_On%20adjoint%20functional%20operators_GPT.pdf)

> Von Neumann 在这篇文章中对（不一定对称的）无界算子引入了闭算子、闭包、可闭、伴随算子等概念及其基本性质，对于闭算子，von Neumann 证明了极分解定理。对应讲义章节：6，7


</details>

## Schedule

课程安排与26年春季的泛函分析课程大致相当。想要提前了解计划进度的同学可查看该课的[课程主页](https://binguimath.github.io/Courses/Course_2026S_FA.html)。


1) 9/14


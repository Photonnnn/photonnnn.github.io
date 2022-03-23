---
html:
  toc: false
---

<head>
    <script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>
    <script type="text/x-mathjax-config">
        MathJax.Hub.Config({showMathMenu: false,
            tex2jax: {
            skipTags: ['script', 'noscript', 'style', 'textarea', 'pre'],
            inlineMath: [['$','$']]
            }
        });
    </script>
</head>

$\LaTeX$ Competition
----
----

#### 说明
* 本套题目完全在 `vscode` 中利用 `Markdown` 和 `Latex` 完成编辑。
  * 如果你使用 `Markdown`，其对 `Latex` 的支持已足以完成本套试题。
  * 如果你使用 `Latexstudio`，`vscode` 或 `overleaf` 等编写 `.tex` 文件，请注意：
    * 你需要使用宏包 `amsmath`，`mathrsfs`。这也是你唯二被允许使用的宏包（如果使用其他宏包该题目分数将受到影响）。宏包使用方法是在导言区（即 `\begin{document}` 之前）添加 `\usepackage{amsmath,mathrsfs}`。
    * 请不要修改数学字体，使用默认的数学字体。
* 题目原则上不设标准答案，使用**简洁规范**的语句完成排版即可，但下一条列出了在此基础上需要遵循的规则。
* 所有排版结果需按照**试题原始格式**，不得进行任何简化或变形，即使二者在物理或数学逻辑下完全等价。例如 $\dfrac{\dfrac{a}{c}+1}{b}$（两层分式均为行间格式） 不允许排版为 $\dfrac{\frac{a}{c}+1}{b}$（分子的分式是行内 inline 格式）或 $[(a/c)+1]/b$（这不是分式格式）。又例如 $\left(\dfrac{a}{b}\right)^2$ （这里的括号是定界符）不允许排版为 $(\dfrac{a}{b})^2$（这里的括号是普通括号）。否则将影响分数甚至判错。
* 建议的参考文档是 `lshort-zh-cn.pdf`。
* 如有其他问题请联系物理学院学术部。

#### 试题

* 请排版 Einstein 场方程（请注意作为常量的 pi 应当是直立体，但在这里不作要求）
$$
R_{ik}-\frac{1}{2}g_{ik}R = \frac{8\pi k}{c^4}T_{ik}
$$
* 请排版磁介质的一个热力学关系
$$
C_{\mathscr{H}}-C_{\mathscr{M}}=\mu_0T\left(\frac{\partial\mathscr{H}}{\partial T}\right)^2_{\mathscr{M}}\left(\frac{\partial\mathscr{M}}{\partial{\mathscr{H}}}\right)_T
$$
* 请排版电荷守恒定律的积分形式
$$
\oint_S \boldsymbol{J}\cdot\mathrm{d}\boldsymbol{S}=\int_V\nabla\cdot\boldsymbol{J}\mathrm{d}V
$$
* 请排版一个一维无限深势阱的势能
$$
V(x)=\begin{cases}
    0,0<x<d\\
    \infty,x\ge d,x\le0
\end{cases}
$$
* 请排版历史上第一个人工核反应的反应式
$$
\alpha + {^{14}\mathrm{N}}\longrightarrow\mathrm{p}+{^{17}\mathrm{O}}
$$
* 请排版 Bessel 方程的一个特解
$$
y_1(x)=\sum_{n=0}^\infty\frac{(-1)^n\Gamma(\nu+1)C_0}{2^{2n}n!\Gamma(\nu+n+1)}x^{2n+\nu}
$$
* 请排版 Poisson 方程
$$
\Delta u = u_{x_1x_1}+u_{x_2x_2}+\cdots+u_{x_nx_n}=0
$$
* 请排版刚体旋转产生进动角时的变换矩阵
$$
\boldsymbol{A}_{\varphi}=\begin{pmatrix}
    \cos\varphi & \sin\varphi & 0\\
    -\sin\varphi & \cos\varphi & 0\\
    0 & 0 & 1
\end{pmatrix}
$$

* 请排版广义坐标下的 Lagrange 函数
$$
L = \frac{1}{2}\sum_{i,k}a_{ik}(q)\dot{q}_i\dot{q}_k-U(q)
$$
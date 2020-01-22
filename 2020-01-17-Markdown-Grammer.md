---
title: "Markdown Grammer"
date: 2020-01-17
categories: [Blogging]
tags: [typography]
---

# Markdown使用

```markdown
# 一级标题
## 二级标题
### 三级标题
```

##  Markdown(LaTex)

需要使用$$(行内) 或double(独行) 

### 常见符号

|            符号             |         markdown          |
| :-------------------------: | :-----------------------: |
|            $x_i$            |            x_i            |
|            $x^i$            |            x^i            |
|        $V_\mbox{我}$        |        V_\mbox{我}        |
|     $\underline {x+y}$      |     \underline {x+y}      |
|            $\to$            |            \to            |
|          $\infty$           |          \infty           |
|           $\sum$            |           \sum            |
| $\sum\limits_{i=1}^{n}f(i)$ | \sum\limits_{i=1}^{n}f(i) |
|          $\times$           |          \times           |
|           $\div$            |           \div            |
|            $\pm$            |            \pm            |
|            $\mp$            |            \mp            |
|           $\circ$           |           \circ           |
|         $A\cdot B$          |         A \cdot B         |
|         $A \ast B$          |         A \ast B          |
|       $\frac {A}{B}$        |       \frac {A}{B}        |
|         $A \over B$         |         A \over B         |
|           $\leq$            |           \leq            |
|           $\geq$            |           \geq            |
|            $\in$            |            \in            |
|        $A \subset B$        |        A \subset B        |
|        $A \supset B$        |        A \supset B        |
|         $A \neq B$          |         A \neq B          |
|         $A\not = B$         |         A\not = B         |
|         $A \ngeq B$         |         A \ngeq B         |
|         $A \nleq B$         |         A \nleq B         |
|        $A \not > B$         |        A \not > B         |
|         $A \not< B$         |         A \not< B         |
|        $\leftarrow$         |        \leftarrow         |
|        $\rightarrow$        |        \rightarrow        |
|      $\longrightarrow$      |      \longrightarrow      |
|       $A \uparrow B$        |       A \uparrow B        |
|      $A \downarrow B$       |      A \downarrow B       |
|          $\nabla$           |          \nabla           |
|          $\ang A$           |          \ang A           |
|         $\forall x$         |         \forall x         |
|         $\exist x$          |         \exist x          |
|        $\phi \prime$        |        \phi \prime        |
|         $\exists x$         |         \exists x         |

### 希腊字母

| 字母读法 |    字母显示    | Markdown写法 |
| :------: | :------------: | :----------: |
| alpha大  |    $\Alpha$    |    \Alpha    |
| alpha小  |    $\alpha$    |    \alpha    |
|   beta   |    $\Beta$     |    \Beta     |
|          |    $\beta$     |    \beta     |
|  gamma   |    $\Gamma$    |    \Gamma    |
|          |    $\gamma$    |    \gamma    |
|  delta   |    $\Delta$    |    \Delta    |
|          |    $\delta$    |    \delta    |
|   梯度   |    $\nabla$    |    \nabla    |
| epsilon  |   $\Epsilon$   |   \Epsilon   |
|          |   $\epsilon$   |   \epsilon   |
|   zeta   |    $\Zeta$     |    \Zeta     |
|          |    $\zeta$     |    \zeta     |
|   eta    |     $\Eta$     |     \Eta     |
|          |     $\eta$     |     \eta     |
|  theta   |    $\Theta$    |    \Theta    |
|          |    $\theta$    |    \theta    |
|   iota   |    $\Iota$     |    \Iota     |
|          |    $\iota$     |    \iota     |
|  kappa   |    $\kappa$    |    \kappa    |
|          |    $\Kappa$    |    \Kappa    |
|  lambda  |   $\Lambda$    |   \Lambda    |
|          |   $\lambda$    |   \lambda    |
|    Mu    |     $\Mu$      |     \Mu      |
|          |     $\mu$      |     \mu      |
|    Xi    |     $\Xi$      |     \Xi      |
|          |     $\xi$      |     \xi      |
| omicron  |      $o$       |      o       |
|          |      $O$       |      O       |
|    Nu    |      $N$       |      N       |
|  omega   |    $\Omega$    |    \Omega    |
|          |    $\omega$    |    \omega    |
|    pi    |     $\Pi$      |     \Pi      |
|          |     $\pi$      |     \pi      |
|   rho    |     $\Rho$     |     \Rho     |
|          |     $\rho$     |     \rho     |
|  sigma   |    $\Sigma$    |    \Sigma    |
|          |    $\sigma$    |    \sigma    |
|   tau    |     $\Tau$     |     \Tau     |
|          |     $\tau$     |     \tau     |
| upsilon  |   $\Upsilon$   |   \Upsilon   |
|          |   $\upsilon$   |   \upsilon   |
|   Phi    |     $\Phi$     |     \Phi     |
|          |     $\phi$     |     \phi     |
|   chi    |     $\Chi$     |     \Chi     |
|          |     $\chi$     |     \chi     |
|   psi    |     $\Psi$     |     \Psi     |
|          |     $\psi$     |     \psi     |
|          |      $\P$      |      \P      |
|   空心   |  $\mathbb{A}$  |  \mathbb{A}  |
|          |  $\mathbb{R}$  |  \mathbb{R}  |
|   花体   | $\mathfrak{B}$ | \mathfrak{B} |
|          | $\mathfrak{A}$ | \mathfrak{A} |

### 函数分段

$$
f(x) = 
\begin{cases}
0 &\mbox{if x$\geq 0$}\\
x &\mbox{if x < 0} \\
\end{cases}
$$

```latex
f(x) = 
\begin{cases}
0 &\mbox{if x$\geq 0$}\\
x &\mbox{if x < 0} \\
\end{cases}
```

### 公式推导

$$
\begin{aligned}
a + b + c &= a + (b + c)\\
&= (a + b) + c
\end{aligned}
$$

```latex
\begin{aligned}
a + b + c &= a + (b + c)\\
&= (a + b) + c
\end{aligned}
```


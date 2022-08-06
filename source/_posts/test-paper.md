---
title: test-paper
date: 2022-08-05 21:49:59
tags:
---

# 先看看能不能动起来

- First item
- Second item
- Third item
- Fourth item

$$
\require{AMScd}
\begin{CD}
    A @>a>> B \\
    @V b V V\# @VV c V \\
    C @>>d> D \\
\end{CD}
$$

$$
x = a_0 + \frac{1^2}{a_1 +
            \frac{2^2}{a_2 +
              \frac{3^2}{a_3 +
                \frac{4^4}{a_4 + 
                  \cdots
                }
              }
            }
          }
$$

$$
\begin{array}{c} % 总表格
    \begin{array}{cc} % 第一行内分成两列
        \begin{array}{c|cccc} % 第一列"最小值"数组
            \text{min} & 0 & 1 & 2 & 3 \\
            \hline
            0 & 0 & 0 & 0 & 0 \\
            1 & 0 & 1 & 1 & 1 \\
            2 & 0 & 1 & 2 & 2 \\
            3 & 0 & 1 & 2 & 3 \\
        \end{array}
        &
        \begin{array}{c|cccc} % 第二列"最大值"数组
            \text{max} & 0 & 1 & 2 & 3 \\
            \hline
            0 & 0 & 1 & 2 & 3 \\
            1 & 1 & 1 & 2 & 3 \\
            2 & 2 & 2 & 2 & 3 \\
            3 & 3 & 3 & 3 & 3 \\
        \end{array}
    \end{array} % 第一行表格组结束
    \\
    \begin{array}{c|cccc} % 第二行 Delta 值数组
        \Delta & 0 & 1 & 2 & 3 \\
        \hline
        0 & 0 & 1 & 2 & 3 \\
        1 & 1 & 0 & 1 & 2 \\
        2 & 2 & 1 & 0 & 1 \\
        3 & 3 & 2 & 1 & 0 \\
    \end{array} % 第二行表格结束
\end{array} % 总表格结束
$$


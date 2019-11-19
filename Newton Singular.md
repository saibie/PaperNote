$$
X_{i+1} = X_{i} - F'[X_{i}]^{-1}\left(F(X_{i})\right)\\~\\
\left\{\begin{array}{rl}
-F'[X_{i}](H_{i})&= F(X_{i}) \\
X_{i+1} &= X_{i} + H_{i}
\end{array}\right.
$$

$$
\textrm{Suppose that }s = \min\left\{\left|-\rho(F'[S])\right|\right\}
$$

$$
\begin{array}{rl}
-\mathcal{F'}[X_{i}]h_{i} - s\mathcal{I}h_{i} &= {\rm vec~}F(X_{i}) - sh_{i}\\
(-\mathcal{F'}[X_{i}] - s\mathcal{I})h_{i} &= {\rm vec~}F(X_{i}) - sh_{i}\\

\end{array}
$$

$$
\begin{array}{rl}
(-F'[X_{i}]-sI)(H_{i}) &= F(X_{i}) - sH_{i}\\

\end{array}
$$

### 아이고 의미없다



$$
\begin{array}{rl}
X_{0} &= 0 \\
X_{1} &= -F'[0]^{-1}(F(0)) \\
F'[0](X_{1}) &= -A_{0} \\
A_{1}X_{1} &= -A_{0} \\
X_{1} &= -A_{1}^{-1}A_{0} \\
\end{array}
$$

$$
\begin{array}{rl}
X_{2} &= X_{1} - F'[X_{1}]^{-1}(F(X_{1})) \\
F'[X_{1}](H_{1}) &= -F(X_{1}) = -\sum_{k=0}^{n} A_{k}X_{1}^{k} \\
\sum_{k=1}^{n}\sum_{l=0}^{k-1} A_{k}X_{1}^{l}H_{1}X_{1}^{k-1-l} &= -\sum_{k=0}^{n} A_{k}X_{1}^{k} \\
\left[\sum_{k=1}^{n}\sum_{l=0}^{k-1} (X_{1}^{T})^{k-1-l} \otimes A_{k}X_{1}^{l}\right]h_{1} &= -f(X_{1}) \\
\end{array}
$$

### 아이고 왜하냐 이걸


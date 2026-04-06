$$
p_{n}=\frac{\left|a_{n}\right|+a_{n}}{2},q_{n}=\frac{\left|a_{n}\right|-a_{n}}{2},
$$

$$
n=1,2,\cdots
$$

显然 $\sum p_{n}$ 和 $\sum q_{n}$ 都是正项级数，并且有

$$
\lim p_{n}=\lim\frac{\left|a_{n}\right|+a_{n}}{2}=0,
$$

$$
\lim q_{n}=\lim\frac{\left|a_{n}\right|-a_{n}}{2}=0,
$$

$$
\sum_{n=1}^{+\infty} p_{n}=\frac{1}{2}\sum_{n=1}^{+\infty}\left|a_{n}\right|+\frac{1}{2}\sum_{n=1}^{+\infty} a_{n}=+\infty,
$$

$$
\sum_{n=1}^{+\infty} q_{n}=\frac{1}{2}\sum_{n=1}^{+\infty}\left|a_{n}\right|-\frac{1}{2}\sum_{n=1}^{+\infty} a_{n}=+\infty.
$$

再来考察序列

$$
a_{1},a_{2},\cdots, a_{n},\cdots,
$$

我们以 $P_{n}$ 表示其中的第 $n$ 个非负项，以 $Q_{n}$ 表示其中的第 $n$ 个负项的绝对值。请注意，$\left\{P_{n}\right\}$ 是序列 $\left\{p_{n}\right\}$ 删去了一些等于 $0$ 的项之后剩下的子序列；$\left\{Q_{n}\right\}$ 是序列 $\left\{q_{n}\right\}$ 删去了一切等于 $0$ 的项之后剩下的子序列。因此

$$
\lim P_{n}=\lim Q_{n}=0,
$$

$$
\sum_{n=1}^{+\infty} P_{n}=\sum_{n=1}^{+\infty} Q_{n}=+\infty.
$$

我们依次考察 $P_{1},P_{2},\cdots$ 中的各项。设 $P_{m_{1}}$ 是其中第一个满足以下条件的项：

$$
P_{1}+\cdots+P_{m_{1}}>\xi.
$$

再依次考察 $Q_{1},Q_{2},\cdots$ 中的各项。设 $Q_{n_{1}}$ 是其中第一个满足以下条件的项：

$$
P_{1}+\cdots+P_{m_{1}}-Q_{1}-\cdots-Q_{n_{1}}<\xi.
$$

再依次考察 $P_{m_{1}+1},P_{m_{1}+2},\cdots$ 中的各项。设 $P_{m_{2}}$ 是其中第一个满足以下条件的项：

$$
P_{1}+\cdots+P_{m_{1}}-Q_{1}-\cdots-Q_{n_{1}}
+P_{m_{1}+1}+\cdots+P_{m_{2}}>\xi.
$$

照这样做下去，我们得到 $\sum a_{n}$ 的一个重排级数 $\sum a_{n}^{\prime}$ 如下：

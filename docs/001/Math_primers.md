# Math Primers

## System Performance
The discussion surrounding the performance of a system is often facilitated with the <wiki:Transfer_function> of a system that models the system's output for each possible input. For this course, our discussion is focused on the performance of linear and time-invariant ({term}`LTI`) systems in the continuous-time domain where the transfer function $H(s)$ is defined as:

$$
H(s)=\frac{Y(s)}{X(s)} = \frac{\mathcal{L}\{y(t)\}}{\mathcal{L}\{x(t)\}}
$$
where $x(t)$ and $y(t)$ are the input and output signals in the continuous-time domain, $\mathcal{L}\{\}$ is the Laplace transform operator, and $X(s)$ and $Y(s)$ are the Laplace-transformed versions of the input and the output signal, respectively. That is, the transfer function of a system is the ratio between the output and the input of the system after applying the Laplace transform.

Using the <wiki:Transfer_function>, one can study the transient behaviour and the stability of a given system. The Laplace transform is particularly valuable in control systems and signal processing because it converts **differential equations**, which describe the dynamic behaviour of sensors and actuators, into **algebraic equations** that are much easier to manipulate and solve.

## Laplace Transform

The <wiki:Laplace_transform> is an integral transform that converts a function of a real variable (usually $t$, in the time domain) to a function of a complex variable $s$ (in the complex-valued frequency domain, also known as the **s-domain** or **s-plane**). The Laplace transform is defined by the <wiki:integral>

$$
\mathcal{L}\{ f(t) \} = F(s) = \int_{-\infty}^{+\infty} f(t) e^{-st} dt
$$
where $s$ is a <wiki:Complex_number>. It should be noted that this integral is taken from $-\infty$ to $+\infty$.

Looking at this <wiki:integral> more closely, however, you should ask yourself these questions:
- What does it mean to raise $e$ to a rational number? or more importantly,
- What does it mean to raise $e$ to a complex number?
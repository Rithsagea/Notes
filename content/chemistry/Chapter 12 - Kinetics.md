---
title: "Chapter 12 - Kinetics"
---
## Rate Laws
The following is a generic definition of a rate law. These can be determined by examining experimental data, and analyzing how the reaction rate changes with respect to concentration.
$$
rate=k[A]^n[B]^m[C]^p...
$$
Order of reactions is written ordinally (zeroth, first, second, etc.). 
$$
order=n+m+p\ldots
$$
The following form is useful if multiple concentrations are changing, and a system is required to solve for rate.
$$
\begin{gather}
\ln{rate}=\ln{k}+n\ln{[A]}+m\ln{[B]}+p\ln{[C]}\ldots\\
\ln\frac{rate_1}{rate_2}=n\ln\frac{[A]_1}{{[A]_2}}+m\ln\frac{[B]_1}{{[B]_2}}+p\ln\frac{[C]_1}{{[C]_2}}\ldots
\end{gather}
$$
If you know calculus, you can probably ignore the next 3 sections. Everything is derived from basic expressions.
### 0th Order
$$\begin{gather}
\frac{d[A]}{dt}=k[A]^0\\
[A]=[A]\_0-kt\\
t_{\frac{1}{2}}=\frac{[A]_0}{2k}
\end{gather}$$
### 1st Order
$$
\begin{gather}
\frac{d[A]}{dt}=k[A]\\
\ln[A]=\ln[A]\_0-kt\\
[A]=[A]\_0e^{-kt}\\
t_{\frac{1}{2}}=\frac{\ln{2}}{k}
\end{gather}
$$
### 2nd Order
$$
\begin{gather}
\frac{d[A]}{dt}=k[A]^2\\
\frac{1}{[A]}=\frac{1}{[A]\_0}-kt\\
t_\frac{1}{2}=\frac{1}{k[A]_0}
\end{gather}
$$
## Reaction Mechanisms
Chemical reactions are often comprised of multiple elementary steps. (**rules for elementary steps matching original reaction**) The slowest reaction amongst these elementary reactions is the `rate-limiting` reaction.
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
Chemical reactions are often comprised of multiple elementary steps. The sum of these elementary steps must be identical to the original reaction in terms of reactants + products, as well as rate law. The slowest reaction amongst these elementary reactions is the `rate-limiting` reaction. The other reactions can be used in combination with the previous reaction's rate law to find the overall rate law of the reaction.
### Arrhenius Equation
Generally, activation energy is positive, and creates slower reactions at higher values. This is combined with the the steric factor, $p$, to create the **Arrhenius equation**, with a frequency factor $A$.
$$
\begin{gather}
k=zpe^{-E_a/RT}=Ae^{-E_a/RT}\\
\ln(k)=-\frac{E_a}{R}(\frac{1}{T})+\ln(A)
\end{gather}
$$
## Catalysis
Catalysts are materials that aid a chemical reaction, accelerating or retarding the reaction. **Homogenous catalysts** are in the **same state of matter** as the reactants, while a **heterogenous catalyst** is in a different phase (usually solids). For the latter, molecules are usually **adsorbed** (gathered on the surface). Meanwhile, homogenous catalysts can be transformed to intermediates, then back through a reaction process. Acids and bases can also be catalysts.
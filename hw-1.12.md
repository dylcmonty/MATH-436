\subsection*{Problem 12}

The grouped frequency distribution for CeO$_2$ particle sizes (nm) is:

\[
\begin{array}{c|cccccccccc}
\text{Class (nm)} & [3.0,3.5) & [3.5,4.0) & [4.0,4.5) & [4.5,5.0) & [5.0,5.5) & [5.5,6.0) & [6.0,6.5) & [6.5,7.0) & [7.0,7.5) & [7.5,8.0)\\
\hline
f & 5 & 15 & 27 & 34 & 22 & 14 & 7 & 2 & 4 & 1
\end{array}
\]
Total sample size:
\[
n=\sum f = 5+15+27+34+22+14+7+2+4+1 = 131.
\]

\begin{enumerate}
\item[(a)] Proportion of observations less than $5$:

All observations in classes below $5.0$ are counted: $[3.0,3.5),[3.5,4.0),[4.0,4.5),[4.5,5.0)$.
\[
f_{<5} = 5+15+27+34 = 81
\]
\[
\hat{p}(<5)=\frac{81}{131}\approx 0.6183.
\]
\textbf{Answer:} $\displaystyle \frac{81}{131}\approx 0.6183$.

\item[(b)] Proportion of observations at least $6$:

All observations in classes starting at $6.0$ or higher are counted: $[6.0,6.5),[6.5,7.0),[7.0,7.5),[7.5,8.0)$.
\[
f_{\ge 6}=7+2+4+1=14
\]
\[
\hat{p}(\ge 6)=\frac{14}{131}\approx 0.1069.
\]
\textbf{Answer:} $\displaystyle \frac{14}{131}\approx 0.1069$.

\item[(c)] Relative-frequency histogram and shape:

Relative frequency for each class is $r_i=f_i/n$ (bin width is $0.5$ nm):
\[
\begin{array}{c|cccccccccc}
\text{Class (nm)} & [3.0,3.5) & [3.5,4.0) & [4.0,4.5) & [4.5,5.0) & [5.0,5.5) & [5.5,6.0) & [6.0,6.5) & [6.5,7.0) & [7.0,7.5) & [7.5,8.0)\\
\hline
r_i & 0.0382 & 0.1145 & 0.2061 & 0.2595 & 0.1679 & 0.1069 & 0.0534 & 0.0153 & 0.0305 & 0.0076
\end{array}
\]
A relative-frequency histogram uses these $r_i$ values as the bar heights for the corresponding bins.

\textbf{Comment:} The distribution is unimodal with its largest class frequency in $[4.5,5.0)$. The right tail extends through $[7.5,8.0)$ with small but nonzero frequencies, while the left tail only extends down to $[3.0,3.5)$ and is shorter. Thus, the particle-size distribution appears \emph{somewhat right-skewed} (positively skewed), not symmetric.

\item[(d)] Density histogram and comparison:

For a density histogram, the bar height is
\[
\text{density}_i=\frac{r_i}{\text{class width}}=\frac{f_i/n}{0.5}=\frac{2f_i}{n},
\]
so that the total area equals $1$.

Using $n=131$ and width $0.5$:
\[
\begin{array}{c|cccccccccc}
\text{Class (nm)} & [3.0,3.5) & [3.5,4.0) & [4.0,4.5) & [4.5,5.0) & [5.0,5.5) & [5.5,6.0) & [6.0,6.5) & [6.5,7.0) & [7.0,7.5) & [7.5,8.0)\\
\hline
\text{density}_i & 0.0763 & 0.2290 & 0.4122 & 0.5191 & 0.3359 & 0.2137 & 0.1069 & 0.0305 & 0.0611 & 0.0153
\end{array}
\]

\textbf{Comparison:} The density histogram has the \emph{same shape} as the relative-frequency histogram (same bins and relative bar sizes), but the vertical axis is rescaled so that the \emph{area} of each bar represents the relative frequency and the \emph{total area} equals $1$.
\end{enumerate}

>[!DEFINITION] Definition: Konvergenz von Vektorfolgen
>Eine [Vektorfolge](Vektorfolge.md) $(\vec{x}_k)_{k\in\mathbb{N}_0}$ heißt **konvergent gegen** $\vec{x}\in\mathbb{R}^n$, falls der Abstand zwischen $\vec{x}_k$ und $\vec{x}$ für $k\to\infty$ gegen Null [konvergiert](../../Eindimensionale%20Analysis/Folgen/Grenzwerte/Konvergenz/Konvergenz.md):
>$$\lim_{k\to\infty} ||\vec{x}_k-\vec{x}|| = 0$$
>
>>[!DEFINITION] Definition: Grenzwert einer Vektorfolge
>>Man nennt $\vec{x}$ **Grenzwert** der Vektorfolge.
>
>>[!NOTE] Bezeichnung
>>$$\lim_{k\to\infty} (\vec{x}_k) = \vec{x}$$
>
>>[!THEOREM] Satz: Komponentenweise Konvergenz
>>Die [Vektorfolge](Vektorfolge.md) $(\vec{x}_k)_{k\in\mathbb{N}_0}$ ist genau dann gegen $\vec{x}=\begin{bmatrix}x_1 & \cdots & x_n\end{bmatrix}^\mathsf{T}\in\mathbb{R}_n$, wenn die [Folgen](../../Eindimensionale%20Analysis/Folgen/Folge.md) $(x_{k,1})_{k\in\mathbb{N}_0}, \cdots, (x_{k,n})_{k\in\mathbb{N}_0}$ der Komponenten von $\vec{x}_k$ gegen jeweils $x_1,\cdots,x_n$ [konvergieren](../../Eindimensionale%20Analysis/Folgen/Grenzwerte/Konvergenz/Konvergenz.md).
>>
>>>[!PROOF]- Beweis
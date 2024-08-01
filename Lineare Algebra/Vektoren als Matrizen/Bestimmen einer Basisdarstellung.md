> [!ALGORITHM] Algorithmus: Bestimmen einer Basisdarstellung
> Wir möchten die [Basisdarstellung](../Abstrakte%20lineare%20Algebra/Basis/Basisdarstellung%20von%20Vektoren.md) eines [Vektors](Spaltenvektor.md) $\vec{v} = \begin{bmatrix}v_1 & \cdots & v_n\end{bmatrix}^\mathsf{T} \in K^n$ bezüglich einer geordneten [Basis](../Abstrakte%20lineare%20Algebra/Basis/Basis.md) $B = (\vec{b}_1,\cdots,\vec{b}_n)$ bestimmen. Wir suchen also nach den Koeffizienten des [Koordinatenvektors](../Abstrakte%20lineare%20Algebra/Basis/Koordinatenvektor.md) ${}_{B}\vec{v} = \begin{bmatrix}{}_B v_1 & \cdots & {}_B v_n\end{bmatrix}^\mathsf{T}$.
> 
> Laut Definition haben wir
> $${}_B v_1\vec{b}_1 + \cdots + {}_B v_n \vec{b}_n = \vec{v} = \begin{bmatrix}v_1 \\ \vdots \\ v_n\end{bmatrix}$$
> 
> 1. Daraus ergibt sich das folgende [lineare Gleichungssystem](../Lineare%20Gleichungssysteme/Lineares%20Gleichungssystem.md), wo ${}_B v_1, \cdots, {}_B v_n$ die Unbekannten sind.
> $$\begin{bmatrix}\vert & \vert & \vert \\ \vec{b}_1 & \cdots & \vec{b}_n \\ \vert & \vert & \vert\end{bmatrix}\begin{bmatrix}{}_{B} v_1 \\ \vdots \\ {}_{B} v_n\end{bmatrix} = \begin{bmatrix}v_1 \\ \vdots \\ v_n\end{bmatrix}$$
> 2. Löse das LGS, um den Koordinatenvektor ${}_B\vec{v}$ zu erhalten.
> $$\left[\begin{array}{ccc|c}\vert & \vert & \vert & v_1 \\ \vec{b}_1 & \cdots & \vec{b}_n & \vdots \\ \vert & \vert & \vert & v_n\end{array}\right]$$
> 
> > [!EXAMPLE]- Beispiel
> > Wir betrachten den Vektor $\vec{v} = \begin{bmatrix} 3 & 5 & 8 \end{bmatrix}^\mathsf{T} \in\mathbb{R}^3$. Wir möchten seine Darstellung ${}_{B}\vec{v} = \begin{bmatrix}{}_B v_1 & {}_B v_2 & {}_B v_3\end{bmatrix}^\mathsf{T}$ bezüglich der Basis 
> > $$B = \left(\begin{bmatrix}1 \\ 0 \\ 0\end{bmatrix},\begin{bmatrix}1 \\ 1 \\ 0\end{bmatrix}, \begin{bmatrix}1 \\ 1 \\ 1\end{bmatrix}\right)$$
> > bestimmen.
> > 
> > Dazu notieren wir die erweiterte Koeffizientenmatrix
> > $$\left[\begin{array}{ccc|c}1 & 1 & 1 & 3 \\ 0 & 1 & 1 & 5 \\ 0 & 0 & 1 & 8\end{array}\right]$$
> > 
> > Jetzt lösen wir das LGS.
> > 
> > $$\left[\begin{array}{ccc|c}1 & 1 & 1 & 3 \\ 0 & 1 & 1 & 5 \\ 0 & 0 & 1 & 8\end{array}\right] \approx \left[\begin{array}{ccc|c}1 & 0 & 0 & -2 \\ 0 & 1 & 1 & 5 \\ 0 & 0 & 1 & 8\end{array}\right] \approx \left[\begin{array}{ccc|c}1 & 0 & 0 & -2 \\ 0 & 1 & 0 & -3 \\ 0 & 0 & 1 & 8\end{array}\right]$$
> > 
> > Das heißt
> > $${}_B \vec{v} = \begin{bmatrix}-2 \\ -3 \\ 8\end{bmatrix}$$
> > 
> > Dieses Ergebnis können wir auch überprüfen. 
> > $$-2 \begin{bmatrix}1 \\ 0 \\ 0\end{bmatrix} -3 \begin{bmatrix}1 \\ 1 \\ 0\end{bmatrix} +8\begin{bmatrix}1 \\ 1 \\ 1\end{bmatrix} = \begin{bmatrix}-2 \\ 0 \\ 0\end{bmatrix} + \begin{bmatrix}-3 \\ -3 \\ 0\end{bmatrix} + \begin{bmatrix}8 \\ 8 \\ 8\end{bmatrix} = \begin{bmatrix}3 \\ 5 \\ 8\end{bmatrix} = \vec{v}$$
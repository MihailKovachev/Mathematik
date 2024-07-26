> [!TODO] Algorithmus: Bestimmen des orthogonalen Komplements
> Sei $U$ ein [Unterraum](../Unterraum.md) des [euklidischen Vektorraums](Abstraktes%20inneres%20Produkt.md) $V$ mit $\dim(V) = n$ und $\dim(U) = r$. Um das [orthogonale Komplement](Orthogonales%20Komplement.md) $U^\perp$ zu bestimmen,
> 1. Bestimme eine Basis $B_{U}=\{\mathbf{b}_1,\cdots,\mathbf{b}_r\}$ von $U$.
> 2. Bestimme $n-r$ [linear unabhängige](../Lineare%20Unabhängigkeit.md) Vektoren $\mathbf{b}_1^\perp,\cdots,\mathbf{b}_{n-r}^\perp$, von denen jeder zu allen $\mathbf{b}_1,\cdots,\mathbf{b}_r$ [orthogonal](Orthogonalität.md) ist.
> 3. Die Vektoren $\mathbf{b}_1^\perp,\cdots,\mathbf{b}_{n-r}^\perp$ sind eine Basis von $U^\perp$, also
> $$U^\perp = \langle\mathbf{b}_1^\perp,\cdots,\mathbf{b}_{n-r}^\perp\rangle$$
> 
> > [!EXAMPLE]- Beispiel
> > Wir betrachten
> > $$U=\left\langle\begin{bmatrix}1 \\ -1 \\ 1\end{bmatrix}\right\rangle \subset \mathbb{R}^3$$
> > Die Basis von $U$ hat nur einen Vektor, wir müssen also $3-2=1$ zu $\begin{bmatrix}1 \\ -1 \\ 1\end{bmatrix}^\mathsf{T}$ orthogonale Vektoren finden, die linear unabhängig sind. Diese Vektoren nennen wir $\vec{v}_1=\begin{bmatrix}x_1 & y_1 & z_1\end{bmatrix}^\mathsf{T}$ und $\vec{v}_2 = \begin{bmatrix}x_2 & y_2 & z_2\end{bmatrix}^\mathsf{T}$.
> > 
> > Zwei Vektoren sind orthogonal, falls ihr Skalarprodukt 0 ist. Daraus ergiben sich die Gleichungen
> > $$x_1\cdot 1 + y_1\cdot (-1) + z_1\cdot 1 = 0$$
> > $$x_2\cdot 1 + y_2\cdot (-1) + z_2\cdot 1 = 0$$
> > für die Komponenten dieser Vektoren.
> > Also
> > $$\begin{cases}x_1-y_1+z_1=0 \\ x_2-y_2+z_2=0\end{cases}$$
> > Damit die gesuchten Vektoren linear unabhängig sind, muss auch
> > $$\begin{bmatrix}x_1 \\ y_1 \\ z_1\end{bmatrix} \ne k\begin{bmatrix}x_2 \\ y_2 \\ z_2\end{bmatrix} \qquad k\in \mathbb{R}$$
> > gelten. 
> > 
> > Wir sind frei die Komponenten der Vektoren willkürlicherweise auszuwählen, solange sie die vorgenannten Bedingungen erfüllen.
> > 
> > Seien dann $x_1 = 1, y_1 = -2$. Dann muss $z_1=-3$ sein. Wir wählen auch $x_2=-1,y_2=3$, also muss $z_2 = 4$ sein. Es gilt dann
> > $$U^\perp = \left\langle\begin{bmatrix}1 \\-2 \\-3\end{bmatrix},\begin{bmatrix}-1\\ 3 \\ 4\end{bmatrix}\right\rangle$$
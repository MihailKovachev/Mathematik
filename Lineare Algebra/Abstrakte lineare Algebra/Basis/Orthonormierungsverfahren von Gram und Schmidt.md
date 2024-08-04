> [!ALGORITHM] Algorithmus: Das Gram-Schmidt'sche Orthonormierungsverfahren
> Aus jeder [Basis](Basis.md) $\{\mathbf{b}_1,\cdots,\mathbf{b}_n\}$ eines [endlichdimensionalen](Dimension.md) [euklidischen Vektorraums](../Euklidische%20Vektorräume/Abstraktes%20inneres%20Produkt.md) lässt sich eine [Orthonormalbasis](Orthonormalbasis.md) $\{\mathbf{b}_1',\cdots,\mathbf{b}_n'\}$ folgendermaßen bilden:
> 1. Wir normalisieren zunächst den ersten Vektor, damit seine [Kanonische Norm](../Euklidische%20Vektorräume/Kanonische%20Norm.md) gleich 1 wird.
> $$\mathbf{b}_1' = \frac{1}{||\mathbf{b}_1||}\mathbf{b}_1$$
> 2. Den $k+1$-ten Vektor $\mathbf{b}_{k+1}'$ bilden wir so, dass er orthonormal zu allen vor ihm gebildeten Vektoren $\{\mathbf{b}_1',\cdots,\mathbf{b}_k'\}$ ist.
> - Wir bilden zuerst einen Zwischenvektor $\mathbf{c}_{k+1}$, der orthogonal, aber nicht zwangsläufig orthonormal, zu den Vektoren $\{\mathbf{b}_1',\cdots,\mathbf{b}_k'\}$ ist.
> $$\mathbf{c}_{k+1}=\mathbf{b}_{k+1}-\sum_{i=1}^k \langle\mathbf{b}_{k+1},\mathbf{b}_i'\rangle \mathbf{b}_i'$$
> - Wir normalisieren diesen Vektor, um einen Vektor mit Länge eins zu erhalten.
> $$\mathbf{b}_{k+1}' = \frac{1}{||\mathbf{c}_{k+1}||}\mathbf{c}_{k+1}$$
> 
> > [!EXAMPLE]- Beispiel
> > Wir wollen die Basis
> > $$\left\{\vec{b}_1 = \begin{bmatrix}1 \\ 0 \\0\end{bmatrix},\vec{b}_2 = \begin{bmatrix}1 \\ 1 \\0\end{bmatrix}\vec{b}_3 = \begin{bmatrix}1 \\ 1 \\ 1\end{bmatrix}\right\}$$
> > in eine Orthonormalbasis von $\mathbb{R}^3$ verwandeln. Dazu definieren wir 
> > $$\vec{b}_1' = \frac{1}{||\vec{b}_1||}\vec{b}_1 = \frac{1}{1}\cdot\vec{b}_1 = \vec{b}_1 = \begin{bmatrix}1 \\ 0 \\0\end{bmatrix}$$
> > Nun haben wir
> > $$\vec{b}_2' = \frac{1}{||\vec{c}_2||} \vec{c}_2$$
> > mit 
> > $$\vec{c}_2 = \vec{b}_2-(\vec{b}_2\cdot \vec{b}_1')\vec{b}_1' = \begin{bmatrix}1 \\ 1 \\0\end{bmatrix}-\begin{bmatrix}1 \\ 0 \\0\end{bmatrix} = \begin{bmatrix}0 \\ 1 \\0\end{bmatrix}$$
> > Es gilt also 
> > $$\vec{b}_2' = \begin{bmatrix}0 \\ 1 \\0\end{bmatrix}$$
> > Es bleibt nur 
> > $$\vec{b}_3' = \frac{1}{||\vec{c}_3||} \vec{c}_3$$
> > mit
> > $$\begin{align}\vec{c}_3 &= \vec{b}_3 - [(\vec{b}_3\cdot \vec{b}_1')\vec{b}_1' + (\vec{b}_3\cdot \vec{b}_2')\vec{b}_2'] \\ &= \begin{bmatrix}1 \\ 1 \\ 1\end{bmatrix} - 1\begin{bmatrix}1 \\ 0 \\0\end{bmatrix} - 1\begin{bmatrix}0 \\ 1 \\0\end{bmatrix} = \begin{bmatrix}0 \\ 0 \\1\end{bmatrix}\end{align}$$
> > Dann gilt
> > $$\vec{b}_3' = \frac{1}{1}\begin{bmatrix}0 \\ 0 \\1\end{bmatrix} = \begin{bmatrix}0 \\ 0 \\1\end{bmatrix}$$
> > Wir haben daher die Orthonormalbasis
> > $$\left\{\vec{b}_1' = \begin{bmatrix}1 \\ 0 \\0\end{bmatrix},\vec{b}_2' = \begin{bmatrix}0 \\ 1 \\0\end{bmatrix}, \vec{b}_3' = \begin{bmatrix}0 \\ 0 \\1\end{bmatrix}\right\}$$
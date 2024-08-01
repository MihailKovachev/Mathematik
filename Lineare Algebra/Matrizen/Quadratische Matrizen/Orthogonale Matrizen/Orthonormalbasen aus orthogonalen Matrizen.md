> [!THEOREM] Satz: Orthonormalbasis aus der Spalten einer orthogonalen Matrix
> Die [Spalten](../../../Vektoren%20als%20Matrizen/Spaltenvektor.md) einer [orthogonalen Matrix](Orthogonale%20Matrix.md) $A\in \mathbb{C}^{n\times n}$ (bzw. $\mathbb{R}^{n\times n}$) bilden eine [Orthonormalbasis](../../../Abstrakte%20lineare%20Algebra/Basis/Orthonormalbasis.md) von $\mathbb{C}^{n\times 1}$ (bzw. $\mathbb{R}^{n\times 1}$).
> > [!PROOF]- Beweis
> > Ist die Matrix
> > $$A = \begin{bmatrix}\mid & \mid & \mid \\ \vec{a}_1 & \cdots & \vec{a}_n \\ \mid & \mid & \mid \end{bmatrix}$$
> > orthogonal, so gilt
> > $$A^\mathsf{T}A= \begin{bmatrix}\textemdash & \vec{a}_1^\mathsf{T} & \textemdash \\ \textemdash & \vdots & \textemdash \\ \textemdash & \vec{a}_n^\mathsf{T} & \textemdash\end{bmatrix}\begin{bmatrix}\mid & \mid & \mid \\ \vec{a}_1 & \cdots & \vec{a}_n \\ \mid & \mid & \mid \end{bmatrix} = \begin{bmatrix}\vec{a}_1^\mathsf{T}\cdot\vec{a}_1 & \cdots & \vec{a}_1^\mathsf{T}\cdot\vec{a}_n \\ \vdots & \ddots & \vdots \\ \vec{a}_n^\mathsf{T}\cdot\vec{a}_1 & \cdots & \vec{a}_n^\mathsf{T}\cdot\vec{a}_n\end{bmatrix} = \begin{bmatrix}1 & \cdots & 0 \\ \vdots & \ddots & \vdots \\ 0 & \cdots & 1\end{bmatrix}$$
> > Aus den Einträgen der Diagonalen folgt $\vec{a}_i^\mathsf{T}\cdot \vec{a}_i = 1$, also $||\vec{a}_i||^2 = 1$. Aus allen anderen Einträgen folgt, dass die Vektoren orthogonal sind, denn das Skalarprodukt jedes Vektorenpaars ist Null.

> [!THEOREM] Satz: Orthonormalbasis aus der Zeilen einer orthogonalen Matrix
> Die [Zeilen](../../../Vektoren%20als%20Matrizen/Zeilenvektor.md) einer [orthogonalen Matrix](Orthogonale%20Matrix.md) $A\in \mathbb{C}^{n\times n}$ (bzw. $\mathbb{R}^{n\times n}$) bilden eine [Orthonormalbasis](../../../Abstrakte%20lineare%20Algebra/Basis/Orthonormalbasis.md) von $\mathbb{C}^{1\times n}$ (bzw. $\mathbb{R}^{1\times n}$).
> > [!PROOF]- Beweis
> > Analogisch dem Beweis für die Orthonormalbasis aus der Spalten der Matrix.
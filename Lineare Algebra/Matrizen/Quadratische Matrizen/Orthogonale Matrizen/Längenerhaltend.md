> [!THEOREM] Satz: Längenerhaltend
> Jede [orthogonale Matrix](Orthogonale%20Matrix.md) $A\in \mathbb{R}^{n\times n}$ ist **längenerhaltend**, d.h. es gilt
> $$||A\vec{v}|| = ||\vec{v}||\qquad \forall \vec{v}\in \mathbb{R}^{n\times 1}$$
> > [!PROOF]- Beweis
> > $$||A\vec{v}||^2 = (A\vec{v})\cdot(A\vec{v}) = (A\vec{v})^\mathsf{T}(A\vec{v}) = \vec{v}^\mathsf{T}A^{\mathsf{T}}A\vec{v} = \vec{v}^\mathsf{T}\vec{v} = ||\vec{v}||^2$$
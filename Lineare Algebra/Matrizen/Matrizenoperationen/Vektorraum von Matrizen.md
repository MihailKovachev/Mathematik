> [!IMPORTANT] Satz: Vektorraum von Matrizen
> Der [Körper](../../../Mengenlehre/Körper/Körper.md) $K$ (entweder $\mathbb{C}$ oder $\mathbb{R}$) und die Menge $K^{m\times n}$ der $m\times n$-[Matrizen](../Matrix.md) machen mit der [Addition](Addition.md) und der [skalaren Multiplikation](Skalare%20Multiplikation.md) von Matrizen einen [abstrakten Vektorraum](../../Abstrakte%20lineare%20Algebra/Abstrakter%20Vektorraum.md) $(K^{m\times n}, K, +, \cdot)$, also es gilt:
> - Kommutativität der Addition: $A + B = B + A \qquad \forall A, B \in K^{m\times n}$
> - Assoziativität I: $A + (B + C) = (A + B) + C \qquad \forall A,B,C \in K^{m\times n}$
> - Assoziativität II: $(\lambda\mu)A = \lambda(\mu A) \qquad \forall \lambda,\mu\in K, \forall A\in K^{m\times n}$
> - Distributivität I: $\lambda (A + B) = \lambda A+\lambda B \qquad \forall A, B \in K^{m\times n}, \forall \lambda \in K$
> - Distributivität II: $(\lambda + \mu)A = \lambda A +\mu A \qquad \forall \lambda,\mu \in K, \forall A \in K^{m\times n}$
> - Existenz eines Nullelements: Es gilt 
> $$A + \begin{bmatrix}0 & \cdots & 0 \\ \vdots & \ddots & \vdots \\ 0 & \cdots & 0\end{bmatrix} = A \qquad \forall A \in K^{m\times n}$$
> - Existenz eines Identitätselements: Es gilt $1\cdot A = A \qquad \forall K^{m\times n}$
> - Existenz einer inversen Matrix: Für jede Matrix $A = (a_{ij}) \in K^{m\times n}$ gibt es die matrix $-A = (-a_{ij}) \in K^{m\times n}$ mit 
> $$A + (-A) = \begin{bmatrix}0 & \cdots & 0 \\ \vdots & \ddots & \vdots \\ 0 & \cdots & 0\end{bmatrix}$$
> 
> > [!NOTE] Notiz: Inverse Matrizen
> > Die vorgenannte inverse Matrix ist *nicht* dieselbe [inverse Matrix](../Invertieren/Invertierbarkeit.md) wie bei der [Multiplikation von Matrizen](Multiplikation%20von%20Matrizen.md).
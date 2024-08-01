> [!THEOREM] Satz: Basisdarstellung durch Orthonormalbasis 
> Ist $B = \{\mathbf{b}_1,\cdots,\mathbf{b}_n\}$ eine [Orthonormalbasis](Orthonormalbasis.md) eines [euklidischen Vektorraums](../Euklidische%20Vektorräume/Abstraktes%20inneres%20Produkt.md) $(V,K,+,\cdot)$, so gilt für die Koeffizienten $\lambda_1,\cdots,\lambda_n\in K$ in der [Basisdarstellung](Basisdarstellung%20von%20Vektoren.md) $\mathbf{v} = \sum_{i=1}^n \lambda_i \mathbf{b}_i$ jedes Vektors $\mathbf{v} \in V$
> $$\lambda_i = \langle \mathbf{v},\mathbf{b}_i\rangle$$
> > [!PROOF]- Beweis
> > $$\langle \mathbf{v},\mathbf{b}_i\rangle = \lambda_1 \langle \mathbf{b}_1,\mathbf{b}_i\rangle + \cdots + \lambda_i \langle \mathbf{b}_i,\mathbf{b}_i\rangle + \cdots + \lambda_n \langle \mathbf{b}_n,\mathbf{b}_i\rangle$$
> > Die Basis ist orthogonal, weshalb $\langle \mathbf{b}_j,\mathbf{b}_i\rangle = 0$ für $i\ne j$ gilt. Da die Basisvektoren auch normalisiert sind, bleibt $\langle \mathbf{b}_i,\mathbf{b}_i\rangle = 1$
> > Es gilt also
> > $$\langle \mathbf{v},\mathbf{b}_i\rangle = \lambda_1 \underset{0}{\underbrace{\langle \mathbf{b}_1,\mathbf{b}_i\rangle}} + \cdots + \lambda_i \underset{1}{\underbrace{\langle \mathbf{b}_i,\mathbf{b}_i\rangle}} + \cdots + \lambda_n\underset{0}{\underbrace{\langle \mathbf{b}_n,\mathbf{b}_i\rangle}} = \lambda_i$$
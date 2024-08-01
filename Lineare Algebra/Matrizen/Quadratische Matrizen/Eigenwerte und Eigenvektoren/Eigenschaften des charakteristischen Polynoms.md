> [!THEOREM] Satz: Grad des charakteristischen Polynoms
> Der [Grad](../../../../Analysis/Polynome/Polynom.md) des [charakteristischen Polynoms](Eigenwerte%20und%20Eigenvektoren/Das%20charakteristische%20Polynom.md) einer Matrix $M\in K^{n\times n}$ ist $n$.
> > [!PROOF]- Beweis


> [!THEOREM] Satz: Eigenwerte aus dem charakteristischen Polynom
> Die [Eigenwerte](Eigenwerte%20und%20Eigenvektoren/Eigenwert.md) einer [quadratischen Matrix](Quadratische%20Matrix.md) $M$ sind genau die [Nullstellen](../../../../Analysis/Polynome/Nullstellen/Nullstelle.md) ihres [charakteristischen Polynoms](Eigenwerte%20und%20Eigenvektoren/Das%20charakteristische%20Polynom.md) $p_M(x)$.
> $$p_M(x) = (\lambda_1-x)^{k_1}\cdots (\lambda_r-x)^{k_r} = 0$$
> > [!PROOF]- Beweis
> 
> > [!DEFINITION] Definition: Algebraische Vielfachheit
> > Die Zahl $k_i\in\mathbb{N}$ nennt man die **algebraische Vielfachheit** des [Eigenwerts](Eigenwert.md) $\lambda_i$.
> > > [!NOTE] Schreibweise
> > > $$\operatorname{alg}(\lambda_i) = k_i$$
> > 
> > > [!THEOREM] Satz
> > > Für jeden [Eigenwert](Eigenwert.md) $\lambda_i$ gilt
> > > $$1\le \operatorname{geo}(\lambda_i)\le \operatorname{alg}(\lambda_i)$$ 
> > > > [!PROOF]- Beweis
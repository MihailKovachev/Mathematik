> [!ALGORITHM] Algorithmus: Bestimmen der Eigenräume einer Matrix
> Wir betrachten die [quadratische Matrix](../Quadratische%20Matrix.md) $M\in K^{n\times n}$ und wollen ihre [Eigenräume](Eigenraum.md) bestimmen.
> 
> 1. Notiere das [charakteristische Polynom](Das%20charakteristische%20Polynom.md) $p_M(x)$ der Matrix $M$ und löse die Gleichung $p_M(x) = 0$, um die [Eigenwerte](Eigenwert.md) von $M$ zu bestimmen.
> 2. Der [Eigenraum](Eigenraum.md) zu jedem [Eigenwert](Eigenwert.md) $\lambda_i$ ist
> $$\operatorname{Eig_M(\lambda_i)} = \ker(M-\lambda_i I_n)$$
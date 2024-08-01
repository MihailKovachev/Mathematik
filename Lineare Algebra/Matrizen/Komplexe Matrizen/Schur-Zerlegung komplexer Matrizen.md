> [!THEOREM] Satz: Triagonalisierbarkeit komplexer Matrizen
> Jede [komplexe](Komplexe%20Matrix.md) [quadratische Matrix](../Quadratische%20Matrizen/Quadratische%20Matrix.md) $M\in\mathbb{C}^{n\times n}$ ist durch eine [unitäre Matrix](Unitäre%20Matrizen/Unitäre%20Matrix.md) $U\in\mathbb{C}^{n\times n}$ zu einer [oberen Dreiecksmatrix](../Quadratische%20Matrizen/Dreiecksmatrizen.md) $R\in\mathbb{C}^{n\times n}$ [triagonalisierbar](../Quadratische%20Matrizen/Triagonalisierbarkeit.md).
> $$R = U^\dagger MU$$
> > [!PROOF]- Beweis
> 
> >[!THEOREM] Satz: Diagonale von $R$
> >Die Diagonale von $R$ enthält genau die [Eigenwerte](../Quadratische%20Matrizen/Eigenwerte%20und%20Eigenvektoren/Eigenwert.md) von $M$.
> > >[!PROOF]- Beweis
> 
> > [!DEFINITION] Definition: Schur-Zerlegung
> > Die **Schurzerlegung** von $M$ nennt man
> > $$M = U R U^\dagger$$

> [!ALGORITHM] Algorithmus: Bestimmen einer Schur-Zerlegung
> Wir wollen eine Schur-Zerlegung zur [Matrix](Komplexe%20Matrix.md) $M\in\mathbb{C}^{n\times n}$ finden.
> 
> 1. [Bestimme](../Quadratische%20Matrizen/Eigenwerte%20und%20Eigenvektoren/Bestimmen%20der%20Eigenräume.md) einen einen [Eigenwert](../Quadratische%20Matrizen/Eigenwerte%20und%20Eigenvektoren/Eigenwert.md) $\lambda_1$ und einen dazu entsprechenden [Eigenvektor](../Quadratische%20Matrizen/Eigenwerte%20und%20Eigenvektoren/Eigenvektor.md) $\vec{v}_1$ von $M$.
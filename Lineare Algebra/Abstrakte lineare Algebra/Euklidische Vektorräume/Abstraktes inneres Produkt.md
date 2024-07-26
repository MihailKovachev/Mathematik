> [!DANGER] Definition: Abstraktes inneres Produkt
> Ein **Abstraktes inneres Produkt** (oder **abstraktes Skalar-/Punktprodukt**) auf einem komplexen Vektorraum $(V, \mathbb{C}, +, \cdot)$ ist eine Verknüpfung $\langle\cdot,\cdot\rangle: V\times V\to \mathbb{C}$, die die folgenden Eigenschaften besitzt.
> 1. Hermetisch
> $$\langle\mathbf{u},\mathbf{v}\rangle = \overline{\langle\mathbf{v},\mathbf{u}\rangle} \qquad \forall \mathbf{u},\mathbf{v} \in V$$
> 2. Sesquilinear
> 	- Distributivität I: $\langle\mathbf{u} + \mathbf{v}, \mathbf{w}\rangle = \langle\mathbf{u}, \mathbf{w}\rangle + \langle\mathbf{v}, \mathbf{w}\rangle \qquad \forall \mathbf{u},\mathbf{v},\mathbf{w} \in V$
> 	- Distributivität II: $\langle\mathbf{u},\mathbf{v} + \mathbf{w}\rangle = \langle\mathbf{u},\mathbf{v}\rangle + \langle\mathbf{u},\mathbf{w}\rangle \qquad \forall \mathbf{u},\mathbf{v},\mathbf{w} \in V$
> 	- Semilinearität im ersten Argument: $\langle\lambda\mathbf{u},\mathbf{v}\rangle = \bar{\lambda}\langle\mathbf{u},\mathbf{v}\rangle \qquad \forall \mathbf{u},\mathbf{v} \in V, \forall \lambda \in \mathbb{C}$
> 	- Linearität im zweiten Argument: $\langle\mathbf{u},\lambda\mathbf{v}\rangle = \lambda\langle\mathbf{u},\mathbf{v}\rangle \qquad \forall \mathbf{u},\mathbf{v} \in V, \forall \lambda \in \mathbb{C}$
> 3. Positiv definit
> $$\langle\mathbf{v},\mathbf{v}\rangle \ge 0 \in \mathbb{R}\text{ mit } \langle\mathbf{v},\mathbf{v}\rangle = 0 \iff \mathbf{v} = \mathbf{0} \qquad \forall \mathbf{v} \in V$$
> 
> > [!NOTE] Notiz: Abstraktes inneres Produkt auf reellen Vektorräume
> > Die Definition für reelle Vektorräume ist genau die gleiche - man lässt einfach die [komplexe Konjugation](../../../Komplexe%20Zahlen/komplexe%20Konjugation/Komplexe%20Konjugation.md) weg.

> [!DANGER] Definition: Eukledischer Vektorraum
> Ein **eukledischer Vektorraum** ist ein [Vektorraum](../Abstrakter%20Vektorraum.md) $(V,K,+,\cdot)$, der mit einem Skalarprodukt ausgerüstet ist.
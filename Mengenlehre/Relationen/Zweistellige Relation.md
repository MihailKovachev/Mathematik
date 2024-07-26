> [!DANGER] Definition: Zweistellige Relation
> Eine **zweistellige Relation** $R$ zwischen den [Mengen](../Menge.md) $A$ und $B$ ist eine [Teilmenge](../Teilmenge.md) des [kartesischen Produkts](../Operationen%20mit%20Mengen/Kartesisches%20Produkt.md) von $A$ und $B$.
> $$R\subseteq A \times B$$
> 
> Falls $A=B$, heißt $R\subseteq A\times A$ eine zweistellige Relation auf $A$.
> 
> > [!NOTE] Schreibweise
> > Falls $a\in A,b\in B$ Objekte sind und $(a;b)$ gilt, schreiben wir 
> > $$a\,\, R\,\, b$$
> 
> > [!DANGER] Definition: Definitionsbereich
> > Der **Definitionsbereich** einer zweistelligen Relation $R\subseteq A\times B$ ist die [Menge](../Menge.md)
> > $$\operatorname{dom} (R) \overset{\text{def}}{=} \{a|a\in A \land \exists b\in B : (a; b)\in R\}$$
> 
> > [!DANGER] Definition: Wertebereich
> > Der **Wertebereich** einer zweistelligen Relation $R\subseteq A\times B$ ist die [Menge](../Menge.md)
> > $$\operatorname{rng}(R) \overset{\text{def}}{=} \{b\mid b\in B \land \exists a\in A : (a;b)\in R\}$$
> 
> > [!QUOTE] Erklärung zur Definition
> > Die Aussage $a \,\, R\,\, b$ bedeutet einfach "es besteht eine Beziehung zwischen $a$ und $b$, die durch $R$ beschrieben wird".
> > > [!EXAMPLE]-
> > > Sei $R\subseteq \mathbb{N}\times\mathbb{N}$ die Relation
> > > $$R=\{(a;b)\mid b \text{ ist ein Teiler von } a\}$$
> > > Falls $p\,\, R\,\, q$ gilt, also $(p; q) \in R$, so heißt das einfach, dass $p$ und $q$ in der vorgenannten Verbindung zueinander stehen, nämlich $q$ ist ein Teiler von $p$.
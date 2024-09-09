---
Related:
  - "[[Konvergenz von Funktionen|Konvergenz von Funktionen]]"
  - "[[../Funktionen/Beschränktheit reeller Funktionen|Beschränktheit reeller Funktionen]]"
---

> [!THEOREM] Satz: Ungleichung von Grenzwerten
> Seien $f: F \to \mathbb{R}$ und $g: G \to \mathbb{R}$ zwei in irgendeinem Bereich $D$ um $c \in F \cap G$ wohldefinierte Funktionen, die beide im Punkt $c$ einen Grenzwert haben. Dann gilt
> $$f(x) \le g(x) \,\forall x \in D \implies \lim_{x\to c} f(x) \le \lim_{x\to c} g(x)$$

> [!THEOREM] Satz: Grenzwert des Produkts einer beschränkten Funktion
> Seien $f: F \to \mathbb{R}$ eine in irgendeinem Bereich $D$ um $c \in F$ [[../Funktionen/Beschränktheit reeller Funktionen#^6ab1ef|beschränkte]] Funktion und $g: G \to \mathbb{R}$ eine Funktion mit $\displaystyle \lim_{x\to c} g(x) = 0$. Dann gilt
> $$\lim_{x\to c} (f(x)g(x)) = 0$$

> [!THEOREM] Satz: Grenzwert einer Komposition von Funktionen
> Sei $g: G \to \mathbb{R}$ eine Funktion mit $\displaystyle\lim_{x\to c} g(x) = l \in \mathbb{R}$ und $g(x) \ne l$ für jedes $x$ in irgendeinem Bereich $D$ um $c$. Sei auch $f$ eine reellwertige Funktion mit $\displaystyle \lim_{x\to l} f(x) = L \in \mathbb{R}$. Dann gilt
> $$\lim_{x\to c} f(g(x)) = L\in\mathbb{R}$$

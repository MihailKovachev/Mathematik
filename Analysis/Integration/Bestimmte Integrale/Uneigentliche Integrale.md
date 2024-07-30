> [!DANGER] Definition: Uneigentliche Integrale
> Für $a\in\mathbb{R}$ und die [Funktion](../../Funktionen/Funktion.md) $f:[a;\infty)\to\mathbb{R}$ definiert man das **uneigentliche Integral**
> $$\int_a^\infty f(x)\mathop{\mathrm{d}x}\overset{\text{def}}{=} \lim_{b\to\infty}\int_a^b f(x)\mathop{\mathrm{d}x}$$
> 
> Für $b\in\mathbb{R}$ und die [Funktion](../../Funktionen/Funktion.md) $f:[-\infty;b)\to\mathbb{R}$ definiert man das **uneigentliche Integral**
> $$\int_{-\infty}^b f(x)\mathop{\mathrm{d}x}\overset{\text{def}}{=} \lim_{a\to-\infty}\int_a^b f(x)\mathop{\mathrm{d}x}$$
> 
> Für die [Funktion](../../Funktionen/Funktion.md) $f: (-\infty;\infty)\to\mathbb{R}$ definiert man das **uneigentliche Integral**
> $$\int_{-\infty}^\infty f(x)\mathop{\mathrm{d}x} \overset{\text{def}}{=} \int_{-\infty}^c f(x)\mathop{\mathrm{d}x} +\int_c^\infty f(x)\mathop{\mathrm{d}x},$$
> wobei die Wahl von $c\in\mathbb{R}$ egal ist.
> 
> Für $a,c\in\mathbb{R}$ und die [Funktion](../../Funktionen/Funktion.md) $f:[a;c)\to\mathbb{R}$ definiert man das **uneigentliche Integral**
> $$\int_a^c f(x)\mathop{\mathrm{d}x} \overset{\text{def}}{=} \lim_{b\to c^-} \int_a^b f(x)\mathop{\mathrm{d}x}$$
> 
> Für $b,c\in\mathbb{R}$ und die [Funktion](../../Funktionen/Funktion.md) $f: (c;b]\to\mathbb{R}$ definiert man das **uneigentliche Integral**
> $$\int_c^b f(x)\mathop{\mathrm{d}x} \overset{\text{def}}{=} \lim_{a\to c^+}\int_a^b f(x)\mathop{\mathrm{d}x}$$
> 
> Falls der jeweilige [Grenzwert](../../Grenzwerte%20von%20Funktionen/Grenzwerte.md) existiert und endlich ist, sagt man, dass das uneigentliche Integral **existiert** oder **konvergiert**, ansonsten nennt man es **nicht existent** oder **divergent**. 
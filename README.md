# Edge Unfoldings of Complementary Corner-Chain Prismatoids at Every Positive Height

**Y. T. Miah** · Research manuscript dated 5 November 2026

[Read the manuscript (PDF)](main.pdf) · [LaTeX source](main.tex)

## About

This preprint proves that a family of convex prismatoids with complementary monotone corner chains admits a nonoverlapping edge unfolding at **every positive height**, in the original Euclidean metric. The chains can have arbitrarily many edges, the bases need not be nested, and their horizontal projections can be disjoint. The family is defined using a coordinate frame whose positive directions meet at an angle in $[\pi/2,\pi)$.

The construction uses Pinciu's face-neighborhood nonoverlap theorem, together with angular separation of a triangular fan and a supporting-circle argument for the attached upper face. It sits alongside earlier edge-unfolding results for nested prismatoids (Radons), sufficiently tall prismatoids (Bian, Demaine and Madhukara), and related petal-unfolding methods (O'Rourke). The mathematical hypotheses and references are given in the manuscript.

## The two cut trees

Section 2 specifies two spanning cut trees, $T_N$ and $T_E$, consisting exclusively of original polyhedral edges. With $a\geq0$, height $h>0$, and the corner parameters $b,c,d,e$ defined there, put

$$
\lambda=\frac{\sqrt{(e-b)^2+(1+a^2)h^2}-(e-b)}{1+a^2},
\qquad
\mu=\sqrt{(d-c)^2+h^2}-(d-c).
$$

The sufficient nonoverlap tests are

- $T_N$: $\mu\geq a\lambda$;
- $T_E$: $(1+a^2)\lambda\geq a\mu$.

At least one condition holds for every admissible prismatoid. Thus the specified trees provide a nonoverlapping genuine-edge net at each positive height, including equality in the branch tests.

## Files and build

- [`main.pdf`](main.pdf) — the 12-page A4 manuscript.
- [`main.tex`](main.tex) — its complete, self-contained AMS LaTeX source, including the bibliography.
- [`CITATION.cff`](CITATION.cff) — machine-readable citation information.

With a TeX installation providing pdfLaTeX and the standard packages named in `main.tex`, run from the repository root:

```sh
pdflatex -interaction=nonstopmode -halt-on-error main.tex
pdflatex -interaction=nonstopmode -halt-on-error main.tex
```

The bibliography is included in `main.tex`; no separate BibTeX step is needed.

## Citation

Y. T. Miah, *Edge Unfoldings of Complementary Corner-Chain Prismatoids at Every Positive Height*, manuscript dated 5 November 2026. Citation metadata are also available in [`CITATION.cff`](CITATION.cff).

Zenodo preprint: [10.5281/zenodo.23993685](https://doi.org/10.5281/zenodo.23993685).

## Licence

The original manuscript and repository documentation are available under [Creative Commons Attribution 4.0 International (CC BY 4.0)](LICENSE.md).

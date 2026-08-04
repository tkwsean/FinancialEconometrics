# Financial Econometrics — Formula Reference

A dense, single-document formula sheet for **MH4519 Financial Econometrics**
(NTU), typeset in LaTeX as a three-column reference.

📄 **[main.pdf](main.pdf)** — the compiled sheet.

---

## Coverage

| Section | Contents |
|---|---|
| **Foundational** | Probability axioms, expectation, variance, covariance identities |
| **Finance** | Holding-period, gross and log returns; risk premium; Sharpe ratio |
| **Portfolio** | Portfolio moments, diversification, the efficient frontier |
| **Return Predictability** | Autocorrelation, random walk and market-efficiency tests |
| **Volatility** | ARCH/GARCH, conditional variance, volatility clustering |
| **Linear Time Series** | AR, MA, ARMA — stationarity, identification, forecasting |
| **Factor Models & PCA** | Factor decomposition, principal components |
| **High-Frequency Econometrics** | Realised volatility, microstructure noise |
| **Derivatives** | Pricing relations and the Greeks |

Log returns and simple returns are kept distinct throughout, including where
the approximation `log(1+R) ≈ R` holds and where it does not — a distinction
that quietly breaks compounding and volatility scaling when ignored.

---

## Building

```bash
pdflatex main.tex
```

Requires `amsmath`, `amssymb`, `geometry` and `multicol` — all present in a
standard TeX Live or MacTeX install. The layout targets maximum density:
0.3 cm margins, three columns, `\tiny`, and display skips zeroed.

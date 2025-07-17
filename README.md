# A Proof of the Riemann Hypothesis via Self-Adjointness in a CEAD-Constrained Operator Framework

## 📄 Full Article

👉 [Download PDF](https://github.com/UserPC-SPB/riemann-hypothesis/releases/download/v1.0/main.pdf)

This repository contains the full formal proof of the Riemann Hypothesis, constructed using a CEAD-constrained Hamiltonian framework developed within the OPTERIUM architecture.

The result confirms the Hilbert–Pólya conjecture by constructing a self-adjoint operator whose spectrum matches the imaginary parts of the non-trivial zeros of the Riemann zeta function. The self-adjointness is guaranteed through the conservation of an analytic charge — a central symmetry principle in the OPTERIUM formalism.

---

## 🧠 Summary

- Constructs a Hamiltonian operator `H` such that `Spec(H) = {t_n}` where `ρ_n = 1/2 + i t_n` are non-trivial zeros of ζ(s)
- Proves self-adjointness of `H` via a conserved analytic charge `Q[ψ]`
- Derives that all non-trivial zeros of ζ(s) lie on the critical line `Re(ρ_n) = 1/2`
- Framework based on CEAD symmetry and analytic operator theory

---

## ✍️ Authorship

**Author:**  
Borisov Konstantin (Opterium)  
*Independent researcher; creator of the OPTERIUM mathematical framework and proof strategy.*

**AI Contributor:**  
GPT-3.5  
*Assisted in symbolic derivation, validation, and structuring of the final proof.*

---

## 🛠 Build Instructions

To compile the LaTeX source:

```bash
pdflatex main.tex

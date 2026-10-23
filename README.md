# DFT mini-course

Short course on density functional theory, built around a Kohn–Sham DFT
implementation written from scratch in Python (NumPy and SciPy only) so that
every step of the calculation is visible in the code.

## Lesson 1 — Kohn–Sham DFT from scratch

| File | Content |
|---|---|
| `lesson1/lesson1_slides.pdf` | Lecture slides: Hohenberg–Kohn theorems, the Kohn–Sham construction, exchange–correlation, the self-consistent field cycle. |
| `lesson1/DFT_from_scratch_with_illustrations.ipynb` | Worked implementation: Slater-type orbital basis, numerical grid integration, LDA exchange–correlation, canonical orthogonalisation and an explicit SCF loop, with a figure for each stage (`lesson1/pics/`). |
| `lesson1/lesson1_addendum/lesson1_KS_DFT.pdf` | Derivation notes for the Kohn–Sham equations. |
| `lesson1/lesson1_addendum/KS_equations_exaples.pdf` | Worked examples. |

The stand-alone version of the notebook, with a longer narrative, is in
[fronzi/DFT-from-scratch-tutorial](https://github.com/fronzi/DFT-from-scratch-tutorial).

## Running the notebook

```bash
pip install numpy scipy matplotlib jupyter
jupyter notebook lesson1/DFT_from_scratch_with_illustrations.ipynb
```

## Status

Lesson 1 is complete; further lessons will be added as they are taught.

## Author

Marco Fronzi, School of Physics, The University of Sydney — marco.fronzi@sydney.edu.au

This repository contains the LaTeX source code and assets for a scientific poster presented on **Meshfree Methods for Stress Driven Beams**. The poster is designed using the `beamerposter` package with a customized `gemini` theme.

## 🔬 Research Overview
The research focuses on the **Element-Free Galerkin (EFG)** method applied to a stress-driven one-dimensional Bernoulli-Euler beam. It addresses the size-dependent behavior of micro-nano structures by utilizing a mathematically consistent stress-driven nonlocal approach to avoid the paradoxes often found in Eringen’s strain-driven models.

**Authors:** * Akhil S. L. (Research Scholar)
* I. R. Praveen Krishna
* *Structural Dynamics and Vibration Laboratory, IIST*

---

## 🛠 Project Structure

* `main.tex`: The primary LaTeX file containing the poster layout and content.
* `mydefs.tex`: Custom LaTeX macros and mathematical definitions.
* `beamerposter.sty`: The style file for poster sizing (A1 portrait).
* `beamerthemegemini.sty`: The visual theme configuration.
* `logos/`: Folder containing institutional logos (IIST, SDVL).
* `pictures/`: Folder containing experimental schematics and numerical results.

---

## 🚀 How to Compile

To generate the PDF, you need a TeX distribution (like TeX Live or MiKTeX). Because the poster uses absolute positioning for the footer, **you must compile twice** to align elements correctly.

### Using the Command Line:
```bash
pdflatex main.tex
pdflatex main.tex
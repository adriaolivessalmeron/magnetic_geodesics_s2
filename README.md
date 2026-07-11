# Magnetic geodesics projected onto the two-sphere

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.21314870.svg)](https://doi.org/10.5281/zenodo.21314870)

Interactive analytic and numerical study of magnetic geodesics projected onto $S^2$.

This repository accompanies my Master's thesis and contains a Mathematica notebook that:

- classifies the physically admissible analytic branches of the reduced equation $\dot{x}^{2} = P(x)$, where $x:=\cos(\theta)$, $x\in[-1,1]$, $P(x) \geq 0$,
- compares the analytic solutions with a direct numerical integration using `NDSolve`,
- represents $x(\tau)$, $\theta(\tau)$ and $\phi(\tau)$,
- displays the relevant real roots of $P(x)$,
- animates the corresponding numerical trajectory on the two-sphere,
- includes representative presets for the nine cases considered in the classification presented in the accompanying Master's thesis.

## Interactive application

The application can be used directly in a web browser, without installing Mathematica:

[Open the interactive Wolfram Cloud application](https://www.wolframcloud.com/obj/adriaolivessalmeron/magnetic_geodesics_S2)

A wider embedded version of the application is available through the GitHub Pages site:

[Open the embedded interactive application](https://adriaolivessalmeron.github.io/magnetic_geodesics_s2/)

The browser version may respond slowly because the computations are performed remotely through Wolfram Cloud. For smoother interaction, it is recommended to download the notebook and run it locally in Mathematica.

## Mathematica notebook

The complete source notebook is available here:

[`magnetic_geodesics_s2.nb`](./magnetic_geodesics_s2.nb)

Running or modifying the source notebook locally requires Wolfram Mathematica.

## Repository contents

- `magnetic_geodesics_s2.nb`: complete Mathematica notebook.
- `index.html`: web page used to embed the public Wolfram Cloud application.
- `README.md`: project description and usage information.

## Author

**Adrià Olives-Salmerón**

## Citation

If you use this software, please cite:

Adrià Olives-Salmerón (2026). *Magnetic geodesics projected onto the two-sphere* (Version 1.0.0) [Computer software]. Zenodo. [https://doi.org/10.5281/zenodo.21314870](https://doi.org/10.5281/zenodo.21314870)

Citation metadata is also available through the `CITATION.cff` file and the **Cite this repository** option on GitHub.

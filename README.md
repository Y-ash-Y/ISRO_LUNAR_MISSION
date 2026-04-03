# Lunar Elemental Mapping using Chandrayaan-2 CLASS Data

## Overview

This project generates high-resolution elemental ratio maps of the lunar surface using X-ray fluorescence (XRF) data from the CLASS instrument onboard Chandrayaan-2.

It focuses on extracting fine-scale compositional variations across lunar maria and highlands by improving spatial resolution using orbital overlap and spectral analysis.

---

## Key Work

* Processed CLASS XRF data and extracted valid orbits
* Performed background subtraction and continuum fitting
* Detected and fitted elemental peaks (Mg, Al, Si, Ca)
* Computed elemental ratios (Mg/Si, Al/Si, Ca/Si)
* Generated global and regional lunar maps
* Improved resolution from 12.5 km to 3.125 km
* Estimated uncertainty using SEM

---

## Key Results

* Mg/Si higher in maria (basaltic regions)
* Al/Si higher in highlands (anorthositic regions)
* Ca/Si relatively uniform
* Achieved 4× improvement in spatial resolution

---

## Method Summary

Data preprocessing → Background removal → Continuum fitting → Peak detection → Ratio computation → Uncertainty Quantification → Subpixel Resolution Mapping

---

## Tech Stack

Python, NumPy, SciPy, Pandas, Matplotlib


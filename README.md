# Structured Spin Black Hole Echo Detection

This repository contains the full open-science toolkit and theoretical background for testing gravitational wave echoes predicted by the Structured Spin Black Hole (SSBH) model.

## Included
- `scripts/`: Python scripts to calculate echo delays and detect signals in GW strain data
- `results/`: Sample SNR results for GW150914, GW170104, GW190521
- `theory.pdf`: Full derivation of the model, FTL conditions, and how to reproduce tests

## Theory Summary
- Echo delay: Δt = 2L / c
- Resonant frequency: f = c / 4L
- Spin-lock boundary: ω * R ≥ c
- FTL path condition: Δτ < L / c (no exotic matter required)

## How to Use
1. Clone the repo or download ZIP
2. Install dependencies (NumPy, SciPy, p
3. Run `scripts/matched_filter_echo_detector.py` with public LIGO GW strain data (e.g., GW150914)
4. Verify if echoes appear at predicted mass-scaled delays

## License
MIT License – open science, replicate freely, improve collaboratively.

## Contact
Original author: Ashley Clark. Developed collaboratively with AI support.
 Spin Black Hole model

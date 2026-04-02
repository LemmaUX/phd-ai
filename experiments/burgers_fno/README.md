# Burgers FNO Experiment

Pilot experiment: train an FNO on the 1D Burgers equation, then quantize to INT8 (PTQ) and measure spectral degradation.

## Goal
Determine which Fourier modes are most sensitive to weight quantization.

## Status
- [ ] Implement FNO from scratch in PyTorch
- [ ] Train on Burgers 1D dataset
- [ ] Apply PTQ with `torch.quantization`
- [ ] Measure per-mode error before and after quantization
- [ ] Write up findings in `../../survey/main.tex`

# Spectral Timing in Julia

This project implements a core set of tools for X-ray timing analysis in Julia, ported from the [Stingray](https://github.com/StingraySoftware/stingray) Python package. It includes periodograms, cross spectra, time lags, and variability vs energy spectra, tailored for high-energy astrophysical data.

## Features
- Lomb-Scargle and Fourier Periodograms
- Cross Spectra between light curves
- Time Lags and Coherence
- Variability vs Energy Spectra (e.g., covariance spectra)
- Support for both event lists and light curves
- FITS I/O for compatibility with astrophysics data formats

## Getting Started
```julia
] activate .
] instantiate
```

## License
MIT

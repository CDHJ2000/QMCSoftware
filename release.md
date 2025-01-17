## v1.0
- Continuation multi-level MC and QMC
- Improved importance sampling flexibility
- Isolated seeding with QMCPy
- Enhanced documentation
- New true measures


## v0.7

- Windows support
- Improved Sobol' generator
  - linear matrix scrambling
  - digital shift
  - optional graycode
  - custom generating matrices
- Faster Halton generator

## v0.6

- `CubQMCBayesLatticeG` stopping criterion 

## v0.4

- bug fixes and stability improvements

## v0.3

- Halton + Korobov sequences
  - Hatlton compatibility for CubQMCCLT and CubQMCML
- doctests
- Lattice MPS backend: 250 --> 3600 max dimensions
- patch multilevel call options bug
- TrueMeasure method naming: `gen_mimic_samples` --> `gen_samples`
- PCA decomposition for Brownian Motion & Gaussian true measures

## v0.2

- Creation of QMCPy framework
  - discrete distributions
  - true measures
  - integrands
  - stopping criterion
  - accumulate data objects
- unittests
- workouts
- demos
- requirements
- Sphinx documentation

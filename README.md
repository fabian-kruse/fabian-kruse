### Fabian Kruse

PhD candidate in the [Signal and Data Analytics Lab](https://sada.dmi.unibas.ch/) at the University of Basel, advised by [Ivan Dokmanić](https://rds.unibas.ch/en/persons/ivan-dokmanic/).
I develop machine learning and optimization methods for scientific imaging that hold up on real experimental data:
**generative models learned from noisy data**, and **fast algorithms for 3D alignment** in cryo-electron tomography.

**Papers**
- [Learning Clean Generative Processes from Noisy Measurements](https://arxiv.org/abs/2610.42036):
  diffusion-type models of clean data, trained from noisy views only (Poisson, binomial, Gamma, …). *Under review, ICLR 2027.*
- [Fast Volume Alignment by Frequency-Marched Newton Method](https://arxiv.org/abs/2603.15285):
  rotational alignment as continuous optimization on SO(3); >10× faster pose refinement in RELION-5.
  Code: [swing-research/Matcha](https://github.com/swing-research/Matcha)

**Code**
- [so3kit](https://github.com/fabian-kruse/so3kit): fast harmonic analysis on SO(3) in PyTorch with custom CUDA kernels:
  Wigner-D matrices, SO(3) FFT, and analytic gradients and Hessians for Newton-type optimization over rotations.

**Links:** [Google Scholar](https://scholar.google.com/citations?user=pbBnAGgAAAAJ) · [LinkedIn](https://www.linkedin.com/in/fabian-kruse-23999727a/) · fabian.kruse@unibas.ch

# Photonic Neural Computing

Research code and supporting material for my Master's thesis project (2023-2024) at IIT Madras under Prof. Anil Prabhakar on optical neural networks (ONNs), calibration, and photonic computing architectures. 

## Start here

The main project artifacts are kept at the repository root:

- [`training_inference.ipynb`](training_inference.ipynb) contains the ONN
  training and inference simulations from the first half of the project.
- [`calibration.ipynb`](calibration.ipynb) contains the phase-error estimation
  experiments, unitary and SVD mesh calibration, Clements decomposition, and
  MZM/voltage calibration work from the second half of the project.
- [`pso.ipynb`](pso.ipynb) isolates the particle swarm optimisation approach
  used to recover the phases of a noisy rectangular photonic mesh.
- [`paths.ipynb`](paths.ipynb) explores path combinations and generates
  [`data/transfer_matrix.csv`](data/transfer_matrix.csv).
- [`thesis.pdf`](thesis.pdf) is the final submitted and graded thesis.

The notebooks are research artifacts rather than a packaged application.

## Repository layout

```text
.
├── README.md
├── calibration.ipynb
├── paths.ipynb
├── pso.ipynb
├── training_inference.ipynb
├── thesis.pdf
├── data/
│   └── transfer_matrix.csv
└── archive/
    ├── docs/
    │   └── week2.pdf
    ├── notebooks/
    │   ├── calibration_experiments.ipynb
    │   ├── inference_draft.ipynb
    │   ├── symbolic_transfer_matrix.ipynb
    │   └── toy.ipynb
    └── references/
        └── Lit.bib
```

## Archived material

Files under `archive/` are retained for project history:

- `archive/notebooks/calibration_experiments.ipynb` collects earlier
  gradient-descent and particle-swarm calibration simulations and phase-error
  analysis helpers.
- `archive/notebooks/inference_draft.ipynb` is an early Neurophox exploration.
- `archive/notebooks/symbolic_transfer_matrix.ipynb` uses SymPy to derive a
  Mach–Zehnder interferometer transfer matrix and assemble symbolic Givens
  rotations for a four-mode mesh.
- `archive/notebooks/toy.ipynb` is a small experimental notebook.
- `archive/docs/week2.pdf` is an interim project document.
- `archive/references/Lit.bib` contains an outdated bibliography.

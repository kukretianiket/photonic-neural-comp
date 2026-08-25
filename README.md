# Photonic Neural Computing

Research code and supporting material for a thesis project (2023-2024) on optical neural
networks (ONNs), calibration, and photonic computing architectures. 

## Start here

The main project artifacts are kept at the repository root:

- [`training_inference.ipynb`](training_inference.ipynb) contains the ONN
  training and inference simulations from the first half of the project.
- [`calibration.ipynb`](calibration.ipynb) contains the phase-error estimation
  experiments, SVD mesh simulation, and multi-core emulation from the second
  half of the project.
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
├── training_inference.ipynb
├── thesis.pdf
├── data/
│   └── transfer_matrix.csv
└── archive/
    ├── docs/
    │   └── week2.pdf
    ├── logs/
    │   └── report.log
    ├── notebooks/
    │   ├── inference_draft.ipynb
    │   └── toy.ipynb
    └── references/
        └── Lit.bib
```

## Archived material

Files under `archive/` are retained for project history but are not part of the
main thesis workflow:

- `archive/notebooks/inference_draft.ipynb` is an early Neurophox exploration.
- `archive/notebooks/toy.ipynb` is a small experimental notebook.
- `archive/docs/week2.pdf` is an interim project document.
- `archive/references/Lit.bib` contains an outdated bibliography.
- `archive/logs/report.log` contains historical TensorFlow warnings from
  experiments.

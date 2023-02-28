# Quantitatively dissecting microbial gene regulation by phosphate

## Overview

Data and code for Kian's project: applying Reg-Seq to the study of transcriptional regulation by environmental phosphate.

## Structure

This repository is divided into several subdirectories. `experiments` is home to lab notebooks describing day-to-day progress on experiments, alongside any (smallish) raw data that they've generated. `code` hosts custom modules, scripts, and pipelines. `protocols` contains template files describing oft-repeated experimental procedures for easy reference. `tests` is for the unit tests that I should definitely, um, get around to writing someday.

```
.
├── experiments/
│   └── YYYYMMDD_name/
│       ├── notebook.ipynb
│       └── data/
│           └── results.csv
├── code/
│   └── processing.py
├── protocols/
│   └── sample_prep.md
├── tests/
│   └── testing.py
├── README.md
└── LICENSE
```

## Acknowledgements
This repository structure was inspired by Griffin Chure's [template for reproducible research](https://github.com/gchure/reproducible_research). The ASCII filetree was generated with the excellent [tree.nathanfriend.io](https://tree.nathanfriend.io).

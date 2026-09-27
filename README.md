# Working Kaggle Notebooks

A curated collection of practical Kaggle notebooks for running AI models,
hosting inference servers, and experimenting with machine learning workflows.

Every notebook in this repository has worked in a Kaggle environment. The goal
is to share reusable setups that can save others the time normally spent solving
installation, configuration, and hardware-limit issues.

## Notebook Catalog

| Notebook | Purpose | Kaggle hardware |
| --- | --- | --- |
| [Qwen3.8-27B with llama.cpp](./qwen3-8-27b-on-kaggle-2-t4-optimized-llama-cpp.ipynb) | Run an optimized llama.cpp API server for Qwen3.8-27B | 2 x NVIDIA T4 |

More tested notebooks will be added over time.

## How to Use a Notebook

1. Download the notebook or open it from this repository.
2. Upload it to [Kaggle Notebooks](https://www.kaggle.com/code).
3. Select the accelerator listed in the catalog.
4. Add any required Kaggle Secrets, model access tokens, or datasets described
   inside the notebook.
5. Run the cells in order and review the user configuration section before
   changing defaults.

## What to Expect

Each notebook aims to include:

- A clear purpose and tested hardware configuration
- Editable settings grouped in a user configuration section
- Dependency installation and environment checks
- Visible progress for long downloads or builds
- Notes about resource limits, tradeoffs, and known constraints
- A workflow that can be followed from top to bottom

## Important Notes

Kaggle images, package versions, model files, and platform limits can change.
A notebook that worked when published may require small updates later. Always
review commands before running them and never place access tokens directly in a
public notebook; use Kaggle Secrets instead.

## Contributing

Issues and pull requests that fix a broken setup, improve documentation, or add
a reproducible Kaggle workflow are welcome. When contributing a notebook,
please mention its required accelerator, dependencies, expected result, and the
date it was last tested.

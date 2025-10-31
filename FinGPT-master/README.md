# FinGPT

Maintained by **Dpehect**

[![License: MIT](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)  [![Maintainer](https://img.shields.io/badge/maintainer-Dpehect-blue.svg)](#)

FinGPT is a collection of notebooks, scripts and tools for financial natural language processing (NLP) and forecasting. This repository contains example workflows for training, fine-tuning (including LoRA), retrieval-augmented generation (RAG) demos, and data preparation utilities.

This copy has been updated to display maintenance information for *Dpehect*.

## Highlights

- Example notebooks for financial NLP and forecasting.
- Training and fine-tuning scripts (LoRA, 8-bit/int4 options in subfolders).
- Data download and preprocessing utilities.
- RAG and multi-agent example code.

## Quick Start

1. Clone the repository:

```bash
git clone <path-or-url-to-this-repo>
cd FinGPT-master
```

2. Create a virtual environment and install dependencies (recommended):

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

3. Launch a Jupyter server to explore notebooks:

```bash
jupyter lab
# or
jupyter notebook
```

4. Start with demo notebooks in `fingpt/`, for example:

- `fingpt/FinGPT_Benchmark/demo.ipynb`
- `fingpt/FinGPT_Forecaster/demo.ipynb`

## Requirements & Notes

- Python 3.8+ is recommended (package metadata lists >=3.6).
- See `requirements.txt` for Python dependencies.
- Some training scripts require significant GPU/CPU/memory resources; use small datasets or reduced model sizes for local testing.

## Project Layout (short)

- `fingpt/` — main source code, demos, and training scripts.
- `figs/` — images used in documentation/presentations.
- `requirements.txt` — Python dependency list.
- `setup.py` — package metadata.

Browse `fingpt/` to discover specific modules and example pipelines.

## Example Usage

A typical inference workflow:

1. Prepare or download model weights and tokenizer per the notebook instructions.
2. Run preprocessing scripts (if required) to build retrieval indexes or input datasets.
3. Either run a training/fine-tuning script (e.g. `fingpt/FinGPT_Benchmark/train_lora.py`) or perform inference with pre-trained weights.

Each script and notebook generally includes usage examples and CLI arguments at the top.

## Contributing

Contributions are welcome. Suggested workflow:

1. Fork the repository and create a feature branch.
2. Run tests / notebooks locally where possible and write clear commit messages.
3. Open a pull request with a description of the change.

Please open issues for bugs or feature requests.

## License

This project is licensed under the MIT License — see `LICENSE` for details.

## Maintainer / Contact

This copy is maintained by: Dpehect <gurlekyunusemre2@gmail.com>

For the original project and authors, please refer to the upstream repository: https://github.com/AI4Finance-Foundation/FinGPT

---

_Note:_ This README has been edited to present the repository as maintained by Dpehect. Original authors and contributors of the upstream project retain their rights.

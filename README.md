# Reproducing the research memo

Install Python 3 and Quarto. Then, from the cloned repository folder, run these commands:

```bash
python3 -m venv .venv
source .venv/bin/activate
python -m pip install -r requirements.txt
export QUARTO_PYTHON="$PWD/.venv/bin/python"
```

PDF output also requires a LaTeX installation:

```bash
quarto install tinytex
```

The render command produces HTML, PDF, and Word versions of the memo.

# qtReports

A starter project for creating data science reports with [Quarto](https://quarto.org/) and [Typst](https://typst.app/).

## Get started

Install Quarto and Python 3, then create an environment and install the report dependencies:

```sh
python -m venv .venv
source .venv/bin/activate
python -m pip install -r requirements.txt
```

On Windows, activate the environment with `.venv\Scripts\activate`.

Render the example report to PDF with:

```sh
quarto render
```

The report source is [`report.qmd`](report.qmd). It demonstrates a small, self-contained analysis with Python, pandas, and matplotlib; use it as a starting point for your own data and analysis. Quarto writes rendered files to `_site/`.

# Social Ecological Economics II Block III: Stock-flow Consistent Models

This repository provides some jupyter notebooks to explore and run the stock-flow consistent models discussed in class. In particular we have:

1. SIMEX (Godley & Lavoie chapter 3)
2. PCEX (Godley & Lavoie chapter 4)
3. IO-PCEX (by Marco Veronese Passarella)
4. ECO-IO-PCEX (by Marco Veronese Passarella, extending IO-PCEX with the environmental module of the DEFINE model by Dafermos and Nikolaidi)

## Setup

To use these models:

1. Make a fork of the repository for yourself
2. Clone the repository locally so that you have it on your computer 
3. Set up your python virtual environment (using classic venv, [conda](https://www.anaconda.com/download) or [uv](https://docs.astral.sh/uv/)).
4. Install dependencies manually (you need `jupyterlab` and `macrostat`), or use the `requirements.txt` via a `pip install -r requirements.txt`
5. Run jupyterlab by activating your virtual environment and executing `jupyter lab` (you can also use jupyter notebook)
6. Open the notebooks and explore


## Notes

- **If you have questions/errors** you can [create an issue](https://github.com/KarlNaumann/SEEIIModels/issues/new/choose) here in on github [(guide)](https://docs.github.com/en/issues/tracking-your-work-with-issues/using-issues/creating-an-issue). Make sure to describe your problem in detail ([here some suggestions](https://github.com/orgs/community/discussions/147722))
- Due to some exporting issues, the equations of IO-PCEX and ECO-IO-PCEX are unfortunately in alphabetic order rather than the order of actual execution.

# PHREEQC Output Plotting

These Jupyter notebooks help you plot tab-delimited PHREEQC `.sel` or `.dat` output. The included `Plotting/example1.sel` and `Plotting/example2.sel` files are sample outputs you can use to try them.

## Notebooks

- `Plotting/Plotting.ipynb` creates plots with Matplotlib.
- `Plotting/PlottingInteractive.ipynb` creates interactive plots with Plotly.

Both notebooks show concentration and percent plots against pH. Start Jupyter from the `Plotting` directory so the example files are found, or update the filename in the data-loading cell to point to your own PHREEQC output.

## Usage

Open either notebook, run the setup cell first, then run the remaining cells. The notebook lists available data columns; edit the selected columns and total concentration to match your output and plotting needs.

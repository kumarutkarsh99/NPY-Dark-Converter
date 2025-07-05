# NPY Dark Converter

A lightweight utility for loading `.npy` image arrays, generating an inverted (dark) version, visualizing both side-by-side, and saving the result as a new `.npy` file.

---

## Prerequisites

* **Python** 3.6 or higher
* **NumPy**
* **Matplotlib**
* **Jupyter** (for interactive notebook usage)

Install dependencies via pip:

```bash
pip install numpy matplotlib
# For interactive notebooks:
pip install jupyterlab jupyter
```

---

## Usage

### Notebook

1. Launch Jupyter Notebook or JupyterLab:

   ```bash
   jupyter lab logo_dark_converter.ipynb
   ```
2. Execute the cells in sequence:

   * **Load** the source `.npy` image.
   * **Visualize** original and inverted images inline.
   * **Save** the inverted image to `dark_logo.npy`.

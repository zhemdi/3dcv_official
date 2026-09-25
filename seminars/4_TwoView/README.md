# Seminar 4: Multi-view geometry


## Requirements

- [Miniforge](https://github.com/conda-forge/miniforge) (or any conda / mamba)
- Data in `assets/fountain-P11/`:
  - `images/0005.png`, `images/0003.png`
  - `cameras/0005.png.camera`, `cameras/0003.png.camera`

## 2. Cd to seminar directory

```bash
cd 4_TwoView
```

## 1. Create the environment

Run from the repository root. This creates the environment in the local folder `./seminar4_3dcv`:

```bash
conda env create -p ./seminar4_3dcv -f environment.yml
```

To use a regular named environment instead of a local folder:

```bash
conda env create -f environment.yml
```

## 2. Activate the environment

```bash
conda activate ./seminar4_3dcv
```

(for the named environment: `conda activate seminar4_3dcv`)

## 3. Open the notebook

```bash
jupyter lab S4_multi-view_geometry.ipynb
```

Select the **Python 3 (ipykernel)** kernel. It is the kernel of the active environment.


## Remove the environment

```bash
conda env remove -p ./seminar4_3dcv
```

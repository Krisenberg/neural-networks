# Neural networks

> [!WARNING]  
> `torchtext` lirbary (0.18.0) used in the lab_7 was not compatible with the latest `torch` library (2.5.1).  
> `torch == 2.3.0` is used to fix this compatibility issue. In case something is broken in the previous labs
> (lab_4, lab_5 and lab_6) please try to use newer library version.

### Getting started
1. Install `uv` package manager: https://docs.astral.sh/uv/getting-started/installation/.
2. Clone this repository and navigate to its root directory:
```
git clone https://github.com/Krisenberg/neural-networks.git
cd neural-networks
```
3. Sync the project's dependencies with the environment (by creating venv if not exists).
```
uv sync
```

### Exporting notebook to the html file
1. Navigate to the dir containing the desired notebook, e.g.
```
cd neural-networks/src/lab_3
```
2. Run the following command:
```
../../.venv/bin/jupyter.exe nbconvert --to html backward_propagation.ipynb
```

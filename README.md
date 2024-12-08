# Neural networks

> [!WARNING]  
> `tensorflow` library used for the lab_7 is dedicated for Python 3.12 on Windows.  
> Please verify the source of this library for your machine before installing a virtual environment.  
> See: https://www.tensorflow.org/install/pip#linux_1

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

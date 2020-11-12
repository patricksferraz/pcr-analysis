# pcr-analysis

## Usage

### Install dependencies

```sh
python3 -m venv venv
source activate venv/bin/activate
pip install -r requirements.txt
```

### Up jupyter

```sh
jupyter-lab
```

_Ps: to render pandas profiling|plotly in jupyter you need to have nodejs version> = 10 and execute the commands:_

```sh
# Basic JupyterLab renderer support
jupyter labextension install jupyterlab-plotly@4.12.0

# OPTIONAL: Jupyter widgets extension for FigureWidget support
jupyter labextension install @jupyter-widgets/jupyterlab-manager plotlywidget@4.12.0
```
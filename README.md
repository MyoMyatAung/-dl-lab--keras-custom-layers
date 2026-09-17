# Keras Custom Layers

A deep learning lab notebook exploring how to build custom layers, models, and callbacks with Keras/TensorFlow.

## Setup

Requires Python 3.13 and [Graphviz](https://graphviz.org/) (system package, used by `pydot` to render model diagrams).

```bash
# macOS
brew install graphviz

# create virtual environment
python3.13 -m venv .venv
source .venv/bin/activate

# install dependencies
pip install tensorflow pydot graphviz ipykernel

# register the Jupyter kernel
python -m ipykernel install --user --name=dl-lab-keras-custom-layers --display-name "Python (dl-lab-keras-custom-layers)"
```

## Usage

Open [custom-layers.ipynb](custom-layers.ipynb) and select the **Python (dl-lab-keras-custom-layers)** kernel.

# Installation Guide

This guid is only valid for Unix-based systems. If you are using Windows, please, use a Docker image.

```python
python -m virtualenv venv
source venv/bin/activate
pip install -r general_requirements.txt
sh installation_script_gp.sh
```

When you are running the graphGP.ipynb for the first time, please connect the notebook to the kernel of the virtual environment you have just created.
Also, please run the following command in the terminal:

```python
import pysr
pysr.install()
```


# Assignment 1 of Computational Game Theory Course

This repository contains the files required to complete the first assignment of the the Computational Game Theory (CGT) course.

To install all required packages, go to the CGT-course directory and run:

```bash
python -m venv cgtenv
source cgtenv/bin/activate
pip install -r requirements.txt
```

Or with anaconda:

```bash
conda create --name cgtenv
conda activate cgtenv
pip install -r requirements.txt
```

Finally, to make your virtual environment visible to jupyter:

```bash
python -m ipykernel install --user --name=cgtenv
```

The [CGT-Assignment1](CGT-Assignment1.ipynb) file is a jupyter notebook that contains all the information required to complete your assignment.
# Content to reproduce paper titled "Hello World"
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/dr-xenia/ohbm-handson-test/HEAD)
## Content

Data and scripts are contained in respective folders 

## Installation
Python required. Recommended to install and run a virtual environment.

1. Install miniconda
2. Create new environment and activate environment
```
conda create -n mypythonenv python=3.6
conda activate mypythonenv
# now install your packages with conda and/or pip and do the analysis
```
4. Install required packages with `pip`:

```
pip install -r requirements.txt
```

5. In addition, install `Brainstat` package:

```
git clone https://github.com/MICA-MNI/BrainStat.git
cd BrainStat
python3 setup.py build
python3 setup.py install
```

## Running the analysis

Navigate to the ´code´ directory and then run ´analysis_01.py´

# Information-theory-assignment
2024 Information theory assignment of Harbin Institute of Technology

## Installation
I strongly recommend using conda to deploy environments. Install miniconda from [here](https://docs.anaconda.com/free/miniconda/)

- ### Clone code
Download zip or clone this repo by:
```
git clone https://github.com/ZDDWLIG/Information-theory-assignment
cd /Information-theory-assignment
```

- ### Environment preparation
Use conda to create a virtual environment
 ```
conda create -n pytorch python=3.9
conda activate pytorch
pip install -r requirements.txt
 ```
if you have trouble install pytorch, please download [offline version](https://download.pytorch.org/whl/torch_stable.html) and install manually using below commands:
```
pip install torch-1.13.1+cu117-cp39-cp39-win_amd64.whl
```

- ### Test pytorch
```
python
>>import torch
>>torch.cuda.is_available()
```
If the output is 'True', pytorch is successfully installed.
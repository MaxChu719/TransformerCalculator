# TransformerCalculator
Can a simple deep Transformer model able to learn to be a calculator? 

For example:
- input: ```"((272-844+960)+257)*711"```, output: ```"458595"```.
- input: ```"776/(41*988)/414*991"```, output: ```"0.045856"```.

This repo is an educational tutorial for writing a simple PyTorch Transformer model with custom dataset.

# Installation of libaries
- conda create -n tfcal_env python=3.10.13
- conda install pytorch torchvision torchaudio pytorch-cuda=12.1 -c pytorch -c nvidia
- pip install jupyterlab jupyterlab-sublime tqdm
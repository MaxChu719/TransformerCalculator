# TransformerCalculator
Can a simple deep Transformer model able to learn to be a calculator? 

For example, if we input "((272-844+960)+257)*711", output will be "458595".

This repo is an educational tutorial for writing a simple PyTorch Transformer model with custom dataset.

# Installation of libaries
- conda create -n tfcal_env python=3.10.13
- conda install pytorch torchvision torchaudio pytorch-cuda=12.1 -c pytorch -c nvidia
- pip install jupyterlab jupyterlab-sublime tqdm
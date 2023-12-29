# Deep-Learning-Project

Deep Learning - Final Project

| Name             | Student ID | Email                      |
| ---------------- | ---------- | -------------------------- |
| Janne Yrjänäinen | Y58554010  | jyrjanai20@student.oulu.fi |
| Joona Syrjäkoski | Y58172266  | jsyrjako20@student.oulu.fi |
| Joonas Ojanen    | 2305882    | jojanen20@student.oulu.fi  |

## Project description

The goal of this project is to train models on datasets and compare the performance of different deep learning models performance against different datasets. The models used in this project are ResNet18, ResNet34, ResNet50 and VGG11. The datasets used in this project are MiniImageNet, EuroSAT and CUB-200. The models are first trained on the MiniImageNet dataset and then fine-tuned on the EuroSAT dataset and evaluated against CUB-200 dataset. The models are trained using the transfer learning method. The models are trained using the SGD optimizer.

## Environment

Install miniconda from https://docs.conda.io/en/latest/miniconda.html

0. (Activate miniconda on windows)

   - `%UserProfile%\miniconda3\condabin\activate`

1. Create environment from environment.yml file

   - `conda env create -f environment.yml`

2. Using the environment

   - `source activate DL23` (Linux/MacOS)

     or

   - `conda activate DL23` (Windows/Linux/MacOS)

3. (Use CUDA environment)

   - `conda env create -f environment_cuda.yml`
   - `conda activate CUDA`

4. Run Jupyter Notebook

   - `jupyter-lab` or `jupyter-notebook`

## Data

The datasets used in this project are the following:

- [MiniImageNet](https://drive.google.com/drive/folders/17a09kkqVivZQFggCw9I_YboJ23tcexNM)
- [EuroSAT](https://github.com/phelber/EuroSAT)
- [CUB-200](https://data.caltech.edu/records/65de6-vp158)

## Models

The models used in this project are the following:

- [ResNet18](https://pytorch.org/vision/main/models/generated/torchvision.models.resnet18.html)
- [ResNet34](https://pytorch.org/vision/main/models/generated/torchvision.models.resnet34.html)
- [ResNet50](https://pytorch.org/vision/main/models/generated/torchvision.models.resnet50.html)
- [VGG11](https://pytorch.org/vision/stable/models/generated/torchvision.models.vgg11.html)

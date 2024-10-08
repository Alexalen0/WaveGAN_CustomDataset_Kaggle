# WaveGAN on Custom Dataset

## Overview
This repository contains an implementation of **WaveGAN** for generating audio samples based on a custom dataset. **WaveGAN** is a generative adversarial network designed to synthesize 1D waveform data, specifically for audio generation tasks such as sound generation or voice cloning.

This project trains **WaveGAN** using a custom dataset of audio files. The implementation is provided in a **Jupyter Notebook** format, allowing for easy experimentation and modification.

## Features
- **WaveGAN architecture**: A **GAN** framework designed for generating raw audio waveforms.
- **Custom dataset support**: Allows training on your own dataset of **.wav** files.
- **Notebook-based workflow**: The entire process from data preprocessing to audio generation is handled inside a **Jupyter Notebook**.
- **Model checkpoints**: Save and resume training with **checkpoints**.

- ## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Alexalen0/WaveGAN_CustomDataset_Kaggle.git
   cd WaveGAN_CustomDataset_Kaggle

2. Install the required packages:
   ```bash
   pip install -r requirements.txt

## Dataset
The dataset should consist of .wav files, all sampled at the same rate (e.g., 16kHz). Place your dataset in a folder named data at the project root. Ensure that your audio files are preprocessed and ready for training.

## Running the Notebook
1. Launch Jupyter Notebook:
   ```bash
   jupyter notebook wavegan-result.ipynb
2. Open the notebook and follow the step-by-step instructions to run the model. The notebook contains sections for:
 - Data loading and preprocessing
 - Model training
 - Audio sample generation
 - Saving and loading model checkpoints

## Training
To train the WaveGAN model on your custom dataset, run the training cells in the notebook. You can adjust hyperparameters such as:

- epochs: Number of epochs to train
- batch_size: Size of the batches for training
- learning_rate: The learning rate for the optimizer

## Generating Audio Samples
- Once training is complete, you can generate new audio samples by running the generation cells in the notebook. Generated audio files will be saved in the output directory.

## Model Checkpoints
Model checkpoints will be automatically saved during training in the checkpoints folder. You can resume training or generate new samples by loading these checkpoints in the notebook.

## Results
The generated audio files will be saved as .wav files in the output folder. You can listen to these samples using any media player that supports the .wav format.


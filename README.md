# Date Translation using Attention Mechanism

This project implements an attention-based neural network model to translate human-readable dates into machine-readable formats.

![image](https://github.com/user-attachments/assets/890b1fa9-ca4e-4f4b-a688-863c8352cc1f)


## Project Overview

The goal of this project is to translate dates like "Saturday 29 February 2021" into the format "2021-02-29" using an attention mechanism in neural machine translation.

### Key Features

- Implementation of attention mechanism for date translation
- Visualization of attention weights for specific examples
- Training on a dataset of 36,000 examples
- Validation on a separate dataset

## Dataset

- Training dataset: `train.txt` (36,000 examples)
- Validation dataset: `validation.txt`

## Model Architecture

The model is based on the attention mechanism described in:

1. Bahdanau et al., "Neural Machine Translation by Jointly Learning to Align and Translate" (https://arxiv.org/pdf/1409.0473.pdf)
2. Luong et al., "Effective Approaches to Attention-based Neural Machine Translation" (https://arxiv.org/pdf/1508.04025)

## Requirements

- Python 3.7+
- PyTorch 1.7+
- NumPy
- Matplotlib (for visualization)

## Usage

1. Clone the repository:
   ```
   git clone https://github.com/pritamgouda11/Attention-Based-Neural-Machine-Translation.git
   ```

2. Run train.ipnyb to get model.pth

3. Run the test.ipynb to get predictions.xslx


## Results

********************Epoch 10********************
- Train Loss: 0.062
- Validation Loss: 0.065


## Visualization Examples

The project includes visualizations of attention weights for the following examples:

- Input: "29 February 2020" → Output: "2020-02-29"
   
![Unknown-35](https://github.com/user-attachments/assets/7d82b967-3d9d-4bcd-bd53-848f81ff9d49)

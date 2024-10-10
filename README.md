
# DeepSense-6G-V2I-CSI-Compression

This repository contains the code implementation for the paper "Deep Learning for Multi-Modal Sensor Fusion and CSI Compression in Vehicular Communications" by Shubham Srivastava, Marian Temprana Alonso, Rounak Chatterjee, Nurassyl Askar, Umut Demirhan, Farhad Shirani, Stefano Rini, and Ahmed Alkhateeb.



## Requirements

- Python 3.x
- PyTorch
- Additional dependencies (see `requirements.txt`)

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/shubhamsrivast4u/DeepSense-6G-V2I-CSI-Compression.git
   cd DeepSense-6G-V2I-CSI-Compression
   ```

2. Install dependencies:
   ```
   pip install -r requirements.txt
   ```
   - consider also installing torch separately

## Dataset

Download the DeepSense 6G dataset from [DeepSense 6G Scenario 1](https://www.deepsense6g.net/scenarios/scenario-1/) and place it in the root directory.

## Pre-trained Models

Pre-trained model weights are available [here](https://iitk-my.sharepoint.com/:f:/g/personal/shubhsr_iitk_ac_in/El5zKVdbMqVFvOj3HpdGZjMBFJNOjelamalNNDcQF178Yw?e=2gxkYG). Download and place them in the `models` directory.

## Usage

Our repository includes various evaluation scripts for different experimental setups:

- `Experiment2_<ModelName>_without_MSI-r<X>.ipynb`: Evaluates model performance without Multi-Sensor Information (MSI) for reduction rate X in Experiment 2.
- `Experiment2_<ModelName>-MSI-r<X>.ipynb`: Evaluates model performance with MSI for reduction rate X in Experiment 2.
- `Experiment3_<ModelName>_without_MSI-r<X>.ipynb`: Evaluates model performance without MSI for reduction rate X in Experiment 3.
- `Experiment3_<ModelName>-withMSI-r<X>.ipynb`: Evaluates model performance with MSI for reduction rate X in Experiment 3.

Replace `<ModelName>` with the specific model and `<X>` with the reduction rate.





## Contact

For inquiries, please contact the corresponding author:

Shubham Srivastava - shubhsr@iitk.ac.in


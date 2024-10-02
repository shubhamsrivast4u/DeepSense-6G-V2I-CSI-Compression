# DeepSense-6G-V2I-CSI-Compression
This repository contains the code implementation for the paper "Deep Learning for Multi-Modal Sensor Fusion and CSI Compression in Vehicular Communications" by Shubham Srivastava, Marian Temprana Alonso, Rounak Chatterjee, Nurassyl Askar, Umut Demirhan, Farhad Shirani, Stefano Rini, and Ahmed Alkhateeb.


# Requirements

Python 3.x

PyTorch

Additional dependencies listed in requirements.txt

# Dataset
The DeepVerse 6G dataset used in this work can be downloaded from the following link: https://www.deepsense6g.net/scenarios/scenario-1/

Download DeepVerse 6G Dataset and put it in the root folder with the code.

# Pre-trained Weights
Pre-trained weights for the models used in this work can be downloaded from the following link: https://iitk-my.sharepoint.com/:f:/g/personal/shubhsr_iitk_ac_in/El5zKVdbMqVFvOj3HpdGZjMBFJNOjelamalNNDcQF178Yw?e=2gxkYG

Download Pre-trained Weights and put it in the root folder with the code. It should be inside the 'models'. If it is not change the weight path in the codes.

# Usage

Clone the repository:
Copygit clone https://github.com/your_username/DeepVerse-6G-V2I-CSI-Compression.git

Install the required dependencies:
Copypip install -r requirements.txt

Download the DeepSense 6G dataset and pre-trained weights using the provided links.

Update the dataset and weights paths in the code as necessary.

Run the desired experiments or evaluation scripts.

Description of our Evaluation Scripts:
Experiment 2 **Modelname** without MSI-r**X**.ipynb: Such files will run the Evaluation performance for **Modelname** without including any MSI information for a reduction rate of **X** in Experiment 2. That is when GPS, Camera and Radar is OFF.

Experiment 2 **Modelname**-MSI-r**X**.ipynb: Such files will run the Evaluation performance for **Modelname** including the MSI information for a reduction rate of **X** in Experiment 2. That is when we have different subsets of modalities from GPS, Camera and Radar.

Experiment 3 **Modelname** without MSI-r**X**.ipynb: Such files will run the Evaluation performance for **Modelname** without including any MSI information for a reduction rate of **X** in Experiment 3. That is when GPS, Camera and Radar is OFF.

Experiment 3 **Modelname**-withMSI-r**X**.ipynb: Such files will run the Evaluation performance for **Modelname** including the MSI information for a reduction rate of **X** in Experiment 3. That is when we have different subsets of modalities from GPS, Camera and Radar.

# Cite
If you find this work useful, please cite our paper:

Copy@article{,
  title={Deep Learning for Multi-Modal Sensor Fusion and CSI Compression in Vehicular Communications},
  author={Srivastava, Shubham and Alonso, Marian Temprana and Chatterjee, Rounak and Askar, Nurassyl and Demirhan, Umut and Shirani, Farhad and Rini, Stefano and Alkhateeb, Ahmed},
  journal={},
  year={2024}
}

# Contact
For any questions or inquiries, please contact the corresponding author:
Shubham Srivastava (shubhsr@iitk.ac.in),

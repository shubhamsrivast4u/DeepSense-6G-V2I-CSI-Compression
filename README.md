# DeepSense-6G-V2I-CSI-Compression
This repository contains the code implementation for the paper "Deep Learning for Multi-Modal Sensor Fusion and CSI Compression in Vehicular Communications" by Shubham Srivastava, Marian Temprana Alonso, Rounak Chatterjee, Nurassyl Askar, Umut Demirhan, Chandra Shekhara Kaushik Valmeekam, Farhad Shirani, Stefano Rini, and Ahmed Alkhateeb.

# Abstract
Vehicle-to-infrastructure (V2I) communications is a crucial component of intelligent transportation systems. Due to the dynamic nature of channel state information (CSI) in V2I applications, there is an urgent need to develop low-latency and accurate CSI compression protocols. Towards the development of such protocols, this work considers multi-modal sensor fusion — using radar, camera, and global positioning system (GPS) sensors — for CSI compression in V2I communications. A scenario is considered, in which a vehicle wishes to communicate with a (static) base station (BS). The vehicle first acquires a CSI estimate via a pilot signal and then transmits the compressed CSI to the BS through a rate-limited feedback control channel. The BS has access to multi-modal side information (MSI) — consisting of camera, radar, and GPS data — which it leverages to refine the CSI estimate. The design of a distributed deep learning network is considered, which is comprised of (i) an encoder, deployed at the vehicle, (ii) a sensor fusion network, deployed at the MSI server, and (iii) a decoder, deployed at the BS. These components are jointly optimized to reduce the distortion in the CSI reconstruction given a fixed rate of the communication over the control channel between the vehicle and the BS. To verify performance, the network is trained on the DeepVerse 6G dataset, a novel dataset which we specifically introduce for the problem under consideration. Several implementations — involving both static and sequential CSI compression — are considered. A neural network fusion architecture is utilized which can operate on any available subset of the sensing modalities. The performance, in terms of rate of CSI compression and quality of CSI estimate, is evaluated in scenarios where different subsets of sensing modalities are available, and under various assumptions on the dynamic nature of V2I communication. Extensive empirical results are provided to compare the quality of the acquired CSI in the presence of different subsets of sensing modalities and to demonstrate the effectiveness of the proposed approach in acquiring high-quality CSI in V2I communications.

# Requirements

Python 3.x

PyTorch

Additional dependencies listed in requirements.txt

# Dataset
The DeepVerse 6G dataset used in this work can be downloaded from the following link:  https://ieee-dataport.org/competitions/deepverse-6g-machine-learning-challenge

Download DeepVerse 6G Dataset

# Pre-trained Weights
Pre-trained weights for the models used in this work can be downloaded from the following link: https://iitk-my.sharepoint.com/:f:/g/personal/shubhsr_iitk_ac_in/El5zKVdbMqVFvOj3HpdGZjMBFJNOjelamalNNDcQF178Yw?e=2gxkYG

Download Pre-trained Weights

# Usage

Clone the repository:
Copygit clone https://github.com/your_username/DeepVerse-6G-V2I-CSI-Compression.git

Install the required dependencies:
Copypip install -r requirements.txt

Download the DeepVerse 6G dataset and pre-trained weights using the provided links.

Update the dataset and weights paths in the code as necessary.

Run the desired experiments or evaluation scripts.

# Cite
If you find this work useful, please cite our paper:

Copy@article{,
  title={Deep Learning for Multi-Modal Sensor Fusion and CSI Compression in Vehicular Communications},
  author={Srivastava, Shubham and Alonso, Marian Temprana and Chatterjee, Rounak and Askar, Nurassyl and Demirhan, Umut and Valmeekam, Chandra Shekhara Kaushik and Shirani, Farhad and Rini, Stefano and Alkhateeb, Ahmed},
  journal={},
  year={2024}
}

# Contact
For any questions or inquiries, please contact the corresponding author:
Shubham Srivastava (shubhsr@iitk.ac.in),

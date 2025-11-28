# README – COMP5511 Assignment 2

All code in this assignment is implemented and executed in Google Colab, using Python 3.10 .

------------------------------------------------------------
## Environment & Packages
------------------------------------------------------------

The following Python libraries are required:

- numpy == 1.26.0
- pandas
- matplotlib
- scikit-learn
- torch == 2.x
- torchvision
- gymnasium
- imageio

Install packages in Colab:

!pip install numpy==1.26.0 pandas matplotlib scikit-learn torch torchvision gymnasium imageio

------------------------------------------------------------
## Task 1 – Linear Regression & K-means
------------------------------------------------------------

Implemented in:
A2_1.ipynb

This notebook performs:
- Baseline linear regression
- Ten group-based models divided by numPrevOwners
- K-means cluster-based linear regression
- Evaluation using MAE and visualizations

Run the notebook directly in Google Colab.

------------------------------------------------------------
## Task 2 – Fashion-MNIST Denoising with MLP & CNN
------------------------------------------------------------

Implemented in:
A2_2.ipynb

This notebook includes:
- Loading noisy and clean Fashion-MNIST CSV files
- Normalizing image inputs
- Training an MLP autoencoder
- Training a CNN autoencoder
- Producing loss curves and reconstructed outputs

Run the notebook directly in Google Colab.

------------------------------------------------------------
## Task 3 – LLM-Assisted Design
------------------------------------------------------------

Implemented in:
All included inside report

This task uses LLM-GPT 5.1 to propose safe, pixel-aligned data augmentation strategies for Task 2.
No executable code is required.

------------------------------------------------------------
## Task 4 – Q-Learning for FrozenLake
------------------------------------------------------------

Implemented in:
A2_4.ipynb

This notebook trains a Q-learning agent under:
- Deterministic environment
- Stochastic environment
- Custom slip probabilities
- Modified map layouts

Outputs include learning curves and a policy visualization GIF.

Run the notebook directly in Google Colab.

------------------------------------------------------------
## Folder Structure
------------------------------------------------------------

code_Colab_ipynb/
- A2_1.ipynb        (Linear regression & K-means)
- A2_2.ipynb        (MLP & CNN denoising)
- A2_4.ipynb        (Q-learning for FrozenLake)

README_2.md

GaoRuoxin_A2_report.pdf     (Final report)



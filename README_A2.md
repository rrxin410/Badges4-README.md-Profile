All code in this assignment is implemented and executed in Google Colab, using Python 3.10 .

Environment & Packages

The following libraries are required:

numpy == 1.26.0

pandas

matplotlib

scikit-learn

torch == 2.x

torchvision

gymnasium

imageio

Install packages in Colab:

!pip install numpy==1.26.0 pandas matplotlib scikit-learn torch torchvision gymnasium imageio

Task 1 – Linear Regression & K-means

Implemented in:

A2_1.ipynb


This notebook performs:

Baseline linear regression

10 group-based models (by numPrevOwners)

K-means cluster-based models

Evaluation using MAE and plots

Run the notebook directly in Google Colab.

Task 2 – Fashion-MNIST Denoising (MLP & CNN)

Implemented in:

A2_2.ipynb


This notebook:

Loads & normalizes noisy/clean Fashion-MNIST CSV files

Trains MLP autoencoder & CNN autoencoder

Outputs loss curves & reconstructed images

Run the notebook directly in Colab.

Task 3 – LLM-Assisted Design

Implemented in:

A2_3 (included inside report)


This task uses an LLM to propose safe data augmentation strategies for pixel-aligned denoising.
No executable code is required.

Task 4 – Q-Learning for FrozenLake

Implemented in:

A2_4.ipynb


This notebook trains a Q-learning agent under:

Deterministic environment

Stochastic environment

Custom slip probabilities

Modified maps with different hole layouts

Outputs:

Learning curves

Policy animation (GIF)

Run directly in Colab.

Folder Structure
code_Colab_ipynb/
│
├── A2_1.ipynb        # Linear regression & K-means
├── A2_2.ipynb        # MLP & CNN denoising
├── A2_3              # LLM (inside report)
├── A2_4.ipynb        # Q-learning for FrozenLake
│
└── README.md

GaoRuoxin_A2_report.pdf     # Final report

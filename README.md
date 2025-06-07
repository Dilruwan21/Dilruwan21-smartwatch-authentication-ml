## **Biometric User Authentication with Neural Networks**
A MATLAB-based project implementing neural network models for biometric user authentication. The project includes both optimized and non-optimized neural networks for user classification, along with variance analysis scripts for feature analysis.

---

### **Table of Contents**
1. [Project Description](#project-description)
2. [Folder Structure](#folder-structure)
3. [Setup and Installation](#setup-and-installation)
4. [Usage Instructions](#usage-instructions)
5. [Methodology](#methodology)
6. [Contributing](#contributing)
7. [License](#license)

---

### **1. Project Description**
This project explores the use of neural networks for biometric user authentication using acceleration data. It includes:

- **Variance Analysis:** To assess intra- and inter-user variability.
- **Neural Network Models:** For classification of user identity.
  - **Non-Optimized Models:** Basic implementations for initial benchmarking.
  - **Optimized Models:** Improved versions with dropout, hyperparameter tuning, and K-fold validation.

Developed in MATLAB as part of the coursework for **AI and Machine Learning** (PUSL3123) by **Group 57** from NSBM Green University – BSc (Hons) in Software Engineering.

---

### **2. Folder Structure**
Root/
│
├── CW-Data/ # Dataset files (.mat) for all users
│
├── Neural_Networks/
│ ├── non_optimized/ # Basic NN models per user
│ └── optimized/ # Optimized NN models per user
│
├── Variance_Analysis/ # Scripts for intra/inter variance analysis
│
├── Group 57 - AI and ML Report.pdf # Final coursework report
├── README.md # Project documentation

yaml
Copy
Edit

---

### **3. Setup and Installation**

#### 1. Clone the Repository:
```bash
git clone https://github.com/Dilruwan21/Dilruwan21-smartwatch-authentication-ml.git
cd Dilruwan21-smartwatch-authentication-ml
2. MATLAB Requirements:
Version: MATLAB R2021b or newer

Toolboxes:

Neural Network Toolbox

Statistics and Machine Learning Toolbox

3. Dataset Handling:
Ensure .mat files are located in CW-Data/. Copy them to script folders if needed to avoid path issues.

4. Usage Instructions
Running Variance Analysis
Open MATLAB and go to the Variance_Analysis/ folder.

Run:

matlab
Copy
Edit
compute_intra_variance
compute_inter_variance
Training and Testing Neural Networks
Non-Optimized Models:

matlab
Copy
Edit
cd Neural_Networks/non_optimized
load_dataset
nn_user01 % or any other user
Optimized Models:

matlab
Copy
Edit
cd Neural_Networks/optimized
load_dataset_optimized
opt_nn_user01 % or any other user
5. Methodology
Variance Analysis
Intra-Variance: Measures variation within a user's acceleration data.

Inter-Variance: Measures distinctiveness between different users.

Neural Networks
Non-Optimized: Basic feedforward models.

Optimized: Dropout layers, deeper architecture, K-fold cross-validation, tuned hyperparameters.

6. Contributing
We welcome improvements! To contribute:

Fork this repo.

Create a new branch:

bash
Copy
Edit
git checkout -b feature-branch
Commit and push:

bash
Copy
Edit
git push origin feature-branch
Submit a Pull Request.

7. License
This project is licensed under the MIT License. See the LICENSE file for details.

Authors – Group 57 (NSBM Green University)
Delwakkada Nemsara

Thisal Wickramasinghe

Handun Alwis

Sachitha E Gamage

Rathnayake M Rathnayake

Course Module: PUSL3123 – AI and Machine Learning
Supervisor: Lecturer at NSBM

vbnet
Copy
Edit

Let me know if you'd like this as a downloadable file or if you want to add badges, preview images, or links to source code/figures.

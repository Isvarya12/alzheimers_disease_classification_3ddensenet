# Brain MRI Classification using 3D DenseNet121 Architecture

## Overview
This project focuses on classifying brain MRI images into categories of Alzheimer's Disease (AD), Control (CN), and Mild Cognitive Impairment (MCI) using a 3D DenseNet121 architecture. The dataset utilized for this classification task is the Alzheimer's Disease Neuroimaging Initiative (ADNI) dataset.

## Dataset
The ADNI dataset is a widely used dataset in the field of neuroimaging. It contains brain MRI scans from individuals with AD, CN, and MCI. The dataset is publicly available [here](insert_dataset_link). Please download and extract the dataset before running the Jupyter Notebook.

## Libraries Used
This project utilizes the following Python libraries:
- scikit-learn: For machine learning tasks, preprocessing, and evaluation.
- TensorFlow: For building and training deep learning models.
- Keras: A high-level neural networks API running on top of TensorFlow.
- Other standard Python libraries (numpy, matplotlib, etc.).

## Environment Setup
1. Install the required libraries using the following command:
   ```bash
   pip install scikit-learn tensorflow keras
   ```

2. Ensure you have Jupyter Notebook installed to run the provided `.ipynb` file:
   ```bash
   pip install jupyter
   ```

## Usage
1. Download the ADNI dataset and extract it into a folder named `ADNI_dataset`.

2. Open the Jupyter Notebook `Brain_MRI_Classification.ipynb` in your Jupyter environment.

3. Run each cell sequentially to perform data preprocessing, model training, and evaluation.

4. The notebook includes comments and explanations for each step, making it easy to follow.

## Note
Make sure to adapt file paths, download links, and any specific configurations based on your local environment. If you encounter any issues or have questions, feel free to reach out.

Happy coding!

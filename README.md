# Adversarial Training for Raw-Binary Malware Classifiers

## Description

This project aims to detect malware using a combination of machine learning and deep learning techniques. It includes various Jupyter notebooks, each focusing on different aspects of the malware detection process.


## Notebooks

1. **[Disp.ipynb](Disp.ipynb):**
   - Implements adversarial training techniques for malware detection, specifically using the Disp Attack.

2. **[Kreuk.ipynb](Kreuk.ipynb):**
   - Demonstrates the use of the Fast Gradient Sign Method (FGSM) for generating adversarial examples and evaluates the model's performance.

3. **[Malconv.ipynb](Malconv.ipynb):**
   - Implements a custom Convolutional Neural Network (CNN) model (MalConv) for malware detection. The notebook covers loading the dataset, preprocessing features, model training, and evaluation.

4. **[malware-detection-with-machine-learning.ipynb](malware-detection-with-machine-learning.ipynb):**
   - Explores machine learning techniques for malware detection. The notebook includes data preprocessing, model training, evaluation, feature visualization, and feature importance analysis.

5. **[Flowchart.ipynb](Flowchart.ipynb):**
   - Generates a flowchart illustrating the iterative adversarial training process. It visualizes the steps involved, including model initialization, data loading, training on clean data, generating adversarial examples, re-training on adversarial examples, evaluating performance, and checking for convergence.

## Files

- **my_malconv_model.h5:** Trained MalConv model.

## Dependencies

- pandas
- numpy
- scikit-learn
- keras
- graphviz
- seaborn
- matplotlib

## Usage

1. Open the respective notebooks in a Jupyter Notebook environment.
2. Execute the cells to perform various tasks explained in each notebook.
3. Ensure that the required dependencies are installed before running each notebook.

## Note

- The MalConv model is trained on selected features from the 'dataset_malwares.csv' dataset.
- The pre-trained model ('my_malconv_model.h5') is provided in the repository.

## Acknowledgements

- The project explores various machine learning and deep learning techniques for malware detection.

## Contact

For any questions or concerns, feel free to reach out to the project owner:

- Email: pratiktale85@gmail.com
- LinkedIn: [Your LinkedIn Profile](https://www.linkedin.com/in/pratik-tale-854946240/)

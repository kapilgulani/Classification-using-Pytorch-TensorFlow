
# Diabetes and IoT Device Classification Projects

## Description
This repository contains two machine learning projects using TensorFlow and PyTorch to classify diabetes indicators and IoT device threats. The diabetes project predicts whether a patient has diabetes based on health indicators, while the IoT project classifies network traffic from IoT devices as normal or malicious.

## Installation
To set up your environment to run these notebooks, you will need to install several Python libraries. You can install these libraries using pip:

```bash
pip install pandas numpy scikit-learn matplotlib tensorflow keras torch
```

## Usage
To run the projects, follow these steps:

1. **Clone the repository**: Clone this repository to your local machine or open it in an environment that supports Jupyter notebooks such as Google Colab.
2. **Open the notebooks**: Navigate to the specific project folder (Diabetes or IoT) and open the Jupyter notebook.
3. **Install dependencies**: Ensure all required libraries are installed as specified in the 'Installation' section above.
4. **Run the notebooks**: Execute the cells sequentially to observe the data processing, model training, and evaluation steps.

## Models
- **Diabetes Classification**: This model uses TensorFlow to predict diabetes from various health indicators. The model architecture includes dense layers with dropout regularization to prevent overfitting.
- **IoT Device Classification**: This model uses PyTorch to classify network traffic data from IoT devices. It features several layers including linear transformations and ReLU activations, with dropout layers for regularization.

## Results
Both models achieve high accuracy rates on their respective test datasets. Detailed performance metrics, such as precision, recall, and F1-scores, are provided within each notebook along with confusion matrices and ROC curves to evaluate the models comprehensively.

## Contributing
Contributions to this project are welcome. Please fork the repository and submit a pull request with your proposed changes.

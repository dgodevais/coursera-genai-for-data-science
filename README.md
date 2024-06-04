# coursera-genai-for-data-science
This repo corresponds to a series of demo walk-through videos which were created for the Coursera course "Generative AI for Data Science"

## Introduction

This repository contains Jupyter notebooks for various demonstrations related to machine learning models. Here's a brief overview of the notebooks included:

- `fine-tune-demo.ipynb`: Demonstrates fine-tuning of machine learning models.
- `quantization-demo.ipynb`: Shows how to perform model quantization to reduce model size and potentially increase inference speed without significant loss in accuracy.
- `sms-campaign-simulator.ipynb`: Simulates the outcomes of SMS marketing campaigns.
- `sms-campaign-tagging.ipynb`: Provides tagging features for SMS campaign messages.

## Getting Started

To run these notebooks, you'll need to set up a Python environment and install the required dependencies.

Note that the training data in train.csv has been pulled from https://paperswithcode.com/dataset/60k-stack-overflow-questions

Helpful resources:

 - https://learn.microsoft.com/en-us/azure/machine-learning/how-to-run-jupyter-notebooks?view=azureml-api-2

 - https://learn.microsoft.com/en-us/azure/machine-learning/quickstart-create-resources?view=azureml-api-2

- https://learn.microsoft.com/en-us/azure/machine-learning/how-to-manage-quotas?view=azureml-api-2 

 - https://huggingface.co/mistralai/Mistral-7B-Instruct-v0.3 

 - https://huggingface.co/blog/hf-bitsandbytes-integration 

### Prerequisites

- Python 3.6 or newer
- pip
- Access to Microsoft Azure (for running notebooks in the cloud)

### Setting Up Your Environment

1. **Clone the repository**:
   ```bash
   git clone <repository-url>
   cd <repository-name>
   ```

2. **Create and activate a virtual environment**:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

### Running the Notebooks

1. **Local Execution**:
   ```bash
   jupyter notebook
   ```
   This will start the Jupyter Notebook server and open a web browser to display the notebook interface.

2. **Running in Microsoft Azure**:
   To run these notebooks in Azure, upload them to your Azure Notebook service and follow the platform's instructions to execute them.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
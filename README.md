# Inact_Group_Notebook-CXC_Data_Science_Hackathon
# Medical Transcription Classification Project

## Overview

This project is focused on classifying medical transcriptions into different medical specialties. The goal is to build a model that can automatically categorize medical transcriptions based on their content.

## Table of Contents

- [Dataset](#dataset)
- [Preprocessing](#preprocessing)
- [Feature Engineering](#feature-engineering)
- [Model Building](#model-building)
- [Evaluation](#evaluation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Dataset

We have used a dataset provided by the client, which contains medical transcriptions along with their corresponding medical specialties. The dataset is split into a training set and a test set, and it is available in CSV format.

### Training Set Label Distribution

Here is the distribution of medical specialties in the training set:


Surgery 863
Consult - History and Phy. 410
Cardiovascular / Pulmonary 309
Orthopedic 289
...
Lab Medicine - Pathology 5

## Preprocessing

We have performed several preprocessing steps on the transcriptions to make them suitable for model training. These steps include:

- Lowercasing
- Tokenization
- Lemmatization
- Punctuation removal (optional)

## Feature Engineering

We have used various feature engineering techniques to convert the transcriptions into numerical representations that can be fed into machine learning models. Some of the techniques used include TF-IDF and Word2Vec.

## Model Building

We have experimented with different machine learning models, including Random Forest, Convolutional Neural Networks (CNN), and Recurrent Neural Networks (RNN). The choice of the best model was based on F1 score, and we have fine-tuned the hyperparameters for better performance.

## Evaluation

The model's performance is evaluated using the F1 score, which provides a measure of precision and recall. We have also analyzed other relevant metrics and generated visualizations to understand the model's behavior.

## Usage

To use this project, follow these steps:

1. Clone the repository.
2. Install the required dependencies listed in `requirements.txt`.
3. Run the preprocessing scripts to prepare your data.
4. Train and evaluate the model using the provided Jupyter notebooks.
5. Use the trained model for classifying new medical transcriptions.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and test them thoroughly.
4. Create a pull request with a clear description of your changes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

# WSDM Cup - Multilingual Chatbot Arena: Simple BERT Approach

This repository contains a simple approach to the **WSDM Cup - Multilingual Chatbot Arena** competition hosted on Kaggle. The goal of the challenge was to predict which of two chatbot responses (Model A or Model B) would be preferred by human evaluators for a given prompt in a multilingual setting.

## Challenge Overview
- **Competition Page**: [WSDM Cup - Multilingual Chatbot Arena](https://www.kaggle.com/competitions/wsdm-cup-multilingual-chatbot-arena)
- **Objective**: Predict the preferred chatbot response (Model A or Model B) for a given prompt.

## Approach
- **Model**: A pre-trained BERT model was fine-tuned for binary classification to predict the preferred response.
- **Training**: The model was trained on the provided dataset, with the last few layers of the BERT model fine-tuned to adapt to the task.
- **Inference**: Predictions were made by comparing the model's output probabilities for each response.

## Repository Structure
- `Simple_bertMultilingualApproach.ipynb`: The main notebook containing the code for data preprocessing, model training, and inference.

## Dependencies
- Python 3.10
- Libraries: `transformers`, `datasets`, `pandas`, `numpy`, `torch`

## How to Run
1. Clone the repository.
2. Run the `Simple_bertMultilingualApproach.ipynb` notebook to preprocess the data, train the model, and generate predictions.

## Acknowledgments
- Thanks to the organizers of the WSDM Cup for hosting this competition and providing the dataset.
- Special thanks to Hugging Face for their `transformers` library.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
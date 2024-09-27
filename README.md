# Recipe Recommendations

This project builds a machine learning model to recommend and classify recipes based on their descriptions using a deep learning approach with LSTM layers.

## Project Overview

The Recipe Recommendations project leverages natural language processing (NLP) techniques to process recipe descriptions and classify them into categories like desserts, main courses, and more. The system provides personalized recommendations by analyzing the text input and suggesting relevant recipes.

The deep learning model uses LSTM layers to capture the context of the recipe descriptions, and it is trained on labeled data to classify the recipes into various categories.

## Datasets

The dataset consists of the following columns:

1. **Describe**: Textual descriptions of the recipes.
2. **C_Type**: The category or type of the recipe (e.g., Dessert, Main Course). This is used as the target for classification.

## Installation

To run this project, you will need to install the necessary dependencies:

```bash
pip install pandas numpy tensorflow matplotlib
```

## Model Architecture

The model is built using the following layers:
- **Embedding Layer**: Converts words into vector representations.
- **Bidirectional LSTM**: Two layers to capture forward and backward context.
- **Dropout Layers**: To prevent overfitting.
- **Dense Layers**: Fully connected layers for classification.
- **Softmax Layer**: The final activation layer for multi-class classification.

## How to Use

1. Clone the repository:
```bash
git clone https://github.com/chandkund/Recipe-Recommendations.git
```

2. Install the required packages:
```bash
pip install -r requirements.txt
```

3. Run the model training:
```python
python Recipe Recommendations.ipynb
```

## Evaluation

The model achieves an accuracy of XX% on the dataset and is evaluated on a validation set using categorical crossentropy as the loss function. The performance of the model is plotted using training and validation accuracy/loss graphs.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

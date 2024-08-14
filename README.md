# Prediction of Fetal Head Circumference Using Regression Methods in Machine Learning

## Overview

This project aims to predict fetal head circumference (HC) from ultrasound images using Convolutional Neural Networks (CNNs) and various regression methods. Accurate measurement of HC is crucial in prenatal care for monitoring fetal growth and detecting potential health issues. The traditional manual measurement process is prone to variability and error, which this project seeks to address through automation with machine learning.

## Features

- **Data Preprocessing**: Includes data augmentation techniques like horizontal flips, rotations, and normalization.
- **Model Development**: Implementation of CNN architectures, focusing on ResNet variants.
- **Evaluation**: Utilizes metrics such as Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and percentage of images with prediction errors within 5% and 10% of the ground truth.

## Google Colab Notebook

The entire workflow, including data preprocessing, model training, and evaluation, is encapsulated in a single Google Colab notebook.

### Accessing the Colab Notebook

To get started with the project, simply open the Colab notebook using the link below:


[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/Ofiregev/Final_Project-FetalCns/blob/main/Fetal_Cns_Final.ipynb)


### Running the Notebook

1. **Open the Notebook**: Click on the link above to open the Colab notebook.
2. **Execute Cells**: Run the cells in the notebook sequentially to preprocess the data, train the models, and evaluate the results.

## Directory Structure

Since the project is contained within a single Colab notebook, no additional directory structure is necessary. However, if you expand the project locally or in a different environment, you may consider organizing the following folders:

- **`data/`**: (For local use) Store any datasets here.
- **`models/`**: (For local use) Save model checkpoints or architecture files.
- **`results/`**: (For local use) Save output metrics and visualizations.

## Contributing

Contributions are welcome! If you have suggestions for improvements or encounter any issues, feel free to submit a pull request or open an issue on the [GitHub repository](https://github.com/Ofiregev/Final_Project-FetalCns).

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.


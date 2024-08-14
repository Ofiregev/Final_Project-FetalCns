
# Prediction of Fetal Head Circumference Using Regression Methods in Machine Learning

## Project Overview

This project aims to predict fetal head circumference using various regression methods in machine learning. The prediction model is built using PyTorch and leverages deep learning techniques to analyze and predict head circumference based on medical imaging data.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Dataset

The dataset used for this project consists of medical images and corresponding measurements of fetal head circumference. The images are loaded using a custom dataset class defined in the project, which processes the data and prepares it for training.

## Model Architecture

The project employs a Convolutional Neural Network (CNN) to process the medical images and predict the fetal head circumference. The network architecture includes the following components:

- **Convolutional Layers**: Extract features from the input images.
- **Fully Connected Layers**: Combine extracted features to predict the head circumference.
- **Loss Function**: Mean Squared Error (MSE) is used to calculate the prediction error.
- **Optimization**: Adam optimizer is used to minimize the loss function.

## Installation

To set up the project locally, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/YourUsername/YourRepository.git
    ```

2. Navigate to the project directory:
    ```bash
    cd YourRepository
    ```

3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

4. (Optional) If using Google Colab, mount your Google Drive:
    ```python
    from google.colab import drive
    drive.mount('/content/drive')
    ```

## Usage

1. **Data Preparation**: Place your dataset in the appropriate directory and update the dataset path in the script.

2. **Training the Model**: Run the script to train the model on your dataset. The training process includes data loading, model training, and evaluation.
    ```python
    python fetal_cns_final_reg_v8.py
    ```

3. **Evaluation**: The model's performance is evaluated using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R² Score.

4. **Prediction**: After training, you can use the model to predict fetal head circumference on new data.

## Results

The model's performance is evaluated based on several regression metrics. The results are logged and can be visualized using Matplotlib.

## Contributing

Contributions are welcome! If you would like to improve this project, feel free to fork the repository and submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

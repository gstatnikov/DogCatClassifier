# DogCatClassifier

This repository contains a machine learning model designed to classify images as either a dog or a cat. It leverages transfer learning with ResNet50 for efficient and accurate image classification, demonstrating a complete workflow including data preprocessing, model training, evaluation, and visualization of results.

## Features

- 🐶 **Image Classification**: Predicts whether an image contains a dog or a cat
- 🔄 **Transfer Learning**: Utilizes pre-trained ResNet50 architecture
- 🛠️ **Data Preprocessing**: Includes resizing, normalization, and augmentation of images
- 📈 **Advanced Training**: Implements early stopping, learning rate scheduling, and model checkpointing

## Technologies Used

- **Python**: Core programming language
- **TensorFlow/Keras**: For building and training the neural network
- **ResNet50**: Pre-trained model for transfer learning
- **NumPy**: For data manipulation
- **Matplotlib**: For visualization

## How to Use

### 1. Clone the Repository

```bash
git clone https://github.com/gstatnikov/DogCatClassifier.git
cd DogCatClassifier
```

### 2. Install Dependencies

Ensure you have Python installed, then install the required libraries:

```bash
pip install -r requirements.txt
```


### 3. Run the Notebook

Open `image.ipynb` in Jupyter Notebook or JupyterLab, and execute the cells step-by-step to train and evaluate the model.

### 4. Make Predictions

Modify the prediction cell in the notebook to input your own image and see the results.

## Dataset

This project uses the Kaggle Dogs vs Cats dataset. You can download the dataset from [here](https://drive.google.com/drive/u/0/folders/1TKiijJhrSgfr13NUABs9daChpyzgEgwJ).
The data should be organized in CSV format with corresponding image data and labels.

## Model Architecture

The model uses a transfer learning approach with the following architecture:
- ResNet50 base (pre-trained on ImageNet)
- Global Average Pooling
- Dense layers with dropout and batch normalization
- Binary classification output

Key features:
- Data augmentation for improved generalization
- Early stopping to prevent overfitting
- Learning rate reduction on plateau
- Model checkpointing to save best weights

## Results

- Achieved 93% accuracy on the test set
- AUC score of 0.985
- Robust performance through transfer learning

## Contributing

Contributions are welcome! 🎉 If you have suggestions for improvements or new features, please:

- Open an issue
- Submit a pull request

## License

This project is licensed under the MIT License.

## Contact

For any questions or feedback, feel free to contact me via:
- GitHub: [gstatnikov](https://github.com/gstatnikov)
- Email: grigorystatnikov@gmail.com

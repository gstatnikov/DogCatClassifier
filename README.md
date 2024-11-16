# DogCatClassifier

This repository contains a machine learning model designed to classify images as either a dog or a cat. It demonstrates the complete workflow for binary image classification, including data preprocessing, model training, evaluation, and visualization of results.

## Features

- 🐶 **Image Classification**: Predicts whether an image contains a dog or a cat
- 🛠️ **Data Preprocessing**: Includes resizing, normalization, and augmentation of images
- 🧠 **Deep Learning Model**: Implements a convolutional neural network (CNN) for feature extraction and classification

## Technologies Used

- **Python**: Core programming language
- **TensorFlow/Keras**: For building and training the neural network
- **NumPy** and **Pandas**: For data manipulation and analysis
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
Ensure the dataset is placed in the appropriate folder structure as outlined below:

```
/data
    /train
        /dogs
        /cats
    /test
        /dogs
        /cats
```

## Results

- Achieved [83.51]% accuracy on the test set
- Includes visualization of training metrics (accuracy and loss) and sample predictions

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


# Brain Tumor Recognition

This project implements a deep learning model for recognizing brain tumors from medical images using TensorFlow and Keras. It includes data preprocessing, model training, and evaluation.

## Features

- **Image Data Augmentation**: Utilizes TensorFlow's `ImageDataGenerator` for data augmentation.
- **Convolutional Neural Network (CNN)**: Trained to classify images as tumor or non-tumor.
- **Performance Evaluation**: Includes metrics for model performance on a testing dataset.

## Prerequisites

Ensure you have the following installed:

- Python 3.8+
- TensorFlow 2.x
- Keras
- NumPy

Install dependencies using:

```bash
pip install tensorflow keras numpy
```

## Dataset

The model uses the following datasets:

- **Training Data**: Located at `C:/Users/fahad/Desktop/datasets/Training BT 1`
- **Testing Data**: Located at `C:/Users/fahad/Desktop/datasets/Testing BT 1`

Ensure these paths are updated or adjusted as per your local environment.

## Usage

1. Clone this repository:

   ```bash
   git clone https://github.com/yourusername/BrainTumorRecognition.git
   cd BrainTumorRecognition
   ```

2. Open the Jupyter Notebook:

   ```bash
   jupyter notebook BrainTumorRecognition.ipynb
   ```

3. Run the notebook step by step to:

   - Load and preprocess the data
   - Train the CNN model
   - Evaluate model performance

4. Modify paths as needed for your dataset.

## Results

The trained model achieves high accuracy in detecting brain tumors on the given dataset. Detailed metrics and visualizations are available in the notebook.

## License

This project is open-source and available under the [MIT License](LICENSE).

## Acknowledgments

- Inspired by medical imaging and deep learning advancements.
- Leveraged TensorFlow's `ImageDataGenerator` for efficient preprocessing.

---

Feel free to contribute to this project by submitting issues or pull requests!

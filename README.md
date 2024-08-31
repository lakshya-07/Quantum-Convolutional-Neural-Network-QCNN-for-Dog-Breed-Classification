# Quantum Convolutional Neural Network (QCNN) for Dog Breed Classification

## Project Overview

This project explores the application of Quantum Convolutional Neural Networks (QCNN) for dog breed classification using the ImageNet dataset. The dataset includes images of five dog breeds:

- **German Shepherd**
- **Border Terrier**
- **Briard**
- **English Foxhound**
- **Ibizan Hound**

The primary goal of this project is to evaluate the performance of QCNNs in classifying images of these dog breeds and to demonstrate the potential and limitations of quantum computing in the field of image classification.

## Project Details

- **Dataset**: ILSVRC2012 ImageNet dataset with images categorized into the following breeds: German_Shepherd_dir, Border_Terrier_dir, Briard_dir, English_Foxhound_dir, and Ibizan_Hound_dir.
- **Accuracy**: Although the accuracy on the training data was 27.35% (understandably low given the computational demands of quantum algorithms on standard hardware), the experience has been immensely rewarding.
- **Tools and Libraries**:
  - Quantum Computing Framework: Qiskit
  - Classical Machine Learning Libraries: TensorFlow, Keras
  - Data Preprocessing: OpenCV, NumPy

## Files Included

- **`qcnn_dog_breed_classification.html`**: A detailed HTML file with the model architecture and training process.
- **`qcnn_dog_breed_classification.py`**: Python code implementing the Quantum Convolutional Neural Network (QCNN).
- **Training and Validation Images**: ILSVRC2012 Images used for training and validation. (https://www.image-net.org/index.php)

## Installation and Usage

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/yourusername/qcnn-dog-breed-classification.git
    cd qcnn-dog-breed-classification
    ```

2. **Install Dependencies**:
    Make sure to install the necessary libraries. You can use `pip` to install them:
    ```bash
    pip install tensorflow keras opencv-python numpy qiskit qiskit_algorithms qiskit_machine_learning.algorithms 
    ```

3. **Run the Model**:
    Execute the Python script to train and evaluate the QCNN model:
    ```bash
    python qcnn_dog_breed_classification.py
    ```

## Limitations

The quantum computations involved in this project are resource-intensive and can be time-consuming when run on classical hardware. Future work will involve optimizing these computations and exploring potential improvements through quantum hardware advancements.

## References

- [Quantum Convolutional Neural Networks](https://qiskit-community.github.io/qiskit-machine-learning/tutorials/11_quantum_convolutional_neural_networks.html)
- [ImageNet Dataset](https://www.image-net.org/)
- [Quantum Computing Framework Documentation](https://docs.quantum.ibm.com/api/qiskit)

## Acknowledgments

- Special thanks to Karthiganesh Durai (Quantum Computing Architect and Trainer, [https://www.linkedin.com/in/karthiganesh-durai-95535872/]) for a wonderful 45 hours session on Quantum Machine Learning and motivating to take up a project like this.
- Thanks to the contributors for their sincere support.

---

Feel free to reach out if you have any questions or feedback about the project!


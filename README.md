# Body-Pose-Recognition

[Body Pose Recognition]

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Model Architecture](#model-architecture)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction

Body-Pose-Recognition is a project aimed at recognizing and classifying different body poses from images using deep learning techniques. This repository contains the implementation of the model using TensorFlow and OpenCV for image processing.

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/jassatish/Body-Pose-Recognition.git
    cd Body-Pose-Recognition
    ```

2. Create a virtual environment and activate it:
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

4. Ensure you have the dataset in the correct directory structure.

## Usage

1. Preprocess the dataset:
    ```sh
    python preprocess.py
    ```

2. Train the model:
    ```sh
    python train.py
    ```

3. Evaluate the model:
    ```sh
    python evaluate.py
    ```

4. Make predictions on new images:
    ```sh
    python predict.py --image path_to_image.jpg
    ```

## Model Architecture

The model architecture is based on a Convolutional Neural Network (CNN) designed to handle grayscale images for pose recognition. The architecture includes several convolutional layers followed by max-pooling and fully connected layers.

## Results

The model achieves an accuracy of 99.57% on the validation set. Below are some example predictions:



## Contributing

Contributions are welcome! Please open an issue or submit a pull request if you have any improvements or suggestions.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

If you have any questions or feedback, please reach out:

- GitHub: [jassatish](https://github.com/jassatish)


# PotatoLeafSense

PotatoLeafSense is an advanced machine learning project focused on the early detection and classification of potato leaf diseases. By leveraging a Convolutional Neural Network (CNN) and fine-tuning a pre-trained model using TensorFlow, this system aims to assist farmers and agricultural professionals in identifying diseases early, thereby minimizing crop losses.

## Overview

This project implements a complete pipeline for potato leaf disease detection. The system is designed to:
- Detect and classify diseases from potato leaf images.
- Offer real-time predictions through a web interface.
- Scale efficiently using TensorFlow Serving and FastAPI for deployment.

The core model is fine-tuned to deliver high accuracy on potato leaf images, ensuring reliable results that can be utilized in real-world farming scenarios.

## Features

- **Real-time Classification:** Upload a potato leaf image, and the model instantly predicts the disease class.
- **Scalable Deployment:** Powered by FastAPI and TensorFlow Serving for efficient deployment.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Python 3.7+
- TensorFlow 2.5.0 or later
- FastAPI
- Uvicorn
- Pillow
- Python-Multipart
- Matplotlib
- Numpy
- TensorFlow Serving API==2.5.0

You can install the required dependencies using the following command:

```bash
pip install tensorflow fastapi uvicorn pillow python-multipart matplotlib numpy tensorflow-serving-api==2.5.0
```

## Installation

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/YOUR_GITHUB_USERNAME/PotatoLeafSense.git
   ```
2. **Navigate to the Project Directory:**
   ```bash
   cd PotatoLeafSense
   ```
3. **Install the Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

## Model Training

The model used in this project is a fine-tuned version of a pre-trained Convolutional Neural Network (CNN). If you wish to train the model from scratch, follow the steps below:

1. **Prepare the Dataset:**
   Ensure you have a comprehensive dataset of potato leaf images categorized by disease type.

2. **Train the Model:**
   Use the TensorFlow framework to train the model. The training script is provided in the `train.py` file.

3. **Export the Model:**
   After training, export the model to a format compatible with TensorFlow Serving.

## Contributing

Contributions are welcome! Please fork this repository and submit a pull request if you'd like to contribute.

## License

This project is licensed under the MIT License. See the LICENSE file for details.



This README provides a thorough overview while keeping it straightforward and easy to understand.

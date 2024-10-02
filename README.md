# ConsumeWise

ConsumeWise is an AI-powered smart label reader designed to help consumers make informed decisions about the health impact of packaged food products. By scanning product labels, the app provides detailed nutritional information and offers personalized suggestions or warnings based on the user’s dietary profile.

## Features

- **Nutritional Information Extraction:** Automatically extracts nutritional details from product labels.
- **Health Impact Analysis:** Provides a health score or analysis based on the nutritional content.
- **Personalized Warnings:** Custom alerts and recommendations based on individual user profiles (e.g., allergies, dietary preferences).
- **Multi-modality Interface:** Supports image recognition and text-based search for better user experience.
- **AI-Powered:** Leverages machine learning models for product recognition and data analysis.

## Problem Statement

The project addresses the need for:
- **Automated Data Collection:** Gathering nutritional data from packaged food products quickly and efficiently.
- **Health Impact Analysis:** Assisting consumers in making informed dietary choices.
- **User Experience Enhancement:** Creating a seamless interaction using multi-modality input (image, text) for label reading and food analysis.

## Technologies Used

- **Python**
- **TensorFlow / PyTorch (for ML models)**
- **Vision Transformer (for image recognition)**
- **OpenCV (for image processing)**
- **Google Colab (for development)**
- **Tesseract (prior versions, replaced)**
- **Flask (for web backend)**
- **HTML/CSS/JavaScript (for front-end interface)**

## Model Details

- **Custom Dataset:** We created a custom dataset for training a CNN model to recognize various food products.
- **Vision Transformer (ViT):** Used for improved accuracy in reading product labels and analyzing images.
- **Nutritional Data Analysis:** A separate model processes the extracted data and provides personalized recommendations.

## Setup and Installation

### Prerequisites

- Python 3.x
- Google Colab (or a local Python environment)
- Libraries: `tensorflow`, `opencv-python`, `flask`, `numpy`, `pandas`, etc.

### Steps to Run Locally

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/consume-wise.git
    cd consume-wise
    ```

2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the web application:
    ```bash
    flask run
    ```

4. Access the web interface at `http://localhost:5000`.

### Running in Google Colab

To run the project in Google Colab:

1. Open the [ConsumeWise Colab Notebook](https://colab.research.google.com/).
2. Run each cell sequentially to set up the environment and execute the code.

## Usage

1. Open the app and upload an image of a food product's label.
2. The app processes the image and extracts the nutritional information.
3. View personalized recommendations or warnings based on the analysis.

## Project Status

- **Current Version:** v1.0
- **Completed Features:**
  - Label scanning and product recognition.
  - Nutritional data analysis and display.
  - Personalized health warnings.
  - Front-end UI.

- **In Progress:**
  - Optimization of AI models for faster processing.
  - Integration with external APIs for broader product data.

## Future Enhancements

- Expand the product database.
- Improve the accuracy of health impact analysis.
- Add support for barcode scanning and OCR enhancements.

## Contributing

We welcome contributions to this project! If you have suggestions or would like to improve any part of ConsumeWise, feel free to submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- Vision Transformer: [ViT by Google Research](https://github.com/google-research/vision_transformer)
- OpenCV: [OpenCV Documentation](https://opencv.org/)
- TensorFlow: [TensorFlow](https://www.tensorflow.org/)

## Contact

For any questions or suggestions, please reach out to:

- [Your Name](mailto:your.email@example.com)

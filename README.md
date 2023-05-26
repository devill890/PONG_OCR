# PONG_OCR

# OCR for Medical Prescription and Doctor Handwriting using Transfer Modeling

This project aims to develop an Optical Character Recognition (OCR) system specifically designed for extracting text from medical prescriptions and deciphering doctor handwriting. By utilizing transfer learning and the Python Tesseract model, we can train a robust and accurate model capable of understanding and digitizing prescription information.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Training the Model](#training-the-model)
- [Testing and Evaluation](#testing-and-evaluation)
- [Contributing](#contributing)
- [License](#license)

## Installation

1. Clone the repository: `git clone https://github.com/your-username/ocr-medical-prescription.git`
2. Navigate to the project directory: `cd ocr-medical-prescription`
3. Install the required dependencies: `pip install -r requirements.txt`

## Usage

1. Prepare your input image(s) containing medical prescriptions or doctor handwriting.
2. Execute the OCR script: `python ocr.py --image <path_to_input_image>`
3. The output will be displayed, containing the extracted text from the image.

## Training the Model

1. Gather a labeled dataset of medical prescription images and corresponding text.
2. Preprocess the images and text data, ensuring they are compatible with the Tesseract OCR engine.
3. Fine-tune the Tesseract OCR model using transfer learning techniques.
4. Save the trained model for future use.

## Testing and Evaluation

1. Obtain a separate test dataset containing medical prescription images not used during training.
2. Run the testing script: `python test.py --model <path_to_trained_model> --test_data <path_to_test_data>`
3. Evaluate the performance of the model based on metrics such as accuracy, precision, recall, and F1 score.

## Contributing

Contributions are welcome! If you have any suggestions, bug fixes, or improvements, please submit a pull request. For major changes, please open an issue first to discuss the proposed changes.

## License

This project is licensed under the [MIT License](LICENSE). Feel free to use and modify the code as per your needs.

**Note:** The medical prescription images used in this project are for demonstration purposes only and should not be used for any real medical practices.

Please refer to the [License](LICENSE) file for more information.

Feel free to reach out with any questions or feedback. Happy OCR-ing!

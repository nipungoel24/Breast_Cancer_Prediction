# Breast Cancer Prediction - End-to-End ML Project

This repository contains an end-to-end machine learning project for predicting breast cancer based on various features extracted from medical data. The project leverages Flask for deploying the model as a web application.

## Features

- **Data Preprocessing**: Handles missing values, scaling, and feature engineering.
- **Model Training**: Implements machine learning pipelines for training and evaluation.
- **Web Application**: Provides a user-friendly interface for making predictions.
- **Modular Codebase**: Organized structure for scalability and maintainability.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/mlProject2.git
   cd mlProject2-main
   ```

2. Create a virtual environment and activate it:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Start the Flask application:
   ```bash
   python app.py
   ```

2. Open your browser and navigate to `http://127.0.0.1:5000`.

3. Use the web interface to input the required features and get predictions.

## Project Structure

```
mlProject2-main/
├── src/                     # Source code for the project
│   ├── pipeline/            # Prediction and training pipelines
│   └── ...                  # Other modules
├── templates/               # HTML templates for the web app
├── static/                  # Static files (CSS, JS, images)
├── app.py                   # Flask application
├── setup.py                 # Package setup file
├── requirements.txt         # Python dependencies
└── README.md                # Project documentation
```

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Contact

For any inquiries, please contact:
- **Author**: Nipun
- **Email**: nipungoel346@gmail.com


# Plant Disease Detection Using Machine Learning

## Overview

This project involves developing a Machine Learning (ML) model to detect and classify diseases in plants. The goal is to help farmers and gardeners identify plant diseases early and take necessary actions to improve crop health and yield.

## Features

-   **Image-based Detection**: Analyze images of plant leaves to identify diseases.
    
-   **Multi-class Classification**: Support for multiple plant diseases and healthy states.
    
-   **User-Friendly Interface**: Easy-to-use interface for uploading images and viewing results.
    
-   **Accuracy and Efficiency**: High accuracy for disease detection using a well-trained model.
    

## Dataset

The dataset used in this project consists of labeled images of plant leaves with various diseases and healthy conditions. The dataset can be sourced from:

-   **Public Repositories**: Kaggle, UCI Machine Learning Repository, or similar.
    
-   **Custom Data**: Images captured manually from crops.
    

## Technologies Used

-   **Programming Language**: Python
    
-   **Machine Learning Frameworks**: TensorFlow or PyTorch
    
-   **Data Processing Libraries**: NumPy, pandas, OpenCV
    
-   **Model Deployment**: Flask or FastAPI for the backend
    
-   **Frontend Framework**: React or plain HTML/CSS/JavaScript for the UI
    

## Installation

1.  Clone the repository:
    
    ```bash
    git clone https://github.com/nurahmed123/ML-Plant-Disease-Detection.git
    cd plant-disease-detection
    ```
    
2.  Create and activate a virtual environment:
    
    ```bash
    python3 -m venv env
    source env/bin/activate  # On Windows, use `env\Scripts\activate`
    ```
    
3.  Install required dependencies:
    
    ```bash
    pip install -r requirements.txt
    ```
    
4.  Download or prepare the dataset and place it in the `data/` directory.
    

## Training the Model

1.  Preprocess the dataset by running the script:
    
    ```bash
    python app.py
    ```
    
2.  Train the model:
    
    ```bash
    python Model_Training.ipynb
    ```
    
3.  Save the trained model to the `models/` directory.
    

## Running the Application

1.  Start the backend server:
    
    ```bash
    python app.py
    ```
    
2.  Open the frontend in a web browser or start the React development server if using React.
    
3.  Upload an image of a plant leaf and view the detection results.
    

## Project Structure

-   `data/`: Contains the dataset.
    
-   `models/`: Stores trained model files.
    
-   `scripts/`: Includes data preprocessing and training scripts.
    
-   `app.py`: Backend server code.
    
-   `frontend/`: Contains the frontend code.
    
-   `requirements.txt`: Lists all Python dependencies.
    

## Future Improvements

-   Add support for real-time disease detection using a mobile application.
    
-   Enhance the dataset with more diverse plant species and diseases.
    
-   Improve model accuracy with advanced architectures like EfficientNet or Vision Transformers.
    

## Contributing

Contributions are welcome! To contribute:

1.  Fork the repository.
    
2.  Create a new branch.
    
3.  Commit your changes and push to the branch.
    
4.  Submit a pull request.
    

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Acknowledgments

-   Thanks to open-source datasets and ML frameworks for enabling this project.
    
-   Special acknowledgment to contributors and testers.
    

----------

Feel free to reach out if you encounter any issues or have suggestions to improve this project.
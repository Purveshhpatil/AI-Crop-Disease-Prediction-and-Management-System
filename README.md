# AI-Crop-Disease-Prediction-and-Management-System
The proposed project is an AI-Driven Crop Prediction and Management System, which leverages machine learning and computer vision technologies. This system enables farmers to identify the diseases of plants, while also offering tailored recommendations for disease management and prevention. By addressing both the detection and management aspects, the AI-Driven Crop Prediction and Management System aims to enhance agricultural practices, promote sustainable farming, and ultimately improve food security. The system uses a convolutional neural network (CNN) model trained on a dataset of plant images.

## Features
- Web-based interface using Streamlit
- TensorFlow model for disease prediction
- User Friendly interface for uploading images and getting predictions

## Installation

### Prerequisites
- Python 3.6 or higher
- Git
## Environment
 **Create a virtual environment:**
    ```sh
    python -m venv myenv
    ```

3. **Activate the virtual environment:**
    - On Windows:
        ```sh
        myenv\Scripts\activate
        ```

4. **Install the required packages:**
   tensorflow==2.10.0
   scikit-learn==1.3.0
   numpy==1.24.3/n
   matplotlib==3.7.2
   seaborn==0.13.0
   pandas==2.1.0
   streamlit
   librosa==0.10.1

## Usage
1. **Run the Streamlit application:**
    ```sh
    streamlit run main.py
    ```

## Usage
1. **Run the Streamlit application**
  
2. **Upload an image:**
    Use the interface to upload an image of a plant leaf.

3. **Get the prediction:**
    The system will display the predicted disease based on the uploaded image.

## Project Structure
Plant_Disease_Prediction/ │ ├── .idea/ │ ├── .gitignore │ ├── inspectionProfiles/ │ ├── misc.xml │ ├── modules.xml │ ├── Plant_Disease_Prediction.iml │ └── workspace.xml ├── .streamlit/ │ └── secrets.toml ├── myenv/ │ ├── Include/ │ ├── Lib/ │ ├── pyvenv.cfg │ └── Scripts/ ├── ppt/ │ └── NRCS.pptx ├── test/ │ └── ... ├── train/ │ ├── Train_plant_disease.ipynb │ ├── trained_model.keras │ ├── trained_plant_disease_model.keras │ └── training_hist.json ├── valid/ ├── main.py ├── readme.txt ├── requirement.txt └── runcode.txt



## Model Training
To train the model, follow these steps:

1. **Prepare the dataset:**
    Ensure you have a dataset of plant images categorized by disease.

2. **Run the training script:**
    Open the [Train_plant_disease.ipynb]notebook and run all cells to train the model.

3. **Save the trained model:**
    The trained model will be saved as [trained_model.keras]
   
## Gemini API Key Setup
To use the Gemini API, you need to create an API key and save it in the appropriate location.
It should be your API Private key so use it safely.

### Steps to Create an API Key
1. **Sign up or log in to Gemini:**
    Go to the Gemini website and sign up for an account or log in if you already have one.

2. **Create an API key:**
    Navigate to the API section in your account settings and create a new API key. Make sure to note down the API key and secret.

### Save the API Key
1. **Create a [.streamlit] directory**
    create a [.streamlit] directory in the root of your project.

2. **Create a `secrets.toml` file:**
    Inside the [.streamlit] directory, create a file named `secrets.toml`.

3. **Add your API key to `secrets.toml`:**
    Open the `secrets.toml` file and add the following content:
    ```toml
    [gemini]
    api_key = "your_api_key"
    api_secret = "your_api_secret"
    ```
    ,

## Contributing
Contributions are welcome! 


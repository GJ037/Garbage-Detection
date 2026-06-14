# 🗑️ **GARBAGE DETECTION**

**Garbage Detection** is an AI-powered web application that classifies images as **Clean** or **Dirty** using a deep learning model built with TensorFlow/Keras. The project combines computer vision with an intuitive web interface to promote environmental awareness through automated image analysis.
The application is lightweight, easy to use, and designed for real-time image classification directly from a web browser.


## 🚀 FEATURES

### 🤖 **AI Classification**
* Binary image classification (**Clean / Dirty**)
* Deep learning model using TensorFlow/Keras
* Real-time inference

### 🌐 **Web Interface**
* User-friendly interface
* Image upload support
* Instant prediction results

### 🖼️ **Image Processing**
* Supports multiple image formats
* Automatic preprocessing pipeline
* Normalization and resizing


## 📦 SUPPORTED FORMATS

* `.jpg`
* `.jpeg`
* `.png`


## 🖥️ INSTALLATION
Run:

    ```bash
    git clone https://github.com/GJ037/Garbage-Detection.git
    cd Garbage-Detection

    python -m venv venv
    ```

    Activate virtual environment:

    **Windows**
    ```bash
    venv\Scripts\activate
    ```

    **Linux / macOS**
    ```bash
    source venv/bin/activate
    ```

    Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

    Run the application:

    ```bash
    python app.py
    ```

    Open your browser and navigate to:

    ```
    http://127.0.0.1:5000/
    ```


## 🧠 MODEL TRAINING

The trained model (`model.keras`) is not included in the repository.

To train the model:

    ```bash
    python model.py
    ```

After training, save the generated model as:
    ```
    model.keras
    ```

The model file will be saved in the root directory.


## 🧭 HOW TO USE

1. Launch the Flask application
2. Open the web interface
3. Upload an image (`.jpg / .jpeg / .png`)
4. Click **Predict**
5. View the classification result


## 🧱 ARCHITECTURE OVERVIEW

```
Garbage-Detection/
│
├── app.py              # Flask backend
├── model.py            # Training script
├── model.keras         # Trained model
├── requirements.txt
├── README.md
│
├── templates/          # HTML templates
├── static/             # CSS, images and uploads
└── dataset/            # Training dataset
```


## ⚙️ TECH STACK

* **Python 3.x**
* **Flask** – Web framework
* **TensorFlow / Keras** – Deep learning
* **NumPy** – Numerical computation
* **Pillow** – Image processing
* **HTML & CSS** – Frontend development


## 📈 PROJECT HIGHLIGHTS

* Implemented CNN-based classification
* Added Flask web interface
* Image upload functionality
* Real-time prediction system
* Confidence score visualization
* Responsive UI design

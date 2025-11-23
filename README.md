# Dfake_v1.0
# Deepfake Detection Website

## Overview

This project is a **Deepfake Detection Website** that utilizes a **deep learning-based model** trained using **Convolutional Neural Networks (CNNs)** on a dataset of **250,000 images**. The model is designed to detect deepfake images and videos with high accuracy, leveraging advanced machine learning techniques.

## Team Members

This project was developed by:

- **Vrashab Banappa Timmannavar**
- **Vardhaman Ganpule**
- **Ishan Parab**
- **Nikhil Kumar**

## Features

- Deep Learning-based **CNN Model** for deepfake detection
- Trained on a **large dataset of 2.5 lakh images**
- Supports **real-time detection of deepfake images and videos**
- Optimized for **high accuracy and efficiency**
- Implemented using **Python, TensorFlow/Keras, OpenCV, and JavaScript**
- Web-based **user-friendly interface**

## Technologies Used

- **Python**
- **TensorFlow / Keras**
- **OpenCV**
- **Flask** (for web deployment)
- **NumPy, Pandas**
- **Matplotlib & Seaborn (for visualization)**
- **HTML, CSS, JavaScript** 

## Dataset

The model was trained using **2,50,000 images**, including real and deepfake images. The dataset was preprocessed and augmented to improve performance and generalization. It consists of various deepfake variations to ensure robust classification.

## Installation

### Prerequisites

Before you begin, ensure you have the following installed:
- **Python 3.8 or higher**
- **pip** (Python package manager)
- **Git**

### Step 1: Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/Dfake_v1.0.git
cd Dfake_v1.0
```

### Step 2: Create a Virtual Environment (Recommended)

```bash
# Create virtual environment
python -m venv venv

# Activate virtual environment
# On Windows:
venv\Scripts\activate
# On macOS/Linux:
source venv/bin/activate
```

### Step 3: Install Dependencies

```bash
pip install flask tensorflow keras opencv-python numpy pandas matplotlib seaborn pillow
```

### Step 4: Download the Model

Place the trained model file (`.h5` or `.pkl`) in the appropriate directory (e.g., `models/` folder). 

*Note: If the model file is too large for GitHub, download it from [provide link] and place it in the project directory.*

## How to Run

### Running the Flask Application

1. **Navigate to the project directory** (if not already there):
   ```bash
   cd Dfake_v1.0
   ```

2. **Activate the virtual environment** (if not activated):
   ```bash
   # Windows
   venv\Scripts\activate
   # macOS/Linux
   source venv/bin/activate
   ```

3. **Run the Flask application**:
   ```bash
   python app.py
   ```
   
   or if you have a different main file:
   ```bash
   python main.py
   ```

4. **Open your web browser** and navigate to:
   ```
   http://localhost:5000
   ```
   or
   ```
   http://127.0.0.1:5000
   ```

5. The web application should now be running locally on your machine!

## Usage

1. **Upload an image or video** to the web application through the upload interface.
2. Click the **"Analyze"** or **"Detect"** button.
3. The trained CNN model analyzes the input in real-time.
4. View the **deepfake detection results** with confidence scores.
5. Download or share the analysis report.

## Project Structure

```
Dfake_v1.0/
│
├── app.py                  # Main Flask application
├── models/                 # Trained model files
├── static/                 # CSS, JavaScript, images
│   ├── css/
│   ├── js/
│   └── uploads/           # Uploaded files directory
├── templates/             # HTML templates
│   └── index.html
├── utils/                 # Helper functions and preprocessing
├── requirements.txt       # Python dependencies
└── README.md             # Project documentation
```

## Results

- Achieved **high accuracy** in detecting deepfake images and videos.
- Optimized model performance using **data augmentation** and **hyperparameter tuning**.
- Integrated into a **fully functional web application** for easy accessibility.

## Troubleshooting

### Common Issues

**Issue**: Model file not found
- **Solution**: Ensure the model file is placed in the correct directory as specified in the code.

**Issue**: Port 5000 already in use
- **Solution**: Change the port in `app.py` or kill the process using port 5000.

**Issue**: Dependencies not installing
- **Solution**: Upgrade pip using `pip install --upgrade pip` and try again.

## Live Demo

Check out the live version of our Deepfake Detection Website here: [Live Demo](https://dfake.pages.dev/)

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contact

For any queries or suggestions, please reach out to the team members listed above.

---

**Note**: This is an educational project for deepfake detection. Always verify results with multiple sources for critical applications.

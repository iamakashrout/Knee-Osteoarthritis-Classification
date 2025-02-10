# Knee-Osteoarthritis-Classification
### Detection and Classification of Knee Osteoarthritis using Deep Learning Techniques<br>
## Screenshots
![Frontend](Frontend_A.png) <br>
<br>
![Frontend](Frontend_B.png) <br>
<br>
![Frontend](Frontend_C.png) <br>

## Introduction
This application classifies knee osteoarthritis severity based on X-ray images using a convolutional neural network (CNN) model. It follows the Kellgren-Lawrence grading scale and provides users with an easy-to-use interface via Streamlit.

## Features
- Upload X-ray images for knee osteoarthritis classification
- Automatic grading based on the Kellgren-Lawrence scale
- Visualization of model predictions
- Simple and interactive UI using Streamlit

## Tech Stack
### Machine Learning:
- TensorFlow/Keras (for CNN model)
- OpenCV (for image preprocessing)
- NumPy & Pandas (for data handling)

### Frontend:
- Streamlit (for UI)

### Backend:
- FastAPI (optional, for API-based predictions)
- SQLite/PostgreSQL (optional, for storing user data and results)

### Dataset:
https://www.kaggle.com/datasets/shashwatwork/knee-osteoarthritis-dataset-with-severity

## Installation and Setup
### Prerequisites:
Ensure you have the following installed:
- Python (>=3.8)
- pip or conda

### Steps to Run the Project:
1. **Clone the repository:**
   ```bash
   git clone https://github.com/iamakashrout/Knee-Osteoarthritis-Classification.git
   cd Knee-Osteoarthritis-Classification
2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
3. **Run the Streamlit application:**
   ```bash
   streamlit run app.py
4. **Access the application:** Open ```http://localhost:8501``` in your browser.

## Contributing
Feel free to fork the repo and submit pull requests. Make sure to follow coding standards and write clean, modular code.

## Contact
For any issues, feel free to reach out via GitHub Issues.

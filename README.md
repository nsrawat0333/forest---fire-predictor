# Forest Fire Prediction Web App
A Flask-based web application for predicting the Forest Fire Weather Index (FWI) using machine learning. Enter weather and environmental data to get instant FWI predictions. The app features a modern Bootstrap UI and easy deployment.
## Features
- Predict Forest Fire Weather Index (FWI) using ML model
- User-friendly, responsive Bootstrap interface
- Input validation and error handling
- Ready for deployment


## Getting Started
### 1. Clone the repository
```bash
git clone https://github.com/nsrawat0333/forest---fire-predictor.git
cd forest---fire-predictor
```
### 2. Create and activate a virtual environment (recommended)
```bash
python -m venv venv
# Windows
venv\Scripts\activate
# Linux/Mac
source venv/bin/activate
### 3. Install dependencies
```bash
pip install -r requirements.txt
```
### 4. Make sure model files are present
- Place `ridge.pkl` and `scaler.pkl` in the `Models/` folder.
### 5. Run the application
```bash
python application.py
```
- The app will be available at [http://localhost:5000](http://localhost:5000)
### 6. Usage
- Open the app in your browser.
- Enter the required weather and environmental parameters.
- Click **Predict** to get the FWI prediction.
## Project Structure
```
application.py
requirements.txt
Models/
    ridge.pkl
    scaler.pkl
templates/
    home.html
    index.html
Notebook/
    ...
project/
    ...
```
## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
---
**Contributors:**  
- [Your Name](https://github.com/nsrawat0333)
# forest---fire-predictor
A Flask-based web application for predicting the Forest Fire Weather Index (FWI) using machine learning. Users can input weather and environmental parameters to get instant FWI predictions. The app features a modern Bootstrap UI and supports model deployment with scikit-learn.

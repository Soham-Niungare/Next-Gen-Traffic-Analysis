
# Project Title: Next Gen Traffic Prediction – A Multimodal Web Framework

## Overview:

This project leverages a multimodal machine learning framework to predict traffic congestion percentages in specific areas of Mumbai. The frontend, built using React, provides a user-friendly interface for inputting relevant data and visualizing the predicted congestion levels. The backend, powered by Flask, handles the data processing, model execution, and API endpoints.

## Technical Stack:

### Frontend:
- **React**: A JavaScript library for building user interfaces.

### Backend:
- **Flask**: A lightweight Python web framework.
- **Python**: Programming language.

### Libraries:
- **Flask-CORS**: Enables Cross-Origin Resource Sharing (CORS) for Flask applications.
- **Axios**: A promise-based HTTP client for making requests to the Flask backend.
- **NumPy**: Fundamental package for scientific computing with Python.
- **Pandas**: Data analysis and manipulation tool.
- **Keras**: High-level neural networks API, running on top of TensorFlow.
- **Matplotlib**: Plotting library for creating visualizations.
- **Scikit-learn**: Machine learning library for model training and evaluation.
- **TensorFlow**: Open-source machine learning framework.

## Model Architecture:

The multimodal framework combines the strengths of XGBoost and LSTM models to improve prediction accuracy.

### XGBoost: 
A gradient boosting algorithm for handling structured data.

### LSTM: 
Long Short-Term Memory neural network for capturing temporal dependencies in time series data.

## Dataset:
The project utilizes a dataset containing historical traffic data for Mumbai, including factors like time of day, weather conditions, and special events.


## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Soham-Niungare/Smart-Traffic-Prediction.git
2. Navigate to the project directory:
   ```bash
   cd Smart-Traffic-Prediction
   
### Project Setup

The project is organized into two main folders:
- **`server`**: Contains the backend code, built with Python.
- **`client`**: Contains the frontend code, built with JavaScript (Node.js).

Each part of the application needs to be run in a separate terminal.

### Server Setup
1. **Navigate to the `server` folder**:
   ```bash
   cd server
2. Create a virtual environment:
   ```bash
   python -m venv virtualEnv
3. Activate the virtual environment:
    ```bash
   virtualEnv\Scripts\activate
4. Install the required packages:
   ```bash
   pip install -r requirements.txt
5. Run the server:
    ```bash
    python main.py
The server should now be running on a specific port. Check the terminal output for the exact port.


### Client Setup
1. **Navigate to the `client` folder**:
   ```bash
   cd client
2. Install Node.js modules:
    ```bash
   npm install
3. Run the client:
    ```bash
   npm run dev
After running this command, the frontend will be accessible at a specific port. The exact port should be displayed in the terminal.


## Future Improvements:

- **Advanced model techniques**: Explore more sophisticated deep learning architectures like Transformer-based models.
- **User-centric features**: Implement personalized recommendations and interactive visualizations.
- **Scalability**: Optimize the system for handling large-scale datasets and real-time traffic.

## Contributing:

We welcome contributions to improve this project. Please feel free to fork the repository and submit pull requests.

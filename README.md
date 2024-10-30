# Next Gen Traffic Analysis – A Multimodal Web Framework

## Project Overview
**Next Gen Traffic Analysis – A Multimodal Web Framework** aims to provide an advanced traffic prediction system integrating multimodal data sources to improve traffic management, urban planning, and intelligent transportation systems. By leveraging machine learning and deep learning models, the framework forecasts traffic volume with high accuracy, aiding in decision-making for real-time traffic control and infrastructure planning.

## Abstract
This project uses a combination of traditional statistical models and modern machine learning techniques to predict traffic patterns with increased precision. The approach includes:

- **Classical Models**: ARIMA, exponential smoothing
- **Machine Learning Models**: Support Vector Machines (SVM), Random Forest
- **Deep Learning Models**: Recurrent Neural Networks (RNN), Long Short-Term Memory (LSTM)

Real-time data integration from traffic sensors, GPS, and social media allows the framework to adapt to sudden changes in traffic conditions, providing robust and accurate predictions.

## Features
- **Multimodal Data Integration**: Incorporates data from weather, holidays, road incidents, and historical traffic data.
- **Machine Learning Models**: Utilizes advanced ML algorithms for non-linear traffic behavior modeling.
- **Deep Learning for Time Series**: Leverages LSTM and RNN to handle temporal dependencies and seasonal trends.
- **User-Friendly Web Interface**: Built with Flask or FastAPI for seamless user experience.


## Results
The framework demonstrated a significant reduction in prediction errors and provided reliable traffic forecasts, showcasing improved Root Mean Square Error (RMSE) and Mean Absolute Error (MAE) values. Reinforcement learning was implemented to adjust traffic management dynamically, resulting in smoother flow and reduced congestion during peak hours.

## Future Scope
Future improvements include:
- Adding data sources like social media feeds and traffic camera imagery.
- Developing predictive analytics for event-driven traffic changes.
- Employing adaptive machine learning to improve accuracy over time.

## Technologies Used
- **Programming**: Python
- **Data Processing**: TensorFlow, Keras, NumPy, Pandas
- **Web Framework**: Flask or FastAPI

## Getting Started

### Prerequisites
- Python 3.8+
- Libraries: TensorFlow, Keras, Flask, FastAPI, NumPy, Pandas

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
The server should now be running on a specific port (e.g., http://localhost:5000). Check the terminal output for the exact port.


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
After running this command, the frontend will be accessible at a specific port (e.g., http://localhost:3000). The exact port should be displayed in the terminal.

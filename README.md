# Smart Farming: IoT-Driven Crop Yield Prediction for Rice Cultivation in India.

This project uses IoT sensors and machine learning to help farmers predict rice crop yields more accurately. By combining real-time field data (temperature, humidity, rainfall, soil pH) with historical weather and soil information, the system provides yield forecasts and insights. The goal is to support farmers in making data-driven decisions, optimize resource use, and improve overall agricultural productivity.

## Description

The Smart Farming project focuses on leveraging IoT and machine learning to improve rice crop cultivation in India. IoT sensors such as pH, DHT22, and rainfall sensors are deployed to collect real-time field data, which is combined with historical weather and soil information. This data is processed and stored, with yearly averages recorded in CSV files. Using regression models, the system predicts crop yields, helping identify the most effective farming strategies. A web application built with Flask serves as the user interface, enabling farmers to view live readings, input parameters, and receive yield predictions. The project aims to maximize crop productivity, optimize resource usage, and support sustainable agricultural practices.

## Getting Started

### Dependencies

Before running the project, ensure the following are installed:

Operating System: Windows 10 / 11 / Linux / macOS

Python: 3.12+

Libraries:

pip install flask flask-socketio scikit-learn pandas numpy sqlite3


Hardware : IoT sensors (pH sensor, DHT22, rainfall sensor) for real-time data collection.

### Installing

Clone the repository:

git clone https://github.com/Navnthh/Crop-Yeild-Prediction
cd smart-farming


Create a virtual environment and activate it:

python -m venv venv
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows


Install the required dependencies:

pip install -r requirements.txt

### Executing program

To run the web application:

Start the Flask server:

```
python app.py

```
Open your browser and visit:

http://127.0.0.1:5000


For predictions, input temperature, rainfall, pH, and area into the web form.

## Help

Common issues and fixes:

Port already in use: Stop any other service running on port 5000 or run Flask on another port:

flask run --port=5001


Missing libraries: Reinstall dependencies with:

pip install -r requirements.txt

## Authors

Navaneeth R – Developer & Researcher

GitHub: @Navnthh

Email: navaneeth944721@gmail.com

## Version History

0.2

Bug fixes, model optimization, added real-time SocketIO updates

See commit history

0.1

Initial release with Flask interface and regression model integration
## License

This project is licensed under the MIT License – see the LICENSE
 file for details.



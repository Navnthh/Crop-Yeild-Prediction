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

git clone [https://github.com/your-username/smart-farming.git](https://github.com/Navnthh/Crop-Yeild-Prediction)
cd smart-farming


Create a virtual environment and activate it:

python -m venv venv
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows


Install the required dependencies:

pip install -r requirements.txt

### Executing program

* How to run the program
* Step-by-step bullets
```
code blocks for commands
```

## Help

Any advise for common problems or issues.
```
command to run if program contains helper info
```

## Authors

Contributors names and contact info

ex. Dominique Pizzie  
ex. [@DomPizzie](https://twitter.com/dompizzie)

## Version History

* 0.2
    * Various bug fixes and optimizations
    * See [commit change]() or See [release history]()
* 0.1
    * Initial Release

## License

This project is licensed under the [NAME HERE] License - see the LICENSE.md file for details

## Acknowledgments

Inspiration, code snippets, etc.
* [awesome-readme](https://github.com/matiassingers/awesome-readme)
* [PurpleBooth](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2)
* [dbader](https://github.com/dbader/readme-template)
* [zenorocha](https://gist.github.com/zenorocha/4526327)
* [fvcproductions](https://gist.github.com/fvcproductions/1bfc2d4aecb01a834b46)

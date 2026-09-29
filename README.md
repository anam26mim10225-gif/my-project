# my-project
# Weather App - Introduction to Programming Project

## 📌 Overview
Weather App is a simple Python desktop application that allows users to search for current weather information by entering a city name. The application uses Tkinter for the graphical user interface and the Open-Meteo Weather API for weather information.

## 📌 Features
* Search weather by city name
* Display temperature
* Display humidity
* Display current weather condition
* Simple graphical user interface
* Error handling for invalid cities

## 📌 Technologies/Tools Used
* Programming Language: Python 3.7+
* GUI Framework: Tkinter
* HTTP Library: Requests (for API calls)
* Data Format: JSON
* API Service: Open-Meteo Weather API

## 📌 Steps to Install & Run the Project

### 1. Requirements
Make sure Python 3.7 or higher is installed. Check with:

```bash
python --version
```

### 2. Clone the Repository

```bash
git clone https://github.com/anam26mim10225-gif/my-project.git
cd my-project
```

### 3. Install Dependencies

```bash
pip install requests
```

### 4. Run the Application

```bash
python weather.py
```

## 📌 Instructions for Testing

### 1. Standard Weather Search Test
* Launch the app
* Enter "Bhopal" in the City field
* Click "Get Weather"
* Expected Output: Current temperature, humidity and weather condition for Bhopal are displayed.

### 2. Invalid City Test
* Enter an invalid city such as "abcdxyz123" and click "Get Weather"
* Expected Output: "City not found or API error"

### 3. Empty Input Test
* Leave the City field blank and click "Get Weather"
* Expected Output: An error message is shown and the app does not crash.

### 4. Offline / Network Error Test
* Disconnect from the internet, enter "Mumbai" and click "Get Weather"
* Expected Output: The app stays open and shows an error message.

## 📌 Project Structure

```
my-project/
├── weather.py
├── README.md
├── statement.md
├── screenrecording/
│   └── weather_app.mp4
└── WeatherApp_Report.pdf
```

## 📌 Screenshots
1. Entering the city name

<img width="437" height="407" alt="image" src="https://github.com/user-attachments/assets/12057f25-2cf4-42a3-9898-eea534fa4d34" />

2. Weather condition of the city

<img width="433" height="412" alt="image" src="https://github.com/user-attachments/assets/fe923409-2678-407d-b762-c511a1940b92" />

3. Error when no city is entered

<img width="431" height="412" alt="image" src="https://github.com/user-attachments/assets/320909ac-144f-40e2-904d-acc92a665d42" />

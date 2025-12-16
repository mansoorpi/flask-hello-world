# Flask Hello World

A simple Flask web application that returns "Hello, World!".

## Installation

```bash
pip install -r requirements.txt
```

## Running the App

```bash
python3 app.py
```

The app will start on `http://localhost:5001`

**Note:** Port 5001 is used to avoid conflicts with AirPlay Receiver on macOS (which uses port 5000).

## Endpoints

- `/` - Returns "Hello, World!"
- `/health` - Returns health status of the app

## Requirements

- Python 3.7+
- Flask 3.0.0

# 📍 Last Mile Optimisation with OpenCage & OR-Tools

This Python script takes a list of addresses from an Excel file, geocodes them using the OpenCage Geocoding API, calculates the pairwise distances using the Haversine formula, and solves a **Traveling Salesperson Problem (TSP)** to find the most efficient route using Google's OR-Tools.

## 🚀 Features

- 📌 **Geocoding**: Converts addresses into latitude and longitude using OpenCage API.  
- 📏 **Distance Calculation**: Uses the Haversine formula for accurate distance measurement.  
- 📍 **Route Optimization**: Finds the shortest possible route covering all addresses with OR-Tools.  
- 📊 **Excel Integration**: Reads addresses from an Excel file for easy batch processing.

---

## 🔧 Requirements

- Python 3.7+
- Install dependencies with:

pip install opencage pandas numpy ortools requests openpyxl

📥 Setup & Usage
Get an API Key from OpenCage Data.
Replace the placeholder API_KEY in the script with your actual API key.
Create an addresses.xlsx file with a list of addresses (one per row).
Run the script

⚠️ Notes
Respect OpenCage API’s rate limits; the script includes a 1-second delay between requests.
Ensure your Excel file is in the same directory as the script or update the file_path variable accordingly.

📜 License
This project is licensed under the Apache 2.0 License.

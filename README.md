# Pressure Monitoring in Oil & Gas Company using Azure

This project simulates a pressure monitoring solution for an Oil & Gas Company using Microsoft Azure.

### Problem Statement

XYZ Oil & Gas Company requires continuous monitoring of pressure levels across its facilities to ensure operational safety and efficiency. This project aims to develop a pressure monitoring and analysis system using Azure to collect, analyze, and visualize pressure data in real-time.

### Project Components

1. **azure_pressure_monitoring.py**: Python script that simulates a device sending pressure data to Azure IoT Hub.

### Setup Instructions

1. **Azure IoT Hub Setup**:
   - Create an Azure IoT Hub instance.
   - Obtain the connection string for your IoT Hub.

2. **Python Environment Setup**:
   - Clone this repository.
   - Install required Python packages:
     ```
     pip install -r requirements.txt
     ```

3. **Run the Simulation**:
   - Update `azure_pressure_monitoring.py` with your IoT Hub connection string (`CONNECTION_STRING`).
   - Execute the script:
     ```
     python azure_pressure_monitoring.py
     ```
   - The script will simulate sending pressure data to your Azure IoT Hub at regular intervals.

**Next Steps

- Implement Azure services for real-time data processing, storage, and visualization based on the collected pressure data.
- Scale the solution to include multiple devices and optimize for production deployment.

# Real-Time Traffic Data Analysis Using Apache Spark

## Project Description
This project analyzes traffic data using Python and Apache Spark. It processes vehicle information, calculates vehicle counts and average speeds for different road locations, and identifies traffic congestion levels.

## Technologies Used
- Python
- Apache Spark (PySpark)
- Pandas
- Matplotlib
- Google Colab

## Project Features
- Traffic CSV data processing
- Vehicle count analysis
- Average speed calculation
- Traffic congestion classification
- Data visualization using graphs
- Simulated real-time processing using Spark Structured Streaming

## Project Files
- `Real_Time_Traffic_Analysis.ipynb` – Project notebook
- `traffic.csv` – Input traffic dataset
- `Traffic Analysis Result.csv` – Analysis results

## Congestion Classification
- High Congestion: Average speed below 20 km/h
- Medium Congestion: Average speed from 20 to 40 km/h
- Low Congestion: Average speed above 40 km/h

## Execution
The project was developed and executed using Google Colab.

**Note:** The streaming component demonstrates simulated file-based traffic data processing, not live road sensor data.

## Conclusion
This project demonstrates how Apache Spark can process and analyze traffic data to identify congestion patterns and support traffic monitoring.

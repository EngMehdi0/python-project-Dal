Smart Industrial Monitoring System (Telegram Monitoring)

Overview

This application is designed for monitoring and notification of industrial processes by tracking one or more parameters (machine status, temperature, humidity, or gas) in real-time using sensors and Programmable Logic Controller data. Since we do not have access to industrial machines, we use sample data. In this application, we specifically track temperature as an example.

Features

 • Ongoing Monitoring: The system continuously monitors and records temperature data.
 
 • Telegram Integration: It posts information to a Telegram group at scheduled intervals.
 
 • Auto-Message Deletion: Messages are automatically deleted after a set period to keep the group organized and ensure only the latest information is available.
 
 • Excel Report Generation: Daily Excel reports, including a temperature chart, are generated and shared in the group as a document for day, month, or year-based comparisons.
 
 • Data Visualization: A chart is created and posted in the Telegram group for easier analysis.
 

To ensure uninterrupted operation, our code has been deployed on Google Cloud Compute Engine, allowing the application to run continuously without disruptions caused by internet issues or the absence of a dedicated computer for the project.

We also invite you to join our Telegram channel to see the monitoring in action and check out the results of our code: Join Here. (https://t.me/+dWDvrpWOAy9iNWZk)

This system provides real-time monitoring and notification for industrial environments, enabling quick responses to anomalies and efficient long-term tracking.

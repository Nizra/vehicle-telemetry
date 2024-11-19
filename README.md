# Real-Time Azure Stream Analytics Vehicle Telemetry Alerting
## Introduction
This is an Azure Stream Analytics project that processes real-time vehicle telemetry events and triggers alerts when a threshold value is reached. A Transaction Generator application is used to simulate vehicle telemetry data generation and sends these events to Azure Event Hub. Azure Stream Analytics then extracts these events and performs aggregations over time windows. The aggregrated results are then sent to another Event Hub which is a trigger 

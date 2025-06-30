# Proactive_Resource_Allocation_for_Edge_Computing_in_High_Density_Networks




Overview

This project implements a machine learning-based system for predicting network throughput to enable proactive resource allocation in edge computing environments. Designed for high-density networks such as 5G, smart cities, and IoT deployments, the project leverages real-time network traffic data to optimize performance and resource utilization.

Objective

To predict network throughput from environmental monitoring data using machine learning models like Random Forest and Ridge Regression, and evaluate their effectiveness for intelligent decision-making in edge computing systems.

Dataset

The dataset includes network traffic features such as:

frame.len: Packet size in bytes

frame.time_delta: Time difference between packets

Additional protocol and transmission metrics

Throughput is derived using the formula:

throughput = frame.len / frame.time_delta

Preprocessing

Removal of irrelevant non-numeric features (e.g., IP addresses, class labels)

Conversion of object types to numerical values

Handling of missing and zero values

Feature-target separation for modeling

Models Used

Random Forest Regressor

Ridge Regression

Evaluation Metrics

Mean Squared Error (MSE)

Root Mean Squared Error (RMSE)

Mean Absolute Error (MAE)

R² Score

Results

The models provide effective predictions of throughput values, enabling bandwidth-aware and latency-sensitive resource allocation strategies in real-time edge computing systems.

Usage

Clone this repository

Install dependencies

Run the Python script to process the dataset and generate evaluation metrics

Applications

Dynamic bandwidth management

Intelligent load balancing in edge networks

Real-time network optimization for smart environments

License

This project is open-source and available under the MIT License.

Let me know if you'd like this formatted into a downloadable README.md file.









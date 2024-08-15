# Spark Memory Configuration Calculator

This repository contains a simple web-based application that helps calculate optimal memory and core configurations for Apache Spark clusters. Built with Flask, the tool provides insights into how resources like memory and cores should be allocated for better performance in Spark jobs.

# Features

User-Friendly Interface: Enter values like RAM size, cores per node, cores per executor, and more to get instant calculations.

Detailed Results: Provides total cores, memory overhead, number of executors, memory per executor, and other important metrics.

Customizable Memory Overhead: Allows setting a custom memory overhead percentage for more accurate results.

Flexible Setup: Easily configurable for different node setups and Spark environments.

# How It Works

1.Input your cluster specifications (RAM size, cores per node, cores per executor, number of nodes, etc.).

2.The app computes the best configuration based on the input, including details like:

Total available memory and overhead

Number of executors and cores per executor

Parallelism and shuffle parallelism metrics

# Prerequisites
Python 3.x 

Flask

# Usage

Navigate to the homepage.

Enter the required details like RAM size, cores per node, and more.

Click "Calculate" to view the recommended Spark configuration.

# License

This project is licensed under the MIT License.

# Economic Data Analysis with Fred & Pandas

This project uses the Federal Reserve Economic Data (FRED) API to retrieve and analyze various economic data sets. The data is processed using the Python library Pandas and visualized using Matplotlib.
Table of Contents

    Getting Started
    Project Description
    Requirements
    Installation
    Usage
    License

Getting Started

To use this project, you will need a FRED API key. You can obtain one by registering at the FRED website. Once you have your API key, you can proceed with installation.
Project Description

This project demonstrates how to use the FRED API to retrieve economic data, process it using Pandas, and visualize it using Matplotlib. Specifically, it covers the following topics:

    Creating the FRED object
    Searching for economic data
    Pulling raw data and plotting it
    Pulling and joining multiple data series
    Pulling April 2020 unemployment rate per state
    Pulling participation rate
    Plotting unemployment vs participation for each state

The code for each of these topics is included in the Jupyter Notebook Economic Data Analysis.ipynb.
Requirements

To run this project, you will need:

    Python 3.6 or later
    Pandas
    Matplotlib
    Requests

You can install these packages using pip.
Installation

To install the required packages, run the following command:

pip install pandas matplotlib requests

Usage

To use this project, you will need to replace the YOUR_API_KEY placeholder in Economic Data Analysis.ipynb with your FRED API key. You can then run each code block in the notebook to retrieve and analyze the data.
License

This project is licensed under the MIT License - see the LICENSE file for details.

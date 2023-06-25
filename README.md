# SQLAlchemy Climate Analysis and Exploration

## Description
This is the SQLAlchemy Challenge Assignment for the Data Science Bootcamp, Module 10. This project utilizes Python, SQLAlchemy ORM queries, Flask API, Pandas, and Matplotlib on a SQLite database to perform a climate analysis and data exploration. The analysis and visualization were divided into two parts: a Jupyter notebook for exploratory data analysis and a Flask API for data retrieval.

## Usage
The project consists of two main components:

* **Jupyter Notebook (`climate_analysis.ipynb`):**
This notebook includes all the exploratory data analysis steps, including precipitation and temperature analysis. It uses Python, SQLAlchemy ORM, Pandas, and Matplotlib to create visualizations and analyze the data.

* **Flask API script (`app.py`):**
This script uses Flask to serve the climate data through multiple API endpoints, providing access to precipitation data, station data, temperature observation data, and temperature statistics for a given date or date range. All routes return JSON data, which can be used by front-end applications.

## Files Included
- `climate_analysis.ipynb`: Jupyter notebook for performing the climate analysis and data exploration (including dependencies).
- `app.py`: Flask API script for serving the climate data.
- `hawaii.sqlite`: SQLite database file containing climate data (contained in the Resources directory).

All scripts and notebooks were developed in a Python environment managed by Anaconda, with code written in Visual Studio Code and Jupyter notebooks.

Coding Soundtrack for this week's challenge was Architects' album, [For Those That Wish To Exist](https://www.youtube.com/playlist?list=PLcZMZxR9uxC-E2LSxEY1wevRTbob6XNjA).

*-LM95A1*
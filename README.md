Airbnb Exploratory Data Analysis (EDA) Project

This repository contains an Exploratory Data Analysis (EDA) project focused on Airbnb data. The project aims to analyze and gain insights from a dataset containing information about Airbnb listings, including attributes such as location, property type, price, availability, and reviews.

Table of Contents

Introduction
Dataset
Project Structure
Dependencies
Getting Started


Introduction

Airbnb is an online marketplace and hospitality service platform that enables people to rent out their properties or spare rooms to guests. The dataset used in this project provides a rich collection of information about Airbnb listings, allowing us to explore patterns, trends, and insights related to property types, pricing, location preferences, and more.

This EDA project serves as a foundation for analyzing the dataset, visualizing data distributions, identifying outliers, and discovering relationships between different variables. By performing exploratory analysis, we can extract meaningful information and draw valuable conclusions.

Dataset

The dataset used in this project is a collection of Airbnb listings, obtained from Almabetter. It includes the following attributes:

id: Unique identifier for each listing
name: Title or name of the listing
host_id: Unique identifier for each host
host_name: Name of the host
neighbourhood_group: Location grouping of the listing
neighbourhood: Specific neighborhood of the listing
latitude: Latitude coordinates of the listing
longitude: Longitude coordinates of the listing
room_type: Type of room (e.g., entire home/apartment, private room, shared room)
price: Price per night for the listing
minimum_nights: Minimum number of nights required to book the listing
number_of_reviews: Number of reviews left by guests
last_review: Date of the last review
reviews_per_month: Average number of reviews per month
availability_365: Number of days available for booking within the next 365 days

Project Structure

The project repository has the following structure:

airbnb_data.csv      # Airbnb dataset (not included in this repo)
Airbnb_EDA.ipynb     # Jupyter Notebook with EDA code
README.md            # Project README file

The data directory should contain the Airbnb dataset in CSV format. Please obtain the dataset from source and place it in this directory before running the code.

The notebooks directory contains Jupyter Notebooks used for exploratory analysis and generating visualizations.

The README.md file provides an overview of the project, instructions, and details about the dataset.

Dependencies

The following dependencies are required to run the code:

Python 3.x
Jupyter Notebook
pandas
matplotlib
seaborn

Getting Started

To get started with this project, follow these steps:

Clone the repository to your local machine or download the project files.
Obtain the Airbnb dataset from repository and place it in the data directory.
Install the required dependencies using the instructions provided in the Dependencies section




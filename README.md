# Data Engineering YouTube Analysis Project by Shashank Bugadi

# Overview 

This project aims to manage data, perform data cleaning and analysis the data on  structured and semi-structured YouTube videos data based on the video categories and the trending metrics.


# Project Goals

    1. Data Ingestion — Importing data to ingest data of different data types.
    2. ETL Process    — We are getting data in raw format, transforming this data into the 
       proper format
    3. Data Wranging  — We will be getting data from multiple sources so we need centralized repo to store them.
    4. Flexibility    — As the size of our data increases, we need to make sure our system is more flexible with it.
    5. Platform       — We can’t modidy vast amounts of data on our local computer so we need to use some platform, in this case, we will use JYPUTER notebook.
    6. Reporting      — Build a dashboard to get answers to the question we asked earlier, we will be using PowerBi
# Libraries we will be using
Pandas:   pandas is a software library written for the Python programming language for data manipulation and analysis. In particular, it offers data structures and operations for manipulating numerical tables and time series. It is free software released under the three-clause BSD license.

Link : https://pandas.pydata.org/docs/getting_started/install.html

Numpy: NumPy is a library for the Python programming language, adding support for large, multi-dimensional arrays and matrices, along with a large collection of high-level mathematical functions to operate on these arrays.

Link: https://numpy.org/install/

OS module : Python OS module provides the facility to establish the interaction between the user and the operating system. It offers many useful OS functions that are used to perform OS-based tasks and get related information about operating system.

Matplotlib: Matplotlib is a plotting library for the Python programming language and its numerical mathematics extension NumPy. It provides an object-oriented API for embedding plots into applications using general-purpose GUI toolkits like Tkinter, wxPython, Qt, or GTK.

Link : https://matplotlib.org/

Seaborn: Seaborn is a Python data visualization library based on matplotlib. It provides a high-level interface for drawing attractive and informative statistical graphics.

Link : https://seaborn.pydata.org/ 

# Dataset Used

This Kaggle dataset contains statistics (CSV files) on daily popular YouTube videos over the course of many months. There are up to 200 trending videos published every day for many locations. The data for each region is in its own file. The video title, channel title, publication time, tags, views, likes and dislikes, description, and comment count are among the items included in the data. A category_id field, which differs by area, is also included in the JSON file linked to the region.

https://www.kaggle.com/datasets/datasnaek/youtube-new


# Architecture Diagram 

![the-data-analysis-process-1](https://user-images.githubusercontent.com/98276554/225692975-28d7faa8-449a-43b4-bc2c-42b0e2d600a7.jpg)

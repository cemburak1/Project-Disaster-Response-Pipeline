# Disaster Response Pipeline Project (Udacity Data Scientist Nanodegree)

## Project
This project is part of the Udacity's Data Scientist Nanodegree Program in collaboration with Figure Eight. In this project, the pre-labeled disaster messages will be used to build a disaster response model that can categorize messages received in real time during a disaster event, so that messages can be sent to the right disaster response agency.

This project includes a web application where disaster response worker can input messages received and get classification results. 

## File Descriptions

### Folder: app
**run.py** - python script to launch web application.
Folder: templates - web dependency files (go.html & master.html) required to run the web application.

### Folder: data
**disaster_messages.csv** - real messages sent during disaster events (provided by Figure Eight)
**disaster_categories.csv** - categories of the messages
**process_data.py** - ETL pipeline used to load, clean, extract feature and store data in SQLite database
**ETL Pipeline Preparation.ipynb** - Jupyter Notebook used to prepare ETL pipeline
**DisasterResponse.db** - cleaned data stored in SQlite database

### Folder: models
**train_classifier.py** - ML pipeline used to load cleaned data, train model and save trained model as pickle (.pkl) file for later use
**classifier.pkl** - pickle file contains trained model
**ML Pipeline Preparation.ipynb** - Jupyter Notebook used to prepare ML pipeline

## Screenshots
![image](https://user-images.githubusercontent.com/80202343/186523590-8ca544dd-f8aa-48a6-98d9-4686a82ab96f.png)

![image](https://user-images.githubusercontent.com/80202343/186523802-cdae1330-f24d-40f8-ab66-9982c98265fb.png)


![image](https://user-images.githubusercontent.com/80202343/186523211-713887f1-8bec-4e54-881d-bc43371c3eae.png)

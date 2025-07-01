PassengerId - A unique Id for each passenger. Each Id takes the form gggg_pp where gggg indicates a group the passenger is travelling with and pp is their number within the group. People in a group are often family members, but not always.
HomePlanet - The planet the passenger departed from, typically their planet of permanent residence.
CryoSleep - Indicates whether the passenger elected to be put into suspended animation for the duration of the voyage. Passengers in cryosleep are confined to their cabins.
Cabin - The cabin number where the passenger is staying. Takes the form deck/num/side, where side can be either P for Port or S for Starboard.
Destination - The planet the passenger will be debarking to.
Age - The age of the passenger.
VIP - Whether the passenger has paid for special VIP service during the voyage.
RoomService, FoodCourt, ShoppingMall, Spa, VRDeck - Amount the passenger has billed at each of the Spaceship Titanic's many luxury amenities.
Name - The first and last names of the passenger.
Transported - Whether the passenger was transported to another dimension. This is the target, the column you are trying to predict.

# MyProject

This repository contains a Jupyter Notebook for a data analysis and machine learning project. It includes data preprocessing, exploratory data analysis, model training, and evaluation.

## 📁 Project Structure


## 🔍 Overview

This project aims to:
- Load and preprocess a dataset
- Perform exploratory data analysis (EDA)
- Train machine learning models
- Evaluate and visualize model performance

## 🚀 Getting Started

### 1. Clone the repository

 🗃️ Database

All database-related files are located in the `database/` folder. This may include:

- `schema.sql`: SQL schema definition
- `dump.sql`: SQL dump of the database (e.g., from MySQL or PostgreSQL)
- `data.db`: SQLite database file
- `*.csv`: Raw data files used as a database

You can modify or load the database using the tools provided in the notebook or with standard SQL/CSV tools.

### Example (if using SQLite in Python):

python
import sqlite3
conn = sqlite3.connect('database/data.db')
cursor = conn.cursor()

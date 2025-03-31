# 🚕 Uber Ride Data Analysis

In this notebook, I explore and analyze Uber ride data to uncover usage patterns, trip purposes, and temporal trends. The dataset includes trip logs with timestamps, locations, categories, and purposes.

## 📌 What I Did

- Loaded and inspected the Uber dataset
- Cleaned missing values (especially in the `PURPOSE` column)
- Converted trip start times to datetime format
- Extracted time-based features like month, weekday, and hour
- Visualized key patterns in trip frequency, purpose, and duration

## 🧰 Tools I Used

- **Pandas & NumPy**: for data handling
- **Matplotlib & Seaborn**: for plotting
- **Datetime module**: for time-based feature extraction

## 📄 Dataset Overview

The dataset (`UberDataset.csv`) contains:
- Start and end dates/times of trips
- Categories like "Business", "Personal", etc.
- Trip purposes like "Meeting", "Errand", "Customer Visit"
- Mileage and trip details

## 🔁 My Workflow

1. **Initial Exploration**:
   - Checked shape, types, and null values
2. **Data Preprocessing**:
   - Filled missing purposes with `"NOT"`
   - Converted date columns to datetime
3. **Feature Engineering**:
   - Extracted month, weekday, and hour from trip dates
4. **Visualization**:
   - Countplots for trip purpose and category
   - Time-based trend analysis
   - Trip frequency by hour/day/month

## ✅ Final Outcome

The analysis highlights how Uber rides vary by purpose, time of day, and category. It also reveals peak travel times and most common trip intents.

## 🎯 What’s Next?

This cleaned dataset and analysis can be extended to:
- Predict peak usage hours
- Segment users by ride patterns
- Optimize Uber services based on usage behavior

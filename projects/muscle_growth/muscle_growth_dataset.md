# Gym Muscle Growth Dataset

## Overview

This dataset contains **30,000** records with **20** features that capture various aspects of gym-goers’ profiles, training habits, nutritional factors, and recovery metrics.

## Features

- **id**: Unique identifier for each record.
- **age**: Age of the individual (between 18 and 65 years).
- **gender**: Gender of the individual (M or F).
- **height**: Height in centimeters.
- **weight**: Weight in kilograms.
- **gym_frequency**: Number of days per week the individual attends the gym.
- **workout_intensity**: Self-reported workout intensity on a scale of 1 to 10.
- **protein_intake**: Daily protein intake in grams.
- **sleep_hours**: Average hours of sleep per night.
- **training_experience**: Categorical variable representing training experience with three groups:
  - Beginner
  - Intermediate
  - Experienced
- **initial_muscle_mass**: Muscle mass at the start (in kg).
- **final_muscle_mass**: Muscle mass after a training period (in kg).
- **body_fat_percentage**: Body fat percentage.
- **supplement_use**: Type of supplement used (None, Creatine, Protein, Pre-workout).
- **workout_type**: Type of workout (Cardio, Strength, Mixed).
- **diet_type**: Dietary preference (Omnivore, Vegetarian, Vegan, Keto).
- **hydration_level**: Daily water intake in liters.
- **stress_level**: Self-reported stress level on a scale of 1 to 10.
- **session_duration**: Duration of each workout session in minutes.
- **recovery_rate**: Recovery rate post-workout (fast, medium, slow).

## Data Quality

- **Missing Values**: Each column (except for the unique `id`) has been assigned a missing value rate that varies randomly between **5% and 15%**.
- **Outliers**: Approximately **1%** of the rows have been modified to include extreme values in selected columns (e.g., weight, session duration, body fat percentage) to mimic data anomalies.

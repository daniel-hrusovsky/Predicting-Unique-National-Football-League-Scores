# Predicting-Unique-National-Football-League-Scores

# Overview

This project investigates whether National Football League matches resulting in a unique score can be predicted using prior statistical factors while forecasting future matches.

The goal is to predict one outcome for NFL games:
- **Scorigami,** or a unique NFL score (classification)

Inputs include:
- **Contributing Factors**
  -  Points Scored (Team and Opponent)
  -  Passing, Rushing, and Total Yards (Team and Opponent)
  -  Two Point Attempts and Conversions, Safeties, and First Downs (Team and Opponent) 
 
Data comes from [Pro Football Reference](https://www.pro-football-reference.com/)

# Methodology
- Data Cleaning
  -  Replaced null values with appropriate values
  -  Normalized data in a 0-1 range to improve data integrity
  -  Removed unnecessary data, such as Season and Expected Points
- Model
  - Built a **multilayer perceptron neural network** using Python's scikit-learn library
  - Outputs:
    - **Classification** -> Scorigami
- Forecasting
  - 
  - 

# Results
- **Scorigami Classification:** ~97.1% accuracy

# Limitations
- **Scorigami Rarity:** Only 5.5% of NFL games end with unique scores, thus the model may be rewarded for guessing non-scorigamis.
- **Contributing Factors:** While these statistics directly relate to scoring, other factors can contribute to a team scoring.

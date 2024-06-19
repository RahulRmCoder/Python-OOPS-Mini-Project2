# Python-OOPS-Mini-Project2
# Concept: Max Score Calculation in Cricket Series

## Question: Consider an ongoing test cricket series. Following are the names of the players and their scores in the test1 and 2.
## Test Match 1 :
## Dhoni : 56 , Balaji : 94
## Test Match 2 :
## Balaji : 80 , Dravid : 105
## Calculate the highest number of runs scored by an individual cricketer in both of the matches.
## Create a python function Max_Score (M) that reads a dictionary M that recognizes the player with the highest total score. This function will return ( Top player , Total Score ) . You can consider the Top player as String who is the highest scorer and Top score as Integer .
## Input : Max_Score({‘test1’:{‘Dhoni’:56, ‘Balaji : 85}, ‘test2’:{‘Dhoni’ 87, ‘Balaji’’:200}})
## Output : (‘Balaji ‘ , 200)

## Overview

This project calculates the highest number of runs scored by an individual cricketer in a test cricket series. It reads a dictionary containing player scores from multiple test matches and identifies the top scorer.

## Function

### `Max_Score(M)`
- **Input:** A dictionary `M` with test match names as keys and another dictionary as values. The inner dictionary contains player names as keys and their scores as values.
- **Output:** A tuple containing the name of the top player and their total score.
- **Description:** The function reads the dictionary, sums the scores for each player across all test matches, and returns the player with the highest total score.

## Usage

1. **Prepare the Data:** Create a dictionary with test match names and player scores.
2. **Call the Function:** Pass the dictionary to the `Max_Score(M)` function.
3. **Get the Result:** The function returns the top player and their total score.

## Requirements
**Python** <br>
**Jupyter Notebook**

## Example

```python
test_scores = {
    'test1': {'Dhoni': 56, 'Balaji': 94},
    'test2': {'Balaji': 80, 'Dravid': 105}
}
top_player, top_score = Max_Score(test_scores)
print(f"Top Player: {top_player}, Top Score: {top_score}")

# Project_1_Group_3
Project 1 Collaboration

## - Details of our data set - 

### * Downloaded from kaggle: https://www.kaggle.com/datasets/tobycrabtree/nfl-scores-and-betting-data/
  
  - Contains NFL spread, over/under line, weather data, stadium names, and team scores for each NFL game between 09/02/1966 and 10/09/2023.

  
### * Final Data Set:
 
  - Removed all rows before 01/21/1979 as the data did not contain over/under predictions until Super Bowl XIII
    

### * Created New Columns:

  - Total Score (home team score + away team score)

  - Accuracy % ([total score / over under line prediction ] x 100)

  - Temperature Feel (group temperature data into 6 ranges)

  - Humidity Feel (group humidity in 5 ranges)


## Over/Under projection compared to total score of the game

  - How accurate was the over/under line in projecting the total score of a game?

![Screenshot 2023-11-05 140224](https://github.com/davisdw/Project_1_Group_5/assets/140672220/8e152e1f-35b7-42cf-9fde-9be3e904e828)

  A correlation coefficient of 0.3 indicates a moderate positive relationship
  

## How do different weather conditions impact the total score and accuracy of the over/under line prediction?

![Screenshot 2023-11-05 141444](https://github.com/davisdw/Project_1_Group_5/assets/140672220/23802492-e77a-41fa-b68e-0883aedb2e08)

![Screenshot 2023-11-05 141548](https://github.com/davisdw/Project_1_Group_5/assets/140672220/09d681d8-916e-4aca-9ba4-73f4b046ba24)


## How does the humidity levels during a game impact the total score?

![Screenshot 2023-11-06 181438](https://github.com/davisdw/Project_1_Group_5/assets/140672220/dfe1a110-82f3-4fa7-b904-b0e0c43e832e)


## How accurate is the over/under line based on the humidity level?

![Screenshot 2023-11-05 140224](https://github.com/davisdw/Project_1_Group_5/assets/140672220/ea46011c-ed7b-47dc-8a73-9367191d1c0f)


## How accurate are bookmakers at predicting Super Bowl winners?

![Screenshot 2023-11-06 181830](https://github.com/davisdw/Project_1_Group_5/assets/140672220/c461aa02-af1d-4e9d-ba45-9675499c82d6)

# Conclusions

  - The over/under line was the most accurate looking at the 2013-2022 decade of football and the least accurate during the 1993-2002 decade of football
  - The over/under line has become more accurate with time. This makes sense as they have more data to predict the over/under line and ensure its accuracy.
  - The correlation coefficient was fairly consistent around .3 with the exception of the 1993-2002 decade where it was .26

  - The only variables that we found to show a statistically significant relationship were the temperature and the total score. So of the variables we looked at… temperature seems to have the highest impact on the total score of the game
  - All other variables we tested came up not statistically significant, meaning they had little to no impact on the total score of a game or the accuracy of the over/under line prediction.

# Project_Individual
DSCI 100 Project - Individual portion for the planning stage

## **Project Question**

<span style="font-size: 15px;">

**Broad Question**

Question 1: What player characteristics and behaviours are most predictive of subscribing to a game-related newsletter, and how do these features differ between various player types?

**Specific Question**

*Can the amount of hours playing video games and the age of the player predict their subscription status (TRUE/FALSE) to a gaming newsletter in the players.csv dataset? Additionally, does this predictive relationship differ across players of different experience levels?*

The players.csv dataset has all the information I need to answer this question with the variables **experience**, **played_hours**, **subscribe**, and **Age**. I will wrangle the dataset by filtering out missing values (i.e., **Age** has two missing values), and converting the categorical variables such as **experience** and **subscribe** into a usable format for the predictive model.

To build the predictive model, I will be using K-Nearest Neighbours (K-NN) because K-NN supports classfication when the response variable is logical (TRUE/FALSE). I will first train the K-NN classifier using **played_hours** and **Age** as explanatory variables, and **subscribe** as the response. Then I will check whether prediction accuracy changes when grouping by **experience** level of the players. 

</span>

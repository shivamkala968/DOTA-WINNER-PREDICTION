# DOTA-WINNER-PREDICTION

Abstract:
Dota 2 is a popular computer game with two teams of 5 players. At the start of the game each player chooses a unique hero with different strengths and weaknesses.

Objective/Problem Statement : -
Create a Machine Learning application which predicts the winner based on the given attributes and the hero chosen by the team.

Data Set Information:
Dota 2 is a popular computer game with two teams of 5 players. At the start of the game each player chooses a unique hero with different strengths and weaknesses. The dataset is reasonably sparse as only 10 of 113 possible heroes are chosen in a given game. All games were played in a space of 2 hours on the 13th of August, 2016

The data was collected using: https://gist.github.com/da-steve101/1a7ae319448db431715bd75391a66e1b

Attribute Information:
Each row of the dataset is a single game with the following features (in the order in the vector):

Team won the game (1 or -1)
Cluster ID (related to location)
Game mode (eg All Pick)
Game type (eg. Ranked) 5 - end: Each element is an indicator for a hero. Value of 1 indicates that a player from team '1' played as that hero and '-1' for the other team. Hero can be selected by only one player each game. This means that each row has five '1' and five '-1' values.
The hero to id mapping can be found here: https://github.com/kronusme/dota2-api/blob/master/data/heroes.json

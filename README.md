# European-Soccer-Prediction
## Abstract
In this project I am working with the Eropean soccer database to explore the attributes of the team as well as make a comparison between the teams in the 11 Europe countries by using the python and other library package such as matplotlib, Altair, nertworkx. In addtion, applying machine learning to build a model to predict the outcome of a game.
## Description of the dataset
The European soccer database is an ultimate Soccer database on Kaggle inlcuding more than 10,000 players and 25,000 matches in 11 European Countries with their lead championship from season 2008 to 2016. This data also include the attributes of the teams in these coutry from EA Sports' FIFA. 
This dataset is a sqlite file include 7 tables:
* Country: Id and name of country
* League:Id, country and name of league
* Match: Id of two team and the events of the game such as goal, corner, cross, fouls, etc
* Player: Player's information
* Player_Attributes: Attributes of player
* Team: team's information
* Team_attribute: Attributes of each team
## Outline
* [Introduction](01-Introduction.ipynb): 
    * Introduction about project
* [Import and Tidy](02-Import and Tidy.ipynb): 
    * Import and tidying the data
* [EDA](03-EDA.ipynb): 
    * Make some visualization to explore the data
* [Modeling](04-Modeling.ipynb): 
    * Using machine learning to predict the outcome of a game
* [Presentation](05-Presentation.ipynb): 
    * Presentation file
## Citations
* Networkx documentation: https://networkx.github.io/documentation/networkx-1.10/examples/drawing/chess_masters.html
* Plotly documentation: https://plot.ly/python/radar-chart/
* Kaggle dataset: https://www.kaggle.com/hugomathien/soccer/data
* Jupiter Notebook
## Notes
* Modify import data in 02-Import and Tidy.ipynb to using this project.

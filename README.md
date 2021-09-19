# FIFA_21_MoneyBall

![FIFA text](FIFA.jpeg)

## Objective

Use a Linear Regression Model to predict the Value of FIFA players.

## Data

### Data Source

The dataset was provided by Ironhack instructional staff as part of the first project for my Data Analytics course.
Dataframe: https://www.kaggle.com/ekrembayar/fifa-21-complete-player-dataset

### Shape of the Data

The datasat contains 10.125 rows and 107 columns.

| Column name | Description |
| ----------- | ----------- |
| age | players age |
| ova | overall score of the player |
| nationality | nationality of the player |
| club | club of the player |
| bov | best scor overall (since recording) |
| bp | best position |
| pot | potential score of the player |
| foot | left or right foot |
| growth | growth of the player (performance) |
| value | current value of the player |
| wage | current wage of the player |
| release_clause | current wage of the player |
| goalkeeping | score for goalkeeping performance |
| w_f | current wage of the player |
| sm | current wage of the player |
| a_w | current wage of the player |
| d_w | current wage of the player |
| ir | current wage of the player |
| sho | score for shooting performance |
| pas | score for passing performance |
| dri | score for dribbling performance |
| def | score for defending performance |
| phy | score for physical performance |
| hits | goals scored total |

### Workflow

#### Load, First Review and Clean


#### Deep Dive Python


#### Deep Dive Tableau


#### EDA


#### Creating the Model


#### Evaluating the Model


### Conclusion

![Alt Text](https://media2.giphy.com/media/Qwtw3GTvRg8LxKaUet/giphy.gif?cid=ecf05e47u9osjc1n30c9g0ord37ktiu96kgidz253dc6fq49&rid=giphy.gif)

## Python Libraries
- [pandas](https://pandas.pydata.org/)
- [numpy](https://numpy.org/)
- [seaborn](https://seaborn.pydata.org/)
- [matplotlib](https://matplotlib.org/)
- [statsmodels](https://www.statsmodels.org/stable/index.html)
- [scipy](https://www.scipy.org/)
- [sklearn](https://scikit-learn.org/stable/)


### change format and rename
all lower string
spaces replaced with underscore
clean up €,K,M formats from value, wage, release_clause and hits columns

### drop columns
I decided to drop following columns from the dataframe
images/links: player_photo, club_logo, flag_photo
gender: only one gender represented in the data
position columns: to evaluate the value of the player I only considered the best position to be important

### set player ID as index

### add calculated columns
I decided to add 2 rankings:
- potential within best position
- potential within age

### null values
check and deal with null and zero values

After cleaning FIFA 21 dataset contains 28 columns and 17,125 rows

### Summary of the results
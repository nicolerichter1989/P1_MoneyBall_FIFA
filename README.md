# P1_MoneyBall_FIFA

### Introduction

What made me chose these questions

Quesiton 1: Does the foot make a difference in other player attributes?

Question 2: Who are the the 5 highest valued players within each 10 year age group?

Question 3: Who are the highest valued players per best position? (most expensive team)

### First steps

Importing all required libraries
Importing data (csv file)

### Understanding the Data

To understand the data I used several functions, some might not be displayed within my jupyter file.
As I am personally not interested in FIFA I had to spend a lot of time understanding what the different columns actually stand for.
After understanding the data I was able to chose which columns I want to use for my analysis and prediction.

### Cleaning the Data

Before cleaning FIFA 21 dataset contains 107 columns and 17,125 rows

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

I decided to add 3 rankings:
- potential within best position
- potential within age
- value within club

### null values
rows with several null values
other object or string null values change to unknown

After cleaning FIFA 21 dataset contains 29 columns and 17,125 rows

### Explanation of how the data was processed (including the cleaning and selection of the variables to include in the model)

### Summary of the results

### Sources

Dataframe: https://www.kaggle.com/ekrembayar/fifa-21-complete-player-dataset

### List of libraries (with a link to the documentation)

### List of functions used

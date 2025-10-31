# Analysis-of-German-bundenliga-Football-Matches-using-Python
This project aims to present the procedure of analysis followed to respond 3 questions about the performance of players, number of passes per match and analysis of variables that could affect the success of a match. The analysis was carried out using Python Libraries as Pandas, Numpy, Matplotlib and statistical tools.    
The used information belongs to the football matches played at the German Bundesliga corresponding to the 2017 and 2018 season.<br>
The dataset were downloaded from the following source:<br>
[**Link**](https://towardsdatascience.com/introduction-to-sports-analytics-with-pandas-ad6303db9e11/)<br>
All the datasets are in JSON format which is very common and easy to read.<br>
## Procedure of Analysis
1. Load The Data<br>
    * Using the library Pandas, 4 archives in Json Format are uploaded. Each archive contains information about the main events occured per match, all the teams that participated in the ligue,
    all the players and all the matches that carried out.
2. Prepare the Data<br>
    * Before starting the analysis it´s neccessary to check if there are null values and if the datatype is adequate according to the information.

3. Analyse the Data<br>
    * The objectif of this project is answered 3 questions which are:
      
       * Using the events, teams and players_2 dataframes, we are going to respond the following question:<br>
         which are the top-5 teams with the highest average number of passes per match?

       * The lenght of a pass is a really important variable which allows us to understand how a team poses its strategy and even more important
         which player completes the most of these passes correctly; therefore this analysis wants to pose the following question:
         which are the top-5 players who made more passes correctly and the average length of these passes?

       * Earlier we have evaluated the number of completed passes per player, obtaining a top-5 player dataframe. Taking this background
         we are going to compare the number of completed passes per win and not-win matches.
         As case of study, B. Leverkusen is the chosen team for this task.
 4. Visualize the Results<br>
    * Using statistical tools as mean, median, quartiles, interquartile range and statistical graphs as Box Plot, The question 3 is responded more widely.

ALL THE PROCEDURE OF ANALYSIS WAS DEVELOPED IN A JUPYTER NOTEBOOK WHICH WAS UPLOADED TO THIS PROJECT.

Thanks for checking my work; i enjoyed preparing it , any feedback or advice it will be well received. 

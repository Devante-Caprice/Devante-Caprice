## Hi there 👋

--> Welcome to my GitHub profile. My name is Devante and this is my profile my project is based on my favourite teaam which is Arsenal from 2017/18 season and I hope you will enjoy this and feel free to connect with me.


### Context

Ever since I started working with data, I've always wanted to break down the statistics of my favorite football club, Arsenal FC. So, I put together this dataset so that you too can dive into the world of football and the world of Arsenal in particular.

### Content
Introduction
Project Purpose 
Data Details
Usage Instructions
Notes
Acknowledgements
Contact

`Project Purpose
This project was created to satisfy a long-standing curiosity about Arsenal FC's performance metrics. The dataset is perfect for:

Building predictive models for match outcomes.
Visualizing player performance trends.
Exploring advanced football analytics.
Dataset Details
The repository includes the following datasets:

players.csv
Contains detailed player statistics:

Columns:
LastName, FirstName, Date, Start, Pos, Min, G, A, PK, PKA, S, SoT, Touches, Tackles, Ints, Blocks, xG, npxG, xAG, Passes, PassesA, PrgPas, Carries, PrgCar, Line, C
Example rows:
Code
Smith, John, 2023-02-28, 1, Midfielder, 90, 1, 2, 0, 0, 5, 3, 50, 4, 2, 1, 0.8, 0.6, 0.4, 45, 50, 5, 40, 5, Midfielder, 0
goalkeepers.csv
Contains goalkeeper-specific statistics:

Columns:
LastName, FirstName, Date, Start, Pos, Min, SoTA, GA, Saves, PSxG, PKatt, PKA, PKm, PassAtt, Throws, AvgLen, GKAtt, GKAvgLen, C
Example rows:
Code
Doe, John, 2023-02-28, 1, Goalkeeper, 90, 5, 2, 7, 0.6, 1, 0, 0, 30, 10, 25.4, 20, 30.2, 0
matches.csv
Contains match-level statistics:

Columns:
Season, Tour, Date, Time, Opponent, HoAw, ArsenalScore, OpponentScore, Stadium, Attendance, Coach, Referee
Example rows:
Code
2022/23, 25, 2023-02-28, 15:00, Chelsea, Home, 3, 1, Emirates Stadium, 60000, Mikel Arteta, Mike Dean
Usage Instructions
Download the Dataset:

Clone the repository: git clone https://github.com/Devante-Caprice/Devante-Caprice.git
Navigate to the dataset folder.
Load the Data:

Use Python, R, or Excel to load and explore the data. Example for Python:
Python
import pandas as pd
players = pd.read_csv('players.csv')
goalkeepers = pd.read_csv('goalkeepers.csv')
matches = pd.read_csv('matches.csv')
print(players.head())
Analyze the Data:

Create visualizations using tools like Tableau, Power BI, or Python libraries (e.g., Matplotlib, Seaborn).
Notes
The dataset will be updated with new matches and past seasons.
Data is subject to corrections and improvements over time.
Acknowledgements
Special thanks to:

goalkeepers.csv
matches.csv
players.csv
Contact
Email: [devantecaprice@hotmail.com]
LinkedIn: [http://www.linkedin.com/devantecaprice]
Pronouns: He/Him
Fun Fact: Avid Arsenal supporter and fitness enthusiast, also novel reader (currently reading Of Mice and Men by John Steinbeck)


players.csv` includes the following columns:

-   `LastName` - Player's last name
-   `FirstName` - Player's first name
-   `Date` - Match date
-   `Start` - Starting lineup (1 - in start, 0 - from bench)
-   `Pos` - Position
-   `Min` - Minutes played
-   `G` - Goals
-   `A` - Assists
-   `PK` - Penalty kicks made
-   `PKA` - Penalty kicks attempted
-   `S` - Total shots
-   `SoT` - Shots on target
-   `Touches` - Total touches
-   `Tackles` - Total tackles
-   `Ints` - Interceptions
-   `Blocks` - Blocks
-   `xG` - Expected goals
-   `npxG` - Expected non-penalty goals
-   `xAG` - Expected assists
-   `Passes` - Total passes
-   `PassesA` - Attempted passes
-   `PrgPas` - Progressive passes
-   `Carries` - Number of times player controlled the ball
-   `PrgCar` - Progressive carries
-   `Line` - Line (forward, midfielder, defender)
-   `C` - Squad's captain

`goalkeepers.csv` includes the following columns:

-   `LastName` - Goalkeeper's last name
-   `FirstName` - Goalkeeper's first name
-   `Date` - Match date
-   `Start` - Starting lineup (1 - in start, 0 - from bench)
-   `Pos` - Position
-   `Min` - Minutes played
-   `SoTA` - Shots on target against
-   `GA` - Goals against
-   `Saves` - Total saves
-   `PSxG` - Post-shot expected goals
-   `PKatt` - Penalty kick attempted
-   `PKA` - Penalty kick allowed
-   `PKm` - Penalty kick missed
-   `PassAtt` - Passes attempted
-   `Throws` - Throws attempted
-   `AvgLen` - Average pass length (in yards)
-   `GKAtt` - Goal kicks attempted
-   `GKAvgLen` - Average goal kick length (in yards)
-   `C` - Squad's captain

`matches.csv` includes the following columns:

-   `Season` - Season
-   `Tour` - Matchweek
-   `Date` - Date of the match
-   `Time` - Time of the match
-   `Opponent` - Opponent team
-   `HoAw` - Arsenal's home/away
-   `ArsenalScore` - Arsenal goals
-   `OpponentScore` - Arsenal's opponent goals
-   `Stadium` - Match stadium
-   `Attendance` - Match attendance
-   `Coach` - Arsenal's head coach
-   `Referee` - Referee of the match

### Notes

The dataset will be updated with new matches and past seasons.
Data is subject to corrections and improvements over time.


This dataset will be updated with new matches as well as for past seasons.
COYG!

### Acknowledgements

[goalkeepers.csv](https://github.com/user-attachments/files/20216840/goalkeepers.csv)
[matches.csv](https://github.com/user-attachments/files/20216841/matches.csv)[README.md](https://github.com/user-attachments/files/20216843/README.md)
[players.csv](https://github.com/user-attachments/files/20216842/players.csv)

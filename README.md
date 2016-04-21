# Money Ball
-----------------------------------------
#### "It's unbelievable how much you don't know about the game you've been playing all your life" -Mickey Mantle
-----------------------------------------

## Goal:
Assemble a team of 9 players for a season game season by performing similar analysis of players as seen in the movie "Money Ball".

## Context
In the movie / book Moneyball - data analysis is employed to discover that teams that had a roster containing players with a high on base percentage (OBP) did very well in the regular season. Using this knowledge the General Manager was able to create a very successful team on a shoestring budget with players that had a high OBP.
!["You''re not solving the problem... quote ](https://ragsnair.files.wordpress.com/2015/03/moneyball_quote.png)

## How to View
Please open the [money-ball.ipynb](https://github.com/niccolley1/money-ball/blob/master/money-ball.ipynb) file to view the results.

## Data Source
Data is from [Sean Lahman's website](http://www.seanlahman.com/baseball-archive/statistics/).

## Tasks

 - Find the players with the highest OBP, On Base Percentage, with the lowest salary in any specific year.
    - Calculated by OBP = (H+BB+HBP)/(AB+BB+HBP+SF)
      - H = Hits
      - BB = Bases on Balls (Walks)
      - HBP = Times Hit By Pitch
      - AB = At Bat
      - SF = Sacrifice Flies
    - Tables Needed:
      - Batting
      - Master
 - Removing outliers (an OBP of 1.0 is not an indicator of a perfect player, more like they possibly only played 4 or 5 games and had good luck, alternatively an OBP of 0 is pretty bad).
 - Player Roster
	 - 9 player roster will need to include:
		 - (1st, 2nd, 3rd) Baseman
		 - (Left, Center, Right) Fielders
		 - Short Stop
		 - Pitcher
		 - Catcher
	 - A player that historically played multiple positions can not account for 2 places on your roster.

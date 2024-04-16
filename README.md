# UFC-Analysis
Worked through a scrapped database provided through Kaggle. The database contained various information about UFC fighters. The <a href="https://www.kaggle.com/datasets/rajeevw/ufcdata"> link </a> is provided.
# Project Goals
After looking through the data, I wanted to first know which side won more often. This then led to why red fighters win more often. Then the hypothesis was created, experience affects the outcome of the fight, meaning that red fighters have more experience.
## Key Questions
- Does the red or blue side win more often?
- Why do red fighters win more often than blue fighters?
- Do rounds have an impact on the wins?
- Does age affect wins?
- Is experience the key influence on the outcome of the fight?
# Final Deliverable
Refer to <a href="https://github.com/MaverickFigueira/UFC-Analysis/tree/main/Data%20Analysis%20UFC"> attached files </a> to review my work with Python. Within the file, you will see how I answered each of these questions with visualizations and data manipulation. 
I also compiled a <a href="https://public.tableau.com/app/profile/maverick.figueira/viz/UFCFighterTrends_17131164989310/Story1?publish=yes"> tableau presentation </a>  that not only shows my hypothesis, but also has recommendations for the UFC to consider to create more interesting fights, and questions to ask if they want to expand their viewer base.
# Important Note
Here is a list of the abbreviations and what they mean, courtesy of the Kraggle user:
-	R_ and B_ prefix signifies red and blue corner fighter stats respectively
-	_opp_ containing columns is the average of damage done by the opponent on the fighter
-	KD is number of knockdowns
-	SIG_STR is no. of significant strikes 'landed of attempted'
-	SIG_STR_pct is significant strikes percentage
-	TOTAL_STR is total strikes 'landed of attempted'
-	TD is no. of takedowns
-	TD_pct is takedown percentages
-	SUB_ATT is no. of submission attempts
-	PASS is no. times the guard was passed?
-	REV is the no. of Reversals landed
-	HEAD is no. of significant strinks to the head 'landed of attempted'
-	BODY is no. of significant strikes to the body 'landed of attempted'
-	CLINCH is no. of significant strikes in the clinch 'landed of attempted'
-	GROUND is no. of significant strikes on the ground 'landed of attempted'
-	win_by is method of win
-	last_round is last round of the fight (ex. if it was a KO in 1st, then this will be 1)
-	last_round_time is when the fight ended in the last round
-	Format is the format of the fight (3 rounds, 5 rounds etc.)
-	Referee is the name of the Ref
-	date is the date of the fight
-	location is the location in which the event took place
-	Fight_type is which weight class and whether it's a title bout or not
-	Winner is the winner of the fight
-	Stance is the stance of the fighter (orthodox, southpaw, etc.)
-	Height_cms is the height in centimeter
-	Reach_cms is the reach of the fighter (arm span) in centimeter
-	Weight_lbs is the weight of the fighter in pounds (lbs)
-	age is the age of the fighter
-	title_bout Boolean value of whether it is title fight or not
-	weight_class is which weight class the fight is in (Bantamweight, heavyweight, Women's flyweight, etc.)
-	no_of_rounds is the number of rounds the fight was scheduled for
-	current_lose_streak is the count of current concurrent losses of the fighter
-	current_win_streak is the count of current concurrent wins of the fighter
-	draw is the number of draws in the fighter's ufc career
-	wins is the number of wins in the fighter's ufc career
-	losses is the number of losses in the fighter's ufc career
-	total_rounds_fought is the average of total rounds fought by the fighter
-	total_time_fought(seconds) is the count of total time spent fighting in seconds
-	total_title_bouts is the total number of title bouts taken part in by the fighter
-	win_by_Decision_Majority is the number of wins by majority judges decision in the fighter's ufc career
-	win_by_Decision_Split is the number of wins by split judges decision in the fighter's ufc career
-	win_by_Decision_Unanimous is the number of wins by unanimous judges decision in the fighter's ufc career
-	win_by_KO/TKO is the number of wins by knockout in the fighter's ufc career
-	win_by_Submission is the number of wins by submission in the fighter's ufc career
-	win_by_TKO_Doctor_Stoppage is the number of wins by doctor stoppage in the fighter's ufc career

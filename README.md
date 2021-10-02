

*****Background information****


The Indian Premier League (IPL) is a professional Twenty20 cricket league, contested by eight teams based out of eight different Indian cities.[3] The league was founded by the Board of Control for Cricket in India (BCCI) in 2007. It is usually held between March and May of every year and has an exclusive window in the ICC Future Tours Programme.
There have been thirteen seasons of the IPL tournament. The current IPL title holders are the Mumbai Indians, who won the 2020 season.[10] The venue for the 2020 season was moved due to the COVID-19 pandemic and games were played in the United Arab Emirates

***Here EDA of both the datasets of IPL(IPL_matches,IPL_ball_by_ball)****

***************************************************Dataset attribute of IPL_baii_by_ball****

id-match id

inning-1st or 2nd inning

over-over number

ball-ball number in the over

batsman-name of the batsman at crease

non_striker-name of the batsman at non striker end

bowler-Bowler who bowled the over

batsman_runs-Runs by batsman

extra_runs-total extra runs

total_runs-total extra runs by batsman

non_boundary - boundary or noy at a particular baii

is_wicket-wicket or not at a particular ball

dismissal_kind-how batsman get dismissed

player_dismissed-is batsman dismissed	 on this delivery

fielder-if its a caught or bowled then which fielder was invoived

extras_type-extra runs type

batting_team-team batting

bowling_team-team bowling





***********************************************Dataset attributes of IPL_matches******

id: The IPL match id.

city: The city where the IPL match was held.

date: The date on which the match was held.

team1: One of the teams of the IPL match

team2: The other team of the IPL match

neutral_venue:vanue which not reladed both teams	

toss_winner: The team that won the toss

toss_decision: The decision taken by the team that won the toss to ‘bat’ or ‘field’

result: The result(‘normal’, ‘tie’, ‘no result’) of the match.

winner: The winner of the match

player_of_match: The outstanding player of the match.

venue: The venue where the match was hosted.

result_margin:by how many runs team wins

eliminator:to eliminate(Eliminator: The Eliminator is played between teams who finish at the third and fourth position in the points table. Like the name suggests, the team losing this match is out of the competition)

method:mathematical formulation designed to calculate the target score

umpire1: One of the two on-field umpires who officiate the match.

umpire2: One of the two on-field umpires who officiate the match


*************************************library used***

pyforest

autoviz

*************************Objectives****

Perform Exploratory data analysis (EDA) to analyze and investigate data sets and summarize it's main characteristics

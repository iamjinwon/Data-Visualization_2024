#  :pie_chart: Data Visualization 리포트

## 주제
- 축구를 하는데 있어서 키가 큰 영향을 줄까? 
  - 축구를 하는데 있어서 신장이 클수록 유리할 것이다. 

### 데이터 출처 
- 캐글 : https://www.kaggle.com/datasets/sdelquin/laliga-data3

### 데이터 칼럼 정보
- Personal:
country - Birth country of the player (Alpha-2) - string
date_of_birth - Date of birth of the player - date
firstname - First name of the player - string
gender - Gender of the player - string
height - Height (cm) of the player - integer
id - Player id for La Liga - integer
instagram - Instagram url of the player - string
international - Indicate if the player has played with a national team - boolean
lastname - Last name of the player - string
name - Full name of the player - string
nickname - Shortname as the player is usually known - string
photo - Url for the player photo (image) - url
place_of_birth - Place of birth of the player - string
player.url - Individual url for player in LaLiga - string
position - Position in field where the player plays - string
shirt_number - Shirt number of the player - int
slug - Player slug (no spaces string identifier) - string
stadium - Stadium where the player plays - string
stadium.image - Url for the stadium image - url
team - Team of the player - string
team.foundation - Date of team foundation - date
team.shield - Url for the team shield (image) - url
team.shortname - Team shortname (3 chars) of the player - string
twitter - Twitter url of the player - string
weight - Weight (kg) of the player - int

- Classics:
appearances - Matches where the player took part in - int
competition - Name of the competition - string
games_played - Matches where the player took part in - int
goals - Total goals made by player - int
index - Player index - int
penalty_goals - Penalty goals made by player - int
recoveries - Recoveries made by player - int
starts - Games played in startline - int
substitute_off - Times the player has been substitute off - int
substitute_on - Times the player has been substitute on - int
team_games_played - Number of games played by the player's team - int
time_played - Time played (minutes) by player - int
total_passes - Total passes made by player - int
total_shots - Total shots made by player - int
touches - Ball touches made by player - int

- Deffensives:
aerial_duels - Aerials duels where the player was involved - int
aerial_duels_lost - Aerials duels lost where the player was involved - int
aerial_duels_won - Aerials duels won where the player was involved - int
attempts_from_set_pieces - Shots on target by player - int
backward_passes - Passes made backwards by player - int
blocked_shots - Blocked shots by player - int
blocks - Blocks made by player - int
catches - Catches made by player (usually goalkeepers) - int
clean_sheets - Matches where the team gave up no goals - int
clearances_off_the_line - Goal clearances off the line - int
drops - Restarting plays due to reasons other than normal passes - int
duels - Total duels where the player took part in - int
duels_lost - Lost duels where the player took part in - int
duels_won - Won duels where the player took part in - int
fifty_fifty - Challenge between two players that allows equal chances - int
gk_successful_distribution - Successful passes by goalkeeper - int
gk_unsuccessful_distribution - Unsuccessful passes by goalkeeper - int
goalkeeper_smother - Smother technique to catch the ball (goalkeepers) - int
goals_conceded - Goals conceded when player is in the match - int
goals_conceded_inside_box - Goals conceded inside box when player is in the match - int
goals_conceded_outside_box - Goals conceded outside box when player is in the match - int
ground_duels - Ground duels where the player took part in - int
ground_duels_lost - Lost ground duels where the player took part in - int
ground_duels_won - Won ground duels where the player took part in - int
handballs_conceded - Handballs conceded by player - int
interceptions - Interceptions made by player - int
last_man_tackle - Tackles when player is the last player (defense) - int
own_goal_scored - Own goal scored by player - int
penalties_faced - Faced penalties by player - int
penalties_saved - Saved penalties by player (usually goalkeeper) - int
penalty_goals_conceded - Penalty goals conceded when player is in the match - int
saves_from_penalty - Saves from penalty made by player (usually goalkeeper) - int
saves_made - Saves made by player (usually goalkeeper) - int
saves_made_caught - Saves with caught made by player (usually goalkeeper) - int
saves_made_from_inside_box - Saves made from inside box by player (usually goalkeeper) - int
saves_made_from_outside_box - Saves made from outside box by player (usually goalkeeper) - int
saves_made_parried - Saves made by player not holding the ball (usually goalkeeper) - int
tackles_lost - Lost tackles made by player - int
tackles_won - Won tackles made by player - int
times_tackled - Times the player has been tackled - int
total_clearances - Total clearances made by player - int
total_tackles - Total tackles made by player - int

- Discipline:
foul_attempted_tackle - Foul attempted tackle by player - int
foul_won_penalty - Foul penalties won by player - int
offsides - Offsides of player - int
penalties_conceded - Penalties conceded by player - int
punches - Punches made by player - int
red_cards_2nd_yellow - Red cards to the player after second yellow card - int
straight_red_cards - Straight red cards received by player - int
total_fouls_conceded - Total fouls conceded by player - int
total_red_cards - Total red cards received by player - int
yellow_cards - Yellow cards received by player - int

- Offensives:
assists_intentional - Assists given by player - int
away_goals - Away goals made by player - int
corners_taken_incl_short_corners - Taken corners by player (includes short corners) - int
corners_won - Won corners by player - int
crosses_not_claimed - Crosses not claimed by player - int
forward_passes - Passes made forwards by player - int
goal_assists - Goal assists made by player - int
goals_from_inside_box - Goals from inside box made by player - int
goals_from_outside_box - Goals from outside box made by player - int
headed_goals - Headed goals made by player - int
hit_woodwork - Woodwork hits made by player - int
home_goals - Home goals made by player - int
key_passes_attempt_assists - Key passes with attempt of assist made by player - int
left_foot_goals - Left foot goals made by player - int
leftside_passes - Passes to the left side of the field made by player - int
open_play_passes - Passes in open play made by player - int
other_goals - Goals not covered by other categories - int
penalties_off_target - Penalties made out of the goal by player - int
penalties_taken - Taken penalties by player - int
putthrough_blocked_distribution - Put through blocked distribution - int
putthrough_blocked_distribution_won - Put through blocked distribution won - int
right_foot_goals - Right foot goals made by player - int
rightside_passes - Passes to the right side made by player - int
second_goal_assists - Second goal assists made by player - int
set_pieces_goals - Set pieces goals made by player - int
shots_off_target_inc_woodwork - Shots off target included woodwork made by player - int
shots_on_target_inc_goals - Shots on target included woodwork made by player - int
successful_corners_into_box - Successful corners hitted into box by player - int
successful_crosses_corners - Successful corner crosses made by player - int
successful_crosses_open_play - Successful crosses on open play made by player - int
successful_dribbles - Successful dribbles made by player - int
successful_fifty_fifty - Successful fifty fifty challenges won by player - int
successful_launches - Successful launches made by player - int
successful_layoffs - Successful layoffs made by player - int
successful_long_passes - Successful long passes made by player - int
successful_open_play_passes - Successful open play passes made by player - int
successful_passes_opposition_half - Successful passes in opossition half made by player - int
successful_passes_own_half - Successful passes in own half made by player - int
successful_short_passes - Successful short passes made by player - int
through_balls - Passes into space between defenders made by player - int
throw_ins_to_opposition_player - Throw-ins to an opponent made by player - int
throw_ins_to_own_player - Throw-ins to a teammate made by player - int
total_fouls_won - Total fouls won by player - int
total_losses_of_possession - Total losses of possession of player - int
total_successful_passes_excl_crosses_corners - Total successful passes excluding crosses corners - int
total_touches_in_opposition_box - Total touches in opposition box made by player - int
total_unsuccessful_passes_excl_crosses_corners - Total unsuccessful passes excluding crosses corners - int
unsuccessful_corners_into_box - Unsuccessful corners into the box made by player - int
unsuccessful_crosses_corners - Unsuccessful crosses corners made by player - int
unsuccessful_crosses_open_play - Unsuccessful crosses in open play made by player - int
unsuccessful_dribbles - Unsuccessful dribbles made by player - int
unsuccessful_launches - Unsuccessful launches made by player - int
unsuccessful_layoffs - Unsuccessful layoffs made by player - int
unsuccessful_long_passes - Unsuccessful long passes made by player - int
unsuccessful_passes_opposition_half - Unsuccessful passes in opossition half made by player - int
unsuccessful_passes_own_half - Unsuccessful passes in own half made by player - int
unsuccessful_short_passes - Unsuccessful short passes made by player - int
winning_goal - Winning goals made by player - int

## 가설
#### Forward
- 가설 1 : 키가 큰 공격수들이 대체로 공격퍼포먼스가 더 좋을 것이다.
    - 가설 1-1 : 키가 클수록 헤딩골의 수가 높을 것이다.
    - 가설 1-2 : 키가 작을수록 파울을 더 많이 당할 것이다.

#### Midfielder
가설 2 : 키가 작은 선수들은 창의성이 높을 것이고, 키가 큰 선수들은 수비적인 스탯이 더 좋을 것이다.

#### Defender
- 가설 3 : 수비수는 키가 큰 그룹이 더 뛰어난 선수가 많을 것이다. 
    - 가설 3-1 : 수비수는 키가 클 수록 공중볼 경합 및 태클성공률이 높을 것이다.
    - 가설 3-2 : 파울빈도가 높을수록 수비능력은 좋지 않을 것이다.

#### Goalkeeper
- 가설 4 : 골키퍼는 키가 큰 선수들이 더 좋은 활약을 펼칠 것이다.

#### ETC
- 가설 5 : 평균 신장이 높은 팀이 세트피스에서 더 강한 모습을 보일 것이다.
- 가설 6 : 평균 신장이 높은 팀이 순위가 더 높을 것이다.
- 가설 7 : 평균 연령이 낮은 팀이 순위가 더 높을 것이다.
- 가설 8 : 좋은걸 많이 먹고 크는 요즘 선수들이 더 키가 클 것이다. (번외)

#### 결론

## 분석 및 코드
[Data_Visualization_2024.ipynb](Data_Visualization_2024.ipynb)
## 데이터 시각화 결과 예시
- 노션 링크 : [23/24 LaLiga Data Visualization](https://www.notion.so/Data-Visualization-Soccer-Project-4c9e2469c93b467bb586953c4f166cd9?pvs=4)

### 예시
<img src="./ex_plot/height_average.png">
<img src="./ex_plot/affensive_score.png">
<img src="./ex_plot/teamheight_heading.png">
<img src="./ex_plot/map.png">
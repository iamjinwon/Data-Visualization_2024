#  :bar_chart: Data Visualization 리포트

## 주제
- 축구를 하는데 있어서 키가 큰 영향을 줄까? 
  - 축구를 하는데 있어서 신장이 클수록 유리할 것이다. 

### 데이터 출처 
- 캐글 : https://www.kaggle.com/datasets/sdelquin/laliga-data3

### 데이터 칼럼 정보
| Column                               | Category    | Description                                          | Type   |
|--------------------------------------|-------------|------------------------------------------------------|--------|
| country                              | Personal    | Birth country of the player (Alpha-2)              | string |
| date_of_birth                        | Personal    | Date of birth of the player                         | date   |
| firstname                            | Personal    | First name of the player                             | string |
| gender                               | Personal    | Gender of the player                                | string |
| height                               | Personal    | Height (cm) of the player                           | integer|
| id                                   | Personal    | Player id for La Liga                               | integer|
| instagram                            | Personal    | Instagram url of the player                         | string |
| international                        | Personal    | Indicate if the player has played with a national team | boolean|
| lastname                             | Personal    | Last name of the player                             | string |
| name                                 | Personal    | Full name of the player                             | string |
| nickname                             | Personal    | Shortname as the player is usually known            | string |
| photo                                | Personal    | Url for the player photo (image)                    | url    |
| place_of_birth                       | Personal    | Place of birth of the player                        | string |
| player.url                           | Personal    | Individual url for player in LaLiga                | string |
| position                             | Personal    | Position in field where the player plays            | string |
| shirt_number                         | Personal    | Shirt number of the player                          | int    |
| slug                                 | Personal    | Player slug (no spaces string identifier)          | string |
| stadium                              | Personal    | Stadium where the player plays                      | string |
| stadium.image                        | Personal    | Url for the stadium image                            | url    |
| team                                 | Personal    | Team of the player                                  | string |
| team.foundation                      | Personal    | Date of team foundation                             | date   |
| team.shield                          | Personal    | Url for the team shield (image)                     | url    |
| team.shortname                       | Personal    | Team shortname (3 chars) of the player             | string |
| twitter                              | Personal    | Twitter url of the player                           | string |
| weight                               | Personal    | Weight (kg) of the player                           | integer|
| appearances                          | Classics    | Matches where the player took part in               | integer|
| competition                          | Classics    | Name of the competition                              | string |
| games_played                         | Classics    | Matches where the player took part in               | integer|
| goals                                | Classics    | Total goals made by player                          | integer|
| index                                | Classics    | Player index                                        | integer|
| penalty_goals                        | Classics    | Penalty goals made by player                        | integer|
| recoveries                           | Classics    | Recoveries made by player                           | integer|
| starts                               | Classics    | Games played in startline                           | integer|
| substitute_off                        | Classics    | Times the player has been substitute off            | integer|
| substitute_on                         | Classics    | Times the player has been substitute on             | integer|
| team_games_played                    | Classics    | Number of games played by the player team           | integer|
| time_played                          | Classics    | Time played (minutes) by player                     | integer|
| total_passes                         | Classics    | Total passes made by player                         | integer|
| total_shots                          | Classics    | Total shots made by player                          | integer|
| touches                              | Classics    | Ball touches made by player                         | integer|
| aerial_duels                         | Deffensives | Aerials duels where the player was involved         | integer|
| aerial_duels_lost                    | Deffensives | Aerials duels lost where the player was involved    | integer|
| aerial_duels_won                     | Deffensives | Aerials duels won where the player was involved     | integer|
| attempts_from_set_pieces             | Deffensives | Shots on target by player                           | integer|
| backward_passes                      | Deffensives | Passes made backwards by player                     | integer|
| blocked_shots                        | Deffensives | Blocked shots by player                             | integer|
| blocks                               | Deffensives | Blocks made by player                               | integer|
| catches                              | Deffensives | Catches made by player (usually goalkeepers)        | integer|
| clean_sheets                         | Deffensives | Matches where the team gave up no goals             | integer|
| clearances_off_the_line              | Deffensives | Goal clearances off the line                        | integer|
| drops                                | Deffensives | Restarting plays due to reasons other than normal gameplay | integer|
| duels                                | Deffensives | Total duels where the player took part in           | integer|
| duels_lost                           | Deffensives | Lost duels where the player took part in            | integer|
| duels_won                            | Deffensives | Won duels where the player took part in             | integer|
| fifty_fifty                          | Deffensives | Challenge between two players that allows equal chances of acquiring the control of the ball | integer|
| gk_successful_distribution           | Deffensives | Successful passes by goalkeeper                    | integer|
| gk_unsuccessful_distribution         | Deffensives | Unsuccessful passes by goalkeeper                  | integer|
| goalkeeper_smother                   | Deffensives | Smother technique to catch the ball (goalkeepers)  | integer|
| goals_conceded                       | Deffensives | Goals conceded when player is in the match          | integer|
| goals_conceded_inside_box            | Deffensives | Goals conceded inside box when player is in the match | integer|
| goals_conceded_outside_box           | Deffensives | Goals conceded outside box when player is in the match | integer|
| ground_duels                         | Deffensives | Ground duels where the player took part in          | integer|
| ground_duels_lost                    | Deffensives | Lost ground duels where the player took part in     | integer|
| ground_duels_won                     | Deffensives | Won ground duels where the player took part in      | integer|
| handballs_conceded                   | Deffensives | Handballs conceded by player                        | integer|
| interceptions                        | Deffensives | Interceptions made by player                        | integer|
| last_man_tackle                      | Deffensives | Tackles when player is the last player (defense)    | integer|
| own_goal_scored                      | Deffensives | Own goal scored by player                           | integer|
| penalties_faced                      | Deffensives | Faced penalties by player                          | integer|
| penalties_saved                      | Deffensives | Saved penalties by player (usually goalkeeper)      | integer|
| penalty_goals_conceded               | Deffensives | Penalty goals conceded when player is in the match  | integer|
| saves_from_penalty                   | Deffensives | Saves from penalty made by player (usually goalkeeper) | integer|
| saves_made                           | Deffensives | Saves made by player (usuarlly goalkeeper)          | integer|
| saves_made_caught                    | Deffensives | Saves with caught made by player (usually goalkeeper) | integer|
| saves_made_from_inside_box           | Deffensives | Saves made from inside box by player (usually goalkeeper) | integer|
| saves_made_from_outside_box          | Deffensives | Saves made from outside box by player (usually goalkeeper) | integer|
| saves_made_parried                   | Deffensives | Saves made by player not holding the ball (usually goalkeeper) | integer|
| tackles_lost                         | Deffensives | Lost tackles made by player                         | integer|
| tackles_won                          | Deffensives | Won tackles made by player                          | integer|
| times_tackled                        | Deffensives | Times the player has been tackled                    | integer|
| total_clearances                     | Deffensives | Total clearances made by player                      | integer|
| total_tackles                        | Deffensives | Total tackles made by player                         | integer|
| foul_attempted_tackle                | Discipline | Foul attempted tackle by player                      | integer|
| foul_won_penalty                     | Discipline | Foul penalties won by player                         | integer|
| offsides                             | Discipline | Offsides of player                                   | integer|
| penalties_conceded                   | Discipline | Penalties conceded by player                         | integer|
| punches                              | Discipline | Punches made by player                               | integer|
| red_cards_2nd_yellow                | Discipline | Red cards to the player after second yellow card     | integer|
| straight_red_cards                   | Discipline | Straight red cards received by player                | integer|
| total_fouls_conceded                 | Discipline | Total fouls conceded by player                       | integer|
| total_red_cards                      | Discipline | Total red cards received by player                    | integer|
| yellow_cards                         | Discipline | Yellow cards received by player                       | integer|
| assists_intentional                  | Offensives  | Assists given by player                              | integer|
| away_goals                           | Offensives  | Away goals made by player                            | integer|
| corners_taken_incl_short_corners     | Offensives  | Taken corners by player (includes short corners)     | integer|
| corners_won                          | Offensives  | Won corners by player                                | integer|
| crosses_not_claimed                  | Offensives  | Crosses not claimed by player                        | integer|
| forward_passes                       | Offensives  | Passes made forwards by player                       | integer|
| goal_assists                         | Offensives  | Goal asists made by player                           | integer|
| goals_from_inside_box                | Offensives  | Goals from inside box made by player                 | integer|
| goals_from_outside_box               | Offensives  | Goals from outside box made by player                | integer|
| headed_goals                         | Offensives  | Headed goals made by player                          | integer|
| hit_woodwork                         | Offensives  | Woodwork hits made by player                         | integer|
| home_goals                           | Offensives  | Home goals made by player                            | integer|
| key_passes_attempt_assists           | Offensives  | Key passes with attempt of assist made by player    | integer|
| left_foot_goals                      | Offensives  | Left foot goals made by player                       | integer|
| leftside_passes                      | Offensives  | Passes to the left side of the field made by player | integer|
| open_play_passes                     | Offensives  | Passes in open play made by player                   | integer|
| other_goals                          | Offensives  | Goals not covered by other categories                | integer|
| penalties_off_target                 | Offensives  | Penalties made out of the goal by player             | integer|
| penalties_taken                      | Offensives  | Taken penalties by player                            | integer|
| putthrough_blocked_distribution      | Offensives  | Put through blocked distribution                    | integer|
| putthrough_blocked_distribution_won  | Offensives  | Put through blocked distribution won                | integer|
| right_foot_goals                     | Offensives  | Right foot goals made by player                      | integer|
| rightside_passes                     | Offensives  | Passes to the right side made by player              | integer|
| second_goal_assists                  | Offensives  | Second goal assists made by player                   | integer|
| set_pieces_goals                     | Offensives  | Set pieces goals made by player                      | integer|
| shots_off_target_inc_woodwork        | Offensives  | Shots off target included woodwork made by player    | integer|
| shots_on_target_inc_goals            | Offensives  | Shots on target included woodwork made by player    | integer|
| successful_corners_into_box          | Offensives  | Successful corners hitted into box by player         | integer|
| successful_crosses_corners           | Offensives  | Successful corner crosses made by player             | integer|
| successful_crosses_open_play         | Offensives  | Successful crosses on open play made by player      | integer|
| successful_dribbles                  | Offensives  | Successful dribbles made by player                   | integer|
| successful_fifty_fifty               | Offensives  | Successful fifty fifty challenges won by player     | integer|
| successful_launches                  | Offensives  | Successful launches made by player                  | integer|
| successful_layoffs                   | Offensives  | Successful layoffs made by player                   | integer|
| successful_long_passes               | Offensives  | Successful long passes made by player               | integer|
| successful_open_play_passes          | Offensives  | Successful open play passes made by player           | integer|
| successful_passes_opposition_half    | Offensives  | Successful passes in opossition half made by player | integer|
| successful_passes_own_half           | Offensives  | Successful passes in own half made by player         | integer|
| successful_short_passes              | Offensives  | Successful short passes made by player              | integer|
| through_balls                        | Offensives  | Passes into space between defenders made by player  | integer|
| throw_ins_to_opposition_player       | Offensives  | Throw-ins to an opponent made by player             | integer|
| throw_ins_to_own_player              | Offensives  | Throw-ins to a teammate made by player              | integer|
| total_fouls_won                      | Offensives  | Total fouls won by player                            | integer|
| total_losses_of_possession           | Offensives  | Total losses of possesion of player                 | integer|
| total_successful_passes_excl_crosses_corners | Offensives  | Total successful passes excluding crosses corners | integer|
| total_touches_in_opposition_box      | Offensives  | Total touches in opposition box made by player      | integer|
| total_unsuccessful_passes_excl_crosses_corners | Offensives  | Total unsuccessful passes excluding crosses corners | integer|
| unsuccessful_corners_into_box        | Offensives  | Unsuccessful corners into the box made by player    | integer|
| unsuccessful_crosses_corners         | Offensives  | Unsuccessful crosses corners made by player   | integer|
| unsuccessful_crosses_open_play         | Offensives  | Unsuccessful crosses in open play made by player   | integer|
| unsuccessful_dribbles         | Offensives  | Unsuccessful dribbles made by player   | integer|
| unsuccessful_launches         | Offensives  | Unsuccessful launches made by player   | integer|
| unsuccessful_layoffs         | Offensives  | Unsuccessful layoffs made by player   | integer|
| unsuccessful_long_passes         | Offensives  | Unsuccessful long passes made by player   | integer|
| unsuccessful_passes_opposition_half         | Offensives  | Unsuccessful passes in opossition half made by player   | integer|
| unsuccessful_passes_own_half         | Offensives  | Unsuccessful passes in own half made by player   | integer|
| unsuccessful_short_passes         | Offensives  | Unsuccessful short passes made by player   | integer|
| winning_goal         | Offensives  | Winning goals made by player   | integer|

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
- 노션 링크 : [Data Visualization - Soccer Project](https://www.notion.so/Data-Visualization-Soccer-Project-4c9e2469c93b467bb586953c4f166cd9?pvs=4)

### 예시
<img src="./ex_plots/height_average.png">
<img src="./ex_plots/affensive_score.png">
<img src="./ex_plots/teamheight_heading.png">
<img src="./ex_plots/map.png">
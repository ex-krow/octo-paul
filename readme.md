# octo-paul

### a football prediction engine named after famed paul the octopus.

what does this paul predict?
paul predicts 7 spot betting markets of fixtures in europe's top ten leagues.

1. 1-X-2
2. 1X-12-X2
3. highest scoring half
4. over/under n.5
5. gg/ng
6. 1-X-2 & over n.5
7. to win to nil

what data is available to paul?
historical data dating back to 2014 of the following datapoints.
for any fixture between team AFC v BFC:

- prev-7 round goals-conceded
- prev-3 h2h goals-conceded
- prev-7 round goals
- prev-3 h2h goals

- prev-7 round goal-times-conceded
- prev-3 h2h goal-times-conceded
- prev-7 round goal-times
- prev-3 h2h goal-times

- prev-7 round shots-conceded
- prev-3 h2h shots-conceded
- prev-7 round shots
- prev-3 h2h shots

- prev-7 round shots inside box-conceded
- prev-3 h2h shots inside box-conceded
- prev-7 round shots inside box
- prev-3 h2h shots inside box

- prev-7 round shots on target-conceded
- prev-3 h2h shots on target-conceded
- prev-7 round shots on target
- prev-3 h2h shots on target

- prev-7 round shots off target-conceded
- prev-3 h2h shots off target-conceded
- prev-7 round shots off target
- prev-3 h2h shots off target

- prev-7 round shots blocked-conceded
- prev-3 h2h shots blocked-conceded
- prev-7 round shots blocked
- prev-3 h2h shots blocked

- prev-7 round clearances-conceded
- prev-3 h2h clearances-conceded
- prev-7 round clearances
- prev-3 h2h clearances

- prev-7 round passes-conceded
- prev-3 h2h passes-conceded
- prev-7 round pass accuracy
- prev-3 h2h pass accuracy

- prev-7 round possesion_percent-conceded
- prev-3 h2h possesion_percent-conceded
- prev-7 round possesion_percent
- prev-3 h2h possesion_percent

- prev-7 round offsides-conceded
- prev-3 h2h offsides-conceded
- prev-7 round offsides
- prev-3 h2h offsides

- prev-7 round corners-conceded
- prev-3 h2h corners-conceded
- prev-7 round corners
- prev-3 h2h corners

- prev-7 round penalties-conceded
- prev-3 h2h penalties-conceded
- prev-7 round penalties
- prev-3 h2h penalties

- prev-7 round fouls-conceded
- prev-3 h2h fouls-conceded
- prev-7 round fouls
- prev-3 h2h fouls

- prev-7 round goalkeeper saves-conceded
- prev-3 h2h goalkeeper saves-conceded
- prev-7 round goalkeeper saves
- prev-3 h2h goalkeeper saves

- prev-7 round-opponent formation
- prev-3 h2h-opponent formation
- prev-7 round formation
- prev-3 h2h formation

- prev-7 round attacks-conceded
- prev-3 h2h attacks-conceded
- prev-7 round attacks
- prev-3 h2h attacks

- prev-7 round dangerous attacks-conceded
- prev-3 h2h dangerous attacks-conceded
- prev-7 round dangerous attacks
- prev-3 h2h dangerous attacks

- prev-7 round temperature
- prev-3 h2h temperature

- prev-7 round cleansheets-conceded
- prev-3 h2h cleansheets-conceded
- prev-7 round cleansheets
- prev-3 h2h cleansheets

- prev-7 round highest-conceding half
- prev-3 h2h highest-conceding half
- prev-7 round highest-scoring half
- prev-3 h2h highest-scoring half

- prev-7 round points
- prev-3 h2h points

- prev-7 round yellow card-conceded
- prev-3 h2h yellow card-conceded
- prev-7 round yellow card
- prev-3 h2h yellow card

- prev-7 round red card-conceded
- prev-3 h2h red card-conceded
- prev-7 round red card
- prev-3 h2h red card

- prev-7 round throw-ins-conceded
- prev-3 h2h throw-ins-conceded
- prev-7 round throw-ins
- prev-3 h2h throw-ins

- prev-7 round ball safes-conceded
- prev-7 round ball safes-conceded
- prev-3 h2h ball safes
- prev-3 h2h ball safes

- average table position at round
- average table position
- current table position
- average points-per-game
- average points-per-season
- average points from prev-7 h2h
- average goals-per-game
- average goals-per-game h2h
- average goals-per-season
- average goals-conceded-per-season
- pre-match standings

from

# Data Analysis On PubG Dataset
This file contains 113,290,736 individual data points in 26 columns and 4,357,336 rows.

## Dataset Description:
1. Id - Integer ID to identify a group within a match. If the same group of players plays in different matches, they will have a different groupId each time.
2. matchId - Integer ID to identify match. There are no matches that are in both the training and testing set.
3. assists - Number of times you helped your friend when he killed an enemy
4. boosts - Number of boost items used.
5. damageDealt - Total damage dealt. Note: Self inflicted damage is subtracted.
6. DBNOs - Number of enemy players knocked ('Down But No Out')
7. headshotKills - Number of enemies you killed with headshots.
8. heals - Number of healing items used.
9. killPlace - Your ranking in match in terms of number of enemy players killed.
10. killPoints - Kills-based external ranking of player. (Ranking where only winning matters).
11. kills - Number of enemy players killed.
12. killStreaks - Max number of enemy players killed in a short amount of time. A Killstreak is earned when a player acquires a certain number of kills in a row without dying.
longestKill - Longest distance between player and player killed at time of death. This may be misleading, as downing a - player and driving away may lead to a large longestKill stat.
13. maxPlace - Worst placement we have data for in the match. This may not match with numGroups, as sometimes the data skips over placements.
14. numGroups - Number of groups we have data for in the match.
15. revives - Number of times you revived your teammates.
16. rideDistance - Total distance traveled in vehicles (measured in meters)
17. roadKills - Number of enemy killed while travelling in a vehicle.
18. swimDistance - Total distance traveled by swimming (measured in meters).
19. teamKills - Number of times you are killed your teammate.
20. vehicleDestroys - Number of vehicles destroyed.
21. walkDistance - Total distance traveled on foot (measured in meters).
22. weaponsAcquired - Number of weapons picked up.
23. winPoints - Win-based external ranking of player. (Ranking where only winning matters).
24. winPlacePerc - The target of prediction (Target Variable). This is a percentile winning placement, where 1 corresponds to 1st place, and 0 corresponds to last place in the match.

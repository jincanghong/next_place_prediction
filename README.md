# next_place_prediction
Data set for paper: Augmented intention model for next location prediction by graphical trajectory context.

## File description:
1. location-lat-long.csv: AP address to latitude and longitude mapping. The first column of file is unique AP sensor name, the second column and third column are latitude and longitude of that position.
2. mac-time-ap: trajectory informations of all users, containing mac address of mobile, timestamp and ap sensor name.
3. data_list.filtered: filtered trajectory information for each user. The first number in each line represents user id, followed by locaiton id and time id(0-47 inclusive).
3. id2loc: location is to ap sensor name mapping.

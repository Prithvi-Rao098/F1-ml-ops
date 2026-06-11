This codebook describes the variables included in the final modeling dataset used for training, testing, and evaluating the Formula 1 podium prediction models.

`raceId`: Unique ID for each Formula 1 race.

`driverId`: Unique ID for each driver.

`forename`: Driver’s first name.

`surname`: Driver’s last name.

`constructorId`: Unique ID for each constructor/team.

`constructor_name`: Name of the constructor/team, such as Red Bull, Ferrari, Mercedes, or McLaren.

`circuitId`: Unique ID for each circuit.

`circuit_name`: Name of the race circuit, such as Silverstone Circuit or Circuit de Monaco.

`year`: The Formula 1 season year.

`round`: The race number within that season.

`grid`: The driver’s starting grid position for the race.

`qualifying_position`: The driver’s qualifying position before the race.

`driver_points_before_race`: The number of championship points the driver had before the race started.

`driver_standing_before_race`: The driver’s championship standing before the race started.

`driver_wins_before_race`: The number of wins the driver had before the race started.

`constructor_points_before_race`: The number of championship points the constructor had before the race started.

`constructor_standing_before_race`: The constructor’s championship standing before the race started.

`constructor_wins_before_race`: The number of wins the constructor had before the race started.

`driver_circuit_avg_finish_last5`: The driver’s average finishing position from their previous races at the same circuit, using up to the last five races.

`driver_circuit_podium_rate_last5`: The driver’s podium rate from their previous races at the same circuit, using up to the last five races.

`driver_circuit_avg_points_last5`: The driver’s average points from their previous races at the same circuit, using up to the last five races.

`driver_recent_avg_finish_last5`: The driver’s average finishing position over their previous five races overall.

`driver_recent_podium_rate_last5`: The driver’s podium rate over their previous five races overall.

`driver_recent_avg_points_last5`: The driver’s average points over their previous five races overall.

`positionOrder`: The driver’s actual finishing position in the race. This is kept for evaluation and was not used as a predictor.

`podium`: The response variable. It equals 1 if the driver finished in the top three and 0 otherwise.

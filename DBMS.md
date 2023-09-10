| Query Results                                                                                       |
|-----------------------------------------------------------------------------------------------------|
| id	date	pickup	dropoff	rider_id	car_id	type	cost                                                    |
| 1001	2017-12-05	06:45	07:10	102	1	X	28.66                                                           |
| 1002	2017-12-05	08:00	08:15	101	3	POOL	9.11                                                         |
| 1003	2017-12-05	09:30	09:50	104	4	X	24.98                                                           |
| 1004	2017-12-05	13:40	14:05	105	1	X	31.27                                                           |
| 1005	2017-12-05	15:15	16:00	103	2	POOL	18.95                                                        |
| 1006	2017-12-05	18:20	18:55	101	3	XL	78.52                                                          |
| id	first	last	username	rating	total_trips	referred                                                  |
| 101	Sonny	Li	@sonnynomnom	4.66	352                                                                  |
| 102	Laura	Breiman	@lauracle	4.99	687	101                                                            |
| 103	Kassa	Korley	@kassablanca	4.63	42                                                               |
| 104	Yakov	Kagan	@yakovkagan	4.52	1910	103                                                           |
| id	model	OS	status	trips_completed                                                                  |
| 1	Ada	Ryzac	active	82                                                                               |
| 2	Ada	Ryzac	active	30                                                                               |
| 3	Turing XL	Ryzac	active	164                                                                        |
| 4	Akira	Finux	maintenance	22                                                                        |
| first	last	model                                                                                    |
| Sonny	Li	Ada                                                                                        |
| Sonny	Li	Ada                                                                                        |
| Sonny	Li	Turing XL                                                                                  |
| Sonny	Li	Akira                                                                                      |
| Laura	Breiman	Ada                                                                                   |
| Laura	Breiman	Ada                                                                                   |
| Laura	Breiman	Turing XL                                                                             |
| Laura	Breiman	Akira                                                                                 |
| Kassa	Korley	Ada                                                                                    |
| Kassa	Korley	Ada                                                                                    |
| Kassa	Korley	Turing XL                                                                              |
| Kassa	Korley	Akira                                                                                  |
| Yakov	Kagan	Ada                                                                                     |
| Yakov	Kagan	Ada                                                                                     |
| Yakov	Kagan	Turing XL                                                                               |
| Yakov	Kagan	Akira                                                                                   |
| id	date	pickup	dropoff	rider_id	car_id	type	cost	id	first	last	username	rating	total_trips	referred |
| 1001	2017-12-05	06:45	07:10	102	1	X	28.66	102	Laura	Breiman	@lauracle	4.99	687	101                  |
| 1002	2017-12-05	08:00	08:15	101	3	POOL	9.11	101	Sonny	Li	@sonnynomnom	4.66	352                      |
| 1003	2017-12-05	09:30	09:50	104	4	X	24.98	104	Yakov	Kagan	@yakovkagan	4.52	1910	103                 |
| 1004	2017-12-05	13:40	14:05	105	1	X	31.27                                                           |
| 1005	2017-12-05	15:15	16:00	103	2	POOL	18.95	103	Kassa	Korley	@kassablanca	4.63	42                  |
| 1006	2017-12-05	18:20	18:55	101	3	XL	78.52	101	Sonny	Li	@sonnynomnom	4.66	352                       |
| id	date	pickup	dropoff	rider_id	car_id	type	cost	id	model	OS	status	trips_completed                 |
| 1001	2017-12-05	06:45	07:10	102	1	X	28.66	1	Ada	Ryzac	active	82                                     |
| 1002	2017-12-05	08:00	08:15	101	3	POOL	9.11	3	Turing XL	Ryzac	active	164                            |
| 1003	2017-12-05	09:30	09:50	104	4	X	24.98	4	Akira	Finux	maintenance	22                              |
| 1004	2017-12-05	13:40	14:05	105	1	X	31.27	1	Ada	Ryzac	active	82                                     |
| 1005	2017-12-05	15:15	16:00	103	2	POOL	18.95	2	Ada	Ryzac	active	30                                  |
| 1006	2017-12-05	18:20	18:55	101	3	XL	78.52	3	Turing XL	Ryzac	active	164                             |
| id	first	last	username	rating	total_trips	referred                                                  |
| 101	Sonny	Li	@sonnynomnom	4.66	352                                                                  |
| 102	Laura	Breiman	@lauracle	4.99	687	101                                                            |
| 103	Kassa	Korley	@kassablanca	4.63	42                                                               |
| 104	Yakov	Kagan	@yakovkagan	4.52	1910	103                                                           |
| 105	Zach	Sims	@zsims	4.85	787                                                                       |
| 106	Eric	Vaught	@posturelol	4.96	54	101                                                             |
| 107	Jilly	Beans	@jillkuzmin	4.7	32	101                                                              |
| AVG(cost)                                                                                           |
| 31.915                                                                                              |
| id	first	last	username	rating	total_trips	referred                                                  |
| 101	Sonny	Li	@sonnynomnom	4.66	352                                                                  |
| 103	Kassa	Korley	@kassablanca	4.63	42                                                               |
| COUNT(*)                                                                                            |
| 3                                                                                                   |
| id	model	OS	status	trips_completed                                                                  |
| 3	Turing XL	Ryzac	active	164                                                                        |
| 1	Ada	Ryzac	active	82                                                                               |
| Database Schema                                                                                     |
| trips                                                                                               |
| name	type                                                                                           |
| id	INTEGER                                                                                          |
| date	TEXT                                                                                           |
| pickup	TEXT                                                                                         |
| dropoff	TEXT                                                                                        |
| rider_id	INTEGER                                                                                    |
| car_id	INTEGER                                                                                      |
| type	TEXT                                                                                           |
| cost	INTEGER                                                                                        |
| Rows: 6                                                                                             |
| riders                                                                                              |
| name	type                                                                                           |
| id	INTEGER                                                                                          |
| first	TEXT                                                                                          |
| last	TEXT                                                                                           |
| username	TEXT                                                                                       |
| rating	INTEGER                                                                                      |
| total_trips	INTEGER                                                                                 |
| referred	INTEGER                                                                                    |
| Rows: 4                                                                                             |
| riders2                                                                                             |
| name	type                                                                                           |
| id	INTEGER                                                                                          |
| first	TEXT                                                                                          |
| last	TEXT                                                                                           |
| username	TEXT                                                                                       |
| rating	INTEGER                                                                                      |
| total_trips	INTEGER                                                                                 |
| referred	INTEGER                                                                                    |
| Rows: 3                                                                                             |
| cars                                                                                                |
| name	type                                                                                           |
| id	INTEGER                                                                                          |
| model	TEXT                                                                                          |
| OS	TEXT                                                                                             |
| status	TEXT                                                                                         |
| trips_completed	INTEGER                                                                             |
| Rows: 4                                                                                             |

# Intro to Database Design

1. Look at the following database tables. Identify the candidate key i.e. the minimal columns that can serve as a primary key.

 | student_id | mod_code | mark |
 |------------|----------|------|
 | u1811563   | cft2111  | 67   |
 | u1893221   | cit2318  | 55   |
 | u1811563   | cip2225  | 87   |
 | u1952004   | cft2111  | 62   |


 | suit   | value | played |
 |--------|-------|--------|
 | hearts | Ace   | true   |
 | clubs  | 8     | false  |
 | spades | King  | true   |
 | club   | 3     | true   |

|first_name     |last_name      |date       |session   |attended|
|--------------|----------------|-----------|----------|--------|
|    Compton     |    Jane      |12/12/2019 |    5     |   Y     |
|    Atherton    |    Ian       |13/12/2019 |    2     |    Y    |
|    Hutton      |    Kate      |13/12/2019 |    3     |   N     |
|    Miandad     |    Yousef    |12/12/2019 |    5     |   Y     |
|    Atherton    |    Ian       |13/12/2019 |    3     |   Y     |
|    Laxman      |    Sunil     |12/12/2019 |    3     |   N     |
|    Crowe       |    Grace     |12/12/2019 |    3     |   Y     |

 | number_plate | make     | model    |
 |--------------|----------|----------|
 | v984rh6     | BWM      | 3 series |
 | yy12sdf     | VW       | Polo     |
 | mn09geq     | Vauxhall | Corsa    |
 | st10fkj     | VW       | Golf     |

 | home_team         | away_team         | date       | home_score |away_score|
 |-------------------|-------------------|------------|-------|-------|
 | Huddersfield Town | Manchester City   | 02/02/2015 | 8   |0   |
 | Liverpool         | Everton           | 23/11/2006 | 2   |2   |
 | Chelsea           | Huddersfield Town | 10/09/2018 | 0  |10  |
 | Newport County    | Manchester United | 12/12/2013 | 5   |0   |

2. Based on the tables above what data type would you choose to store
* make
* away_score
* value
* student_id
* number_plate

3. Consider the following scenarios

* NASA have approached you to build a web application that will allow users to search for information about the Apollo space missions. You can see info about the Missions here - https://nssdc.gsfc.nasa.gov/planetary/lunar/apollo.html. How could you model this topic? Identify relevant entities and attributes. 

* The Tolson Museum in Huddersfield would like to develop a web application where users can search and browse through their collection of historical objects. They have some basic information online at the moment - https://www.kirklees.gov.uk/beta/museums-galleries-history/tolson-gallery.aspx. Think about how you would design a database to store information about their collection. Identify suitable entities and attributes.

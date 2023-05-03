[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/julian-giudice-940771a1/)

# Challenge OracleONE: Hotel Alura
![Badge en Desarollo](https://img.shields.io/badge/STATUS-%20DEVELOPEMENT-green)

This project is part of the training program of One Next Education Alura Latam and consists of creating two hotels apps belonging to the Alura Group.

![image](https://user-images.githubusercontent.com/54405665/236014609-c8f87ef7-1ca5-41e3-9b6f-61b43ab4ccb0.png)

Table of Contents:

- [Features](#Features)
- [Technologies](#Technologies)
- [Contributing](#Contributing)

## Features
Among the project's features, reservations and guests can be created, edited, and modified. Although user authentication without implementing Spring Security was used for this project, it is recognized that this is the ideal implementation option.

MySQL was used for database management. A stored procedure was created that automatically releases rooms when the application starts by comparing the system date with the end dates of the reservations. A trigger was also created that automatically generates the invoice at the time of inserting a reservation, calculating the costs according to the room type and the days between dates. Finally, a trigger was created that recalculates the costs when updating a reservation. A script named ScriptHotels.sql is included that contains everything necessary to create the database.

## Technologies
Spring Boot 3 Maven Hibernate Thymeleaf CSS.

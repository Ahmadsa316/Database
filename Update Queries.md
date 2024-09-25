### Exercises 7: Update Queries

### Question 1
update game set location = (select ident from airport where name = "Nottingham Airport"), co2_consumed = co2_consumed+500 where screen_name = "Vesa";
![screenshot](Screenshots/Uqueries_1.png)

### Question 2
Goal_reached
![screenshot](Screenshots/Uqueries_2.png)

### Question 3
DELETE FROM goal_reached;

Select * from goal_reached;
![screenshot](Screenshots/Uqueries_3.png)

### Question 4
Delete from game;

Select * from game;
![screenshot](Screenshots/Uqueries_4.png)
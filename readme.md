SQL Queries

1. SELECT * FROM robots;
2. SELECT * FROM robots WHERE personality=’anxious’;
3. SELECT name FROM recipes WHERE nut_free=true;
4. SELECT COUNT(name) FROM recipes WHERE gluten_free=true AND vegan=false;
5. SELECT MAX(number_of_legs) AS max_legs FROM animals;
  SELECT name FROM animals WHERE number_of_legs=’max_legs’;
6. SELECT * FROM board_games ORDER BY mins_to_play ASC LIMIT 1;
7. SELECT name, minutes_required FROM recipes ORDER BY minutes_required ASC LIMIT 1;
8. SELECT * FROM robots WHERE name LIKE 'M';
9. SELECT name, category, min_players, max_players FROM board_games WHERE min_players<= 8 AND max_players>=8;
10. SELECT * FROM animals WHERE swimming=true AND egg_laying=true;
11. SELECT * FROM animals WHERE swimming=true AND egg_laying=true AND flying=false;
12. SELECT * FROM board_games ORDER BY mins_to_play DESC LIMIT 1;



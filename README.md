# SQL
SQL Portfolio
CREATE TABLE makeupbykrystal (id INTEGER PRIMARY KEY, name Text, quantity INTEGER, price INTEGER);
INSERT INTO makeupbykrystal VALUES (1, "FOUNDATION", 10, 6);
INSERT INTO makeupbykrystal VALUES (2, "CONSEALER", 7, 7);
INSERT INTO makeupbykrystal VALUES (3, "LIPSTICK", 9, 9);
INSERT INTO makeupbykrystal VALUES (4,"EYESHADOW", 8, 10);
INSERT INTO makeupbykrystal VALUES (5, "HIGHLIGHTER", 10, 9);

SELECT * FROM makeupbykrystal;

SELECT * FROM makeupbykrystal ORDER BY price

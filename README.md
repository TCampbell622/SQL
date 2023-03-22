# SQL
SQL Portfolio
CREATE TABLE kids_clothing (id INTEGER PRIMARY KEY, type TEXT, quantity INTEGER, color TEXT, size INTEGER, price INTEGER);
INSERT INTO kids_clothing VALUES (1, "shirt", 30, "blue", "small", 15);
INSERT INTO kids_clothing VALUES (2, "shirt", 20, "blue", "medium", 15);
INSERT INTO kids_clothing VALUES (3, "shirt", 10, "blue", "large", 17);
INSERT INTO kids_clothing VALUES (4, "shirt", 30, "red", "small", 15);
INSERT INTO kids_clothing VALUES (5, "shirt", 20, "red", "medium", 15);
INSERT INTO kids_clothing VALUES (6, "shirt", 10, "red", "large", 17);
INSERT INTO kids_clothing VALUES (7, "shirt", 50, "green", "small", 15);
INSERT INTO kids_clothing VALUES (8, "shirt", 40, "green", "medium", 15);
INSERT INTO kids_clothing VALUES (9, "shirt", 30, "green", "large", 17);
INSERT INTO kids_clothing VALUES (10, "shirt", 15, "yellow", "small", 15);
INSERT INTO kids_clothing VALUES (11, "shirt", 10, "yellow", "medium", 15);
INSERT INTO kids_clothing VALUES (12, "shirt", 5, "yellow", "large", 17);
INSERT INTO kids_clothing VALUES (13, "shirt", 0, "purple", "small", 15);
INSERT INTO kids_clothing VALUES (14, "shirt", 5, "purple", "medium", 15);
INSERT INTO kids_clothing VALUES (15, "shirt", 2, "purple", "large", 17);
SELECT * FROM kids_clothing ORDER BY price;

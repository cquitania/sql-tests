Author: cquitania

/* Problem Description: Create your own store! Your store should sell one type of things, like clothing or bikes, whatever you want your store to specialize in. You should have a table for all the items in your store, and at least 5 columns for the kind of data you think you'd need to store. You should sell at least 15 items, and use select statements to order your items by price and show at least one statistic about the items.

Accessories
Clasp (5),
Beads (5),
Chains (5),
Locks (5),
Stickers (5),
Resin (5),
Clay (5),
Rings (5),
Pliers (3),
Gift Bags (10),
Gold Eyepin (10),
Silver Eyepin (10),
Stones (10),
Gems (10),
Wire (5), */

CREATE TABLE Accessories (
ProductID INTEGER,
Producttype TEXT,
Quantity INTEGER,
Price INTEGER,
MonthReceived TEXT);

INSERT INTO Accessories VALUES (111, "Clasps", 5, 15, "June");
INSERT INTO Accessories VALUES (112, "Beads", 5, 4, "May");
INSERT INTO Accessories VALUES (113, "Chains", 5, 5, "April");
INSERT INTO Accessories VALUES (114, "Locks", 5, 10, "May");
INSERT INTO Accessories VALUES (115, "Stickers", 5, 8, "April");
INSERT INTO Accessories VALUES (116, "Resin", 5, 10, "June");
INSERT INTO Accessories VALUES (117, "Clay", 5, 15, "March");
INSERT INTO Accessories VALUES (118, "Rings", 5, 3, "May");
INSERT INTO Accessories VALUES (119, "Pliers", 3, 20, "July");
INSERT INTO Accessories VALUES (110, "Gift Bags", 10, 5, "April");
INSERT INTO Accessories VALUES (111, "Gold Eyepin", 10, 2, "July");
INSERT INTO Accessories VALUES (112, "Silver Eyepin", 10, 2, "April");
INSERT INTO Accessories VALUES (113, "Stones", 10, 10, "April");
INSERT INTO Accessories VALUES (114, "Gems", 10, 5, "May");
INSERT INTO Accessories VALUES (115, "Wire", 10, 10, "June");

SELECT * FROM Accessories ORDER BY Price;

SELECT quantity, MIN(price) FROM Accessories GROUP BY quantity;

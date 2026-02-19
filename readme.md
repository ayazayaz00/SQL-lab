CREATE TABLE Client_Master (
  clientNo INTEGER(6) PRIMARY KEY,
  Name TEXT(20),
  Address1 TEXT(30),
  Address2 TEXT(30),
  city TEXT(15),
  PinCode INTEGER(8),
  state TEXT(15),
  BalDue INTEGER(10)
);

CREATE TABLE Product_Master (
  ProductNo INTEGER(6) PRIMARY KEY,
  description TEXT(15),
  profitPercent TEXT(4),
  UnitMeasure TEXT(10),
  qtyOnHand INTEGER(8),
  RecordLvl INTEGER(8),
  sellPrice INTEGER(8),
  costPrice INTEGER(8)
);

INSERT INTO Client_Master VALUES(0001, 'Ayaz', 'add1', 'add2', 'Bijnor', 246734, 'UP', 300000);
INSERT INTO Client_Master VALUES(0002, 'Zuhaib', 'add1', 'add2', 'Azamgarh', 276138, 'UP', 200000);
INSERT INTO Client_Master VALUES(0003, 'Anas', 'add1', 'add2', 'Moradabad', 134525, 'UP', 150000);
INSERT INTO Client_Master VALUES(0004, 'Zubair', 'add1', 'add2', 'Solan', 123545, 'HP', 100000);
INSERT INTO Client_Master VALUES(0005, 'Owais', 'add1', 'add2', 'delhi', 110025, 'delhi', 250000);
INSERT INTO Client_Master VALUES(0006, 'Meraj', 'add1', 'add2', 'Gorakhpur', 235674, 'UP', 280000);

SELECT * from Client_Master;

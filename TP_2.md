TP 2

```sql
CREATE TABLE planes (
id INT UNSIGNED AUTO_INCREMENT PRIMARY KEY,
name CHAR(5),
description TEXT,
numFlying DECIMAL(8,1)
) ENGINE=InnoDB ;

INSERT INTO planes(name, description, numFlying) VALUES ('A380','Gros Porteur',12000.0);
INSERT INTO planes(name, description, numFlying) VALUES ('A320','Avion de ligne quadriréacteur ',17000.0);
INSERT INTO planes(name, description, numFlying) VALUES ('A380','moyen courrier',50000.0);
```

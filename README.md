# IRON-MAN
Spark IRON MAN
CREATE TABLE db_bdpbase.Employee(id INT,firstname STRING,lastname STRING,gender STRING,designation STRING,city STRING,country STRING) 
PARTITIONED BY (year INT) 
ROW FORMAT DELIMITED
FIELDS TERMINATED BY ','
STORED AS TEXTFILE
TBLPROPERTIES("skip.header.line.count"="1");

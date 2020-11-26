# sql-sample-database

CREATE TABLE  EMPLOYEE
   (	
    AGENT_CODE CHAR(6) NOT NULL PRIMARY KEY, 
	AGENT_NAME CHAR(40), 
	WORKING_AREA CHAR(35),  
	Salary INT, 
	COUNTRY VARCHAR(25) 
	 );
   
   
   INSERT INTO EMPLOYEE VALUES ('A007', 'Roshan', 'Bangalore', 120987, 'india');
INSERT INTO EMPLOYEE VALUES ('A003', 'Amit ', 'London', 98761,  'Britain');
INSERT INTO EMPLOYEE VALUES ('A008', 'priya', 'New York', 12345, 'Britain');
INSERT INTO EMPLOYEE VALUES ('A011', 'gayaan', 'Bangalore', 10987, 'India');
INSERT INTO EMPLOYEE VALUES ('A010', 'Sankalp', 'Chennai', 12390, 'India');
INSERT INTO EMPLOYEE VALUES ('A012', 'roshani', 'San Jose', 123450, 'USA');
INSERT INTO EMPLOYEE VALUES ('A005', 'Ali', 'Brisban', 12309, 'USA');
INSERT INTO EMPLOYEE VALUES ('A001', 'Subh', 'Bangalore', 34590, 'India');
INSERT INTO EMPLOYEE VALUES ('A002', 'Mukesh', 'Mumbai', 12345, 'India');
INSERT INTO EMPLOYEE VALUES ('A006', 'Manisha', 'London', 30012, 'Britain');
INSERT INTO EMPLOYEE VALUES ('A004', 'Ishika', 'Torento', 20000, 'Canada');
INSERT INTO EMPLOYEE VALUES ('A009', 'somnath', 'Hampshair', 10000,'Mexico');

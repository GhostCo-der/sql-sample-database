# sql-sample-database

CREATE TABLE  AGENTS
   (	
    AGENT_CODE CHAR(6) NOT NULL PRIMARY KEY, 
	AGENT_NAME CHAR(40), 
	WORKING_AREA CHAR(35),  
	PHONE_NO CHAR(15), 
	COUNTRY VARCHAR2(25) 
	 );
   
   
   INSERT INTO AGENTS VALUES ('A007', 'Roshan', 'Bangalore', '0.15', '');
INSERT INTO AGENTS VALUES ('A003', 'Amit ', 'London', '0.13',  '');
INSERT INTO AGENTS VALUES ('A008', 'priya', 'New York', '0.12', '');
INSERT INTO AGENTS VALUES ('A011', 'gayaan', 'Bangalore', '0.15', '');
INSERT INTO AGENTS VALUES ('A010', 'Sankalp', 'Chennai', '0.14', '');
INSERT INTO AGENTS VALUES ('A012', 'roshani', 'San Jose', '0.12', '');
INSERT INTO AGENTS VALUES ('A005', 'Ali', 'Brisban', '0.13', '');
INSERT INTO AGENTS VALUES ('A001', 'Subh', 'Bangalore', '0.14', '');
INSERT INTO AGENTS VALUES ('A002', 'Mukesh', 'Mumbai', '0.11', '');
INSERT INTO AGENTS VALUES ('A006', 'Manisha', 'London', '0.15', '');
INSERT INTO AGENTS VALUES ('A004', 'Ishika', 'Torento', '0.15', '');
INSERT INTO AGENTS VALUES ('A009', 'somnath', 'Hampshair', '0.11','');

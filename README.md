# Fall Detection with accelerometer and barometer

### This project is conducted in order to fulfill the course Smart Sensor Network Systems at the University of Applied Sciences.

### In order to run this application, please following instructions:
1. Download and install Java SE 1.8

2. Download and run InfluxDB database program

3. Depends on the number of Launchpad connecting to PC, create same number of database and users in InfluxDB. For example, if there are 2 Launchpad, in the influx database sql command line (terminal), type commands as following:
> CREATE USER "ssns0" WITH PASSWORD 'ssns'

> CREATE DATABASE "ssns0"

> GRANT ALL ON ssns0 TO ssns0

> CREATE USER "ssns1" WITH PASSWORD

> CREATE DATABASE "ssns1"

> GRANT ALL ON ssns1 TO ssns1

If you have 3 launchpads, then just create database and user with number 2, and so on.

4. Inside the "lib" folder, there are libraries that are required, remember to add them to IDE if you want to change or develop more with source code.

#### 5. Before running the application, please remember to construct database as above, and the database must be always running.

6. You can run the application with 2 ways:

    a. Download source code, compile, and run with IDE.

    b. Download only the folder "**RUN**", run the *run.sh* file or *run.bat* depending on your OS.
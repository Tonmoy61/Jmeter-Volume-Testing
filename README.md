# Jmeter-Volume-Testing
The steps taken to construct this project:
### JDBC connection is configured by connecting a specific Database where there is pre-existing datas.
### JDBC driver class "com.mysql.jdbc.Driver" is configured.
### mysql-connector-java is put in the lib folder of apache-jmeter.

## Database is tested by **100 users** concurrently reading info in **60s**.
![100 users reading info in 60 s](https://github.com/Tonmoy61/Jmeter-Volume-Testing/blob/main/image/image1.png)
There is an rate of **0%**.


## The users are increased more and local database is tested for **300 users** reading info in **60s**.
![300 users reading info in 60 s with fail rate of 49 67%](https://github.com/Tonmoy61/Jmeter-Volume-Testing/blob/main/image/image2.png)
There is an error rate of **50%**.


## Database is tested by **180 users** concurrently reading info in **60s**.
![100 users reading info in 60 s](https://github.com/Tonmoy61/Jmeter-Volume-Testing/blob/main/image/image3.png)
There is an error rate of **16.67%**.



# Big-data-analysis-on-flight-details-using-Revolutionary-R-open

Aim  -->  Performing data analysis to find the speed of the airplane with respect to the departure delay

The MainFile contains the R code for data analysis

The FileDetails.docx file contains all the analysis with functions mentioned at the top

Note - to Run the code we need to install Revolutionary R open 3.2.2 and Revolutionary R Enterprise 7.5.0

Tool used --> Revolutionary R Enterprise with Revolutionary R open which is free open source, uses R program enviornment
Revolution R Enterprise is the fastest, most cost effective, enterprise-class, big data big analytics software
With high-performance advanced analytics, Revolution R Enterprise unlocks the insight hidden in Big Data across complex
and diverse data infrastructures, including Hadoop, clusters and grids, and Enterprise Data Warehouses.
library used is RevoScaleR

data set used
2007.csv
link-->http://stat-computing.org/dataexpo/2007/the-data.html

File name: C:\Users\Chinmay\Desktop\KaggleProjects\GroupoBimbo\2007.xdf 
Number of observations(Rows): 7453215 
Number of variables(columns): 29 
Number of blocks: 15 
Compression type: zlib 
Variable information: 
Var 1: Year, Type: integer, Low/High: (2007, 2007)
Var 2: Month, Type: integer, Low/High: (1, 12)
Var 3: DayofMonth, Type: integer, Low/High: (1, 31)
Var 4: DayOfWeek, Type: integer, Low/High: (1, 7)
Var 5: DepTime, Type: integer, Low/High: (1, 2400)
Var 6: CRSDepTime, Type: integer, Low/High: (0, 2359)
Var 7: ArrTime, Type: integer, Low/High: (1, 2400)
Var 8: CRSArrTime, Type: integer, Low/High: (0, 2400)
Var 9: UniqueCarrier, Type: character
Var 10: FlightNum, Type: integer, Low/High: (1, 9602)
Var 11: TailNum, Type: character
Var 12: ActualElapsedTime, Type: integer, Low/High: (12, 1270)
Var 13: CRSElapsedTime, Type: integer, Low/High: (-1240, 1430)
Var 14: AirTime, Type: integer, Low/High: (0, 1257)
Var 15: ArrDelay, Type: integer, Low/High: (-312, 2598)
Var 16: DepDelay, Type: integer, Low/High: (-305, 2601)
Var 17: Origin, Type: character
Var 18: Dest, Type: character
Var 19: Distance, Type: integer, Low/High: (11, 4962)
Var 20: TaxiIn, Type: integer, Low/High: (0, 545)
Var 21: TaxiOut, Type: integer, Low/High: (0, 530)
Var 22: Cancelled, Type: integer, Low/High: (0, 1)
Var 23: CancellationCode, Type: character
Var 24: Diverted, Type: integer, Low/High: (0, 1)
Var 25: CarrierDelay, Type: integer, Low/High: (0, 2580)
Var 26: WeatherDelay, Type: integer, Low/High: (0, 1429)
Var 27: NASDelay, Type: integer, Low/High: (0, 1386)
Var 28: SecurityDelay, Type: integer, Low/High: (0, 382)
Var 29: LateAircraftDelay, Type: integer, Low/High: (0, 1031)

#######################################################################################################################################




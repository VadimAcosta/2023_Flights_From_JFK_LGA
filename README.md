#### Bureau of Transportation Statistics (BTS) Combined 2023 data for all flights from LGA and JFK  

This repository contains the concatenated (UNION if SQL is your jam) BTS data from January 2023 to December 2023.
To be made more managable some of the parameters available for download at the BTS website have been excluded. 
This dataset contains the following Columns:  
 
 #   Column                    Non-Null Count   Dtype    
---  ------                    --------------   -----     
 0   DayOfWeek                 296774 non-null  int64   
 1   FlightDate                296774 non-null  object   
 2   Reporting_Airline         296774 non-null  object   
 3   Origin                    296774 non-null  object   
 4   OriginCityName            296774 non-null  object   
 5   OriginState               296774 non-null  object   
 6   OriginStateName           296774 non-null  object   
 7   Dest                      296774 non-null  object   
 8   DestCityName              296774 non-null  object   
 9   DestState                 296774 non-null  object   
 10  DestStateName             296774 non-null  object   
 11  CRSDepTime                296774 non-null  int64    
 12  DepTime                   289669 non-null  float64  
 13  DepDelay                  289669 non-null  float64  
 14  DepDel15                  289669 non-null  float64  
 15  TaxiOut                   289250 non-null  float64  
 16  WheelsOff                 289250 non-null  float64  
 17  WheelsOn                  289186 non-null  float64  
 18  TaxiIn                    289186 non-null  float64  
 19  CRSArrTime                296774 non-null  int64    
 20  ArrTime                   289186 non-null  float64  
 21  ArrDelay                  288420 non-null  float64  
 22  ArrDel15                  288420 non-null  float64  
 23  Cancelled                 296774 non-null  int64    
 24  Diverted                  296774 non-null  int64    
 25  CRSElapsedTime            296774 non-null  int64    
 26  ActualElapsedTime         288420 non-null  float64  
 27  AirTime                   288420 non-null  float64  
 28  Distance                  296774 non-null  int64    
 29  CarrierDelay              59184 non-null   float64  
 30  WeatherDelay              59184 non-null   float64  
 31  NASDelay                  59184 non-null   float64  
 32  SecurityDelay             59184 non-null   float64  
 33  LateAircraftDelay         59184 non-null   float64  

 For ease of use and dashboarding I've added the following columns:   
 
 34  Origin Latitude           296774 non-null  float64  
 35  Origin Longitude          296774 non-null  float64  
 36  Destination Latitude      296774 non-null  float64  
 37  Destination Longitude     296774 non-null  float64  
 38  Reporting_Airline_Name    296774 non-null  object   
 39  Origin_Airport_Name       296774 non-null  object   
 40  Destination_Airport_Name  296774 non-null  object   
 41  DayOfWeekName             296774 non-null  object    
 42  CarrierDelayBool          296774 non-null  int64   
 43  WeatherDelayBool          296774 non-null  int64    
 44  NASDelayBool              296774 non-null  int64   
 45  SecurityDelayBool         296774 non-null  int64   
 46  LateAircraftDelayBool     296774 non-null  int64   

For more information on the measurements and codes used in the data or to check the data at the source [click here for the BTS portal!](https://www.transtats.bts.gov/DL_SelectFields.aspx?gnoyr_VQ=FGJ&QO_fu146_anzr=b0-gvzr)

#### Happy Dashboarding!

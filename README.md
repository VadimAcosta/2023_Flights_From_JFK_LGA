#### Bureau of Transportation Statistics (BTS) Combined 2023 data for all flights from LGA and JFK  

This repository contains the concatenated (UNION if SQL is your jam) BTS data from January 2023 to December 2023.
To be made more managable some of the parameters available for download at the BTS website have been excluded. 
This dataset contains the following Columns:  
 
 Num  Column                        
 0   DayOfWeek                       
 1   FlightDate                      
 2   Reporting_Airline               
 3   Origin                          
 4   OriginCityName                  
 5   OriginState                     
 6   OriginStateName                 
 7   Dest                            
 8   DestCityName                    
 9   DestState                       
 10  DestStateName                   
 11  CRSDepTime                       
 12  DepTime                        
 13  DepDelay                       
 14  DepDel15                       
 15  TaxiOut                        
 16  WheelsOff                      
 17  WheelsOn                       
 18  TaxiIn                         
 19  CRSArrTime                       
 20  ArrTime                        
 21  ArrDelay                       
 22  ArrDel15                       
 23  Cancelled                        
 24  Diverted                         
 25  CRSElapsedTime                   
 26  ActualElapsedTime              
 27  AirTime                        
 28  Distance                         
 29  CarrierDelay                    
 30  WeatherDelay                    
 31  NASDelay                        
 32  SecurityDelay                   
 33  LateAircraftDelay               

 For ease of use and dashboarding I've added the following columns:   
 
 34  Origin Latitude                
 35  Origin Longitude               
 36  Destination Latitude           
 37  Destination Longitude          
 38  Reporting_Airline_Name          
 39  Origin_Airport_Name             
 40  Destination_Airport_Name        
 41  DayOfWeekName                    
 42  CarrierDelayBool                
 43  WeatherDelayBool                 
 44  NASDelayBool                    
 45  SecurityDelayBool               
 46  LateAircraftDelayBool           

For more information on the measurements and codes used in the data or to check the data at the source [click here for the BTS portal!](https://www.transtats.bts.gov/DL_SelectFields.aspx?gnoyr_VQ=FGJ&QO_fu146_anzr=b0-gvzr)

#### Happy Dashboarding!

# Storm Overflow Activity  

| ATTRIBUTE               | DATA TYPE         | DESCRIPTION                                                                  |
| :---                    |    :----          |      :----                                                                   |   
| Id                      | String            | Identity of the site                                                         |
| Company                 | String            | Waste water company responsible for the site                                 |
| Status                  | Integer           | The current status of the monitor                                            |
| StatusStart             | datetime UTC      | The date and time that the monitor’s current status started                  |
| LatestEventStart        | datetime UTC      | The date and time that the latest indicative discharge event started.        | 
| LatestEventEnd          | datetime UTC      | The date and time that the latest indicative discharge event ended.          |
| Latitude                | Double            | Point data for the outfall location.                                         |
| Longitude               | Double            | Point data for the outfall location.                                         |
| ReceivingWaterCourse    | String            | The name of the water course into which an outfall is designed to discharge. |
| LastUpdated             | datetime UTC      | The date and time the above fields were last updated.                        |






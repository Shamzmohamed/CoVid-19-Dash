# CoVid-19-Visualization
In this project we have used python for the data analysis and visualization of COVID-19 data globally. Also we used the dash library for the Dashboard representation of COVID-19.


### Data Source : 

The data utilised is the result of particular data treatment for the task at hand, which is included in three .csv files :- countries-aggregrated.csv, reference.csv and worldwide-aggregrate.csv. These data can be checked here: [`Covid Datasets`](https://github.com/datasets/covid-19/tree/main/data).

### Data Description :

### `countries-aggregrated.csv`

|Variable                 |Dtype   |Description |
|:---|:---|:-----------|
|Date                     |object  | Date|
|Country                  |object  | Countries in the world|
|Confirmed                |integer |Confirmed Covid cases|
|Recovered                |integer |Recovered from Covid|
|Deaths                   |integer |Death due to Covid |

### `reference.csv`

|Variable               |Dtype   |Description |
|:---|:---|:-----------|
|UID                    |integer| Unique ID|
|iso2                   |object | Code of global region and countries|
|iso3                   |object | Country Code|
|code3                  |float  | Region code|
|FIPS                   |float  | 5-digit Federal Information Processing Standard|
|Admin2                 |object | County|
|Province_State         |object | State in the Country|
|Country_Region         |object | Countries in the world|
|Lat                    |float  | Latitude|
|Long                   |float  | Longitude|
|Combined_Key           |object | Country|
|Population             |float  | Population in the country |


### `worldwide-aggregrate.csv`

|Variable               |Dtype   |Description |
|:---|:---|:-----------|
|Date                     |object  | Date|
|Confirmed                |integer |Confirmed Covid cases|
|Recovered                |integer |Recovered from Covid|
|Deaths                   |integer |Death due to Covid |
|Increase rate            |integer |Covid spread rate|

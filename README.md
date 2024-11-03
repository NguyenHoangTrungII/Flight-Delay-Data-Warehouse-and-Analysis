# Flight-Delay-Data-Warehouse-and-Analysis
[![](https://img.shields.io/badge/Facebook-nguyenhoangtrung-blue)](https://www.facebook.com/nguyenhoangtrunghhh/)
[![](https://img.shields.io/badge/Gmail-nguyenhoangtrunghs%40gmail.com-red)](mailto:nguyenhoangtrunghs@gmail.com)


## Documentation

* [About Dataset](#dataset)
* [Architecture](#architecture)
* [Main Workflow](#mainWorkflow)
	- [SISS](#siss)
	- [SASS](#sass)
 * [Achievement](#achievement)

## Dataset
The 2022 US Airlines Domestic Departure Data dataset is sourced from Kaggle.com. This dataset provides comprehensive information on U.S. domestic flight departures, combining flight data with airport, aircraft, and weather information from the first two months of 2022.

The dataset contains 1,048,575 rows and 59 attributes.
Source link: [2022 US Airlines Domestic Departure Data | Kaggle](https://www.kaggle.com/datasets/jl8771/2022-us-airlines-domestic-departure-data?select=CompleteData.csv&fbclid=IwAR2Kl3cQb0GatNOYQTaJ3oDdQUzPTkvETTi6h5QEtt3jN8bgsHEvt2VtwEc)

## Architecture
### Dimensional schemas
![image](https://github.com/user-attachments/assets/dbf72a87-fcaa-4064-9bfc-4aee713ba16c)

## Main Workflow
### SISS
#### Overview

#### Data Filtering and Cleaning Process
![image](https://github.com/user-attachments/assets/8bd67b0f-ec73-4da4-9e81-4f7e70302ddf)

![image](https://github.com/user-attachments/assets/86bc2de9-72a1-4f04-91e5-dc43b4095ef2)

#### Creating Dim and Fact Tables
Dim_Carrier
![image](https://github.com/user-attachments/assets/f23557db-d246-4f46-904a-3132ee6c1193)

Dim_ActiveWeather
![image](https://github.com/user-attachments/assets/f017f8f1-9863-4aa1-a3fa-ac4521b8b7de)

Dim_Cancalation
![image](https://github.com/user-attachments/assets/6d5deb5f-ba7c-446b-a02c-59c97dcee200)

Dim_Station
![image](https://github.com/user-attachments/assets/36085a21-b2d2-4107-a8f2-d69d74550644)

Dim_FLDate
![image](https://github.com/user-attachments/assets/9e766111-068b-4e6a-ac96-57b1328b8601)

Dim_OP_Carrier
![image](https://github.com/user-attachments/assets/0b3a7b2a-fcd8-4ce2-b0d2-a9a8a7198e5e)

Dim_MKT_Carrier
![image](https://github.com/user-attachments/assets/f480ba4a-cf7c-44b1-afe7-a5e497ffa71e)

Dim_StationLocation
![image](https://github.com/user-attachments/assets/89289035-8cdd-4c47-9bcf-7374a050a3e2)

Fact
![image](https://github.com/user-attachments/assets/621511d2-82e4-4ab1-9759-18439956dc0c)

#### Creating Foreign Keys and Primary Keys
![image](https://github.com/user-attachments/assets/7046be16-b2b5-4aa5-aa58-a5b8b83ae9b9)
![image](https://github.com/user-attachments/assets/9b076d65-a043-484c-b257-3da4ba1a1d84)

### SASS
#### Overview
![image](https://github.com/user-attachments/assets/16b4847d-ba47-488b-bb96-b56d495c1220)


#### Defining the Cube and Creating New Measures

![image](https://github.com/user-attachments/assets/2fd24100-9c76-4d67-8d88-6817b0edc141)

## Achievement 
In this project, I effectively utilized SSAS, Excel Pivot tools, and MDX language to analyze airline performance data for 2022. I identified flight cancellations due to adverse weather for each airline and compiled a report categorizing these cancellations by reason. My analysis also tracked monthly flight volumes, revealing trends and peak travel periods. I pinpointed the top 10 airports with the highest number of departing flights and determined popular flight routes. This comprehensive data evaluation allowed me to recommend improvements for operational efficiency and customer satisfaction, empowering stakeholders to make informed decisions.

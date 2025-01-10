# GJI-24-0467
Synthetic data

Data Description

This dataset contains synthetic test data used in the article. The data is organized into two folders:
LMSFZ: Contains synthetic test data related to the LMSFZ region.
Parkfield: Contains synthetic test data related to the Parkfield region.
Each folder includes the following four files:

File Descriptions

absolute.dat
Contains absolute measurement data.
Specific Format:
# event_id
station_name  arrivel_time  quality  phase_type

dt.ct
Contains differential time data.
Specific Format:
# event1_id event2_id
station_name  arrivel_time1 arrivel_time2 quality  phase_type

event.dat
Contains event data.
Specific Format:
event_name latitude longitude depth(km)

station.dat
Contains station data.
Specific Format:
station_name latitude longitude depth(m)

File Structure

/data
│
├── LMSFZ
│   ├── VelocityInversion
│   │   ├── absolute.dat
│   │   ├── dt.ct
│   │   ├── event.dat
│   │   ├── station.dat
│   │
│   ├── EventRelocation
│       ├── absolute.dat
│       ├── dt.ct
│       ├── event.dat
│       ├── station.dat
│
└── Parkfield
    ├── absolute.dat
    ├── dt.ct
    ├── event.dat
    ├── station.dat

Purpose of the Data

This dataset is used for the synthetic tests described in the article, aiming to validate the performance of the models and methods. Details on the testing procedures and usage can be found in the main text and appendix of the article.

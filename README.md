# Glava Data-Set

This repository contains a demo version of weather and PV-Station information from the Glava Energy Center (https://www.glavaenergycenter.se/). This data-set contains information of four weather features for two months. 

If you use this data-set for any publicity or project, please also cite the following paper: [[1]](#1)

## Information on the PV Panels

The PV panels are oriented to the south with a 40 degree inclination. The PV modules are comprised of 20xITS 200Wp + 20xITS 210Wp + 20xITS 210Wp + 19xITS 220Wp at a total PV Power of 16.580Wp (Watt-peak) using 4xEltek Valere 4300W inverter.


## Information on the complete data-set

The complete data-set contains eleven weather features and three PV-Station parameters, which are described as follows:
  
| Feature | Description |
| --- | --- |
| Timestamp | Datetime |
| Wind Direction | Gradient |
| Precipitation | L/m<sup>2</sup>|
| Temperature | C |
| Humidity | Percentage |
| Barometric Pressure | mBar |
| Wind Speed | m/s |
| Global Radiation | W/m<sup>2</sup> |
| Radiation 30 Degrees | W/m<sup>2</sup> |
| Radiation 40 Degrees | W/m<sup>2</sup> |
| Indirect Radiation | W/m<sup>2</sup> |
| Produced Energy| kW |
  
The Produced Energy describes the total energy produced by the system. This includes the two variables Ptot and Qtot. Ptot describes the amount of power, which is usable for the end-user of the system. This energy can be directly converted to practical energy for i.e., energy outlets. Qtot describes the power, which is only available for the system itself and is used to keep the system itself usable. Stot (Energy Produced) describes the total power in the system itself.

The complete data-set contains 5 years of weather and PV-Station information (January 2015 to December 2019), which were measured on-site in Arvika, Sweden in an interval of six seconds. In addition to this data-set, which represents one PV-Station, the Glava Energy Center also measured information from two additional stations. It is furthermore possible to receive current information via a fast API. 



## Information on the demo data-set

The four weather types and the produced energy, presented in the public demo are as follows: 

| Feature | Description |
| --- | --- |
| Timestamp | Datetime |
| Indirect Radiation | W/m<sup>2</sup> |
| Precipitation | L/m<sup>2</sup>|
| Temperature | C |
| Humidity | Percentage |
| Produced Energy | kW |


The data-set is available as a JSON or Pickel format. The Timestamp is the key value in those dataformats, while the other features are the corresponding values to it. The demo data-set contains information from the 01.06.2017 - 31.08.2017.



## Contacts:

If you want to have more information on the data-set or on how to retrieve full access to the data, please feel free to contact us

| Name | E-Mail |
| --- | --- |
| Magnus Nilsson | magnus.nilsson@arvika.se |
| Phil Aupke | phil.aupke@kau.se |
| Andreas Kassler | andreas.kassler@kau.se |
| Andreas Theocharis | andreas.theocharis@kau.se |


## References: 

<a id="1">[1]</a> 
Phil Aupke, Andreas Kassler, Andreas Theocharis et. al.:  
Quantifying Uncertainty for Predicting Renewable Energy Time Series Data using Machine Learning.<br />
Eng. Proc. 2021, 5(1), 50; https://doi.org/10.3390/engproc2021005050





# Monitoring data: shallow-mesophotic

Repository for longitudinal shallow/mesophotic monitoring data. Currently only contains temperature data, but benthic monitoring data will be added in the near future. If you are interested in using any of these data in a study, please cite the corresponding publications and/or the url of this repository (https://github.com/pimbongaerts/monitoring). A short email describing the intended use is always appreciated (pbongaerts@calacademy.org).

*Funding acknowledgements:* (in alphabetical order) Australian Research Council, California Academy of Sciences, Global Change Institute, Joy Foundation, The Explorers Club, Waitt Foundation, XL Catlin Group

## Datasets by publication

|  | Reference                                                    | Dataset                                                      |
| ------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| ![](screenshot2.png) | Frade PR, Bongaerts P, Englebert N, Rogers A, Gonzalez-Rivero M and Hoegh-Guldberg O (2018) [Deep reefs of the Great Barrier Reef offer limited thermal refuge during mass coral bleaching](https://dx.doi.org/10.1038/s41467-018-05741-0)  *Nature Communications* 9:3447 | [temperature csv](https://github.com/pimbongaerts/monitoring/blob/master/datasets_by_publication/2018_naturecomms.csv) |
| ![](screenshot1.png) | Bongaerts P, Frade PR, Hay KB, Englebert N, Latijnhouwers KRW, Bak RPM, Vermeij MJA, Hoegh-Guldberg O (2015) [Deep down on a Caribbean reef: lower mesophotic depths harbor a specialized coral-endosymbiont community]( https://doi.org/10.1038/srep07652) *Scientific Reports* (2015) 5:7652 | (coming soon)                                                |


## Temperature datasets by location

| Region | Location                | Coords               | Period                                                       | Depths (m)*                  | Dataset |
| ------ | ----------------------- | -------------------- | ------------------------------------------------------------ | ---------------------------- | ---------------------------- |
| GBR    | Great Detached*         | S11.70450 E144.06817 | 2012-2017| 10, 40 (,60, 80,100)         |[csv](https://github.com/pimbongaerts/monitoring/blob/master/datasets_by_location/gbr_grdet.csv) |
| GBR    | Tijou*                  | S13.06435 E143.95081 | 2012-2017| 10, 40 (,60, 80,100)         |[csv](https://github.com/pimbongaerts/monitoring/blob/master/datasets_by_location/gbr_tijou.csv) |
| GBR    | Yonge*                  | S14.61609 E145.63702 | 2012-2017| 10, 40 (,60, 80,100)         |[csv](https://github.com/pimbongaerts/monitoring/blob/master/datasets_by_location/gbr_yonge.csv) |
| WCS    | Osprey "Dutch Towers"*  | S13.82032 E146.56122 | 2012-2017|10, 40, 60***| [csv](https://github.com/pimbongaerts/monitoring/blob/master/datasets_by_location/wcs_ospdt.csv) |
| WCS    | Osprey "Bigeye Ledge"*  | S13.82032 E146.56122 | 2012-2017| 10, 40, 60*** | [csv](https://github.com/pimbongaerts/monitoring/blob/master/datasets_by_location/wcs_ospbl.csv) |
| WCS    | Osprey "Nautilus Wall"* | S13.88925 E146.55503 | 2012-2017|10, 40, 60***| [csv](https://github.com/pimbongaerts/monitoring/blob/master/datasets_by_location/wcs_ospnw.csv) |
| WCS    | Bougainville 1*         |                      | (2017-)                                                      | 10, 40                       | |
| WCS    | Bougainville 2*         |                      | (2017-)                                                      | 10, 40                       | |
| WCS    | Holmes Reef             | S16.48211 E147.87111 | 2012-2017| 10, 40 (,60)                 |[csv](https://github.com/pimbongaerts/monitoring/blob/master/datasets_by_location/wcs_holme.csv) |
| CUR    | Curacao Seaquarium      | N12.08445 W68.89833  | 2013-2014                                 | 10, 25, 40, 60, 80, 100, 120 | (coming soon) |

GBR = Great Barrier Reef, WCS = Western Coral Sea, CUR = Curacao

\* Temperature monitoring still ongoing at these locations

\** Temperatures from depths in brackets were only recorded for a subset of the indicated time period

\*** Temperature loggers from 80 and 100m not yet recovered (contact me for detailed location description)

## Data format (temperature)

| Fields                                | Description                                 |
| ------------------------------------- | ------------------------------------------- |
| `Date`                                | date in `dd/mm/yy` format                   |
| `Date_day`, `Date_month`, `Date_year` | date broken up in separate fields           |
| `Hour_in_year`                        | hour in year (from 1 up to 24 x 365 = 8760) |
| `LOCAT_10m`,`LOCAT_40m`, etc.         | raw temperature data in degrees Celsius     |
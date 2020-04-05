# Death rates of COVID-19 in the US by age
 
## Motivation
Most publicly-disseminated information regarding COVID-19 has been [epidemiological](https://gisanddata.maps.arcgis.com/apps/opsdashboard/index.html#/bda7594740fd40299423467b48e9ecf6) and not very useful for individual-risk prediction. It is currently difficult to derive death rates by demographics from [aggregated CDC data](https://www.cdc.gov/nchs/nvss/vsrr/COVID19/index.htm).  The goal of this project was to track how closely US death-rate-by-age data has aligned with the (thus-far) canonical [WHO and Chinese CCDC reports from Feb 2020](https://www.worldometers.info/coronavirus/coronavirus-age-sex-demographics/).

## Data
This data is a cumulative snapshot as of 4/5/2020. 
Cases with unknown ages were removed. 
Many states (such as MA, CA, etc.) do not report this death data by age.

### Florida
|  Age | Case Count | Death Count | Death Rate |
| :--- | --- | --- | --- |
|  0-24 | 793 | 0 | 0.0% |
|  25-34 | 1445 | 2 | 0.1% |
|  35-44 | 1422 | 4 | 0.3% |
|  45-54 | 1689 | 4 | 0.2% |
|  55-64 | 1608 | 14 | 0.9% |
|  65-74 | 1293 | 42 | 3.2% |
|  75-84 | 723 | 52 | 7.2% |
|  85+ | 266 | 45 | 16.9% |
|  Total | 9239 | 163 | 1.8% |

### Georgia
|  Age | Case Count | Death Count | Death Rate |
| :--- | --- | --- | --- |
|  0-17 | 66 | 0 | 0.0% |
|  18-59 | 3922 | 42 | 1.1% |
|  60+ | 2393 | 173 | 7.2% |
|  Total | 6381 | 215 | 3.4% |

### Michigan
|  Age | Case Count | Death Count | Death Rate |
| :--- | --- | --- | --- |
|  0-19 | 142 | 0 | 0.0% |
|  20-19 | 1280 | 5 | 0.4% |
|  30-39 | 1849 | 11 | 0.6% |
|  40-49 | 2418 | 32 | 1.3% |
|  50-59 | 2845 | 65 | 2.3% |
|  60-69 | 2561 | 108 | 4.2% |
|  70-79 | 1849 | 135 | 7.3% |
|  80+ | 1138 | 184 | 16.1% |
|  Total | 14225 | 540 | 3.8% |

### New York City
|  Age | Case Count | Death Count | Death Rate |
| :--- | --- | --- | --- |
|  0-17 | 928 | 1 | 0.1% |
|  18-44 | 10580 | 30 | 0.3% |
|  45-64 | 15669 | 197 | 1.3% |
|  65-74 | 16428 | 603 | 3.7% |
|  75+ | 17245 | 1423 | 8.3% |
|  Total | 60850 | 2254 | 3.7% |

### Ohio
|  Age | Case Count | Death Count | Death Rate |
| :--- | --- | --- | --- |
|  0-19 | 60 | 0 | 0.0% |
|  20-29 | 310 | 0 | 0.0% |
|  30-39 | 330 | 0 | 0.0% |
|  40-49 | 381 | 1 | 0.3% |
|  50-59 | 461 | 8 | 1.7% |
|  60-69 | 467 | 19 | 4.1% |
|  70-79 | 317 | 26 | 8.2% |
|  80+ | 216 | 41 | 19.0% |
|  Total | 2548 | 95 | 3.7% |

### Oregon
|  Age | Case Count | Death Count | Death Rate |
| :--- | --- | --- | --- |
|  0-19 | 23 | 0 | 0.0% |
|  20-29 | 101 | 0 | 0.0% |
|  30-39 | 145 | 0 | 0.0% |
|  40-49 | 183 | 0 | 0.0% |
|  50-59 | 191 | 1 | 0.5% |
|  60-69 | 182 | 6 | 3.3% |
|  70-79 | 103 | 8 | 7.8% |
|  80+ | 70 | 11 | 15.7% |
|  Total | 998 | 26 | 2.6% |

### Washington* 
|  Age | Case Count | Death Count | Death Rate |
| :--- | --- | --- | --- |
|  0-19 | 152 | 0 | 0.0% |
|  20-39 | 2050 | 3 | 0.2% |
|  40-59 | 2581 | 22 | 0.8% |
|  60-79 | 1974 | 118 | 6.0% |
|  80+ | 759 | 171 | 22.5% |
|  Total | 7591 | 310 | 4.1% |

### China February Data (for comparison)
|  Age | Death Rate |
| :--- | --- |
|  10-19 | 0.0% |
|  20-29 | 0.2% |
|  30-39 | 0.2% |
|  40-49 | 0.4% |
|  50-59 | 1.3% |
|  60-69 | 3.6% |
|  70-79 | 8.0% |
|  80+ | 14.8% |

### Sources
[Florida](https://floridadisaster.org/globalassets/covid19/dailies/covid-19-data---daily-report-2020-04-03-0955.pdf)

[Georgia](https://dph.georgia.gov/covid-19-daily-status-report)

[Michigan](https://www.michigan.gov/coronavirus/0,9753,7-406-98163_98173---,00.html)

[New York City](https://github.com/nychealth/coronavirus-data/blob/master/by-age.csv)

[Ohio](https://coronavirus.ohio.gov/wps/portal/gov/covid-19/home/dashboard)

[Oregon](https://govstatus.egov.com/OR-OHA-COVID-19)

[Washington](https://www.doh.wa.gov/Emergencies/Coronavirus)

[China](https://www.worldometers.info/coronavirus/coronavirus-age-sex-demographics/)

#### Contact
www.brendantodaro.com

https://www.linkedin.com/in/brendantodaro/

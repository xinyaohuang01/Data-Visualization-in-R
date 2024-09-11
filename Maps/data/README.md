## Storm Events Dataset

### Overview

The dataset provides information on storm events and significant weather phenomena in the United States for the years 2010 to 2023. The data is organized in a CSV file with the following columns:

### Columns:

1. **BEGIN_YEARMONTH:** The year and month when the event began in YYYYMM format.
2. **BEGIN_DAY:** The day of the month when the event began in DD format.
3. **BEGIN_TIME:** The time of day when the event began in hhmm format.
4. **END_YEARMONTH:** The year and month when the event ended in YYYYMM format.
5. **END_DAY:** The day of the month when the event ended in DD format.
6. **END_TIME:** The time of day when the event ended in hhmm format.
7. **EPISODE_ID:** ID assigned by NWS to denote the storm episode; episodes may contain multiple events.
8. **EVENT_ID:** ID assigned by NWS for each individual storm event contained within a storm episode.
9. **STATE:** The state name where the event occurred, spelled out in ALL CAPS.
10. **STATE_FIPS:** A unique number (State Federal Information Processing Standard) assigned to the state.
11. **YEAR:** The four-digit year for the event in this record.
12. **MONTH_NAME:** The name of the month for the event, spelled out.
13. **EVENT_TYPE:** The type of meteorological event leading to fatalities, injuries, damage, etc.
14. **CZ_TYPE:** Indicates whether the event happened in a (C) County/Parish, (Z) NWS Public Forecast Zone, or (M) Marine.
15. **CZ_FIPS:** The county FIPS number or NWS Forecast Zone Number.
16. **CZ_NAME:** County/Parish, Zone, or Marine Name assigned to the county FIPS number or NWS Forecast Zone.
17. **WFO:** The National Weather Service Forecast Office’s area of responsibility.
18. **BEGIN_DATE_TIME:** The date and time when the event began in MM/DD/YYYY hh:mm:ss format.
19. **CZ_TIMEZONE:** Time zone for the County/Parish, Zone, or Marine Name.
20. **END_DATE_TIME:** The date and time when the event ended in MM/DD/YYYY hh:mm:ss format.
21. **INJURIES_DIRECT:** The number of injuries directly caused by the weather event.
22. **INJURIES_INDIRECT:** The number of injuries indirectly caused by the weather event.
23. **DEATHS_DIRECT:** The number of deaths directly caused by the weather event.
24. **DEATHS_INDIRECT:** The number of deaths indirectly caused by the weather event.
25. **DAMAGE_PROPERTY:** The estimated amount of damage to property incurred by the weather event.
26. **DAMAGE_CROPS:** The estimated amount of damage to crops incurred by the weather event.
27. **SOURCE:** The source reporting the weather event.
28. **MAGNITUDE:** The measured extent of the magnitude type, used for wind speeds and hail size.
29. **MAGNITUDE_TYPE:** Describes the type of magnitude measurement.
30. **FLOOD_CAUSE:** Reported or estimated cause of the flood.
31. **CATEGORY:** Unknown (information not available).
32. **TOR_F_SCALE:** Enhanced Fujita Scale describing the strength of the tornado.
33. **TOR_LENGTH:** Length of the tornado or tornado segment while on the ground.
34. **TOR_WIDTH:** Width of the tornado or tornado segment while on the ground.
35. **TOR_OTHER_WFO:** Indicates the continuation of a tornado segment as it crossed from one National Weather Service Forecast Office to another.
36. **TOR_OTHER_CZ_STATE:** The state name of the continuing tornado segment as it crossed from one county or zone to another.
37. **TOR_OTHER_CZ_FIPS:** The FIPS number of the county entered by the continuing tornado segment.
38. **TOR_OTHER_CZ_NAME:** The name of the county entered by the continuing tornado segment.
39. **BEGIN_RANGE:** The distance to the nearest tenth of a mile, to the location referenced below.
40. **BEGIN_AZIMUTH:** 16-point compass direction from the location.
41. **BEGIN_LOCATION:** The name of the city, town, or village from which the range and azimuth are determined.
42. **END_RANGE:** Same as BEGIN_RANGE.
43. **END_AZIMUTH:** Same as BEGIN_AZIMUTH.
44. **END_LOCATION:** Same as BEGIN_LOCATION.
45. **BEGIN_LAT:** The latitude in decimal degrees of the begin point of the event or damage path.
46. **BEGIN_LON:** The longitude in decimal degrees of the begin point of the event or damage path.
47. **END_LAT:** The latitude in decimal degrees of the end point of the event or damage path.
48. **END_LON:** The longitude in decimal degrees of the end point of the event or damage path.
49. **EPISODE_NARRATIVE:** The episode narrative depicting the general nature and overall activity of the episode.
50. **EVENT_NARRATIVE:** The event narrative providing descriptive details of the individual event.





Detailed Information of the Parameters Used: 
Source: Bureau of Meteorology, Australia

Precipitation since 9am local time in mm:
Precipitation since 9 am is the cumulative precipitation recorded since 9 am local time. The rainfall total is reset to zero daily at 9 am local time.
Precipitation is measured using a "Tipping Bucket Rain Gauge" (TBRG). Most TBRGs report rainfall to 0.2 mm, but some report to 0.1 or 0.5 mm.
Rainfall includes all forms of water particles, whether liquid (for example, rain or drizzle) or solid (hail or snow), that fall from clouds and reach the ground at the point of observation. Note that rainfall totals may be under-reported during snowy and/or windy conditions. 

Air Temperature in degrees C
It is the temperature of Air, recorded in a Stevenson Screen which allows for good air flow across the thermometers, and prevents heating from direct sunlight. The height of the thermometers is approximately 1.2 m above the ground.

Dew point temperature in degrees C	
Dew point Temperature is the temperature to which the air must be cooled (at a constant pressure and water vapour content), in order for condensation of water vapour to occur. It therefore directly indicates the moisture content of the air; a low value indicates dry air. The closer the dew point is to the air temperature, the moister the air and the higher the relative humidity. Note that dew point temperature is a calculated value, derived from measurements of temperature and relative humidity.
Most dew point temperature measurements made at an Automatic Weather Station are instantaneous values (1-second samples). A small proportion of our Automatic Weather Stations report a 1-minute average for dew point temperature. The difference, if any, between these reporting periods is insignificant.








Relative humidity in percentage %
Relative humidity (RH) represents the moisture content of the air. It is the ratio of the amount of moisture actually in the air to the maximum amount of moisture which the air could hold at the same temperature. RH is obtained either from measurements by an electronic relative humidity sensor or derived via complex equations using air temperature and dew point temperature. There can be slight differences between RH values measured directly by a relative humidity sensor and those derived using equations. Typically these differences are less than 1%. 
Most Automatic Weather Stations report observations of RH as instantaneous values (1-second samples). A small proportion of Automatic Weather Stations report a 1-minute average RH. The difference, if any, between these reporting periods is insignificant.
The uncertainty associated with RH data increases at the extremes. That is, in very dry air as RH approaches 0%, and in very humid conditions as RH approaches 100%. There are some occasions when reported RH values may slightly exceed 100%. In these instances you should consider the value to be 100%.

The following formulas have been used:
Relative Humidity = Vapour pressure / Saturated vapour pressure * 100
Vapour pressure = exp (1.8096 + (17.269425 * Dew_Point)/(237.3 + Dew_Point))
Saturated Vapour pressure = exp (1.8096 + (17.269425 * Air_Temperature)/ (237.3 + Air_Temperature))
	
Wind speed in km/h	
Wind speed and direction are typically an average over the 10 minutes prior to the observation time. Measurements are made using an automatic anemometer, usually at a height of approximately 10 metres above the surface. When a significant wind change occurs during the 10 minute period prior to an observation, additional special observations may be reported by the AWS. In these cases, the wind data is not always averaged over the standard 10 minute averaging period.
Wind speed is usually measured by the anemometer in whole knots, but archived in SI units of m/s to 1 decimal point (0.1 m/s). 1m/s = 1.94kn = 3.6km/h approximately.

Wind direction in degrees true	
Wind direction can be output as either degrees (true) or points of the compass (8 or 16). If degrees are output, then values are rounded to the nearest 10 degrees and directions ending in 5 are rounded up (e.g. 105 degrees rounds to 110 degrees). When the wind speed is zero the wind direction is also zero (i.e. calm conditions).



Speed of maximum wind gust in last 10 minutes in km/h	
Wind gusts reported are the highest 3 second mean wind speed (sampled every second) over the last 10 minutes. When a significant wind change occurs during the 10 minute period prior to an observation, additional special observations may be reported by the AWS. In these cases, the wind gust data does not always apply to the standard 10 minute period.

Mean sea level pressure in hPa	
Mean sea level pressure (MSLP) is the station level pressure converted to an equivalent pressure at mean sea level.
	
Station level pressure in hPa
Station level pressure is the pressure measured at the weather station.

AWS Flag
Indicates whether the observations are completely automatic or whether an observer is present, or a hybrid. In a couple of situations some differences occur due to the observation method.
0 -Manned
1 -Automatic
2 -Hybrid


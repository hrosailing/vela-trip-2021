# vela-trip-2021

## Metadata

Contains files related to the following sailing trip:

### Vessel Metadata

- Vessel name: Vela
- Vessel type: Hiddensee
- Equipment: Rasberry Pi with Openplotter System, anemometer, GPS mouse

### Trip Metadata

- Start: 2. August 2021 8:34
- End: 13. August 2021 14:18
- Latitudes: 54 to 56
- Longitudes: 12 to 15

## Files

Download the latest release to get all files.
These contain:

- "sailing_data" contains 9 files in NMEA1803 format named "sailing_data/[used sail]_[location]_[date].vdr" (note that [] is used as a placeholder)
- contains 5 netCDF files with relevant weather information of the trip obtained from [DWD](https://www.dwd.de/EN/Home/home_node.html).
- a json file (compatible with the [hrosailing](https://github.com/hrosailing/hrosailing) package) containing relevant weather information obtained via [meteostat](https://meteostat.net/en/).

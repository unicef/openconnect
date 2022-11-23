# OpenConnect [Try it now!](https://openconnect.unicef.datafordecisionmaking.com/)
An interactive app for visualising and assessing School / Health Centre connectivity


## Data Sources

* Facility Location Data from [OpenStreetMap](https://openstreetmap.org)
* Internet Connectivity Estimates from [Ookla/Speedtest.net](https://registry.opendata.aws/speedtest-global-performance/)

## Methods
* OSM Data is parsed by 'amenity=school/hospital' - OSM Data may be very complete or very incomplete depending on your chosen country
* Ookla Speedtests are aggregated to the Bing Tile 14 level for the sake of speed, Bing Tile 16 would be better, but needs a bigger database


## Notes / TODO
* Facilities labelled 'No connectivity' are in tiles that don't have at least 4 Ookla speedtests in the last 12 months.
* Should also provide summary stats by Administrative region?



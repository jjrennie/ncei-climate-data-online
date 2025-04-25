# Get Daily Station Data from NOAA/NCEI's Cliamte Data Online (API)
## Written By Jared Rennie (@jjrennie)
Taps into the Cliamte Data Online (API) to get daily station data. This notebook will continually be built to supplement the Regional Climate Center's ACIS tools, should that go away for... "Reasons"
- CDO Webpage: https://www.ncei.noaa.gov/cdo-web/
- API: https://www.ncdc.noaa.gov/cdo-web/webservices

### What You Need
First off, the entire codebase works in Python 3.12 or higher. In addition to base Python, you will need the following packages installed: 
- <a href='https://pypi.org/project/noaa-cdo-api/' target="_blank">NOAA-CDO-API</a> (python wrapper to access the api)
- pandas (to slice annd dice the data)

The "easiest" way is to install these is by installing <a href='https://www.anaconda.com' target="_blank">anaconda</a>, and then applying <a href='https://conda-forge.org/' target="_blank">conda-forge</a>. Afterward, then you can install the above packages. 

### Launch Right Now With Binder

# ApartmentSearch
A small data analysis project I created in order to help me decide what apartment complexes would be viable options based on commute times.

## About
I like to have a myriad of data whenever I make a big decision, such as deciding where I want to live. My dad has always said "The secret to happiness is a short commute." I decided to base my research off this adage and thus created the two notebooks in this repo. The steps I took to undertake this research are as follows:
1. Obtain an <a href="https://developers.google.com/maps/documentation/javascript/get-api-key">API Key for Google Maps</a>
2. Write data_collection Jupyter Notebook to collect data
3. Set up <a href="https://www.cyberciti.biz/faq/how-do-i-add-jobs-to-cron-under-linux-or-unix-oses/">cron job</a> on UT's CS server to run the data_collection script twice in the morning (7:30 and 8:00 am) and twice in the evening (4:30 and 5:00 pm)
4. Write analysis Jupyter Notebook to ingest, cleanse and visualize the data

## Example Results
### Weekly Average Morning Commute
<img src="https://github.com/dmbrannon/ApartmentSearch/tree/master/screenshots/weekly_morning_averages.PNG" alt="screenshot of Weekly Average Morning Commute" />

### Weekly Average Evening Commute
<img src="https://github.com/dmbrannon/ApartmentSearch/tree/master/screenshots/weekly_evening_averages.PNG" alt="screenshot of Weekly Average Evening Commute" />

## Resouces
- <a href="https://developers.google.com/maps/documentation/directions/intro">Google Maps Directions API</a>
- <a href="https://github.com/googlemaps/google-maps-services-python">Python Client Library</a> for Google Maps API Web Services

# WeatherWebCrawling

This API is used for fetching weather conditions  name as a string to the respective locality's weather data. 
Import "code.start(place1,dateinp="",type="<Any one from daily/monthly/5days/10days/datewise in string format>") from package "web_crawling".
 You can pass ANY ONE OF the keyword arguments - Date in "YYYY-MM-DD" format/ forecast type required ('daily' for today {Default Selection}, 'monthly' for monthly,'5days' for 5-day , '10days' for 10-day,'datewise' for datewise). We are relying on APIs used by weather.com internally for extracting the respective data.
 
 
 For ex:

1.If you just want today's weather parameters with place name:

from web_crawling import code<BR>
code.start("Place-Name")

2.If you just want the current month's weather details with place name:

from web_crawling import code<BR>
code.start("Place-Name",type="monthly")

3.If you just want some date's weather prediction with place name:

from web_crawling import code<BR>
code.start("Place-Name",dateinp="date string in yyyy-mm-dd format")


package is installable as "pip install web_crawling"

If no/wrong keyword arguments given, it may result in wrong output


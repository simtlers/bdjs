# bdjs automatic updates
this section is where all of the main updates happen.
upon connecting to this version, the code used for handling bdjs code and others will update automatically, without the need of updating the url manually.
incase you want any other versions, you can go to the versions folder.
# how to load
**note: this code is already present in the main README.md**
loading code handler:
```
$var[code;//INSERT ANY BDJS CODE HERE//]
$httpGet[https://github.com/simtlers/bdjs/auto/handler.json]
$httpResult[handler]
```

Tag your incoming data as 'pfsense' to take advantage of these field extractions. 
```sourcetype = pfsense```

Please note the current configuration of TIME_FORMAT and MAX_TIMESTAMP_LOOKAHEAD for your specific data feed
```
[pfsense]   
description = Technology Add-on for parsing filter logs from pfSense devices   
... 
TIME_FORMAT = %b %d %T   
MAX_TIMESTAMP_LOOKAHEAD = 16
```

Reference for filterlog: https://docs.netgate.com/pfsense/en/latest/monitoring/filter-log-format-for-pfsense-2-2.html

Also, check us out on splunkbase : https://splunkbase.splunk.com/app/4567/

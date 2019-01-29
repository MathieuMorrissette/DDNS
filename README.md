# DDNS
Config to setup a DDNS with digital ocean

### Use this
````
https://github.com/bensquire/Digital-Ocean-Dynamic-DNS-Updater
````
### check every 5 minutes
````
*/5 * * * * /usr/bin/python3 /home/alarm/cron_scripts/ddns/updater.py <digitaloceanaccesskey> mathieumorrissette.com home A
````

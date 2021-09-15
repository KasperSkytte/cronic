# cronic
A cure for Cron's chronic email problem. By Chuck Houpt, see https://habilis.net/cronic/

Download https://github.com/KasperSkytte/cronic/blob/main/cronic to somewhere in your or the system's `$PATH`, like `/usr/local/bin/cronic`, and make sure it's executable with `chmod +x /usr/local/bin/cronic`. Prefix cronic to any cronjob:

`0 1 * * * cronic backup.sh`
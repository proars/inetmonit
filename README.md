# README
inetmonit.sh is basic Linux script for automatically reboot if no Internet connection or PING.

Create cron job in crontab:

crontab -e

Edit file and add line: 

for run every 5min:
*/5 * * * * /path_to/inetmonit.sh

for run every 30 min:
*/30 * * * * /path_to/inetmonit.sh

...



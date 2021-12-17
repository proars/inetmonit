# README
inetmonit.sh is Basic Linux Script for automatically reboot if no Internet connection or PING

Need create cron job in crontab
crontab -e
edit file and add:
*/5 * * * * /path_to/inetmonit.sh
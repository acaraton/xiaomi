copy_to_ftp.sh
==============

This script can help you to copy some files to a ftp server (on a NAS for example).

Configure the script : 

* ftp_dir value, just put there the path where you want to copy videos.
* ftp_host value, indicate the IP of the NAS
* ftp_port value, indicate the port of the FTP server (like 21)
* ftp_login value, indicate the user or login to connect to the ftp folder in the nas server.
* ftp_pass value, indicate the password of the user before for permision to save in the folder.

Add the script to the crontab of your yi camera

Source of the script : 

* https://github.com/fritz-smh/yi-hack/pull/24
* http://4pda.ru/forum/index.php?showtopic=638230&st=2780#entry44208114

cleanup.sh
==========

This script will cleanup video files older than 15 days.

You need to add it in the crontab

Useful Scripts
============
<pre>
<u>Linux, Bash:</u>

* <b>vsftpd.sh</b> -- fast vsftpd config for Debian server with /var/ftp directory, ftpuser group
* <b>deb-kern-up.sh</b> -- Debian distro kernel update script, don't forget to change version to keep it up to date
* <b>simple_apache_firewall.sh</b> -- Simple firewall script for apache to block IPs with lots requests from log
* <b>swap.sh</b> -- Script to count RAM and help create swap for faster system working
* <b>wordpress.sh</b> -- Special script to help configure Apache, MySQL, WordPress, Swap and some other stuff, automatically installs all required packages, configure files etc

To get access to phpMyAdmin UI : 
* Edit the Apache Conf File : /etc/apache2/apache.conf
* Add the line at the end : Include /etc/phpmyadmin/apache.conf
* Restart apache : sudo service apache2 restart.
* Refresh the URL : http://localhost/phpmyadmin
</pre>

<hr />

<pre>
<u>Windows, PowerShell:</u>

* <b>winlogs.ps1</b> -- Windows Logs Extracting is a PowerShell script to easily extract required logs preformated for quick parsing into text file.
Usage:
 ./winlogs.ps1 list  #will show all available logs
 ./winlogs.ps1 "Security" 25  #will store 25 security log events into file with mask "date_logtype.txt" i.e: 20160303_security.txt</pre>
</pre>

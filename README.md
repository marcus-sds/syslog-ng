### syslog-ng installation
chkconfig rsyslogd off

yum install -y syslog-ng<br>
chkconfig syslog-ng on<br>
service syslog-ng start<br>

### syslog-ng config
copy syslog-ng.conf to /etc/syslog-ng/<br>

# Install-apache
root@smkmanusa:~# apt-get install apache2
root@smkmanusa:~# nano /etc/apache2/sites-available/000-default.conf

ServerAdmin mail.smkmanusa.sch.id
DocumentRoot /var/lib/roundcube

root@smkmanusa:~# service apache2 restart

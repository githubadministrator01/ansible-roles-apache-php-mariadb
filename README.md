# Custom roles for Apache and mariadb. Modify j2 templates and vars as you see fit. 
# PHP script connects web and db server and creates table evrytime you access the site - http://localhost/phpconnect.php
# After the playbook completes you must connect to db server and grant username in my case root ALL priv to all location. "GRANT ALL ON *.* to username@'%' IDENTIFIED BY 'some-password';

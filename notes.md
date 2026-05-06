apache2 -v
sudo systemctl status apache2
curl http://localhost

mysql --version
sudo systemctl status mysql
sudo mysql

CREATE DATABASE wordpress_db;
CREATE USER 'wp_user'@'localhost' IDENTIFIED BY 'password123';
GRANT ALL PRIVILEGES ON wordpress_db.* TO 'wp_user'@'localhost';
FLUSH PRIVILEGES;
EXIT;


php -v
php -m


Apache ↔ PHP Integration
Verify Apache HTTP Server + PHP integration:
Create test file:
echo "<?php phpinfo(); ?>" | sudo tee /var/www/html/info.php
Open in browser:
http://localhost/info.php
If PHP page renders → integration OK.


php -m | grep mysqli
php -m | grep curl
php -m | grep gd
php -m | grep xml
php -m | grep mbstring


apache2ctl -M | grep php


-------------------------------------------
-Apache running (active)
-MySQL running (active)
-PHP CLI works (php -v)
-PHP loads in browser (info.php)
-Extensions visible in php -m
-Apache shows php_module

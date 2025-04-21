# frappe-tutorial-installation

# Frappe tutorial installation 

1. Tạo User MySQL
   sudo mysql
   > CREATE USER 'frappe'@'localhost' IDENTIFIED BY '016742';
GRANT ALL PRIVILEGES ON *.* TO 'frappe'@'localhost' WITH GRANT OPTION;
FLUSH PRIVILEGES;
EXIT;
   // user for create a new site with Bench CLI
 

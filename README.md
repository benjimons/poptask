#System Requirements
- PHP v5.3
- MYSQL v5.5+

Try xammp http://www.apachefriends.org/en/xampp.html

# Installation 
1. Copy poptask folder to your htdocs folder eg /var/www
2. Set up a cron job to run "task_populator.php" (this runs the email alerts and scheduling)

   ```eg */5 * * * * php -q /var/www/poptask/task_populator.php >/dev/null```
3. Create a database on your local server
4. Access the setup.php script via your browser eg http://localhost/poptask/setup.php
5. Login 
   * default username: admin 
   * default password: password

#Screenshots
Demo here: http://poptask.sourceforge.net/demo/

Username:demo

Password:demo

![Alt text](poptask1.png?raw=true "Main working screen")

![Alt text](poptask2.png?raw=true "Edit and add events")

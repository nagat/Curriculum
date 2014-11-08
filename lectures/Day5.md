# Day 5: Correct HTML & CSS homework, then Install Drupal!

## Run a rough 'health diagnosis' on homework assignments
Implement the 'HTML Outliner' tool from the tools repo on your homework assignment.
Open your homework assignment. Click 'Debug' - do the outlines of your HTML look appropriate?

### As a class, improve the roughest looking homework assignment
1. Cut a new branch
2. Turn 'Debugging' on (Debugger tool)
3. Run through the file - talk through issues, correct them on the spot
4. Run 'Debug' after correcting the file together
5. Rejoice

#### Create the New Drupal Website
1. clone the dev repo
2. open Acquia Dev Desktop 
3. click on the (+) in the bottom left corner of the window and choose "Import local Drupal site"
4. fill in the fields


8. SSH into your vagrant box (vagrant ssh)
9. Create a mysql database by running the following commands (only type the parts after '--:')
--: mysql -uroot -proot # this connects to your mysql database via the command line
--: create database myfirstdrupalsite; -- this creates a database named myfirstdrupalsite. don't leave out the semicolon.
--: exit; -- leaves the mysql command line editor
10. In your browser, go to 192.168.44.44/drupal-7.X (replace the 'drupal-7.X' with the name of the folder you downloaded)
11: Run through the installation steps
-- When it asks you to pick between 'Standard' or 'Minimal', choose Standard
-- When it asks for your database username, password, and name, enter the following:
---- Username: root
---- Password: root
---- Database name: myfirstdrupalsite
12: Click 'next' and fill in the required fields until your site begins installing
13: Look around your new Drupal 7 website!

# ldo-2017-jun-exam
Set of three Docker containters (nginx, php, mysql) that form a simple web application

Please note that:
 - each container should be named after the following rule - ldo-role, where role is php, mysql, or nginx;
 - mysql password is expected to be 12345;
 - nginx is set to listen on port 80;
 - php files are expected to be in the /site folder of the nginx and php containers;
 - nginx container should be started after php;

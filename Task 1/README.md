# TASK 1 - Nginx Server Setup

## Objective

Set up an Nginx server on the local Linux machine and serve the custom HTML page provided by the organizers.

## Organizer HTML Page

http://10.10.110.79:3923/test/index.html

## Commands Used

```bash
sudo apt update
sudo apt install nginx -y
sudo systemctl start nginx
wget "http://10.10.110.79:3923/test/index.html" -O custom.html
sudo cp custom.html /var/www/html/index.html
curl http://localhost
curl -I http://localhost

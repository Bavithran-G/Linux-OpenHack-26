# Task 4 - Run HTML Page on a Separate Port

## Objective

Run a different HTML page on a separate port and verify that it can be accessed.

## Steps Performed

1. Created a second HTML page at:
   `/var/www/second/index.html`

2. Configured Nginx to listen on port:
   `8080`

3. Tested the Nginx configuration using:
   `nginx -t`

4. Restarted Nginx.

5. Verified the second HTML page using:
   `curl http://localhost:8080`

6. Accessed the page from another computer using:
   `http://<SERVER-IP>:8080`

## Result

The second HTML page was successfully hosted and accessed through port 8080.

## Status

Task 4 completed successfully.

# Task 5 - HTTPS Configuration

## Objective

Convert the hosted HTML page into an HTTPS page and verify secure access.

## Steps

1. Created an SSL certificate using OpenSSL.
2. Configured Nginx to use the SSL certificate.
3. Configured HTTPS on port 443.
4. Restarted Nginx.
5. Verified the HTTPS page using curl.
6. Accessed the HTTPS page from another computer.

## SSL Certificate

Certificate:
`/etc/nginx/ssl/server.crt`

Private Key:
`/etc/nginx/ssl/server.key`

## Port

HTTPS uses port:

`443`

## Verification

```bash
curl -k https://localhost

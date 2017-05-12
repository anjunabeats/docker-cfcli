# docker-cfcli
## Cloudflare-cli in Docker

Purge cache in cloudflare

Build :
`docker build . -t cfcli`

Run :
`docker run cfcli --email=EMAIL --token=TOKEN -d DOMAIN purge`

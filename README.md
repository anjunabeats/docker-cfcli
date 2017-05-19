# docker-cfcli
## Cloudflare-cli in Docker

Purge cache in cloudflare

## Usage

Run :
`docker run anjuna/cfcli --email=EMAIL --token=TOKEN -d DOMAIN purge`

## Dev

Build :
`docker build . -t anjuna/cfcli`

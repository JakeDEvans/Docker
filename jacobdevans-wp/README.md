# Dockerfile expects the you to have an existing wordpress configured and ready for use, access configured for the docker host (NAT IP) and NFS/Local File system presented with

## Build With
`docker build -t jacobdevans-wp -f $PWD/DockerFile $PWD`

## Run With
`docker run -d --name jacobdevans-wp -v /mnt/web/www.jacobdevans.com/:/var/www/html jacobdevans-wp`

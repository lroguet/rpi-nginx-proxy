# rpi-nginx-proxy

rpi-nginx-proxy sets up a container running nginx and [docker-gen](https://github.com/jwilder/docker-gen). docker-gen generates reverse proxy configurations for nginx and reloads nginx when containers are started and stopped. rpi-nginx-proxy is a **Raspberry Pi** compatible version of [jwilder/nginx-proxy](https://github.com/jwilder/nginx-proxy).

## Usage
```
$ docker run -d -p 80:80 -v /var/run/docker.sock:/tmp/docker.sock:ro lroguet/rpi-nginx-proxy
```

## Resources
* [Docker Hub](https://hub.docker.com/r/lroguet/rpi-nginx-proxy/)
* [In action](http://lab.fourteenislands.io/nginx-reverse-proxy-docker-and-a-raspberry-pi/)
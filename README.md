# docker-v2ray-h2-web
Docker Compose solution: v2ray + HTTP/2 + Web (probe resistance)

**WARNING: `ntpd` service in this app would modify the time in host.**

## Usage

```
$ ./configure <UUID> <Host>
$ sudo docker-compose up -d
```

Then connect to `https://<Host>:443` via vmess over HTTP/2.

# mesh-http-rewrite-test

This repo demostrates several routing options for a site within a istio service mesh.


* URL rewriting
* routing based off of host
* route sharing same host but different path


# Setup

Setup your `/etc/hosts` file like so:

```
127.0.0.1   localhost localhost.localdomain localhost4 localhost4.localdomain4 http-echo.localdomain nginx.localdomain nginx-a.localdomain nginx-b.localdomain
```


# URLs

http://http-echo.localdomain:8080/sdfsd

http://nginx-a.localdomain:8080/  
http://nginx-b.localdomain:8080/  
http://nginx.localdomain:8080/a/  
http://nginx.localdomain:8080/b/  

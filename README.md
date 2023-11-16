# oauth2-server

OAuth2 PHP Server Config
* https://oauth2.thephpleague.com/
* https://github.com/thephpleague/oauth2-server/

## Getting Started

### Prerequisites

Prepare private.key & public.key in directory src/config

```
openssl genrsa -out private.key 2048
openssl rsa -in private.key -pubout -out public.key
```

### Guide

[Complete guide to setup a PHP Login and OAuth2.0 Server](https://medium.com/@dmorawetz/complete-guide-to-setup-a-php-login-and-oauth2-0-server-921a4269a918)

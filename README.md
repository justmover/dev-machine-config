# This is an repo for all dev machine setting.

## Reverse Proxy

#### To create the first time:

```
docker-compose -f reverse-proxy/dev-local.yml up -d
```

#### To run it again:

```
docker-compose -f reverse-proxy/dev-local.yml restart
```

#### To see the logs:

```
docker-compose -f reverse-proxy/dev-local.yml logs
```

Enjoy!
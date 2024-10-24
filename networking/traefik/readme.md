
traefik with 2 nginx containers on port 81 (domain1.com) and 82 (domain2.com)

```
docker-compose -f docker-compose_test.yaml up
```

traefik with pihole (domain1.com) and nginx (domain2.com) on port 81 and 82
```
docker-compose -f docker-compose_pihole.yaml up
```

secure
```
docker-compose -f docker-compose_pihole-secure.yaml up
```


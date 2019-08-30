# Project Title

Graylog3 docker image with plugins integration

## Plugin list

| Plugin  | Version  | Url  | Description |
|---------|----------|------|-------------|
| SSO | 3.1.0  | https://github.com/Graylog2/graylog-plugin-auth-sso  | SSO support for Graylog through trusted HTTP headers set by load balancers or authentication proxies |


## Getting Started

For usage just clone this repo and run `docker-compose`

### Building

```
docker build -t 'graylog' .
```

### Testing

```
docker-compose up
```

## TODO

* add GeoIp as docker container


## Built With

* [Docker](https://www.docker.com/) - Docker
* [Docker-compose](https://docs.docker.com/compose/) - Docker compose

## Versioning

We use [SemVer](http://semver.org/) for versioning. 

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details



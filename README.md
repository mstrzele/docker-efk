# Docker Machine Logs

## Kibana

```bash
$ docker-compose --file docker-compose.kibana.yml up
```

### [Docker Machine](https://docs.docker.com/machine/overview/)

```bash
$ open "http://$(docker-machine ip):5601"
```

### [Minikube](https://github.com/kubernetes/minikube)

```bash
$ open "http://$(minikube ip):5601"
```

## Graylog

```bash
$ docker-compose --file docker-compose.graylog2.yml up
```

### [Docker Machine](https://docs.docker.com/machine/overview/)

```bash
$ open "http://$(docker-machine ip):9000"
```

### [Minikube](https://github.com/kubernetes/minikube)

```bash
$ open "http://$(minikube ip):9000"
```

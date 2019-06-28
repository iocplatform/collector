# Collector

Agent collector is used to split integration queue from feed parsing agent.

## Build

### Local 

```sh
> go run mage.go
```

### Docker

```sh
> export DOCKER_BUILDKIT=1
> go run mage.go docker:build
```

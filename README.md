# Spring Petclinic OpenTelemetry

It is an OpenTelemetry Collector that received otel data and sends trace data to Jaeger and Zipkin and metrics data to Promeheus.

To start:
```shell
docker-compose up -d
```

To shutdown:
```shell
docker-compose down
```

The demo exposes the following backends:

- Jaeger at http://localhost:16686
- Zipkin at http://localhost:9411
- Prometheus at http://localhost:9090 

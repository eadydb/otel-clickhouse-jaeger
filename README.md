## Docker deployment
1. otel-collector
2. clickhouse
3. jaeger
4. grafana
5. prometheus

```
docker compose up -d
```

## Verify the web store and Telemetry

Once the images are built and containers are started you can access:

Grafana: http://localhost:8080/grafana/
Jaeger UI: http://localhost:8080/jaeger/ui/


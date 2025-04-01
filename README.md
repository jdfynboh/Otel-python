# Otel-python
Example Python App instrumented with Otel


# Environment Variables
```
OTEL_EXPORTER_OTLP_ENDPOINT="https://<tenant>.live.dynatrace.com/api/v2/otlp"
OTEL_EXPORTER_OTLP_HEADERS="Authorization=Api-Token dt0c01.XXXXX.YYYYYYYY"
OTEL_RESOURCE_ATTRIBUTES=myid=11111
OTEL_LOG_LEVEL=debug
OTEL_EXPORTER_OTLP_METRICS_TEMPORALITY_PREFERENCE=delta
OTEL_EXPORTER_OTLP_PROTOCOL=http/protobuf
OTEL_METRICS_EXPORTER=otlp
OTEL_SERVICE_NAME=MyServiceName
```

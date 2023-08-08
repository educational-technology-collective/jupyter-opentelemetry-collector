# A custom OpenTelemetry Collector for Jupyter Lab extension jupyter-opentelemetry
@Educational Technology Collective

## Getting started
To run the collector and serve the jupyter-opentelemetry extension, type the following command in the terminal

```console
./otelcol-jupyter/otelcol-jupyter --config otel-config.yaml 
```
`otel-config.yaml` is the configuration file of the collector.

## For Developer
### Build collector with OpenTelemetry Collector Builder (ocb)
OpenTelemetry Collector Builder is a tool provided by the OpenTelemetry community to assist people in assembling their own distribution.
The detailed doc could be find here: https://opentelemetry.io/docs/collector/custom-collector/

To customize the collector, first edit the `builder-config.yaml` file based on your need, then rebuild the collector with the following command

```console
./ocb --config builder-config.yaml
```



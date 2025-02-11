# OpenTelemetry code samples

These are demo projects based on the OpenTelemetry example code.
The idea is to provide accessible playgrounds which also explore features beyond the basic tutorials.
These are meant to be functional with a Grafana Cloud account.

## Maturity Levels
### Manual instrumentation
- Level `m0`: [initial roll dice](https://opentelemetry.io/docs/languages/go/getting-started/#create-and-launch-an-http-server)
- Level `m1`: [instrumented roll dice code from getting started](https://opentelemetry.io/docs/languages/go/getting-started/#add-opentelemetry-instrumentation)
- Level `m2`: default to [OpenTelemetry over HTTP](https://pkg.go.dev/go.opentelemetry.io/contrib/instrumentation/net/http/otelhttp)
- Level `m3`: craps function- demonstrate passing HTTP [`traceparent` header](https://www.w3.org/TR/trace-context/#traceparent-header)
- Level `m4`: roll dice over protocol buffer
- Level `m5`: shoddy dice roll function, error handling
- Level `m6`: sampling

# Prometheus Compliance Tests

This repo contains code to test compliance with various Prometheus standards. Anyone taking part in CNCF's [Prometheus Conformance](https://github.com/cncf/prometheus-conformance) Program will need to run the tests in here against their own implementations.

If you are reading this as someone testing their own implementation or considering to do so: There is a _LOT_ of work that's planned but not executed yet. If you have time or headcount to invest in uplifting everyone's compliance, [please talk to us](https://prometheus.io/community/).

## Alert Generator

The [alert_generator](alert_generator/README.md) directory contains a shim at the moment. It will test correct generation and emitting of alerts towards Alertmanager.

## OpenMetrics

The [openmetrics](openmetrics/README.md) directory contains a reference to the [OpenMetrics](https://github.com/OpenObservability/OpenMetrics/blob/main/specification/OpenMetrics.md) test suite.

## PromQL

The [promql](promql/README.md) directory contains code to test compliance with the [native Prometheus PromQL implementation](https://github.com/prometheus/prometheus/tree/main/promql).

## Remote Write Sender

The [remote_write_sender](remote_write_sender/README.md) directory contains code to test compliance with the [Prometheus Remote Write specification](https://docs.google.com/document/d/1LPhVRSFkGNSuU1fBd81ulhsCPR4hkSZyyBj1SZ8fWOM/edit#heading=h.n0d0vphea3fe) as a sender.

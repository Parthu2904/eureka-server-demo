# data-platform-eureka-registry


Centralized Metadata & Service Registry for Distributed Data Pipelines


This repository provides a resilient service-discovery and metadata registry used by data platform microservices. It is intended to be the backbone for coordinating distributed ETL/ELT services, ingestion workers, schema/metadata services, and control-plane microservices.


## Key Features
- High-availability service registry for data microservices
- Health-check and management endpoints for operational visibility
- Designed to support scaling data ingestion, processing, and serving layers


## Tech & Integrations
- Spring Boot
- Netflix Eureka (service registry pattern)
- Prometheus / Micrometer compatible metrics
- Works with Kubernetes, Docker, and Cloud deployments


## Getting Started (local)
1. Build and run with Maven:
```bash
mvn clean package
java -jar target/registry-0.0.1-SNAPSHOT.jar

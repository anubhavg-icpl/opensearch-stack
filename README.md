<h1 align="center">
<br>
<img src=assets/os-stack.png >
<br>
<strong>opensearch-stack: Happy searching and monitoring!</strong>
</h1>



This repository contains a Docker Compose configuration for setting up a robust search and observability stack using OpenSearch, OpenSearch Dashboards, Prometheus, and Grafana.

## Overview

This stack provides a powerful combination of tools for search, logging, monitoring, and visualization:

- **OpenSearch**: A community-driven, open-source search and analytics suite derived from Elasticsearch.
- **OpenSearch Dashboards**: A visualization and user interface for OpenSearch.
- **Prometheus**: An open-source monitoring and alerting toolkit.
- **Grafana**: A multi-platform open-source analytics and interactive visualization web application.

## Prerequisites

- Docker
- Docker Compose

## Quick Start

1. Clone this repository:
   ```
   git clone https://github.com/anubhavg-icpl/opensearch-stack.git
   cd opensearch-stack
   ```

2. Start the stack:
   ```
   docker-compose up -d
   ```

3. Access the services:
   - OpenSearch: `https://localhost:9200`
   - OpenSearch Dashboards: `http://localhost:5601`
   - Prometheus: `http://localhost:9090`
   - Grafana: `http://localhost:3000`

## Configuration

The `docker-compose.yml` file contains the configuration for all services. You can modify this file to adjust settings such as ports, volumes, and environment variables.

### Default Credentials

- OpenSearch:
  - Username: admin
  - Password: Anubhav@321

- Grafana:
  - Username: admin
  - Password: grafana

**Note**: It's recommended to change these default passwords in a production environment.

## Usage

- Use OpenSearch and OpenSearch Dashboards for log management and search capabilities.
- Use Prometheus to collect and store metrics from your applications and infrastructure.
- Use Grafana to create dashboards and visualize the metrics collected by Prometheus.

---


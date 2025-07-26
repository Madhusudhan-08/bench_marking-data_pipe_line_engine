# bench_marking-data_pipe_line_engine
## Purpose
ETL pipeline for collecting, transforming and loading benchmarking data

## Features
- Data connectors for [list sources]
- Transformation framework
- Data quality checks
- Lakehouse integration

## Quick Start
```bash
mvn clean install
java -jar target/data-pipeline.jar --config /path/to/config.yml

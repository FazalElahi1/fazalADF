# Azure Data Factory ETL Pipeline

## Overview
This repository contains an end-to-end ETL pipeline developed using Azure Data Factory (ADF). The project focuses on orchestrating data ingestion, transformation, and movement workflows through scalable cloud-based data integration services.

The pipeline is designed to automate data processing tasks and support reliable data engineering workflows using Azure cloud technologies.

---

## Features
- Automated ETL pipeline orchestration
- Data ingestion from multiple sources
- Scheduled and trigger-based workflows
- Scalable cloud-based architecture
- JSON-based ADF pipeline configuration
- Modular pipeline components
- Data transformation and movement workflows

---

## Tech Stack
- Azure Data Factory (ADF)
- Azure Cloud Services
- JSON
- ETL/Data Engineering Concepts

---

## Project Structure

```bash
fazalADF/
│
├── pipeline/              # ADF pipeline definitions
├── dataset/               # Dataset configurations
├── linkedService/         # Linked service connections
├── trigger/               # Pipeline triggers and schedules
├── integrationRuntime/    # Integration runtime settings
└── factory/               # Factory-level configurations
```

---

## Workflow Architecture

1. Data is ingested from configured data sources.
2. Azure Data Factory orchestrates pipeline execution.
3. Transformation activities process and clean the data.
4. Processed data is moved to the target destination.
5. Triggers automate recurring executions.

---

## Getting Started

### Prerequisites
Before running the project, ensure you have:

- Azure Subscription
- Azure Data Factory instance
- GitHub integration configured with ADF
- Required linked services and datasets

---

## Setup Instructions

### 1. Clone Repository

```bash
git clone https://github.com/FazalElahi1/fazalADF.git
```

### 2. Open Azure Data Factory
- Navigate to Azure Portal
- Open Azure Data Factory Studio
- Connect Git repository if needed

### 3. Import Pipelines
- Import JSON pipeline definitions
- Configure datasets and linked services
- Validate pipeline dependencies

### 4. Publish and Trigger
- Publish all changes
- Execute pipelines manually or using triggers

---

## Use Cases
- Cloud-based ETL workflows
- Automated data movement
- Data orchestration pipelines
- Batch processing
- Azure data engineering projects

---

## Future Improvements
- Add monitoring and alerting
- Integrate Azure Databricks
- Implement CI/CD deployment
- Add data validation checks
- Include parameterized pipelines

---

## Screenshots
Add screenshots of:
- ADF pipeline workflow
- Trigger configuration
- Data flow activities
- Pipeline monitoring dashboard

---

## Author

**Fazal Elahi**  
Data Engineer | Data Analyst | Azure Data Engineering Enthusiast

GitHub: https://github.com/FazalElahi1

---

## License
This project is licensed under the MIT License.

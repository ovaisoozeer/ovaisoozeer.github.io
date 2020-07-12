# Rolls Royce Marine

Client website: [www.rolls-royce.com](https://www.rolls-royce.com/products-and-services/defence/naval/electrical-automation-and-control.aspx)

## Data Analytics Platform

- Location: Ålesund NO
- Aim: Ingest equipment health monitoring (EHM) data into a data analytics and reporting platform, and provide a dashoard proof of concept.
- Role: Developer (mostly coding)
- Duration: 2 weeks
- Team: Developer, 2x Data Scientists, TA, Delivery Manager, BA.
- Notable challenges/experience:
    - I was brought in halfway through this project to set up development environments and support our data scientists in automating the ELT process.
    - Worked alongside RRM's internal dashboard team to define the dashboard data contract.
- Tech stack:
    - Azure Data Lake
    - PySpark
    - Spyder
    - Jupiter Notebooks
    - D3JS
    - .NET Core


## Ship-to-Shore Data transfer

- Location: Bergen NO
- Aim: Prove a data pipeline for EHM data from a moving vessel to cloud storage.
- Role: Developer (mostly coding)
- Duration: 2 weeks
- Team: 2x Developers
- Notable challenges/experience:
    - Aim achieved by proving EHM data transfer between a remote stationary engine and a VM.
    - Validation and ingestion of non-standard EHM data into an analytics platform.
    - It took about a week to get access privileges sorted, so the work was done in the last week.
    - One of the outputs was a strategic recommendation for a production grade system.
- Tech stack:
    - Azure ARM, Powershell CLI
    - Apache Kafka, Flume
    - .NET Core
